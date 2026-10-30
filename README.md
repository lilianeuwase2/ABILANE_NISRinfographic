
# Same Harvest, Bigger Food Bill

**Team ABILANE** (Liliane Uwase and Abigail Tendo) · NISR Infographic Competition 2026

Rwanda's harvest barely grew from 2024 to 2025, but food prices rose faster and reached a record high. This project tells that story with a static infographic (poster) and a dynamic infographic (video), using official NISR data.

## Key findings (2024 → 2025)

| Finding | Number |
|---|---|
| Harvest of major food crops | +1.1% (7.08 → 7.15 million tonnes) |
| Food prices, yearly average | +4.5% |
| All prices (general CPI), yearly average | +5.9% |
| Food price index, 2025 average (February 2014 = 100) | 255.7, the highest on record |
| Staple crops that produced less | 5 of 10 |
| Share of a rural household's budget spent on food | 48.0% |
| Farmers who irrigated, Season A 2025 | 13.4% |

## Files

| File | What it is |
|---|---|
| `nisr_calculations.ipynb` | Python notebook that calculates and checks every number and draws the charts |
| `static.png` | Static infographic (poster, 1200 × 7000 px) |
| `dynamic.mp4` | Dynamic infographic (animated video, 1920 × 1080) |

## Data sources

- National Institute of Statistics of Rwanda (NISR), Seasonal Agricultural Survey (SAS) 2025 report, December 2025 (Annual Tables): `SAS 2025_Annual Tables.xlsx`
- National Institute of Statistics of Rwanda (NISR), Consumer Price Index (CPI) time series, published August 2026: `CPI_time_series_August 2026.xls` (only 2014–2025 data is used)

Every comparison covers the same period, 2024 → 2025. Food prices are yearly averages (January to December). The 2025 CPI numbers were checked against NISR's September 2025 CPI publication and match.

## How to run the notebook

1. Open [Google Colab](https://colab.research.google.com) and choose **File → Upload notebook**, then pick `nisr_calculations.ipynb`.
2. Click the folder icon on the left and upload the two NISR data files. Keep their names exactly as they are.
3. Choose **Runtime → Run all**.

The notebook:

- prints each number next to the value used on the poster, so you can check they match;
- saves them in `numbers_for_poster.xlsx`;
- saves the charts as transparent PNG files in a `charts` folder and downloads them as `charts.zip`.

## Tools used

- **Python** (pandas, matplotlib) in Google Colab for the calculations and charts
- **Canva** for the poster and the video layout, animation and export

## Credits

Data: NISR. Icons and photos : canva.