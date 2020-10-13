# bluSensor® Microsoft Azure

In order to connect a bluSensor device to your IoT Hub on Microsoft Azure, you need to first setup an IoT Hub on Azure. Next you need to configure the IoT connection on your sensors. In order to do so, you need to put the device into ADMIN MODE. The device will make a Wi-Fi hotspot (name=serialnumber) that you can connect to. 

Once connected you can open the URL: http://blusensor.local

Select the menu item "Internet of Things" to configure your sensor. Next select Azure IoT as your provider and fill out the "Endpoint Configuration". Azure requires special formatting. Please find hints below the text fields.

The sensor will automatically use topics that will be compatible with Azure IoT Hub. 

Once your configuration is finished, you need to restart the device. You can check our iOS/Android app for connection states. Detailed informations can be found on the sensor's information page.

## Create an IoTHub on Azure

https://azure.microsoft.com/en-us/

## Enter Admin Mode 

<img src="blusensor_aiq_admin.png" width="800">

## Configure Internet of Things

<img src="blusensor_aiq_admin_dasbhoard.png" width="800">
