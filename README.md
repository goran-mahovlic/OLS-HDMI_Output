# OLS_HDMI_Output
HDMI output on Open Bench Logic Sniffer

http://dangerousprototypes.com/docs/Open_Bench_Logic_Sniffer

got the source from

http://www.fpga4fun.com/HDMI.html

connect HDI output on side Wing 

data0+ LOC=P53 - Wing1

data0- LOC=P54 - Wing2

data1+ LOC=P57 - Wing3

data1- LOC=P58 - Wing4

data2+ LOC=P60 - Wing5

data2- LOC=P61 - Wing6

clock+ LOC=P62 - Wing7

clock- LOC=P63 - Wing8

for upload bit file use 

ols-loader -write -erase -p:COM4 -wB:hdmi_test.bit

If all is working you shoud get this pic

http://www.fpga4fun.com/images/HDMI1.jpg
