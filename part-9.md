---
layout: default
title: Part 9 – Reference
---

# Part 9 – Reference

## 32. Annual reporting checklist

Print this page and tick the boxes as you go.

**Before you start**

- [ ] I can log in and my **Profile** shows the correct country.
- [ ] I know which **response year** I am reporting.
- [ ] I have collected the observed values, sources and evidence files for every disaggregation.
- [ ] For indicators never reported before, I have the **baseline values** and sources.

**For each pillar → each indicator (Apps → Indicators)**

- [ ] Baseline set (first time only) – all disaggregations, methodology and source filled.
- [ ] National target configured, if my country has one (optional).
- [ ] Correct **Response Year** selected in the coloured strip.
- [ ] Every disaggregation answered (all dots green, **N/N Complete**).
- [ ] Data source and evidence files attached.

**Programmatic part (Apps → Deliverables)**

- [ ] Deliverables of each pillar recorded and up to date.
- [ ] Projects / activities added with period, budget and results with achievement status.

**Success stories**

- [ ] At least one story per pillar written, reviewed and published.

**Review**

- [ ] Per Country dashboard shows a pillar score for every pillar.
- [ ] Indicator detail pages show the expected raw values and statuses.
- [ ] Pillars Dashboard shows the Overall Country Score (not **Not Available**).
- [ ] A CSV report has been exported and archived nationally (if reports are enabled).

## 33. Troubleshooting

| Problem | Likely cause | What to do |
|---|---|---|
| **I cannot log in** | Wrong email or password. | Use **Forgot Your Password?**. If you never received an account, ask your country administrator (there is no self-registration). |
| **Message: Please select a response year!** | No year selected in the coloured strip above the response form. | Select the **Response Year** and save again. |
| **The response form does not appear; I see Set Baseline instead** | The baseline is missing for this indicator, or a new disaggregation was added. | Complete the **Set Baseline** form (section 15). |
| **The year I need is not in the Response Year list** | The list starts the year after the baseline year and ends this year. | Check the baseline year. If it is wrong, contact the administrator. |
| **I saved a wrong value** | Saved answers are read only for country users. | Contact the platform administrator with the indicator, disaggregation, year and correct value. |
| **Dashboard still shows No Data after saving** | Scores are computed in the background and can take a few seconds. | Wait a moment and refresh the page. If it never appears, tell the administrator (the background worker may be stopped). |
| **Overall Country Score shows Not Available** | One or more pillars have no score for the year. | Enter data for at least one indicator in every pillar. |
| **A score is negative** | The value moved away from the target compared with the baseline. | Verify the value and the baseline. If both are correct, the red status is genuine. |
| **A score is above 100** | The target has been exceeded. | Nothing to do – this is good news. |
| **A page says 403 / access denied** | Your role does not include that page. | Ask your administrator to adjust your role. |
| **I cannot see other countries' data** | Country users see only their own country. | This is by design. Use **Country Comparison** for scores of other countries. |
| **Reports or Success Stories are missing from the menu** | Not included in your role. | Stories are still reachable via **Deliverables → Manage Stories**. Ask the administrator for report permissions. |
| **An uploaded file will not open** | Storage problem on the server. | Tell the administrator. |
| **The interface is in the wrong language** | Language preference. | Click the **EN / FR** badge at the top right. |
| **Message: You cannot delete yourself** | You tried to remove your own account. | Ask another administrator if your account must be removed. |
| **The page looks broken or old** | Browser cache. | Reload with Ctrl + F5, or try another browser. |

## 34. Frequently asked questions

**Which year do I choose as the response year?**

The year the data **refers to**, not the year you are typing it. A 2024 survey value belongs to response year 2024 even if you enter it in 2025.

**Can I enter data for several years?**

Yes. Change the **Response Year** and answer the disaggregations again for that year. Each year has its own set of answers and scores.

**Do I have to answer every disaggregation?**

Scores are only calculated from answered disaggregations, so an indicator with missing disaggregations gives an incomplete picture. Use **Skip** only temporarily and come back when you have the data.

**What is the difference between the common target and the national target?**

The common target is the same rule for all countries and is defined centrally. The national target is your country's own commitment; it is optional and only affects the National Dashboard.

**Why is the baseline as a percentage?**

The indicator-level baseline is a summary value expressed as a percentage. The disaggregation-level baselines can be in the unit of the disaggregation.

**Who can see my success story?**

Drafts are visible only inside the platform. Published stories are visible to everyone on the public website.

**Can I change the pillars, indicators or disaggregations?**

No. They are defined centrally by the platform administrator so that all countries report on the same basis.

**How do I get more accounts for my team?**

Country administrators can create accounts under **Set up → Users**. Otherwise contact the platform administrator.

## 35. Glossary

| Term | Definition |
|---|---|
| **Accelerate** | Yellow status: progress is being made, but too slowly to reach the target on time. |
| **Achievement ratio (R)** | Progress achieved divided by the share of time elapsed; 1 means exactly on pace. |
| **Actual value** | The observed value entered as an answer for a response year. |
| **Baseline** | The reference value in the baseline year from which progress is measured. |
| **Baseline year** | The year of the baseline value, usually the year before tracking started (2017). |
| **Common target** | The target set centrally for all countries. |
| **Deliverable** | A committed output under a pillar. |
| **Direction** | Whether the indicator should increase (+) or decrease (−) to improve. |
| **Disaggregation** | A component of an indicator answered separately (also called a question). |
| **End tracking year** | The year by which the target should be reached (for example 2025). |
| **Geometric mean** | The n-th root of the product of n numbers; used for the overall country score. |
| **Indicator** | A measurable statistic under a pillar. |
| **Maintain** | Green status: on track; keep the current pace. |
| **Methodology** | How a baseline value was obtained: Actual, Estimated, Modelled or Provisional. |
| **National label** | Your country's own wording for a disaggregation. |
| **National target** | An optional target set by your country. |
| **Pillar** | One of the four thematic areas of the Roadmap. |
| **Project / activity** | A programme contributing to a deliverable. |
| **Response score** | Progress of one disaggregation from baseline to target, in percent. |
| **Response year** | The year the entered data refers to. |
| **Reverse** | Red status: no progress or movement in the wrong direction. |
| **Start tracking year** | The first year for which responses are entered (baseline year + 1). |
| **Success story** | A published article about an achievement or good practice. |

## 36. Appendix A – Scoring formulas in detail

| Level | Formula | Notes |
|---|---|---|
| Response score (S) | S = (A − B) ÷ (T − B) × 100 | A = actual, B = baseline, T = target. If T = B: S = 100 when A ≥ T, otherwise 0. |
| Indicator score (I) | I = mean(S) over answered disaggregations | Per country and year. |
| Achievement ratio (R) | R = (I ÷ 100) × (Y_end − Y_base) ÷ (Y_resp − Y_base) | Y_end = end tracking year, Y_base = baseline year (country-specific if set), Y_resp = response year. R = 0 if Y_resp ≤ Y_base. |
| Indicator status | R > 0.9 → Maintain; 0.5 < R ≤ 0.9 → Accelerate; R ≤ 0.5 → Reverse | Default ranges; the administrator can change them in **Indicator Settings**. |
| Pillar score (P) | P = mean(I) over the pillar's indicators | Per country and year. |
| Overall country score | (P1 × P2 × P3 × P4) ^ (1 ÷ 4) | Requires all four pillar scores. |
| Comparison grade | A ≥ 75; B 60–74.9; C 50–59.9; D 35–49.9; E < 35 | Country Comparison page. |
| Regional status | ≥ 80 Maintain; ≥ 30 Accelerate; < 30 Reverse | Regional Comparison page. |
| Project score | period (0/1) + budget (0/1) + mean(result status 0/1/2) | Maximum 4. |
| Deliverable score | mean of project scores | |
| Pillar deliverable score | mean of deliverable scores | Colours: green ≥ 4, yellow 2–3.9, red < 2 (default **Pillar Settings**). |
| National scores | Same formulas with T = national target | Disaggregations without a national target are excluded. |

## 37. Appendix B – Answer types

| Type (set by the administrator) | What you see | Value used for scoring |
|---|---|---|
| Scale | Number box with a range, e.g. 0–5 | The number entered |
| Numeric | Number box with a maximum | The number entered |
| Percentage | Number box with **%** (0–100) | The percentage entered |
| Yes / No | Drop-down **No / Yes** | Yes = 1, No = 0 |
| Options | Drop-down list | The score attached to the chosen option |
| Checklist | Check boxes | Sum of the scores of the ticked items |

## 38. Appendix C – What a Country Admin can see and do

Default permissions of the **Country Admin** role. Your administrator can extend them.

| Area | Allowed |
|---|---|
| Per Country, Pillars Dashboard, National Dashboard | View own country |
| Country Comparison, Regional Comparison | View |
| Indicators app (baseline, national target, responses) | Own country |
| Deliverables app (deliverables, projects) | Own country |
| Success stories via Deliverables → Manage Stories | Own country; edit own stories |
| Users | View, create, edit, activate/deactivate and delete users of own country |
| Reports and Report Builder | Only if granted |
| Platform set-up (pillars, indicators, countries, regions, settings) | Not available – administrator only |

---

**End of manual. For platform support, contact your country focal point or the platform administrator.**

---

[← Part 8](part-8.html) · [Manual home](index.html) · [Home →](index.html)
