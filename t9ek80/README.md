# EK80 SN90
Simrad EK15/60/80 and SN90 echosounder python interface module. The t9ek80.py should normally not be modified, 
it contains the generic interface. The biomass and singletargetchirp are example user files. The xml files are 
configuration files. Usage:

    pip install t9ek80
 
 or
    
    copy the t9ek80.py to the local folder... 


Then download the examples for github.

  
git clone https://github.com/The1only/ek80.git

cd ./ek80/examples

python3 biomass.py biomass.xml 

or

python3 biomass.py biomass.xml 0

To select transducer 0 and run automatially ( no user input required) 



PS: All testing has been done using python3

The Simrad EK80 user manual can be found at: https://www.simrad.online/ek80/ref_en/default.htm
