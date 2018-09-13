# Modbus-RTU-Communication-Module-on-serial-bus-Using-Python

This is Modbus RTU Communication Module on serial bus.
Tested on ModbusMaster-Master Library on Arduino: https://github.com/4-20ma/ModbusMaster

The module supports all 10 functions of the library.

The module uses on PySerial 3.0 : https://pythonhosted.org/pyserial/index.html

Functions available :
    ModbusBegin(Baudrate,comPort,changeFlag,byteSize,stopBits,parityBits)
    ModbusRead(slaveId)
    ModbusReadNewData()
    
![Modbus RTU Communication Module](https://github.com/KarimHamdy1/Modbus-RTU-Communication-Module-on-serial-bus-Using-Python/blob/master/Capture1.PNG?raw=true)
