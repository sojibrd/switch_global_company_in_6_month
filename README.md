# switch_global_company_in_6_month

১৮০ দিনের plan: দেশে থেকে big tech মানের কোম্পানিতে রিমোট — ১০টা আবেদন আর অন্তত ৩টা সম্পূর্ণ interview process। DSA, আটটা সিস্টেমের design, frontend system design আর behavioral — প্রতিদিন একটা করে করার কাজ, শেখার বিজ্ঞান মেনে।

এটা তিনটা বিকল্প plan-এর একটা। একজন একটাই চালায়: [লোকাল](https://github.com/sojibrd/switch_local_company_in_6_month) · [রিমোট](https://github.com/sojibrd/switch_remote_company_in_6_month) · **গ্লোবাল** (এটা)। তিনটার কোড হুবহু এক।

**লাইভ:** https://sojibrd.github.io/switch_global_company_in_6_month/

## Functional Requirement

- **আজ (`/`):** প্রথমবার খুললে শুরুর তারিখ জিজ্ঞেস করে। তারপর ক্যালেন্ডারের আজকের দিন — ক্রম: dip-এর সতর্কতা → জমে থাকা ⚑ মাইলফলক → আজকের ঝালাই → আজকের দিন।
- **Rail:** সব পাতায় বাঁয়ে একটা rail থাকে, মোবাইলে drawer। তাতে ৩টা পাতার লিংক, plan-এর gauge আর ৬টা ব্লক; যে ব্লক খোলা শুধু তার দিনগুলো দেখায়।
- **দিন (`/day/<nnn>/`) · ব্লক (`/block/<slug>/`):** দিনের কাজ আর দিন বা ব্লক শেষের হ্যাঁ/না।
- **ঝালাই (`/review/`):** প্রতিটা 🔁 কাজ টিকের দিন থেকে ১/৩/৭/২১ দিন পরে ফিরে আসে। "মনে ছিল" দিলে পরের ধাপে, "আটকে গেছি" দিলে আজ থেকে আবার ১ দিনে।
- **নিয়ম (`/rules/`):** `docs/00-rules.md` হুবহু।
- **🧠 chip:** চাপলে এক লাইনে দেখায় কেন কাজটা এভাবে, সাথে `learning_to_learn` সাইটের লিংক।

## Non-Functional Requirement

- **সত্যের উৎস `docs/`।** কোডে কোনো ব্লক, দিন বা কাজ হার্ডকোড নেই।
- **ফাইলে তারিখ নেই।** তারিখ = শুরুর তারিখ + (দিন − ১); শুরুর তারিখ ব্রাউজারে। দিন ০০১ = সোমবার ধরে লেখা।
- **"আজ" = ক্যালেন্ডারের তারিখ।** plan পেছায় না। বাদ পড়া সাধারণ কাজ ফেরে না; শুধু ⚑ জমে থাকে।
- **DSA এই সাইটে নয়।** দিন ০০৮–১৭৫ [`dsa_prep_global_company`](https://sojibrd.github.io/dsa_prep_global_company/) — ১১০টা প্রবলেম, ১৮০ দিনের মধ্যেই শেষ; ঐ সাইটের সাতটা DSA mock এই plan-এর শনিবারে (দিন ০৩৪, ০৬২, ০৯০, ১১৮, ১৪৬, ১৬৭, ১৭৪)।
- **Static export → GitHub Pages।** Backend নেই।
- **Progress শুধু `localStorage`-এ,** একমাত্র `app/hooks/useProgress.ts` দিয়ে। **`app/lib/plan.ts` server-only।**
- **তিন plan-এর কোড এক।** পার্থক্য শুধু `app/lib/site.ts`, `next.config.ts`-এর basePath আর `docs/`। কোড বদলালে তিন repo-তেই একই বদল।
- **Theme contract অলঙ্ঘনীয়, সাইট dark-only।** Tailwind শুধু লেআউটে; চেহারা role class আর `--t-*` টোকেনে।
- **স্ট্যাক:** Next.js 16, React 19, TypeScript, Tailwind v4, react-markdown।

## ডক ইনডেক্স

| ফাইল | দিন | Gist |
|---|---|---|
| [docs/00-rules.md](docs/00-rules.md) | — | লক্ষ্য (১০ আবেদন, ৩ process; সীমা $১,৭০০), কেন ১০, সত্যের উৎস, বাজারের দুই শর্ত (big tech মানের loop + বাংলাদেশ থেকে রিমোট), চার রাউন্ড, সপ্তাহের ছন্দ, DSA-র সাইট (দিন ০০৮–১৭৫, সাত শনিবারে mock), design-এর বসা আর আট সিস্টেম, আবেদন ও interview-এর নিয়ম, Dip-এর নিয়ম, যা করবেন না, টাকা, দিন ১৮০-র পরে |
| [docs/01-foundation.md](docs/01-foundation.md) | ০০১–০৩০ | portfolio, সংখ্যাসহ সিভি, যাচাই করা ১৫টা নাম, রেফারেলের মানচিত্র, টাকার ব্যবস্থা, design আর frontend-এর ছাঁচের কার্ড, ৬ STAR। আবেদন দিন ০১৪ ও ০২৮-এ |
| [docs/02-design-template.md](docs/02-design-template.md) | ০৩১–০৬০ | `srdtube`-এর ইংরেজি design doc, URL shortener · rate limiter · srdtube ৪৫′-এ মুখে, scoping, চারটা ধারণা ডক ছাড়া, story → signal; DSA mock #১ দিন ০৩৪-এ। শেষে: ৪টা আবেদন |
| [docs/03-systems.md](docs/03-systems.md) | ০৬১–০৯০ · dip | chat, news feed, file storage — লেখা আর ৪৫′-এ বলা; infinite feed আর autocomplete UI; ফানেলের প্রথম দেখা। শেষে: ৬টা আবেদন |
| [docs/04-recruiter-and-dsa.md](docs/04-recruiter-and-dsa.md) | ০৯১–১২০ · dip | recruiter call-এর ছয় প্রশ্ন (level, রিমোট কীভাবে), offer-এর সীমা, DSA mock #৪ দিন ১১৮-এ, mock #১ (DSA), ride sharing আর video streaming-এর doc। শেষে: ৮টা আবেদন |
| [docs/05-rounds.md](docs/05-rounds.md) | ১২১–১৫০ · dip | এলোমেলো সিস্টেম ৪৫′-এ, এলোমেলো UI ২০′-এ, signal ধরে story, mock #২ (system design), দশম আবেদন দিন ১৪০-এ, আট সিস্টেমের এক পাতা |
| [docs/06-three-processes.md](docs/06-three-processes.md) | ১৫১–১৮০ · dip | নোট থেকে সিলেবাস, mock #৩ (behavioral), ফানেলের শেষ রায়, রিমোট offer-এর চেকলিস্ট, mock #৪ (৯০′-এর পুরো loop), ইংরেজির তুলনা। শেষে: ১০ আবেদন, ৩ process |

## প্রজেক্ট-নির্দিষ্ট নিয়ম

### তথ্য বদলানোর ক্রম

`legacy_and_wisdom/docs/ASSUMPTIONS.md` → `brainstorming/` (`dsa-prep-how-many-paths.md`, `*-what-works-for-faang.md`, `crack-remote-company-roadmap.md`, `how-to-write-my-cv.md`, `after-joining/11-next-jump.md`, `after-getting-response/`) → এই ফোল্ডারের `docs/`।

### ব্লক ফাইলের যে ছাঁচ parser মানে

- `# ব্লক ১ — নাম` — প্রথম H1; "— "-এর পরের অংশ rail-এ দেখায়।
- `*দিন ০০১–০৩০ · dip*` — H1-এর নিচের italic লাইন। শেষে `· dip` থাকলে হোমে Dip-এর সতর্কতা আসে।
- `> **ব্লক শেষে:** …` · `### দিন ০০৭ · শিরোনাম` · `- [ ] ৩০′ …` · `> **দিন শেষে:** …`
- দিনের নম্বর সব ব্লক মিলিয়ে পরপর না হলে build ভাঙে।
- `⚑` = মাইলফলক, `🔁` = ঝালাই হবে, শেষে `🧠 (নাম · নাম)`। নতুন 🧠 নাম লিখলে `app/lib/principles.ts`-এ যোগ করুন — তিন repo-তেই।

### Progress key

| key | মান |
|---|---|
| `sgc6:v1:start` | শুরুর তারিখ `"YYYY-MM-DD"` |
| `sgc6:v1:task` | কাজ শেষের তারিখ। id = দিন + কাজের **লেখা** থেকে hash — লেখা বদলালে ঐ কাজের টিক হারায় |
| `sgc6:v1:check` | দিন শেষ (`d007`) ও ব্লক শেষ (`b1`)-এর হ্যাঁ/না |
| `sgc6:v1:review` | 🔁 কাজের ঝালাইয়ের অবস্থা `{ base, step }` |

## চালানো

```bash
npm install
npm run dev      # http://localhost:3000
npm run build    # static export → out/
```

push করলে `.github/workflows/deploy.yml` সাইটটা GitHub Pages-এ তোলে।
