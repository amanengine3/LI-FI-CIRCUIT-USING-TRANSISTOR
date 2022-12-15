# LI-FI-CIRCUIT-USING-TRANSISTOR
My  project is a transistor based analog audio Li-Fi circuit which can stream good quality music from our phone/mp3 player to speakers at home. 

Li-Fi stands for Light Fidelity, which uses visible light as medium for data transmission. The Li-Fi system consists of normal LED light bulbs and modulating circuits. The idea of Li-Fi is to use existing light infrastructure to transmit data to our computer, Smartphones, tablets etc. This will eliminate some of the main limitations and disadvantages of traditional radio communication, such as the Wi-Fi system that we use at home or office. Li-Fi utilizes LED light bulbs which are connected to a modulating circuit which will convert incoming data streams into rapidly flashing light. We human beings can’t perceive the high frequency flashing light but we will perceive a steady room lighting without any flicker. The receiver circuit can capture the high frequency flashing of LED and decodes it into understandable data streams for our computer or smartphone.
# Applications of Li-Fi
1. Li-Fi and Live Streaming
2. Li-Fi technology in Hospitals
3. Li-Fi in the Workplace
4. Li-Fi in Schools
5. Li-Fi in Retail
# Introduction
The whole idea of our project is that we are preparing a Li-Fi which sends data by amplitude modulation of the light source in a well-defined and standardized way.The millivolts peaks from solar cell must be amplified adequately using a USB computer speaker or any other good sensitive amplifier so that it can drive a speaker. To keep the circuit simple as possible (to avoid multistage) of the transmitter, we have connected three low power transistor in parallel so that it can drive 1 watt LED with adequate current.The 4.7K and 1 K resistors provide necessary DC biasing for the three transistors which will put the transistors in active mode where the transistors act as amplifiers. (If we over bias the circuit with lower resistor values, it will put the transistor in saturation mode where the transistor fully ON and does not respond to the input. If we under bias the transistors it will go to cut-off mode where output current will be too low to drive the LED ON.)We can spot the 4.7K resistor is connected in series with 100k variable resistor, this is to adjust the quiescent current of the amplifier (transmitter) thus adjusting the brightness of the LED.(Quiescent current: Quiescent current is the current consumed when the circuit performing does not work.)The quiescent current in the circuit is the reason why the LED stays ON regardless of the audio input. We have used the quiescent current to our advantage to glow the LED.
# Requirements
In this project we used various electronic components in order to make the circuit. The circuit was set up on a circuit board and hence tested. We used the following components:
  1. 3 x BC337 NPN Transistor
  2. 1 x 4.7K resistor
  3. 1 x 1K resistor
  4. 3 x 1000uF/25V electrolytic capacitor
  5. 1 x 1 Watt LED
  6. 1 x 100K Variable Resistor
  7. 1 x switch
  8. 1 x 3V to 6V Solar cell
  9. 1 speaker
  10. 1 audio jack
  11. 1 Circuit board
# Circuit Diagram
<img width="562" alt="image" src="https://user-images.githubusercontent.com/60310409/207787240-4aab41c6-857e-4663-b5b4-2161f201c17d.png">


