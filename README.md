# split-software-serial
Arduino SoftwareSerial split into two SoftwareSerialRx and SoftwareSerialTx classes

The SplitSoftwareSerial library is derived from the Arduino SoftwareSerial library, and provides the same functionality of serial communication on any digital pin of the board, using software to replicate the functionality of the hardware UART. It is possible to have multiple software serial ports with speeds up to 115200 bps. 

SplitSoftwareSerial breaks SoftwareSerial into two separate classes, SoftwareSerialRx and SoftwareSerialTx, each taking one pin.
