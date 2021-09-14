# Thermal Tools: package reading the thermal camera MLX90640 data.

The Melexis MLX90640 Far Infrared Thermal Sensor is a fully calibrated 32 x 24 pixel thermal IR array housed in a small, industry-standard package with a digital interface. 768 FIR (Far Infrared) pixels make up the MLX90640. An environmental sensor is included to monitor the chip's ambient temperature, as well as a supply sensor to monitor the VDD.

Specifications | Parameters
------------ | --------------
Small size, low cost  |  32x24 pixels IR array
Noise Equivalent Temperature Difference (NETD) |  0.1K RMS @1Hz refresh rate
Digital interface | I2C 
Programmable refresh rate | 0.5Hz...64Hz
Supply voltage| 3.3V 
2 FOV options |  55°x35° and 110°x75°
Target temperature | -40°C ÷ 300°C 
Temperature accuracy |  ±1°C

![ Pixels position MLX90640 ] (https://github.com/TriKnight/thermal_tools/tree/master/images/pixels_position.png)

## 1. Install dependences 
Package running and testing with Python 3.6
- Installing [Jupyter notebook](https://jupyter.org/install)
    ```
    pip install jupyterlab
    ```
- Installing jupyter notebook via Anaconda(optional)
    ```
    conda install -c conda-forge jupyterlab
    ```
- Installing [Matplot](https://matplotlib.org/stable/users/installing.html) && [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
    ```
    pip install matplotlib
    pip install pandas
    ```
## 2. Running the Jupyter notebook
Open new Terminal and run:

```
jupyter-notebook
```
## 3. Results
### 3.1 Example plot fake MLX90640 data
![ Fake data] (https://github.com/TriKnight/thermal_tools/tree/master/images/fake_data.png)
### 3.2 Plot MLX90640 data form CSV file
![ CSV data] (https://github.com/TriKnight/thermal_tools/tree/master/images/csv_data.png)