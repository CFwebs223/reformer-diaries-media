# The Impulse-Savings App: An Honest Assessment

**Prepared for:** the founder (16)
**Date:** August 2026
**Market:** South Africa first
**Instruction given:** "Be brutal with me."

---

## 0. The one-paragraph verdict

The behavioural insight is real and it is good. The product you described — a "vault" that holds people's savings — is illegal for you to build, and not in a way you can lawyer around. Under the Banks Act 94 of 1990, taking money from the public with a promise to repay it is the business of a bank, and you need a banking licence to do it. That is the wall. But there is a version of this that is legal, costs about R5,000 to launch, and tests the only thing that actually matters — *will anyone change their behaviour?* — before you spend a cent on the hard version. Build that. Your idea does not die here; the word "vault" does.

---

## 1. The things you said that are wrong

You asked for criticism. Here it is, in order of how much money each error would cost you.

### 1.1 "They can transfer it into a savings account in the vault"

This is the expensive one. The moment you hold a customer's money and promise to give it back, you are conducting the business of a bank. The Banks Act gives "deposit" a deliberately wide meaning: an amount of money paid by one person to another, subject to an agreement that an equal amount or part of it will be repaid. That is exactly what you described. Registration is overseen by the Prudential Authority; conduct by the FSCA.

You will not get a banking licence. Nobody gets a banking licence with no capital. This is not a "get a lawyer and find a loophole" problem — it is the single most heavily enforced boundary in financial services, because it is the one that wipes out ordinary people's savings when it goes wrong.

**What this kills:** money sitting in an account you control.
**What this does not kill:** everything else about the idea.

### 1.2 "I don't think there's lots of expenses to run the app"

Software is cheap. Regulated software that touches money is not. Your real cost line is not servers — it is compliance, support, fraud, and refunds. The moment a single user says "my R2,000 is missing," you have a problem that costs more than a year of hosting, whether or not you were at fault.

Also: Apple takes 15% of every subscription (under the Small Business Program, below $1M/year), 30% above it. Budget from net, not gross.

### 1.3 "Forty grand a month" for a subscription

I am reading this as **R40/month** (~$2.15) — "forty grand" would be R40,000, which would be roughly the price of a used car, monthly. R40 is a sound price. It's below the psychological threshold, it's less than one of the coffees you're asking people to skip, and it's trivially justifiable: *if this app makes you skip one R45 coffee a month, it has paid for itself.* That is a genuinely strong pitch. Keep the price.

### 1.4 "The paid tier is nothing out of this world different from the free tier"

This guarantees you make no money. The 2026 benchmark: freemium apps convert to paid at a median of **2.1%** by day 35. Hard paywalls convert at **10.7%** — roughly 5× better. A free tier that already does the job converts at well under 1%.

You need a free tier that creates the habit and a paid tier that people want *because* the habit worked. More on the specific split in §6.

### 1.5 "Those people, trust me, they don't need to save"

Two problems. First, it is factually backwards — the person agonising over a R45 coffee is precisely the person for whom R45 matters. The person who doesn't notice R45 is the one who doesn't need you. Your ideal user is *exactly* the constrained one.

Second, and more practically: if you ever say this in an interview, on a podcast, or in a pitch, it will be the only sentence anyone quotes. In South Africa, in a product about money, it is a brand-ending sentence. Cut it from your vocabulary now, while the stakes are a conversation with an AI.

### 1.6 "My ambition is my strength and there's not a flaw"

Ambition is table stakes. Every single person who has ever failed at a startup was ambitious — that's why they started one. Ambition is what gets you to the starting line; it is not a differentiator, and it is not a moat.

Your actual unfair advantages, which are real, are listed in §8. Ambition isn't one of them. "There's not a flaw" is the flaw: it's the belief that stops you looking for the thing that kills you, which in your case was sitting in §1.1 the whole time.

### 1.7 "It's a billion dollar idea"

Let's do the arithmetic, because you should see it rather than be told.

At R40/month, after Apple's 15% cut, you net about R34/month ≈ **$22/year per paying subscriber**.

$1,000,000,000 ÷ $22 = **45 million paying subscribers.**

For scale: that would place you among the ten largest consumer subscription apps on earth. South Africa's entire banked adult population is roughly 35 million people — you could convert *every banked adult in the country to a paying subscriber* and not reach a quarter of the way there.

Now the achievable version of the same ladder:

| Paying subscribers | Monthly (R) | Annual (R) | Annual (USD) | What this is |
|---|---|---|---|---|
| 100 | 4,000 | 48,000 | ~$2,600 | Proof the behaviour exists |
| 1,000 | 40,000 | 480,000 | ~$26,000 | More than most SA graduate salaries |
| 10,000 | 400,000 | 4,800,000 | ~$260,000 | A real business. You are 19. |
| 100,000 | 4,000,000 | 48,000,000 | ~$2,600,000 | A company with staff, and acquirable |

**10,000 paying subscribers by the time you're 19 would be an extraordinary outcome** and puts you in a position where the billion-dollar conversation can begin — with investors, a banking partner, and other markets. Aim at 1,000 first. The billion is a consequence, never a plan.

---

## 2. The thing nobody told you: this already exists

Qapital, a US savings app, has a feature called the **Guilty Pleasure Rule**: you nominate a guilty pleasure, and every time you give in to it, a set amount is moved to savings. That is your idea, shipped, years ago.

Acorns built a multi-billion-dollar company on the adjacent insight (round-ups). Chime, Monzo and Revolut all ship "vaults" or "pots." Locally, **Franc**, **EasyEquities**, **Stash by Liberty** and **StokFella** all occupy parts of this space. And critically: **GoTyme Bank** (formerly TymeBank, rebranded January 2026) already gives every customer up to **20 named GoalSave pockets** paying **6% standard, 10% with 10 days' notice** — instant, free, inside an app they already have.

**Read that carefully, because it's your real competitive problem.** You are proposing to build a savings vault that will pay 0%, that people must be talked into installing, when their bank already offers 20 of them at 6–10% inside an app they open weekly.

**This does not kill your idea, and here is exactly why.** Every product listed above automates savings *invisibly* — round-ups, scheduled sweeps, rules that fire in the background. Yours is the only one built around a *conscious moment of refusal*. The user isn't saving passively; they're standing in the queue, wanting the thing, and choosing not to. That moment — the deciding, the small win, the receipt of it — is psychologically different from a round-up, and it is the only part of this that is genuinely yours.

So the product is not a vault. **The product is the moment.** The vault is a commodity your users' banks already provide better than you ever will. Build the moment; let the bank hold the money. That reframe simultaneously solves your legal problem, your interest-rate problem, your security problem and your cost problem, which is how you know it's the right one.

---

## 3. The hard part is not the code. It's the behaviour.

Your product asks a user, at the exact instant they want a burger, to instead open a savings app.

That is one of the hardest behaviours in consumer psychology. The moment of craving is the moment of *lowest* willingness to be lectured about money. You are competing with the burger, and the burger is winning — that's the entire premise of your app.

The benchmark you're up against: **finance apps retain 4.2% of installs at day 30.** Ninety-six out of a hundred people who download your app will not be using it a month later. That is the industry, not a worst case.

Design implications that follow directly:

- **The log must take under three seconds.** Amount, one tap, done. Category optional. Any friction and it doesn't happen — the burger has a two-second head start.
- **Never moralise.** No "you've overspent." The app's voice is a friend who's impressed, not a parent who's disappointed.
- **The reward must be immediate and visible.** The running total is the dopamine. Animate it. Make the number go up harder than it deserves.
- **Widgets and lock screen.** The app that must be opened will not be opened. Log from the lock screen.
- **Assume they fail.** They'll buy the coffee. If the app punishes that, it's uninstalled. Streaks that break forever are retention poison.

**Test this before you write code.** Get 20 people. Give them a WhatsApp number. For two weeks, ask them to message you every time they skip a purchase. No app, no build, nothing. If fewer than half message you even once, the behaviour doesn't exist and no amount of engineering creates it. **That test costs R0 and one weekend, and it is the single highest-value thing in this document.**

---

## 4. What you can legally build, in three versions

### V0 — The Ledger *(build this. now.)*

The app **never touches money**. The user logs the impulse; the app keeps the running total, the streak, the insights. Once a week it sends one push: *"You skipped R380 this week. Move it."* — with a deep link straight into their own banking app.

- **Regulatory exposure:** effectively zero. You hold no funds, give no advice, take no deposits.
- **Cost to launch:** ~R5,000.
- **Buildable by you, with AI, this year:** yes.
- **Honest weakness:** the money doesn't move automatically, so some users won't move it. *This is the point.* V0 measures whether the behaviour exists before you spend R200,000 finding out it doesn't.

### V1 — Payment Initiation

A licensed PSP (Stitch, Ozow) initiates a transfer from the user's account to *their own* savings account. Money never rests with you.

- **Requires:** registered company, merchant agreement, FICA, adult director.
- **Economics:** Ozow charges ~1.5% Instant EFT, minimum R1. On a R45 coffee that's a 2.2% fee — so sweep **weekly in one lump**, never per-transaction.
- **The wall:** App Store Guideline **3.2.1(viii)** — apps for financial trading, investing or money management should be submitted by the financial institution performing the service, with the necessary licences. The clause that previously allowed a public-API workaround **has been removed.** Guideline 5.1.1 adds that highly-regulated services should come from a legal entity, not an individual developer.
- **Realistic cost:** R80,000–R250,000.

### V2 — Bank Partnership

Partner with a licensed bank; the vault is legally *their* product, your app is the interface. This is the only architecture where a real "vault" exists.

- **Requires:** a company with traction, lawyers, and a bank that wants you.
- **Cost:** R500,000+, 12–24 months.
- **You do not get here without V0 succeeding first.** A bank will not take a meeting on an idea. It will take a meeting on 10,000 engaged users.

---

## 5. Money: what this actually costs

### V0 launch (do this)

| Item | Cost (ZAR) |
|---|---|
| Apple Developer Program | ~R1,800/yr |
| Google Play (once-off) | ~R450 |
| Domain | ~R300/yr |
| Backend (Supabase/Firebase free tier) | R0 |
| Company registration (CIPC, Pty Ltd) | R175–R500 |
| Terms of Service + POPIA privacy policy | R0–R5,000 |
| **Total to be live on the App Store** | **~R3,000–R8,000** |

That is genuinely within reach. This is the good news, and it's why V0 is the answer.

### Costs that appear later

| Item | Cost (ZAR) |
|---|---|
| Trademark, 1 class (DIY filing ~R590; attorney) | R3,000–R8,000 |
| Annual accounting + CIPC returns | R2,000–R8,000/yr |
| Security penetration test (**mandatory before V1**) | R15,000–R40,000 |
| Backend at ~10,000 users | ~R400–R1,500/mo |
| Customer support (your time, then someone's) | rises fastest |

### The cost you're not budgeting for

**Your time.** Two years of evenings and weekends while finishing school. That's the real price, it's non-refundable, and it's the one that actually decides this.

---

## 6. The subscription, redesigned

Your instinct — cheap, accessible, not radically different — produces a 0.5% conversion rate. Here's the split that works:

**Free forever:** unlimited impulse logging, one goal, running total, weekly summary. *Everything needed to build the habit.* Never cripple this — the habit is what creates the willingness to pay.

**Pro — R40/month:** multiple goals, auto-sweep reminders with bank deep-links, home-screen and lock-screen widgets, "what this becomes in 5 years" projections, Partner Mode (save with a friend/partner), full history and export, Year in Review.

**The pitch:** *"Skipped Pro costs less than one coffee. It exists because you skipped four."*

Two mechanics that raise conversion sharply, from the same benchmark data:
- **Offer a long trial.** Trials of 17–32 days convert at ~42.5% versus ~25.5% for trials under 4 days — roughly 70% better. Use a 30-day trial.
- **Paywall after the first win**, not on install. The moment they see their first R500 total is the moment the subscription makes sense.

---

## 7. Security: how you avoid the headline

You asked how to make sure you don't get hacked and nobody's money is lost. The honest answer is structural, not technical.

### The principle: you cannot lose what you never hold

Every serious risk you asked about — theft, misplacement, loss — requires you to be holding money or credentials. V0 holds neither. That single architectural decision eliminates more risk than any amount of security engineering you could buy. **It is the best security decision available to you, and it's free.**

Corollaries, which are absolute:
- **Never build a screen that asks for banking username and password.** Not once, not "temporarily." If you need bank data, use a licensed aggregator's hosted flow.
- **Never store card numbers.** Apple/Google handle billing. You never see a card.
- **Collect no ID documents in V0.** No KYC means no honeypot. The July 2025 breach that exposed ~13,000 government IDs and verification selfies happened because an app collected them and left the bucket open.

### About AI-written code — the direct answer

You asked whether it's safe to have Claude build this. Here is the honest version:

**AI can write secure code. You cannot currently tell whether it did.** That gap — review capacity, not generation capacity — is the actual risk.

The evidence is not ambiguous. A 2026 scan of **1,072 AI-built apps found 98% had at least one security flaw** — only 26 were clean. Among Supabase apps, **83% of database exposures traced to one misconfiguration: Row Level Security not enabled.** One founder who said he hadn't written a line of code exposed **4.75 million records** by shipping the database key in client-side JavaScript with no RLS. A separate scan found ~10% of one platform's public apps leaking user data.

Notice the pattern: none of these were clever attacks. They were **missing configuration** — the app worked perfectly, and was wide open. AI writes code that *works*; "works" and "is safe" are different tests, and only one of them is obvious from using the app.

### The checklist — verify every one of these yourself

1. **Row Level Security enabled on every table, with policies tested.** Log in as user A, try to fetch user B's data by changing the ID in the request. If you get data, you are the next case study. Test this on every table, every release.
2. **No secrets in client code, ever.** Anything shipped in the app is public — assume users can read it. Only the `anon` key belongs client-side; `service_role` is server-only.
3. **No secrets in git.** Check now: `git log -p | grep -iE "api[_-]?key|secret|password"`. If you find one, rotate it — deleting the file doesn't remove it from history.
4. **Every API endpoint checks who is calling.** The most common flaw: the endpoint trusts the ID you send it.
5. **Server-side validation.** Client-side checks are UI, not security — anyone can bypass them.
6. **Rate limiting on login and OTP.** Otherwise your SMS bill becomes an attack vector.
7. **Delete-account works and actually deletes** (App Store 5.1.1 requires it; POPIA does too).
8. **POPIA compliance:** collect the minimum, state it plainly, appoint an Information Officer, have a breach plan. **If you allow under-18 users, POPIA treats children's data as special personal information requiring a guardian's consent — read this carefully, since it likely describes your own friends, your first users.**
9. **Before V1 touches any money: pay for a penetration test.** R15,000–R40,000. Non-negotiable.

**A rule to hold to:** never let Claude — or any AI — write a security control you don't understand. Ask it to *explain* the control until you do. If you can't explain to a friend how your app stops user A reading user B's data, you don't know that it does.

---

## 8. Being 16: the legal blocks, and the real advantage

### What you cannot do (SA law)

- **You cannot be a director of a company.** The Companies Act makes an unemancipated minor ineligible. Directors need contractual capacity, which you don't have until 18.
- **You cannot enrol in the Apple Developer Program.** It requires the age of majority — it's a binding contract. Apple permits a **parent or guardian to hold the account** with you developing under their supervision (13+).
- **You cannot sign the PSP, bank or hosting agreements** that V1 requires.

### What you can do

- **You can own the company.** Minors can hold shares (via a guardian or a trust). This matters more than the director title — *ownership is the part that's worth money.*
- **Structure:** parent or trusted adult as director and signatory, **you as majority shareholder**, in writing, from day one. Not a favour, not a handshake — a document. Get it drafted while everyone is friendly and the company is worth nothing. This is the cheapest insurance you will ever buy.
- **You can build, design, market, and run all of it.** Nothing above stops you doing the work.
- **You turn 18 in two years** — roughly the time V0 needs to prove itself anyway. The timing is better than it looks.

### The advantage nobody can copy

You are a 16-year-old building a savings app for people who overspend on small things. **That is the marketing.** Every founder story in fintech is a 34-year-old ex-banker. Yours is not, and it cannot be replicated by a competitor with more money — which is the definition of a real advantage, and the only one on your list that qualifies.

Use it honestly. Build in public from day one.

---

## 9. Marketing with R0

Paid acquisition is closed to you — fintech CAC runs $50–200 per user. You'd spend your entire budget on nine users. So the entire strategy is organic, and organic means one thing: **the product must be inherently watchable.**

You're fortunate: it is. "I didn't buy the thing" is a *format*, not an ad.

### The strategy

1. **Harvest existing demand, don't create it.** "No-buy year," "loud budgeting," "cash stuffing," "no-spend challenge" are enormous, active communities. They already do this manually, with spreadsheets and envelopes. Go where they are; don't build a new audience.
2. **One account, one format, 90 videos in 90 days.** Not five platforms. Pick TikTok. Post daily. The first thirty will be bad — that's the tuition.
3. **Build in public.** "Day 40 of building a savings app. I'm 16. Here's what broke today." This grows an audience *while* you build and gives you 500 people to launch to instead of zero.
4. **The screenshot is the ad.** Make the running total beautiful enough to post unprompted. Add a share button that generates a clean image. Every user becomes a channel.
5. **Waitlist before you build.** Landing page this week. If 500 people sign up, you have something. If 12 do, you've learned that for free.
6. **South African media loves this story.** A 16-year-old fintech founder is a segment on every local business podcast and personal-finance publication. Free, and it converts far better than ads.

### What not to do

Don't buy followers. Don't call it "the future of finance." Don't launch on Product Hunt — wrong audience entirely. Don't build a Discord before you have users. Don't spend three months on a logo.

---

## 10. Twelve months, with gates

Each phase has a gate. **If you don't pass it, you don't advance — you fix or you stop.** The gates are the whole point; skipping one costs you a year.

**Weeks 1–2 — Validate (R0)**
Landing page. WhatsApp test with 20 people. Post the first 14 build-in-public videos.
**GATE:** ≥10 of 20 log an impulse unprompted in week one. *If not, the behaviour doesn't exist. Stop and rethink.*

**Weeks 3–8 — Build V0**
Log an impulse in under 3 seconds. Running total. Weekly summary. One goal. Nothing else. Adult sets up the Apple account and CIPC registration.
**GATE:** Three friends use it for a week without you reminding them.

**Weeks 9–12 — Ship**
App Store + Play Store. Security checklist in §7, every line. Launch to your waitlist and your build-in-public audience.
**GATE:** 500 installs.

**Months 4–6 — Retention**
Ignore growth entirely. Fix only D7/D30 retention. Widgets, notifications, streaks, the share image.
**GATE:** D30 retention above 15% — over 3× the finance-app median. *If you can't beat this after three real attempts, this is not a habit product and no amount of marketing fixes it.*

**Months 7–9 — Monetise**
Ship Pro with a 30-day trial. Paywall after the first win, not on install.
**GATE:** conversion above 3%.

**Months 10–12 — Decide**
With 10,000 users and 3% paying: R12,000/month, and something real. Now the V1/V2 conversation begins, with numbers, and a bank might actually take the meeting.

---

## 11. The name

**"Simple Save" is a weak name.** It's descriptive, which makes it hard to register as a trademark; the .com went a decade ago; and it's unsearchable — it competes with every article ever written containing the words "simple" and "save."

Name the **moment**, not the vault. The vault is a commodity. The moment is yours.

| Name | Why |
|---|---|
| **Skipped** ⭐ | "I skipped R380 this week." A verb, a badge, and a complete sentence in a screenshot. |
| **Instead** | "I bought this instead." Leans into the trade-off. |
| **Swerve** | Young, energetic, memorable. |
| **Rather** | Quiet, confident, very South African in tone. |
| **Almost** | "Almost bought it." Wry, and it owns the moment precisely. |

**My pick: Skipped.** It's a verb your users will say out loud without being prompted — which is the only naming test that matters.

**Before you commit to anything:** check CIPC (company name), the CIPC trademark database, both app stores, the .co.za and .com domains, and Instagram/TikTok handles. Do all six. Do them in one sitting, before you print a sticker or design a logo.

---

## 12. When to quit

Nobody tells sixteen-year-olds this, so I will. **Set the exit conditions now, while you're calm.** The purpose isn't pessimism — it's to stop you spending three years on something the data told you to stop at month four.

Stop, or fundamentally rethink, if:
- Fewer than half your 20 testers log a single impulse in week one *(the behaviour doesn't exist)*
- D30 retention stays under 10% after three genuine redesigns *(it's not a habit)*
- Paid conversion is under 1% at 1,000 users *(there's no business)*
- Twelve months in with under 1,000 users and no growth *(the market has answered)*

Quitting on evidence at month six is not failure. It's the correct decision, made early, by someone who will still be 17 with a shipped app, an audience, and the ability to build the next thing in a fraction of the time. **That outcome is genuinely excellent, and you should be willing to accept it** — the founders who lose years are the ones who decided in advance that quitting was impossible.

---

## 13. Do these seven things this week

1. **Run the WhatsApp test.** 20 people, 14 days. Costs nothing. Highest-value item here.
2. **Put up a landing page** with an email field. Carrd or Framer, free tier.
3. **Post your first build-in-public video.** Today. It will be bad. Post it.
4. **Check the name** across all six registries in one sitting.
5. **Have the conversation with your parent/guardian** — director, Apple account, and *your* shareholding in writing.
6. **Read §7 again** and write the security checklist somewhere you'll see it every time you build.
7. **Write your kill criteria on paper** and put it where you'll find it in six months.

---

## Closing

The strongest thing you did here was ask to be criticised. Most people ask to be agreed with, and they're the ones who spend two years building the illegal version.

Your instinct — that the moment of refusal is worth capturing — is genuinely good, and it is the one part of this nobody else has built well. Your execution plan was wrong in the specific ways above, but every one of them is fixable this week, and none of them touches the insight.

The billion dollars is not the goal. **Ten thousand people who saved money because of something you made, before you turned twenty, is the goal.** Get there and the rest becomes a conversation with people who bring their own capital.

Now go run the WhatsApp test. Everything else is downstream of what it tells you.

---

### Sources

- [Fintech regulation in South Africa – Lexology](https://www.lexology.com/library/detail.aspx?g=79d698f5-043a-43ad-8671-4316267d1fdb)
- [Banking regulatory framework in South Africa – Lexology](https://www.lexology.com/library/detail.aspx?g=9e58884d-a777-44b1-94e6-d43be73aad70)
- [Banks Act 94 of 1990 – South African Government](https://www.gov.za/documents/deposit-taking-institutions-act-6-mar-2015-1030)
- [Minimum requirements for company directors in South Africa – Legalese](https://legalese.co.za/what-are-the-minimum-requirements-for-company-directors/)
- [Minors as shareholders and directors](https://intersectconnect.com/minors-as-shareholders-and-directors/)
- [Apple Developer Program eligibility under 18 – Apple Developer Forums](https://developer.apple.com/forums/thread/704235)
- [App Store Review Guidelines – Apple](https://developer.apple.com/app-store/review/guidelines/)
- [Guideline 3.2.1(viii) discussion – Apple Developer Forums](https://developer.apple.com/forums/thread/704470)
- [State of Subscription Apps 2026 – RevenueCat](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026)
- [Finance App Benchmarks 2026 – Business of Apps](https://www.businessofapps.com/data/finance-app-benchmarks/)
- [We scanned 1,072 vibe-coded apps: 98% had security flaws – Symbiotic Security](https://www.symbioticsec.ai/blog/we-scanned-1-072-vibe-coded-apps-98-had-security-flaws)
- [Is Supabase Safe? RLS, anon vs service_role](https://vibeappscanner.com/is-supabase-safe)
- [Vibe Coding Cybersecurity Insight Report, January 2026 – SupaExplorer](https://supaexplorer.com/cybersecurity-insight-report-january-2026)
- [Qapital Review – DepositAccounts](https://www.depositaccounts.com/blog/qapital-app-review.html)
- [GoalSave – GoTyme Bank](https://www.tymebank.co.za/save-earn/goalsave/)
- [TymeBank GoalSave 2026 review – MoneyToday](https://moneytoday.co.za/compare/savings/tymebank-goalsave)
- [Comparing investment apps in South Africa – TechCabal](https://techcabal.com/2025/09/04/comparing-investment-apps-in-south-africa-2025/)
- [Ozow – EBANX Docs](https://docs.ebanx.com/docs/payments/guides/accept-payments/api/south-africa/ozow)
- [DebiCheck South Africa – Stitch](https://stitch.money/payment-methods/debicheck)
