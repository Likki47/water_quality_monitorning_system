# water_quality_monitorning_system

An IOT project which indicates the purity of water and the data can be accessed using a webserver.
Maintaining optimal water quality is crucial in aquaculture, and one key aspect of this is understanding the concentration of various elements and compounds in the water, often measured in parts per million (ppm). Monitoring ppm values provides critical insights into the suitability of the water environment for aquatic organisms. For instance, measuring parameters like dissolved oxygen, ammonia, nitrites, nitrates, and salinity in ppm allows aquaculturists to assess potential stressors and make informed adjustments. High ammonia or nitrite levels, even in small ppm ranges, can lead to toxic conditions, hindering growth and causing health issues. Conversely, knowing the ppm of essential nutrients like minerals and trace elements enables precise supplementation to ensure proper growth and metabolic functions. By grasping ppm values, aquaculture practitioners can take timely corrective measures, optimize feed usage, prevent waterborne diseases, and enhance overall production efficiency, contributing to both healthy aquatic life and the economic viability of the operation

# Hardware Components Required:

ESP 32 Board
DC Motor
TDS Sensor
Temperature Sensor
LCD Display(16X2)
L298n (Motor Driver)
Power supply Board with
12V,5V, Ground Pins

# Working:
> The Project is a Prototype involving an webserver connected to the hardware Setup.
> When we on the Power Supply and Connect ESP  32 to your PC through arduino IDE console ,you observe your ESP 32 being connected to WiFi.
> Once its Connected It generates an IP address through which one can handle the hardware through a predesigned Server. IP address is observed in the Serial Monitor.
> The designing includes to buttons (On/OFF) in the website each for motor andTDS Sensor.
> When the motor button is ON, it drives the motor to Go down such that theTDS sensor Pin Attached to the motor gets Sinks in the Water then you can On the TDS Sensor.
> As soon as you ON your TDs sensor you will get the reading of amount of solids dissolved in water in terms of PPM.
> As you observe your TDS value on your Webserver as well as LCD Display turn of the TDS sensor Button on web Server and OFF the motor so that it can move up to its Original 
  position.
> The motor Require 9V to 12V of supply that can be driven to it through L298n Driver to which we give a 12V supply from Power source
> Use an 15V battery or 12V to Power Up the whole system through Power Supply attached
