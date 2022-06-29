# M031BSP_SPI_LSM6DSL
 M031BSP_SPI_LSM6DSL

update @ 2022/06/29

1. use SPI0 initial LSM6DSL 

PA0 : SPI0_MOSI , connect to LSM6DSL PIN#14:SDA

PA1 : SPI0_MISO , connect to LSM6DSL PIN#1:SDO/SA0

PA2 : SPI0_CLK , connect to LSM6DSL PIN#13:SCL

PA3 : SPI0_SS , connect to LSM6DSL PIN#12:CS

2. use terminal , digit 1 to display pitch/roll data , digit 2 to display acc/gryo raw data

pitch/roll data
![image](https://github.com/released/M031BSP_SPI_LSM6DSL/blob/main/digit_1_pitch_roll.jpg)	
	
acc/gryo raw data
![image](https://github.com/released/M031BSP_SPI_LSM6DSL/blob/main/digit_2_raw_data.jpg)

3. below is LA capture 

WHO_AM_I
![image](https://github.com/released/M031BSP_SPI_LSM6DSL/blob/main/WHO_AM_I.jpg)	
	
acc/gryo raw data	
![image](https://github.com/released/M031BSP_SPI_LSM6DSL/blob/main/LA.jpg)	
	
