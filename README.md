# Time_Series_Forecasting

## Main Highlights:
1. Two model architechtures (MLP and RNN)
2. Add a NVIDIA SM monitoring, refresh after 10 seconds.
3. Create Batch Data.
   - e.g. [256, 120, 4]
   -  256 samples per batch
   -  120 timesteps
   -  4 variables (Temp, Pressure, Dew Point, Reltive Humidity


Notes:
1. Takes about 120 seconds on P100 to run 1 epoch with batch size 256.
2. P100 has about 16Gb memory, batch size 512 gives 1Gb memory utilization.
3. Monitoring relvealed that GPU utilization is about 60%.

