# IBS app competitor study: findings

Research date: 13 Oct 2026. The full report with screenshots is [`index.html`](index.html) (open it in a browser). This file is the short version.

## Apps reviewed

| App | Market | Type | Rating | Stands out for | Weak at |
|---|---|---|---|---|---|
| Gut-Buddy | India | Tracker + therapy + consults | 500+ downloads | Indian diet plans, IBS type/severity assessment, gut-brain therapies, GI and dietitian consults | Tiny user base; generic diary prompts |
| Guto | India | AI tracker | 4.3 (103) | Photo meal logging, mascot shows daily gut score, predictive alerts | Unproven AI claims |
| HealthifyMe | India | Nutrition | 4.6 (66.6K, IN) | Largest Indian food database, photo logging, AI nutritionist | No bowel, symptom or FODMAP tracking |
| Cara Care | Germany | All-in-one | 4.8 (4.7K) | Tracks everything, 12-week program, dietitian chat | US iOS build not updated since 2020; sleep capped at 8 h |
| Bowelle | Sweden | Symptom diary | 4.7 (2.2K) | 1-screen check-in, custom fields, doctor PDF | 1–5 stool scale, not Bristol; no correlations |
| mySymptoms | UK | Symptom diary | 4.6 (4K+) | Most granular logging, "top suspects" analysis, CSV/PDF export | Dated UI; analysis rarely tells users anything new |
| Bearable | UK | General tracker | 4.8 (IN) | "What hurts / what helps" ranked by %, factor chips | Not gut-specific |
| Monash FODMAP | Australia | Food guide | 4.2 (2.6K) | Traffic light per FODMAP group per serve | No meal-level FODMAP total |
| IBS Pal | UK | Scanner + tracker | 4.8 (6, IN) | Meal scan, FODMAP protocol, flare insights, gut audios | New; Western foods |
| Fig / Spoonful | USA | Food scanners | 4.7 / 4.6 | Ingredient rules: Can eat / Limit / Avoid | US groceries only |
| Nerva, Calm Gut, IBS Buddy, Mahana | Various | Gut-brain therapy | — | Hypnotherapy or CBT programs | No tracking; price complaints (Nerva) |

## How inputs are given

| Category | Patterns seen | Suggested for this app |
|---|---|---|
| Food | Free text, database search, photo AI, barcode, favourites | Search Indian dishes → portion stepper (katori / roti / cup) → onion / garlic / hing toggles; pills for frequent meals; photo optional |
| Bowel movement | Bristol picker, 1–5 scale, text descriptors | 7 Bristol icon buttons + time; pills for urgency / straining / mucus; "No BM today" |
| Symptoms | Icon tiles, 0–10 sliders, preset tag pills + custom tag | Pick symptoms as pills, then a slider only for the ones picked |
| Stress / mood | Faces, 1–10 number grid, emotion pills, sliders, severity blocks | Timed entry: 5 faces + cause pills (work, family, travel, sleep debt, eating out) |
| Water | Glass stepper, ml goal | +1 glass; separate pills for chai, coffee, buttermilk |
| Sleep | Hours slider, bed/wake time, quality, tags | Bed / wake time + quality faces |
| Exercise | Activity pills, type + intensity, steps | Pills (walk, yoga, pranayama, gym) + minutes + "after meal" toggle |

**Gut-brain:** stress is logged as its own entry in Bowelle, Cara, Monash, mySymptoms and Bearable. Gut-brain therapy sits in a separate tab (Gut-Buddy, IBS Pal) or a separate app (Nerva, Calm Gut, Mahana). No app asks what caused the stress or links a stress spike to a later flare.

## Gaps for an Indian user

- No app breaks a home-cooked dish (dal tadka, sabzi) into ingredients.
- Onion, garlic and hing in tadka are a major hidden fructan source, and no app flags them.
- No Indian portions (katori, roti count, ladle).
- Pulses aren't split by type: moong is lower FODMAP, rajma / chole / chana are high in GOS.
- Chai, curd, buttermilk and paneer aren't treated as dairy context.
- No tags for tiffin, restaurant, street food, fasting or festivals.
- No Hinglish search (bhindi, atta).

## Recommended scope

**Must have:** Indian dish database with ingredient breakdown and FODMAP per portion · tadka toggles · meal-level FODMAP total · Bristol 1–7 + "No BM today" · 1-screen daily check-in (food, BM, symptoms, water, sleep, exercise) · saved meals and "repeat yesterday" · food → symptom links with a 2–72 h lag · doctor PDF.

**Should have:** elimination → reintroduction tracker · personal Can eat / Limit / Avoid rules · drinks split out · yoga / walk / pranayama with timing · cycle, meds and supplements (isabgol, probiotics) · custom fields · keyboard-first desktop logging.

**Skip for now:** barcode scanning · hypnotherapy audio · calories and weight · gamified mascot · dietitian chat.

## Method and limits

- Apps came from web, App Store and Play Store research. The Reddit thread (r/WholeGutHealing) couldn't be opened from the research browsers.
- Screens are store marketing screenshots, not logged-in flows. Mobbin wasn't used.
- Ratings are from the US App Store unless marked IN (India), as of 13 Oct 2026.
