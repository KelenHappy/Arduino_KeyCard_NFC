# Arduino KeyCard NFC

# 1. Arduino

To get started with Arduino, follow these steps:

- Download the [Arduino IDE](https://www.arduino.cc/en/software) for your operating system.
- Arduino programming language is based on C and C++. It is more affordable than Raspberry Pi.

## Raspberry Pi vs. Arduino (Just example. Raspberry have so many version too.)

| Feature             | Raspberry Pi                              | Arduino                   |
|---------------------|-----------------------------------------|---------------------------|
| Processor           | ARM Cortex-A72 quad-core                | Atmel ATmega328P          |
| Clock Speed         | 1.5GHz                                  | 16MHz                     |
| RAM                 | 1GB or more                             | 2KB or more               |
| Storage             | microSD card                            | None or microSD card      |
| Operating System    | Linux                                   | None                      |
| Programming Language| Python, C/C++, Java, etc                | Arduino programming language |
| Connectivity        | Ethernet, Wi-Fi, Bluetooth              | None or limited (Need extension) |

If you need to complete a big project and require a more powerful tool, Raspberry Pi might be a better choice. For smaller projects, you can start with Arduino. However, be aware of different hardware versions. You can learn more about them in the [Arduino Hardware](https://www.arduino.cc/en/hardware) documentation.

  
# 2.NFC
## NFC vs. RFID
| Feature             | NFC                                       | RFID                                             |
|---------------------|-----------------------------------------|-------------------------------------------------|
| Frequency           | High frequency (13.56 MHz)              | Wide range of frequencies (low, high, ultrahigh)|
| Range               | Up to 20 cm                             | Up to 100 m or more                             |
| Communication       | Two-way                                 | One-way or two-way                              |
| Cost                | Tags are relatively inexpensive         | Tags can be expensive                           |

You can learn [more](https://www.atlasrfidstore.com/rfid-insider/rfid-vs-nfc) about comparison. 
##  Encryption type
- Symmetric Encryption  
  Just need a key to encrypt and decrypt. So if we know how to encrypt and we know how to decrypt.  
  Some old equipment is using it. So you nuch be careful.
  Door, Control Panel, Elevator Shaft, ......    
- Asymmetric Encryption  
  You need two or more key to encrypt and decrypt.  
  It is much more safe.  
  Credit card, Email Encryption, SL/TLS for Secure Web Browsing, ......  
   
# 3.Code
## Find Your Board
### CAREFUL !!! Find your board on your Arduino chip
![](https://github.com/KelenHappy/Arduino_KeyCard_NFC/blob/main/image/328pb_tool_box.png)
### And choose it in Arduino IDE
![](https://github.com/KelenHappy/Arduino_KeyCard_NFC/blob/9cbd2125da0e7e70e4dcd0c547c705f1e25f1f5e/image/choose_your_board.png)

## Reader of keycard
## Writer of keycard

