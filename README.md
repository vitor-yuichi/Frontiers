# Data Processing Documentation🚀🐍

Welcome to the documentation for the data processing in the work published in Geosciences. You can access the full article [here](https://www.mdpi.com/2076-3263/13/4/111).

- Data processing was mainly executed using Jupyter Notebook on Google Colab (Python) ✨.

## Files Documentation

### Tweets Data

- `812A_2019_JAN_2KM.csv`: All tweets extracted in the study area for January.
- `812A_2019_FEV_2KM.csv`: All tweets extracted in the study area for February.
- `812A_2019_MAR_2KM.csv`: All tweets extracted in the study area for March.

### Flood Data

- `812A_alag.csv`, `833A_alag.csv`, `857A_alag.csv`: Flood data around 812A, 833A, and 857A rain gauges, respectively.
- `Alagamentos_2019.csv`: Raw file containing all extracted floods in 2019.

### Other Data

- `boxplot.csv`: Data for word frequency boxplots.
- `data1.csv`, `data2.csv`, `data3.csv`: Raw rainfall gauge data for 812A, 833A, and 857A corresponding to January, February, and March, respectively.

### Main Processed Data

- `MainDataProcessed.csv`: All results are aggregated on a daily basis. The columns `words_fr_812|833|857` represent word frequencies, `tw_833|812|857` represent tweet frequencies, `floods_812|833|857` represent flood data, and `gauge_812|833|857` represent rainfall gauge data.

### Radar Data

- `radar_2019.csv`: Raw radar data.

Enjoy exploring the data! 