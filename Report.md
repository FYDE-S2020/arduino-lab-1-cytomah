Name: Christian Tomah

EID: ct29442

Team Number: 15

## Questions

1. Why does your program need a setup and a loop?

    The setup does one thing once and then the loop is done over and over.

2. What is the downside to putting all your code in a loop?

   It will keep repeating over and over and may not do the correct thing that you want.

3. Why does your code need to be compiled?

    It changes from the language we wrote in into code that the computer can understand.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    If the frequency is too low, it wouldn't be able to be seen by the human eye. Smart LED are some solutions to dimmers in the real world.

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    To ensure that the circuit is made properly so everything works in the right manner.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous is synchronized by an external clock, while asynchronous are sychronized by special signals along the transmission medium.

7. Profile of UART: Sent X bytes in Y time 

  64 bytes in 189 microseconds

8. Profile of SPI: Sent X bytes in Y time

   64 bytes in 63 microseconds

9. Why is SPI so much faster than UART?

    SPI uses more wires and pins.

10. list one pro and one con of UART

    Pro: No need for a clock
    Con: Slower

11. list one pro and one con of SPI

    Pro: Simpler Protocal
    Con: Amount of connections

12. list one pro and one con of I2C

    Pro: Open Collector Bus which allows some flexibility in bus voltage
    Con: Half-Duplex Only

13. Why does I2C need external resistors to work?

    Provide a default state for a signal line or GPIO pin.

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](C:\Users\cytom\OneDrive\Documents\First Year Design\arduino-lab-1-cytomah\img\Part A Blink.PNG)

Procedure A, step 4:
![Put path to your image here ->](C:\Users\cytom\OneDrive\Documents\First Year Design\arduino-lab-1-cytomah\img\Part A Dimmer.PNG)

Procedure B, UART:
![Put path to your image here ->](C:\Users\cytom\OneDrive\Documents\First Year Design\arduino-lab-1-cytomah\img\Timing UART.PNG)

Procedure B, SPI:
![Put path to your image here ->](C:\Users\cytom\OneDrive\Documents\First Year Design\arduino-lab-1-cytomah\img\SPI Image.PNG)
