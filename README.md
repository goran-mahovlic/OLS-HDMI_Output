# OLS_HDMI_OUTPUT
HDMI output on Open Bench Logic Analyser

http://www.fpga4fun.com/HDMI.html

connect HDI output on side Wing 

data0+ - Wing1 ; data0- LOC=P54 Wing1 ; data1+ LOC=P57 Wing1 ; data1- LOC=P58 Wing1 ; data2+ LOC=P60 Wing1

data2- LOC=P61 Wing1 ; clock+ LOC=P62 Wing1 ; clock- LOC=P63 Wing1

for upload bit file use 

ols-loader -write -erase -p:COM4 -wB:hdmi_test.bit

If all is working you shoud get this pic

http://www.fpga4fun.com/images/HDMI1.jpg


