# Lidar-Dataset

This data set was obtained from YDLIDAR X4 LIDAR unit mounted on an
autonomous robot. Each scan is provided with a pose change estimation
relative to the time of the previous scan.

### The Robot

![](http://broombot.express-portfolios.com/img/portfolio/robot.jpg)

## Scan Format

| Subject        | Value |
| -------------  |:-------------:|
| Min Range      | 0.12 m        |
| Max Range      | 10.0 m        |
| Scan Frequency | ~7.5 Hz       |
| Scan Size      | ~640          |
| Scan Angle     | 360 Degress   |


## Data Format

Each line represents 1 scan. The first three numbers represent
the post change, containing distance traveled, change in angle,
and elapsed time, respectively. The remaining data contains each
individual sample from the lidar scan. The samples are distance measurements
(in meters) with a constant angle between each sample.


## Examples

#### Lidar Scan Visualized

![](http://broombot.express-portfolios.com/img/portfolio/lidar.png)


#### Example Map with CoreSLAM

![](http://broombot.express-portfolios.com/img/portfolio/map.png)

