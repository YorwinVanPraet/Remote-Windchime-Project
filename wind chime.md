# Remote-Windchime-Project

For the course Principles of repurpusing of electronics i had to create a electronic devices out of recycled and repurpused eletornics. 
i am orinigly a psychology student with no preknowledge about electronics, so it was i really challanged myself with this courses. 
togheter with the teacher i discussed what might be a project that is on a level that i could understand and learn it in a easy and fast way.

In my project i created a Windchime device. in this picture below you can see how the protoype looks.![WhatsApp Image 2022-12-28 at 14 36 05](https://user-images.githubusercontent.com/121553579/209814721-6d9a0c35-7d71-42e9-a177-73df867d03d9.jpeg)

# Parts used

- Old used cooking pan.

![WhatsApp Image 2022-12-28 at 14 36 10](https://user-images.githubusercontent.com/121553579/209816692-9450c4c7-0f04-4d24-8177-716842147d89.jpeg)

- Old used corkscrew.
- Old iron sword-shaped metal.
- Old used windchime 
Down below you see all three: corkscrew, sword and windchime.

![WhatsApp Image 2022-12-28 at 14 36 08](https://user-images.githubusercontent.com/121553579/209816564-32651d87-b8fb-4667-bbbe-6a6186f93c74.jpeg)

- Old working cellphone.

![WhatsApp Image 2022-12-28 at 14 36 00 (2)](https://user-images.githubusercontent.com/121553579/209816704-b6c4a25c-c5c1-4840-aa46-9d5d3ae7301c.jpeg)

- Used computer fan.

![WhatsApp Image 2022-12-28 at 14 35 57](https://user-images.githubusercontent.com/121553579/209816485-8e425b6a-dd06-4d2e-bc2f-d9a0934e4bfe.jpeg)

- Old decoration (beanie and leaf crown)
- Tape

# Electrical parts used

- Adruino 12v adapter. 
![WhatsApp Image 2022-12-28 at 14 35 59](https://user-images.githubusercontent.com/121553579/209816395-46ab2d93-5781-4f0a-a46e-ad047a4cd7c0.jpeg)

- Joy-it mega
- 

- Resistors ...
- trasistor ...
- light sensor ...

Down here you see the three: photoresitor, tranistor and resistor
![image](https://user-images.githubusercontent.com/121553579/209834156-413e4426-be45-44be-9163-e2733aeaeb7c.png)



# Arduino 
![overwview](https://user-images.githubusercontent.com/121553579/209814876-22cf98eb-8fba-4687-8494-975da17d1075.jpeg)

In this picture you see the hwo i connected the boards together and finaly how the fan is connected.
The code i used can be found here:  https://github.com/YorwinVanPraet/Remote-Windchime-Project/issues/2#issue-1512796448





# Design procedure and explaination


When i had to think of what kind of thing i was going to create i wanted to implement my psychological background to the project.
i thought of a product that creates the feeling of recognisiation, valuation and warmth.
the first idea that i had was to create a remote candle/light. which implies that when i am in the amsterdam and the person that has this candle at home is in boekarest.
than when i call the number that is conneted to that candle/light it would lit up.
after some discussion with my tutor for this course we came to the conclusion that it is nice to replace the candle/light with a fan that is stimulatimng a windcime.

So how am i going to build this device. First of all i needed to understand urduino, it was for me more difficult than i expected. i looked up tutorials on youtube and at some point i got a bit the hang of it. I used thinkercad to simulate the arduino. with the tutorials i first learned how to create use the Photo resistor as a (input) to decide the volume of the light (output). with being able to make this the only thing i had to change was the output from a small led to a fan. 
  
  To make the fan work i needed a 12v power source. The Joy-it mega only was capable of 5V and only has a 5V output. Therefore i needed to sold a extra cable to the bottom of the Joy-it mega, and connect this with a direct connection to the fan. 
   
   After i managed this, its was time to programm the code. What i wanted to code is that when the photoresistor recieves light a sequence is started which takes 5 minitus. First my thoughts where to do it longer but after listing to the windchime and getting feedback from others i decided to shorten the time to 5 mintutes. What i also wanted to implement is that the fan is not blowing constantly at the same speed. I wrote a code that makes the frequences of the voltages input of the fan random. by doing this the fan will constantly swift between speeds.
   
When i finished the code and the physical electronics. i started to create the design of the Indoor Windchime.

Down here you see the first sketch of the product
![6806A9C4-9610-4564-8371-A624D0FEF399](https://user-images.githubusercontent.com/121553579/209830583-4187ba1a-4e12-4192-acb5-dab1ab316ba4.jpg)

With the sketch in mind i started to search for materials. The windchime I found on the facebook market place. The pan, the sword shaped metal and the curkscrew i found in the storage room of my apartment. my orignal thought was to use a wooden sauna bucket as the bowl(the base in the picture) but unfortunatly i was not able to obtain a used one for a affortable price. so with all the materials i started building. i mostly used tape. because i thought for a prototype it does not has to be the most beutufiull thing. After a few days i finished the process of building it. it did defenityl not derve the beuty price but it worked. 

   
   

# The product

The product works as followed.
- You call the number connected to the small cellphone in the device.
- By calling this phone the screen of the phone lights up.
- The light of the phone gives a signal to the photoresistor.
- The photresistor sends a signal to the Joy-it Mega.
- The Joy-it Mega sends a signal which incluced a the code which implies that the fan will run a secuence random frequency for the remainder of 5 min.       after this, the fan shuts off.
- During this 5 minutes the fan will create a windflow which impacts the windchime.
- The windchime will make for 5 minutes at random times during this 5 minutes soft sounds.


# Reflection and further development




