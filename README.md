# JH Chart Text Generator

**JH Chart Text Generator** is a lightweight, web-based tool designed to convert raw tabular data exported from **Jagannatha Hora** into standardized, human-readable plain text descriptions. 

It streamlines Vedic astrology report creation and data preparation for analysis by automatically calculating house lordships, conjunctions, aspects, and optional planetary conditions.

---

## Key Features

* **Automatic Text Standardization:** Converts raw planetary longitudes and positions from Jagannatha Hora into clear, grammatically structured sentences.
* **Smart Conjunction Grouping:** Automatically identifies co-located planets in the same house and formats them into clean conjunction statements.
* **Automated Drishti (Aspect) Calculations:** Calculates 7th house aspects as well as special planetary aspects (Mars, Jupiter, Saturn, Rahu, Ketu) and identifies mutual planetary aspects.
* **Chara Karaka Integration:** Parses and appends Chara Karaka roles (Atmakaraka, Amatyakaraka, etc.) to the respective planets.
* **Combustion Tracking:** Integrates combustion status directly into planetary descriptions.
* **Bhava Chalit Support:** Tracks and notes house shifts from the Rasi chart to the Bhava Chalit chart.
* **Custom Ascendant Override:** Allows manual selection of the Lagna/Ascendant sign if needed.

---

## How to Use

1. **Copy Chart Data from Jagannatha Hora:**
   * Open Jagannatha Hora and locate the **Rasi (D-1)** or divisional chart planetary position table.
   * Highlight and copy the tabular data (containing columns like *Body*, *Longitude*, *Rasi*, etc.).

2. **Paste & Configure:**
   * Paste the table directly into the **Input Data** text box.
   * *(Optional)* Toggle **Aspects** to include full aspect calculations in the output.
   * *(Optional)* Toggle **Combustion** or **Chara Karaka** and paste the respective tables from Jagannatha Hora into the popup modals.
   * *(Optional)* Toggle **Bhava Chalit** and enter any shifted house numbers (1–12) for affected planets.
   * Adjust the **Ascendant** dropdown if you wish to override the parsed Lagna.

3. **Generate & Copy:**
   * Click **Generate Text**.
   * Copy the output text with one click using the **Copy to Clipboard** button.

---

## Example Output

```text
d-1 chart ascendant sign is leo.
lord of the ascendant and 8th house Sun conjunct and placed on the 1st house on the sign of leo.
retrograde Atmakaraka Saturn lord of the 6th and 7th house is placed on the 10th house on the sign of taurus. Saturn aspects the 12th house, 4th house and 7th house and is aspected by Jupiter.
