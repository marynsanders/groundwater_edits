# groundwater_edits

## transducer data
automatically recorded data by pressure transducer in designated well 

## manual measurements
measurements made in Rivendell wells with an e-line and recorded through the sensor database

## mariel corrections
Corrections made by Mariel Nelson by use of manual measurements. The corrections were needed 
because of misplacement of the pressure transducer when it was removed for sampling or neutron 
probing. This was done by finding the difference of the transducer value and manual measurement
value, then a rolling mean was applied for the values between each manual measurement. 

## manually corrected data
For 2016 to 2020, Maryn Sanders manually edited Mariel's corrected data in order to account for
the sections where her averaging method did not apply. This was done by sorting through the 
Excel file for obviously wrong data, and then fitting a linear funtion between the upper and 
lower bounds. A text file (replaced_transducer_data.txt) is included in this repository with 
the timespans that the edits apply to. 
