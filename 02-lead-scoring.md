# Lead-Scoring Model

The score combines **fit**, **intent**, and **negative signals**. It is a prioritization aid, not an automatic buying decision.

## Fit score

| Signal | Points |
|---|---:|
| Located in target geography | +10 |
| Target industry | +15 |
| Target company size | +10 |
| Decision-maker or strong influencer | +15 |
| Clear use case matches an offered solution | +15 |

## Engagement and intent score

| Action | Points |
|---|---:|
| Visits a high-intent product/pricing page | +8 |
| Downloads a relevant guide | +5 |
| Attends a webinar | +10 |
| Replies to a marketing email | +12 |
| Requests consultation/demo | +25 |
| Returns to the website within 14 days | +6 |

## Negative scoring

| Signal | Points |
|---|---:|
| Student/vendor/job-seeker intent | −20 |
| Personal email where business email is required | −8 |
| No meaningful activity for 30 days | −10 |
| Unsubscribed or invalid email | Suppress |
| Existing open opportunity | Remove from acquisition nurture |

## Thresholds

- **0–24:** early-stage lead; educational nurture.
- **25–49:** engaged lead; solution-focused nurture.
- **50–69:** MQL review queue.
- **70+:** priority MQL when mandatory fit criteria are also met.

## Safeguards

- Add caps to repetitive actions such as email opens and page views.
- Do not treat email opens as strong intent because tracking can be unreliable.
- Require at least one fit criterion and one intent event for MQL creation.
- Review thresholds monthly using accepted, rejected, won, and lost outcomes.
- Record the scoring reason so sales can understand why the lead was routed.

