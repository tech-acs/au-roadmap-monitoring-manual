---
layout: default
title: Part 3 – Reporting on indicators (main workflow)
---

# Part 3 – Reporting on indicators (main workflow)

This is the core of the platform. Follow the steps in order.

## 12. The reporting cycle at a glance

```text
 ONE TIME PER INDICATOR                       EVERY YEAR PER INDICATOR
 ┌────────────────────┐   ┌──────────────────────┐   ┌───────────────────┐
 │ Step 3             │   │ Step 4 (optional)    │   │ Step 5            │
 │ Set the baseline   │──►│ Configure national   │──►│ Choose the        │
 │ (year + values)    │   │ target               │   │ response year     │
 └────────────────────┘   └──────────────────────┘   └─────────┬─────────┘
                                                               ▼
 ┌────────────────────┐   ┌──────────────────────┐   ┌───────────────────┐
 │ Step 7             │   │ Scores are computed  │   │ Step 6            │
 │ Review dashboards  │◄──│ automatically        │◄──│ Answer every      │
 │ and indicator page │   │ (a few seconds)      │   │ disaggregation    │
 └────────────────────┘   └──────────────────────┘   └───────────────────┘
```

**Before you start, gather:**

- the baseline value of every disaggregation for the baseline year (usually 2017), with its source;
- the observed value of every disaggregation for the year you are reporting, with its source;
- supporting documents (survey reports, statistical bulletins, PDFs, spreadsheets) to upload as evidence.

## 13. Step 1 – Open the Indicators app and choose a pillar

1. In the side menu, under **Apps**, click **Indicators**.
2. The **Manage Indicators** page shows one card per pillar. Each card tells you how many **Indicators** and how many **Disaggregation** items the pillar contains.
3. Use the **Search pillars…** box if you have many pillars.
4. Click **Manage** on the pillar you want to work on.

## 14. Step 2 – Select an indicator

The pillar page has two columns.

**Left column**

- **Back to Pillars** – returns to the pillar cards.
- The pillar name and a **Search indicators…** box.
- The **list of indicators**. Each item shows the indicator **code**, its name, the number of disaggregations ("questions"), a **Progress** bar and a status icon:
  - ▶ grey = no data yet for the selected year,
  - ⏱ yellow = in progress,
  - ✔ green = complete.
- **Pillar Progress** – overall completion for the selected year: **Disaggregation Answered** (for example 3/12) and **Indicators Completed**.

**Right column**

- Before you choose, it reads **Select an Indicator – Choose an indicator from the sidebar to begin answering assessment questions.**

**To select an indicator:** click it in the list. The right column then shows **one of two things**:

| What appears | Meaning | Go to |
|---|---|---|
| A red **Set Baseline** form | Your country has not set the baseline for this indicator yet (or a disaggregation was added and needs a baseline). | Step 3 (section 15) |
| The **response form** with a **Response Year** selector | The baseline exists. You can enter yearly data. | Step 5 (section 17) |

## 15. Step 3 – Set the baseline (first time only)

The baseline is entered **once per indicator** for your country. It is the reference point for all future scores, so enter it carefully.

1. Check the **Baseline Year**. It is pre-filled with the indicator's default baseline year (usually 2017). Change it only if your country's reference data is from another year.
2. Enter the indicator's overall baseline in the field labelled with the indicator code and name, **as a Percentage (%)**.
3. Under **Set Baseline on Disaggregation**, for **every** disaggregation listed:
   1. **Baseline Value** – the value in the baseline year (a number).
   2. **Methodology** – how the value was obtained. Choose one:
      - **Actual** – measured data (census, survey, administrative records),
      - **Estimated** – an estimate,
      - **Modelled** – produced by a statistical model,
      - **Provisional** – preliminary figure that may be revised.
   3. **Data Source** – where the value comes from (for example "National Statistics Office, Labour Force Survey 2017, table 4").
4. Click **Set Baseline** at the bottom.
5. A green success message appears and the page reloads on the same indicator, now showing the response form.

**What happens automatically**

- The **common target** for each disaggregation is calculated from your baseline (if the administrator defined the target as a formula) or shown as the fixed value. You can see it next to each disaggregation: **Common Target: … | National Target: …**.

> **Important** – Once saved, the baseline is **locked** in this screen and cannot be edited by country users. Double-check every value before clicking **Set Baseline**. If you must correct a baseline later, contact the platform administrator.

> **Note** – If the administrator later adds a new disaggregation to the indicator, the **Set Baseline** form reappears with your existing values pre-filled. Simply enter the baseline for the new disaggregation and click **Set Baseline** again.

## 16. Step 4 – Configure a national target (optional)

The **common target** applies to all countries. In addition, your country may define its own **national target** for any disaggregation. National targets feed the **National Dashboard** only; they never change the common scores.

The **Configure National Target** button is available:

- on the baseline form, next to each disaggregation that already has a baseline, and
- on the response form, at the top right of the current disaggregation card.

1. Click **Configure National Target**.
2. A **National Target** window opens. At the top you see the disaggregation text, its **Baseline Value** and the **Common Target** (read only).
3. **National Label** (optional) – a local name for this disaggregation, in your own wording. If you fill it in, this label replaces the disaggregation text on the response form.
4. Choose how the national target is defined:
   - **Fixed Value** – **Use a specific number as the target.** Enter the number in **Target Value**.
   - **Based on Baseline (Formula)** – **Calculate target using a formula based on the country baseline.** Use the **Formula Builder**:
     - click **BASELINE** to insert your baseline value as a variable;
     - click the operators **+ − × ÷ ^ ( )**;
     - click a function: **MIN( )**, **MAX( )**, **ROUND( )**, **CEIL( )**, **FLOOR( )**, **ABS( )**;
     - or type the formula directly, for example `BASELINE * 2`, `BASELINE + 100`, `MIN(BASELINE * 2, 500)`;
     - click **Clear** to start again. The formula **must** contain the word `BASELINE`.
5. Check the green box **Resolved National Target** – it shows the target the platform will actually use.
6. Click **Save National Target**.

> **Note** – If you save a national target after responses already exist, the national scores of those responses are recalculated automatically.

> **Tip** – Leave the national target empty if your country has not adopted a target of its own. **No national target** is a valid state.

## 17. Step 5 – Choose the response year

The response form starts with a coloured strip containing the **Response Year** drop-down.

1. Click the **Response Year** drop-down (it reads **Select response Year** when empty).
2. Select the year **the data refers to**, for example 2024 for a 2024 survey value. The list runs from the year after your baseline year up to the current year.
3. The form reloads and shows the answers already recorded for that year, if any.

> **Important** – You **must** select a year before saving an answer. If you forget, the message **Please select a response year!** appears and nothing is saved.

> **Tip** – The selected year is remembered for 30 days, so you do not have to select it again for every indicator. Always glance at the strip to confirm the year before entering data.

## 18. Step 6 – Answer each disaggregation

### 18.1 Understanding the response form

- **Header** – indicator code, pillar, name and description, and **Progress x/y Complete** (answered / total disaggregations for the year).
- **Disaggregation Progress** bar.
- **Navigation** – **‹** and **›** arrows, the text **Disaggregation 1 of N**, and one **dot** per disaggregation:
  - blue dot = the one you are on,
  - green dot = already answered,
  - grey dot = not yet answered.
  Click any dot to jump to that disaggregation.
- **Current disaggregation card** – its number, its text (or your national label), the **Configure National Target** button, and either the answer form or the saved answer.

The platform opens automatically on the **first unanswered** disaggregation for the selected year.

### 18.2 Enter an answer

1. Read the disaggregation text.
2. Fill in **Answer** (required). The type of field depends on the disaggregation:

   | Field shown | What to enter |
   |---|---|
   | Number box with a range, e.g. **(1-100)** | A numeric value within the range shown (decimals allowed). |
   | Number box with **%** | A percentage between 0 and 100. |
   | Drop-down **No / Yes** | Choose **Yes** or **No**. |
   | Drop-down with options | Choose one option from the list. |
   | Check boxes | Tick every item that applies. |

3. **Data Source** (recommended) – where the value comes from, for example **National Statistics Office 2024**. Up to 500 characters.
4. **Source Files** (recommended) – click the field and select one or more files as evidence (PDF, Word, Excel, images). Selected files are listed underneath; click **Remove** to drop one before saving.
5. **Additional Notes** (optional) – methodology remarks, caveats, definitions used. Up to 1000 characters.
6. Click **Save & Continue**. The message **Answer saved successfully!** appears and the form moves to the next disaggregation.
7. Repeat until every dot is green. The header shows **N/N Complete**.

**Other buttons**

- **Skip** – moves to the next disaggregation **without saving**. Use it when you do not have the value yet; you can come back later with the dots.

### 18.3 After saving

- The saved answer is displayed in the card: **Observed** value, **Source**, **Files** (with **View** and **Download** links), **Notes**, the calculated **Score** and the **Updated At** date.
- In the background the platform recalculates the response score, the indicator score and the pillar score for that year. This usually takes a few seconds. Refresh the page if a dashboard does not show the new score immediately.

> **Important** – A saved answer for a given year is shown as **read only** on this screen. Check your values before saving. If you saved a wrong value, contact the platform administrator to have it corrected.

> **Tip** – Enter data for one indicator completely (all dots green) before moving to the next one. The **Pillar Progress** box on the left tells you how much of the pillar is done.

## 19. Step 7 – Review your progress and results

After entering data, check the results in this order:

1. **Indicator list (left column)** – the status icon of the indicator should have changed and the progress bar should show a value.
2. **Per Country dashboard → View** on the indicator (section 7.2) – confirm the **Raw Value**, **Baseline**, **Common Target** and **Common Response Score** of each disaggregation, and read the **Performance Status**.
3. **Pillars Dashboard** (section 8) – see the indicator score in the year column and open the **score breakdown** to see all the numbers used.
4. If you configured national targets, check the **National Dashboard** (section 9).

## 20. How your scores are calculated

You do not need to calculate anything yourself, but understanding the logic helps you interpret the dashboards.

### 20.1 Response score (per disaggregation)

> **Response score = (Actual − Baseline) ÷ (Target − Baseline) × 100**

- **0** means no progress since the baseline.
- **100** means the target has been reached.
- **Above 100** means the target has been exceeded.
- **Negative** means the value moved **away** from the target.
- The formula works for both directions. For an indicator that should **decrease** (for example an unemployment rate), the target is lower than the baseline and the same formula still gives positive progress when the value goes down.
- Special case: if the target equals the baseline, the score is 100 when the actual value has reached the target and 0 otherwise.

### 20.2 Indicator score

> **Indicator score = average of the response scores of all answered disaggregations for the year**

### 20.3 Achievement ratio (R) and performance status

The achievement ratio compares the progress achieved with the time elapsed in the tracking period.

> **R = (Indicator score ÷ 100) × (End year − Baseline year) ÷ (Response year − Baseline year)**

- **R = 1** means you are exactly on pace to reach the target in the end year.
- **R above 1** means you are ahead of schedule.
- **R below 1** means you are behind schedule.

The status colours (default settings, adjustable by the administrator under **Indicator Settings**):

| Achievement ratio | Status | Colour | Interpretation |
|---|---|---|---|
| R above 0.9 | **Maintain** | Green | Keep doing what you are doing. |
| R above 0.5 up to 0.9 | **Accelerate** | Yellow | Progress exists but is too slow. |
| R of 0.5 or below (including negative) | **Reverse** | Red | No progress or moving in the wrong direction. |

### 20.4 Pillar score and overall score

- **Pillar score** = average of the indicator scores in the pillar for the year.
- **Overall country score** = geometric mean of the four pillar scores (the fourth root of their product). All four pillars must have a score, otherwise the overall score is **Not Available**.

### 20.5 Worked example

**Indicator:** Account ownership among young adults (should **increase**). Baseline year 2017, end tracking year 2025.

| Item | Value |
|---|---|
| Baseline (2017) | 40 % |
| Common target | 60 % |
| Actual value entered for response year 2021 | 50 % |

1. Response score = (50 − 40) ÷ (60 − 40) × 100 = **50**.
2. This indicator has one disaggregation, so the indicator score = **50**.
3. R = (50 ÷ 100) × (2025 − 2017) ÷ (2021 − 2017) = 0.5 × 8 ÷ 4 = **1.0** → **Maintain** (green). Half of the time has passed and half of the progress has been made: on track.

If instead the 2021 value had been 46 %, the response score would be 30, R would be 0.3 × 2 = **0.6** → **Accelerate** (yellow).

**Decreasing indicator example:** unemployment rate with baseline 30 %, target 20 %, actual 25 % → (25 − 30) ÷ (20 − 30) × 100 = **50**. The decrease counts as progress.

### 20.6 National scores

The National Dashboard uses **exactly the same formulas**, replacing the common target with your **national target**. Disaggregations without a national target are ignored in national scores.

---

[← Part 2](part-2.html) · [Manual home](index.html) · [Part 4 →](part-4.html)
