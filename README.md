# JLDG JD-3001 Sensor

This repository contains code for plotting sensor data from the JLDG JD-3001 sensor. The sensor data includes temperature, humidity, and nuclear radiation levels.

## How to Run

To use this code, please follow these steps:

1. Set up a virtual environment and activate it.
2. Install the required dependencies by running the following command:

   ```shell
   pip install -r requirements.txt
   ```

3. Copy your sensor data in CSV format to the `data` folder.
4. Run the script to visualize the data.

The expected schema for the sensor data CSV file is as follows:

```csv
nuclear,2023.05.15,
time,temperature(℃),humidity(%),real(usv/h),avg(usv/h),acc(msv),
00:00:12,25.8,27.8,0.3,0.1,1.267,
```

Please make sure that your data adheres to this schema before running the script.