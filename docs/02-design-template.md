# ব্লক ২ — design doc-এর ছাঁচ

*দিন ০৩১–০৬০*

big tech-এর system design রাউন্ড ৪৫ মিনিট, মুখে, ঘড়ির নিচে। এই ব্লকে ছাঁচটা হাতে আসে: `srdtube`-এর **ইংরেজি design doc**, আর আগে থেকে তিন লেভেলে করা **URL shortener আর rate limiter ৪৫′-এ মুখে।** পাশাপাশি big tech-এর "Tell me about yourself", story → signal ম্যাপ, আর mock-এর সঙ্গী। লোকাল DSA দিন ০৪৭-এ শেষ, **দিন ০৫০ থেকে রিমোট DSA।**

মাইলফলক: `srdtube`-এর design doc (দিন ০৩৪), URL shortener মুখে (দিন ০৩৫), লোকাল DSA শেষ (দিন ০৪৭), mock-এর সঙ্গী (দিন ০৪৮), রিমোট DSA শুরু (দিন ০৫০)।

> **ব্লক শেষে:** ৪টা আবেদন, `srdtube`-এর ইংরেজি design doc, URL shortener আর rate limiter ৪৫′-এ বলা, রিমোট DSA চলছে, mock-এর সঙ্গী আছে?

### দিন ০৩১ · GitHub প্রোফাইল

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ GitHub প্রোফাইল পরিষ্কার — pin শুধু `dsa_prep_local_company`, `system_design`, `srdtube`; প্রোফাইল README-তে ইংরেজিতে ৩ লাইন: কে, কী বানান, *"Open to remote (UTC+6)"* 🧠 (Pareto)
- [ ] ১৫′ ইংরেজি — আজকের DSA প্রবলেমের approach জোরে

> **দিন শেষে:** GitHub-এ ঠিক তিনটা pin?

### দিন ০৩২ · state কোথায়

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ frontend design-এর মূল প্রশ্ন — **কোন state কোথায়:** component, service/store, নাকি URL; তিনটার প্রতিটায় নিজের কাজ থেকে একটা উদাহরণ, আর ভুল জায়গায় রাখলে কী ভাঙে 🔁 🧠 (Feynman · Concepts vs Facts)
- [ ] ১৫′ ইংরেজি — উদাহরণ তিনটা জোরে

> **দিন শেষে:** তিনটা জায়গার তিনটা উদাহরণ লেখা?

### দিন ০৩৩ · বার্তা

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ বার্তা ×১ — তৃতীয় আবেদনের কোম্পানিতে রেফারেলের জন্য
- [ ] ১৫′ ইংরেজি — আজকের DSA প্রবলেমের approach জোরে

> **দিন শেষে:** বার্তা গেছে?

### দিন ০৩৪ · design doc — srdtube

- [ ] ৬০′ ⚑ `srdtube`-এর **design doc, ইংরেজিতে, ছয় সেকশন** — কী বানিয়েছি → কতজন ব্যবহারকারী ধরে (quota থেকে হিসাব) → সিদ্ধান্ত (৫০-id batching, auto-pagination বন্ধ) → যা বাদ দিলাম → গঠন → কোথায় ভাঙবে; বুলেটে, এক বসায় 🧠 (Active learning · Trunk based knowledge)

> **দিন শেষে:** ছয় সেকশনই লেখা?

### দিন ০৩৫ · URL shortener, ৪৫′

- [ ] ১০′ সপ্তাহের হিসাব
- [ ] ৪৫′ ⚑ **URL shortener — ৪৫′ টাইমারে, মুখে, ইংরেজিতে** — লেখা বন্ধ, কাগজে আঁকতে আঁকতে; functional → reliable → scalable, প্রতিটা ধাপে কেন; ফোনে রেকর্ড। আগে থেকে জানা জিনিস, তাই এখানে পরীক্ষা জ্ঞানের নয় — বলার 🔁 🧠 (Test yourself · Deep work)

> **দিন শেষে:** ৪৫ মিনিটে তিন লেভেল পর্যন্ত গেছে?

### দিন ০৩৬ · বার্তা

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ বার্তা ×১
- [ ] ১৫′ ইংরেজি — কালকের রেকর্ডিং থেকে একটা বাক্য, এবার পরিষ্কার করে

> **দিন শেষে:** বার্তা গেছে?

### দিন ০৩৭ · কোথায় ভাঙবে

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ URL shortener রেকর্ডিং শুনে তিনটা জিনিস — কোথায় চুপ হলেন, scope কি শুরুতে বলেছিলেন, "কোথায় ভাঙবে" নিজে থেকে এসেছে কি; সবচেয়ে দুর্বলটা এক লাইনে 🧠 (Feedback)
- [ ] ১৫′ ইংরেজি — *"What happens if traffic grows 10×?"* — সহজ উত্তর আগে

> **দিন শেষে:** সবচেয়ে দুর্বল জায়গাটা লেখা?

### দিন ০৩৮ · Tell me about yourself

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ ৬০ সেকেন্ডের **"Tell me about yourself"** ইংরেজিতে — এখন কী করেন (একটা সংখ্যাসহ) → কীভাবে এলেন → কেন এই পদ; তারপর পাঁচবার জোরে 🔁 🧠 (Active learning)
- [ ] ১৫′ ইংরেজি — ২ মিনিট নিজের কাজ নিয়ে, রেকর্ড; ফাইলটা `baseline` নামে রেখে দিন — দিন ১৭৫-এ তুলনা হবে 🧠 (Feedback)

> **দিন শেষে:** `baseline` রেকর্ডিং রাখা আছে?

### দিন ০৩৯ · news feed UI, মুখে

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ *"Design a news feed UI"* — ছয় ধাপে ইংরেজিতে জোরে: চাহিদা → component → state → ডেটা আনা ও cache (পাতা ধরে আনা) → performance (লম্বা তালিকা) → accessibility; কাগজে আঁকতে আঁকতে 🔁 🧠 (Chunk the subject · The power of senses)
- [ ] ১৫′ ইংরেজি — কোন ধাপে সবচেয়ে কম বলার ছিল

> **দিন শেষে:** ছয় ধাপের সবগুলোয় অন্তত দুটো কথা?

### দিন ০৪০ · mock-এর সঙ্গী খোঁজা

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ mock interview-এর সঙ্গী — ইংরেজিতে DSA বা design interview নিতে পারে এমন ৩ জনের নাম, তিনজনকেই বার্তা: দিন ১০৪ থেকে মাসে একবার ৪৫′; বদলে আপনিও তার interviewer হবেন 🧠 (Community)
- [ ] ১৫′ ইংরেজি — আজকের DSA প্রবলেমের approach জোরে

> **দিন শেষে:** তিনজনকে বার্তা গেছে?

### দিন ০৪১ · rate limiter, ৪৫′

- [ ] ৪৫′ **rate limiter — ৪৫′ টাইমারে, মুখে, ইংরেজিতে** — প্রশ্ন আর scope আগে, তারপর সহজ কাজ-করা ডিজাইন, তারপর ধাপে ধাপে; রেকর্ড 🔁 🧠 (Test yourself · Deep work)
- [ ] ১৫′ রেকর্ডিং শুনে তিনটা জিনিস — চুপ, scope, "ভাঙবে"; দিন ০৩৭-এর দুর্বলতাটা এবার ঠিক হলো কি 🧠 (Feedback · Deliberate practice)

> **দিন শেষে:** আগের দুর্বলতাটা এবার কম?

### দিন ০৪২ · তৃতীয় আবেদন

- [ ] ১০′ সপ্তাহের হিসাব
- [ ] ৪০′ আবেদন — এ পর্যন্ত লক্ষ্য ৩টা; রেফারেল পেলে সেই পথে; সিভি ১০′ JD মেলানো; spreadsheet-এ সারি 🧠 (System vs goal)
- [ ] ১৫′ ইংরেজি — "Why this company?" — আজকের কোম্পানি নিয়ে ১ মিনিট

> **দিন শেষে:** এ পর্যন্ত ৩টা আবেদন?

### দিন ০৪৩ · বার্তা

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ বার্তা ×১ — প্রথম আবেদনে সাড়া না এলে একবার follow-up
- [ ] ১৫′ ইংরেজি — আজকের DSA প্রবলেমের approach জোরে

> **দিন শেষে:** বার্তা গেছে?

### দিন ০৪৪ · স্কেলের অনুমান — chat

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ পরের ব্লকের প্রথম সিস্টেম — **chat**-এর স্কেলের অনুমান আগে থেকে: কতজন একসাথে online, দিনে কত বার্তা, কত জায়গা; সংখ্যা নিজে ধরে নিন আর লিখে রাখুন কেন 🔁 🧠 (Test yourself)
- [ ] ১৫′ ইংরেজি — হিসাবটা জোরে, সংখ্যাসহ

> **দিন শেষে:** chat-এর অনুমান লেখা?

### দিন ০৪৫ · story → signal

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ story → signal ম্যাপ — দায়িত্ব, মতবিরোধ, ব্যর্থতা, অস্পষ্টতা, প্রভাব, শেখা; প্রতিটায় অন্তত একটা story? ফাঁক কোথায় — [`behavioural_interview`](../../behavioural_interview/docs/02-stories/06-story-signal-map.md) মিলিয়ে 🧠 (Chunk the subject)
- [ ] ১৫′ ইংরেজি — ফাঁকের signal-এর জন্য কোন story বদলানো যায়, ১ মিনিট

> **দিন শেষে:** ছয় signal-এর পাশে story-র নাম?

### দিন ০৪৬ · modal-এর accessibility

- [ ] ৩০′ DSA — আজকের দিন [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এ; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ **Modal, focus trap সহ** — খুললে focus ভেতরে, Tab ঘোরে ভেতরেই, Esc-এ বন্ধ, বন্ধ হলে focus আগের বোতামে; ছোট কোডে, টাইমার ২৫′ 🔁 🧠 (Deliberate practice · Parkinson's law)
- [ ] ১৫′ ইংরেজি — কেন focus ফেরাতে হয়, ৩০ সেকেন্ডে

> **দিন শেষে:** keyboard দিয়ে সব কাজ করে?

### দিন ০৪৭ · লোকালের ৩০টা — শেষ

- [ ] ৩০′ ⚑ DSA — [লোকাল DSA](https://sojibrd.github.io/dsa_prep_local_company/)-এর শেষ দিন; ৩০টা শেষ। নতুন প্রবলেম ঐ সাইটে আর নয় 🧠 (Deliberate practice · Have an endpoint)
- [ ] ১৫′ বার্তা ×১
- [ ] ১৫′ ইংরেজি — ৩০টার মধ্যে সবচেয়ে কঠিনটা, approach জোরে

> **দিন শেষে:** লোকালের ৩০টা শেষ?

### দিন ০৪৮ · ছয় story, সঙ্গী নিশ্চিত

- [ ] ৪০′ ছয় story, এলোমেলো — প্রশ্ন ব্যাংক থেকে ৪টা নতুন প্রশ্ন, একই signal-এর দুটো পরপর নয়; নোট বন্ধ, ইংরেজিতে রেকর্ড 🧠 (Interleaving · Test yourself)
- [ ] ১০′ ⚑ mock-এর সঙ্গী নিশ্চিত — কে, আর প্রথম mock-এর দিন (দিন ১০৪) 🧠 (Community)
- [ ] ১০′ ইংরেজি — কোন প্রশ্নে কোন story বাছলেন, কেন

> **দিন শেষে:** ৬ story, লোকালের ৩০ DSA, mock-এর সঙ্গী — তিনটাই আছে?

### দিন ০৪৯ · srdtube, ৪৫′

- [ ] ১০′ সপ্তাহের হিসাব — আজ ২০২৬-১১-০১ বা তার পরে হলে সিভির সারাংশে "nearly 4 years" → **"4 years"**
- [ ] ৪৫′ `srdtube` — **৪৫′ টাইমারে, মুখে,** নিজের design doc বন্ধ রেখে; রেকর্ড। নিজের সিস্টেম, তাই follow-up-এ গভীরে যাওয়ার সুযোগ — ওটাই নিন 🔁 🧠 (Test yourself · Deep work)

> **দিন শেষে:** doc না দেখে ছয় সেকশনই বলা গেছে?

### দিন ০৫০ · রিমোট DSA শুরু, Dip-এর নিয়ম

- [ ] ৩০′ ⚑ DSA — [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ শুরুর তারিখ = আজ, তারপর আজকের দিন; **টাইমার, সাদা editor, ইংরেজিতে জোরে** 🧠 (Deliberate practice · Test yourself)
- [ ] ১০′ `00-rules.md`-এর Dip-এর নিয়ম নিজের ভাষায় ৩ লাইনে — কাগজে, ল্যাপটপের পাশে 🧠 (The dip)
- [ ] ১৫′ ইংরেজি — "উত্তর দেরিতে এলে কী করব" — নিজেকে ১ মিনিট বলুন

> **দিন শেষে:** রিমোট DSA-র প্রথম দিন হয়েছে, Dip-এর নিয়ম কাগজে?

### দিন ০৫১ · যা বাদ দিলাম

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ **scoping** — URL shortener, rate limiter, `srdtube`: প্রতিটায় ৩টা জিনিস যা ইচ্ছাকৃতভাবে বাদ, আর কেন; interviewer সবচেয়ে বেশি নম্বর দেন যখন আপনি নিজে থেকে বলেন কী আলোচনার বাইরে 🔁 🧠 (Pareto)
- [ ] ১৫′ ইংরেজি — *"For this interview I'd leave out… because…"* — তিনবার

> **দিন শেষে:** তিন সিস্টেমে ৯টা "বাদ" লেখা?

### দিন ০৫২ · follow-up প্রশ্নে টেকা

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ story #১–#৩ — প্রতিটায় তিনটা follow-up: *"Why did you choose that?" · "What was the result, exactly?" · "What would you do differently?"*; রেকর্ড 🧠 (Test yourself)
- [ ] ১৫′ ইংরেজি — যে follow-up-এ থামলেন, সেটার উত্তর আবার, ধীরে

> **দিন শেষে:** ৯টা follow-up-এর উত্তর দেওয়া গেছে?

### দিন ০৫৩ · news feed UI, আবার

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ news feed UI আবার, এবার দিন ০৩৯-এর দুর্বল ধাপ ধরে — like চাপলে সঙ্গে সঙ্গে দেখানো (optimistic update) আর ব্যর্থ হলে ফেরানো; ২০′ টাইমার 🔁 🧠 (Deliberate practice · Parkinson's law)
- [ ] ১৫′ ইংরেজি — optimistic update কেন আর কখন নয়

> **দিন শেষে:** দুর্বল ধাপটা এবার ভরা?

### দিন ০৫৪ · follow-up

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ ৭–১০ দিন আগের আবেদনে একবার follow-up · বার্তা ×১
- [ ] ১৫′ ইংরেজি — আজকের প্রবলেমের approach জোরে

> **দিন শেষে:** follow-up গেছে?

### দিন ০৫৫ · চারটা ধারণা, ডক বন্ধ

- [ ] ৪৫′ `system_design`-এর concepts tracker-এর চারটা — **caching, load balancing, consistency, message queue** — প্রতিটা ইংরেজিতে ৮ লাইনে, **ডক বন্ধ করে**; আটকালে তবেই ডক খুলুন, তারপর বন্ধ করে আবার লিখুন। ২৫টা ডক পড়া ইনপুট, এটা আউটপুট 🔁 🧠 (Feynman · Test yourself)
- [ ] ১৫′ ইংরেজি — চারটার একটা, ঠান্ডা শুরুতে

> **দিন শেষে:** চারটা ধারণা ডক ছাড়া লেখা?

### দিন ০৫৬ · চতুর্থ আবেদন

- [ ] ১০′ সপ্তাহের হিসাব
- [ ] ৪০′ আবেদন — এ পর্যন্ত লক্ষ্য ৪টা; রেফারেল পেলে সেই পথে; সিভি ১০′ JD মেলানো 🧠 (System vs goal)
- [ ] ১৫′ ইংরেজি — "Why this company?"

> **দিন শেষে:** এ পর্যন্ত ৪টা আবেদন?

### দিন ০৫৭ · বার্তা

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ বার্তা ×১
- [ ] ১৫′ ইংরেজি — story #৬ (ব্যর্থতা) — "তারপর থেকে কী আলাদা করি" আরও নির্দিষ্ট করে

> **দিন শেষে:** বার্তা গেছে?

### দিন ০৫৮ · বেতন — উৎস ১

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ বেতনের তথ্য, উৎস ১ — big tech মানের কোম্পানিতে রিমোটে কাজ করা একজনকে জিজ্ঞেস: আপনার অভিজ্ঞতায় কোন level, কত, EOR নাকি contract; তারপর `00-rules.md`-এর ⏳ সীমা বসাতে পারলে বসান 🧠 (Trust this one person)
- [ ] ১৫′ ইংরেজি — *"What level is this role, and what's the range?"*

> **দিন শেষে:** একজনের উত্তর লেখা?

### দিন ০৫৯ · Why this company

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ২৫′ "Why this company?"-এর ছাঁচ — ওদের প্রোডাক্টের একটা নির্দিষ্ট জিনিস, ওদের স্কেলের একটা সমস্যা যা আপনাকে টানে, আর আপনার একটা কাজ যা ওখানে খাটে; তালিকার দুটো কোম্পানিতে ভরে 🔁 🧠 (Everything is a game)
- [ ] ১৫′ ইংরেজি — দুটোই জোরে, একটার পর একটা

> **দিন শেষে:** দুই কোম্পানির উত্তর লেখা?

### দিন ০৬০ · ব্লক ২-এর হিসাব

- [ ] ৩০′ DSA — আজকের দিন [রিমোট DSA](https://sojibrd.github.io/dsa_prep_remote_company/)-এ, ঘড়ি ধরে, ইংরেজিতে; ঝালাইও ঐ সাইটে 🧠 (Deliberate practice)
- [ ] ১৫′ ব্লক ২-এর হিসাব — ৪ আবেদন, `srdtube` doc, তিনটা ৪৫′-এর রেকর্ডিং, লোকালের ৩০ DSA, mock-এর সঙ্গী, চারটা ধারণা: কোনটা বাকি, এক লাইনে 🧠 (It's all in the frame)
- [ ] ১৫′ ইংরেজি — "Tell me about yourself", রেকর্ড — `baseline`-এর সাথে একবার শুনে দেখুন

> **দিন শেষে:** এ পর্যন্ত ৪টা আবেদন, আর তিনটা সিস্টেম ৪৫′-এ বলা?
