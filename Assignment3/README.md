# Assignment #3 - Time Series Data

This assignment focuses on getting own time series data.

- The dataset is obtained from the **fpp2** R package, which compiles quarterly international visitor arrivals to Australia from major source countries (Japan, New Zealand, UK, US).  
- The data originates from the **Australian Bureau of Statistics**, covering the period **1981 Q1 – 2012 Q3**.  
- The series provides a clear example of seasonality and long-term trends, making it suitable for time series analysis.

---

## Data Dictionary

| Variable | Description                                              | Unit                  | Notes                                |
|----------|----------------------------------------------------------|-----------------------|--------------------------------------|
| Quarter  | Time index, quarterly frequency, starting from 1981 Q1   | Year-Quarter format   | 1981 Q1 – 2012 Q3                    |
| Japan    | Number of visitors from Japan to Australia               | Thousands of persons  | e.g., 14.763 = 14,763 arrivals       |
| NZ       | Number of visitors from New Zealand to Australia         | Thousands of persons  |                                      |
| UK       | Number of visitors from the United Kingdom to Australia  | Thousands of persons  |                                      |
| US       | Number of visitors from the United States to Australia   | Thousands of persons  |                                      |

---

## Why This Dataset is Interesting

International tourism is highly sensitive to global economic cycles, policy changes, and unexpected events (e.g., currency fluctuations, the Olympics, or health crises).  
This dataset is intriguing because:

- It exhibits **strong seasonality** (e.g., peaks during certain quarters).  
- It shows **long-term growth and decline trends** in visitor flows.
