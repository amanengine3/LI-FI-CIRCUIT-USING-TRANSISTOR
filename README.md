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
# Transmitter Circuit Diagram
<img width="562" alt="image" src="https://user-images.githubusercontent.com/60310409/207787240-4aab41c6-857e-4663-b5b4-2161f201c17d.png">

# Receiver Diagram 
<img width="452" alt="image" src="https://user-images.githubusercontent.com/60310409/207787615-738b2969-de9f-4854-bad1-859ab5ccd0be.png">

# Results
### Main Circuit

<img width="452" alt="image" src="https://user-images.githubusercontent.com/60310409/207787795-e2358e4a-cc7e-44d0-8e70-a2d7d143c67d.png">

### Receiver Circuit

<img width="417" alt="image" src="https://user-images.githubusercontent.com/60310409/207787867-63282e27-6b89-454c-a7ab-03ee8c284336.png">

## COMMENTS AND CONCLUSION
***Is Li-Fi better than Radio Communication?***

The Limitations/disadvantage of Radio communication are:
+ Radio Waves have Limited Bandwidth.
+ Cannot be used in some restricted areas.
+ Security.
+ Health Hazards.
Let’s explore each of them.
1) Radio waves have limited bandwidth:
<sub>
Radio frequencies range from 3 KHz to 300 GHz. The radio frequencies are
classified into many categories like Low frequency, Medium Frequency, High
frequency, Ultra High Frequency, Extremely High frequency etc. Each of them
is allocated for specific applications.For example FM radio signal is allocated
from 88 MHz to 108 MHz and AM stations from 535 KHz to 1905 KHz.Due to
increasing of wireless devices per person and emerging of internet of things
(IoT) devices, allocating the radio frequencies is getting tighter day by day and
licensing the radio spectrum costs enormous.We have something called ISM
band which stands for Industrial Medical and Scientific band, the devices
operating at this frequency don’t need to be licensed by the users. The best
example is our Wi-Fi router,it operates at 2.4 GHz and also 5 GHz.We feel
that our Wi-Fi internet is slow at times? If yes, then we are probably living in
an apartment with many of our neighbors using Wi-Fi.Wi-Fi routers mostly
operate at 2.4 GHz range and some high end routers operate at 5 GHz. Due
to the interference of many Wi-Fi signals from we and our neighbour’s router,
the data transmission gets slower than our wired connection.Due to this
congestion router manufacturers are introducing 5 GHz band to avoid such
Wi-Fi congestions, but with 5 GHz we will get shorter range, yet this is not a
full solution for our future needs.</sub>
2) Restriction of Radio waves:
Radio waves are restricted in many areas such as hospitals, operation
theatres, airplanes, research facilities etc. We cannot always enjoy Wi-Fi
internet in a hospital or in an airplane or in a place where the radio
communications are restricted, because there could be interference with
sensitive hospital equipment, which treats a valuable patient’s life or very
expensive experiment and interference of radio waves could alter the results.
So not everywhere radio communications are permitted.
3) Security:
Guess what the worst thing can occur to our wireless internet, is it a
disconnection of our internet? No, it is our network getting hacked by
someone else! Wi-Fi can penetrate through walls and surround our area, We
may say that my Wi-Fi is secured with a password but, a skilled black hat can
break into our network without any notice, and many of We are not good at
setting a strong password for our router.
4) Health Hazard:
High energetic radio waves are suspected to cause health issues; there are
some people who complained that they are affected from high energetic radio
waves. But there is no documented evidence to support the statement that
radio waves cause cancer. Maybe science has yet to discover the health
hazards on humans and animals and even plants.
Now, let’s see how Li-Fi can overcome these limitations:
1) No Bandwidth Limitations and Interference:
The Li-Fi has bandwidth at least 1000 times greater than the radio waves, this
can handle the future internet needs with ease. No interference with the
neighbour's internet connection as our internet will not go beyond our room
and neither other’s internet will enter our room. Very high data transfer speed
compared to Wi-Fi, researcher calculated theoretical maximum data transfer
speed of 224 Gb/s isn’t that mind blowing?
So, now We have very high speed data connection without any interference.
2) We can access Internet anywhere:
Radio communications are restricted in some areas, guess what is not
restricted? Visible light! Now we can restore access to the internet in airplanes
or in hospitals or in research facilities without worrying about radio
transmission interference.
3) Security is enhanced:
Now the internet will not go beyond our room as the light from our room will
not leak like Wi-Fi and black hats will have tougher time to hack our
network.To access the network the black hat must be physically present in our
room and we know what to do next if such an unknown person is present in
our room.
4) Reduced Health Hazards:
We are using visible light since the discovery of fire; visible light spectrum has
little to no health hazard. LEDs don’t contain any mercury or other toxic
chemicals present in like CFLs, which also emits a small amount of ultraviolet
rays, and yet CFLs don’t cause health hazards, so we can say that LEDs are
one of the safest light sources available.
In conclusion we can say that Li-Fi is superior to traditional radio based
communication, but Li-Fi may not be without its limitations or disadvantages
which may be yet to discover.




