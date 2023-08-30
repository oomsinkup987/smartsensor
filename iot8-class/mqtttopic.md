## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301025/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301025/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"CO2": "3"}
        - {"Pressure Sensor": "4"}
        - {"Current": "50"}
        - {"Humidity": "10"}
        - {"Load Detection ": "4"}
        - {"pH sensor": "7"}
        - {"Time": "30"}
        - {"Water Level": "4"}
        - {"Dry sensor": "5"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301025/model-01/sn-001
    - payload
        - {"Temperature": "25.2"}
        - {"3D Magnetic": "value"}
        - {"Humidity": "10"}
        - {"Trust M": "ON"}
        - {"Bluetooth": "ON"}
        - {"MEMS microphone": "ON"}
        - {"Hall sensor": "value"}
        - {"Wifi": "ON"}



