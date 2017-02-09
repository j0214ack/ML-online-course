
This homework is to predict PM 2.5 density value (a rather large dust particle)
in the air. Features are other meteorological value like temperature, wind, etc.

The data are collected from 豐原(Fong Yuan) observation station
every hour, 24 hours a day, 365 days an year.

The training data consist of the first 20 days of the month.

Testing data are collected randomly from the remaining 10 days,
each datum point represents value of consecutive 10 hours in the period
(And only the first 9 hours are shown)

Our goal is to use the first 9 hours' value as feature to predict 10th hour's PM 2.5


Notes:

NMHC non-methane hydrocarbons
AMB_TEMP ambient temperature 室內溫度
RAIN_FALL NR means no rain
RH relative humidity 相對濕度
THC total hydrocarbon 
WIND_SPEED      m/sec   every hour's last ten minutes avg 風速(以每小時最後10分鐘算術平均)
WIND_DIREC      degress every hour's last ten minutes avg 風向(以每小時最後10分鐘向量平均)
WS_HR           m/sec   whole hour avg 風速小時值(以整個小時向量平均)
WD_HR           degress whole hour avg 風向小時值(以整個小時向量平均)
