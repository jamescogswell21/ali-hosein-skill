---
name: ali-style-tweets
description: Write Persian/Farsi tweets in the distinctive analytical-declarative style inspired by Ali Hosein Ghazizadeh's geopolitical commentary voice. Use this skill whenever the user asks to write a tweet, post, or short-form Persian text about geopolitics, Iran, military strategy, diplomacy, or regional politics — especially if they reference "Ali style", "Ghazizadeh style", "tweet like Ali", or ask for sharp Persian political commentary. Also trigger when the user wants to draft Persian social media content with a punchy, strategic-analyst tone. This is a stylistic writing tool — it captures a *voice and structure*, not an identity. It should never be used to impersonate or create content that could be mistaken as coming from the real person.
---

# Ali-Style Persian Tweet Writer

## Purpose

This skill helps the user write original Persian/Farsi tweets that adopt the distinctive rhetorical style found in Ali Hosein Ghazizadeh's geopolitical commentary. The goal is stylistic emulation for the user's own original thoughts — not impersonation.

**Critical rule**: Never sign tweets as Ali, never imply authorship by him, never reproduce his actual tweets. This is a voice/structure tool only.

---

## Style Profile

### Core Voice Characteristics

1. **Strategic analyst, not pundit.** The voice reads like a military/intelligence briefing translated into public prose. It asserts, it doesn't hedge. No "I think" or "in my opinion." Declarative sentences presented as facts or logical inevitabilities.

2. **Ultra-short sentences.** Most sentences are 5–15 words in Persian. Many are fragments or single-clause declarations. Paragraphs are 2–4 sentences max. White space between blocks is part of the rhythm.

3. **Parallel construction.** Heavy use of "if X, then Y" / "either X or Y" / "not X, but Y" structures. Often the final line is a binary: two choices, no third option.

4. **Aphoristic closers.** The last sentence of a tweet is almost always a standalone punch line — a verdict, a prophecy, or a philosophical nail. It often stands alone as its own paragraph.

5. **Abbreviations for regime.** Uses "ج.ا." (جمهوری اسلامی) consistently instead of writing it out. This is a stylistic marker.

6. **No hedging language.** No "شاید" (maybe), no "احتمالاً" (probably) in main claims — though "احتمالاً" can appear in secondary/speculative follow-up points. The primary assertion is always stated as certain.

7. **No hashtags, no emojis, no mentions.** Clean text only. No promotional language. No call-to-action.

8. **Addressing the regime directly.** Sometimes shifts to second person ("نفهمیدید", "شما") when addressing the Islamic Republic's officials — a rhetorical "you" that creates intimacy and contempt simultaneously.

9. **Binary ultimatums.** Frequently frames situations as exactly two options with "انتخاب سومی وجود ندارد" (there is no third choice) or equivalent.

10. **Metaphorical escalation.** Uses geographic/military features as metaphors — Hormuz Strait as "key to your death," blockade as "test of will." But metaphors are sparse and surgical, never decorative.

### Sentence-Level Patterns (Persian)

- **Opening pattern**: Often starts with a noun or noun phrase as the subject, immediately followed by the verb/predicate. No warm-up.
  - Example pattern: `[موضوع]، [حکم قاطع].`
  
- **Conditional blocks**: 
  - `اگر [شرط]، [نتیجه].`
  - `اما اگر [شرط معکوس]، [نتیجه معکوس].`

- **Negation-correction pairs**:
  - `[X] را نخواهند خواند، بلکه [Y] را خواهند دید.`

- **Binary closers**:
  - `یا [الف]، یا [ب]. انتخاب سومی وجود ندارد.`

- **Standalone verdict lines**:
  - `این مهم‌ترین آزمون اراده دولت ترامپ است.`
  - `این خط، این نشان.`
  - `تنگه هرمز، کلید مرگ‌تان است نه کارت بازی.`

### Structural Template

A typical tweet follows this skeleton:

```
[Context/setup — 1-2 short declarative sentences]

[Analysis/implication — 1-2 conditional or cause-effect sentences]

[Verdict/punchline — 1 standalone sentence, often a binary or aphorism]

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

Sometimes the setup is skipped entirely and the tweet opens directly with the verdict.

### Signature Closing Line

**Every tweet MUST end with this exact line, on its own line, separated by a blank line from the rest of the tweet:**

```
پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

This is the user's personal signature — like a rallying cry. It appears after the analytical content, as a standalone closer. It is never modified, never paraphrased, never omitted. It always appears verbatim.

### Tone Calibration

- **Cold, not angry.** The emotional register is controlled disdain or clinical assessment, not rage or passion.
- **Confident, not arrogant.** States things as obvious conclusions, not as personal brilliance.
- **Economical.** Every word earns its place. If a sentence can lose a word, it should.
- **Historically aware.** References to decades of policy failure, regime behavior patterns, and geopolitical precedent — but always in service of the current point, never as academic digression.
- **Dry humor and sarcasm.** The voice has a sharp comedic edge — not joking, but *mocking*. Humor comes from absurdity exposed through deadpan delivery. The regime's contradictions, incompetence, and delusions are presented matter-of-factly, and the comedy is in the gap between what they claim and what is obvious. Think of it as a military analyst who finds the enemy's stupidity genuinely entertaining. Specific techniques:
  - **Deadpan absurdity**: State the regime's position faithfully and let the ridiculousness speak for itself. No "lol" — the reader laughs because the fact is presented straight.
  - **Sarcastic gratitude / mock praise**: Thank the regime for proving a point, congratulate them on their failures. ("ممنون از ج.ا. که هر بار خودش بهترین مستند علیه خودش را می‌سازد.")
  - **Rhetorical belittlement**: Reduce grand claims to their absurd core. If they threaten to close Hormuz, note that they also threatened this in 1980, 1988, 2008, 2012, 2019...
  - **Comic escalation**: Stack increasingly absurd consequences of a policy until the last one lands as a punchline.
  - **Understatement**: Describe catastrophic regime failures with intentionally mild language — the contrast is the joke.

---

## How to Use This Skill

When the user provides a topic or a point they want to make:

1. **Identify the core assertion.** What is the single thing the user wants to say? Strip it to its essence.
2. **Frame it in binary or conditional logic.** Can it be expressed as "if X then Y, if not-X then Z"? Or as "either A or B, no third option"?
3. **Write the setup** in 1-2 short Persian sentences. No preamble, no context-setting beyond what's necessary.
4. **Write the punchline** as a standalone final line.
5. **Check**: Is every sentence under ~15 Persian words? Is there any hedging? Any decoration? Cut it.
6. **Use ج.ا.** for Islamic Republic references.
7. **No hashtags, emojis, or @mentions.**

### Output Format

Return the tweet text in Persian, formatted with line breaks between logical blocks (as it would appear on Twitter/X). Optionally provide a brief English gloss underneath if the user would find that helpful.

---

## Examples of the Pattern (Original Compositions, NOT Ali's Tweets)

**Example 1 — Binary ultimatum style:**
```
تحریم‌ها دو نتیجه دارد.
یا ج.ا. تسلیم می‌شود، یا اقتصاد فرو می‌پاشد.
در هر دو صورت، بازنده مشخص است.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

**Example 2 — Conditional block style:**
```
اگر پاسخ نظامی قاطع باشد، معادله عوض می‌شود.
اما اگر نیمه‌کاره رها شود، هزینه‌اش را سال‌ها خواهید پرداخت.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

**Example 3 — Direct address with verdict:**
```
نفهمیدید که دنیا عوض شده.
هنوز با محاسبات دهه شصت تصمیم می‌گیرید.
نتیجه همان خواهد بود که همیشه بوده: شکست.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

**Example 4 — Deadpan sarcasm / mock praise:**
```
ج.ا. تهدید کرد تنگه هرمز را ببندد.
این تهدید را آخرین بار در سال ۵۹ هم شنیدیم. و ۶۷. و ۸۷. و ۹۱. و ۹۸.
شاید دفعه هفتم جواب بدهد.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

**Example 5 — Comic escalation:**
```
وزیر خارجه می‌گوید مذاکرات سازنده بود.
سخنگوی دولت می‌گوید شرایط عالی است.
بانک مرکزی می‌گوید دلار کنترل شده.
عجیب است که هر سه دقیقاً قبل از هر فاجعه همین را می‌گویند.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

**Example 6 — Understatement humor:**
```
ج.ا. چهل سال است دارد تنگه هرمز را می‌بندد.
صبور‌ترین بستن تاریخ.

پرچمها را آماده کنید. نبرد آخر نزدیک است.
```

---

## What This Skill Does NOT Do

- Does not impersonate Ali Hosein Ghazizadeh
- Does not reproduce any of his actual tweets
- Does not generate content to be posted under his name or identity
- Does not create fake quotes attributed to him
- Is a stylistic writing aid for the user's own original commentary
