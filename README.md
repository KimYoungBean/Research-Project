# stepCounter
> ### Kyujeong & YoungBean's research project
### 1. Implementation of the Samsung Fitness function without using the step counter sensor
> <img src="http://blogfiles9.naver.net/MjAxNzA3MjlfMjUz/MDAxNTAxMzE1NTk0NzE0.V9MguvZMU3bmzZKzmEqbMjGsDClxqhyKI3mhd-itsEUg.cUeimuJq60XFNZMYs43oRR7wNUgciulOka5636Io8Yog.PNG.kkkclub1/Screenshot_20170729-160933.png" width="60%" height="30%">

### 2. Identify and distinguish four cases
1. *Holding and walking*
2. *Pocket and walking*
3. *Walking with Typing*
4. *Waling with Calling*

### 3. Measuring the number of steps with acceleration sensor and gyro sensor

### 4. Each use sensor according to four cases
- *Holding and walking* - **Accelerometer, Gyroscope**
- *Pocket and walking* - **Accelerometer, Proximity Sensor**
- *Walking with Typing* - **Accelerometer, Gyroscope**
- *Waling with Calling* - **Accelerometer, Proximity Sensor**

### 5. Outputs the total number of steps measured in 4 cases

### Graph
- Graph of X,Y,Z
> ![xyz](https://user-images.githubusercontent.com/21302833/34510888-f7406930-f09a-11e7-990e-c11ce1ec9e4a.png)
- Graph of angleXZ, angleYZ
> ![xzyz](https://user-images.githubusercontent.com/21302833/34510891-fa660cf0-f09a-11e7-880f-898b222cf4fb.png)


### Drawing Line
- Drawing Ling following the Path
- Correct the Compass function

### Low pass Filter
- Apply to the compass

### Use the Sunset & Sunrise Time
- For lightSensor to distribute the DAY/NIGHT

#### What to do..
- Modify the low pass filter for correct direction
- Research and Use the wifi/AP for find current location exactly 
