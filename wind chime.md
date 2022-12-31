# Remote-Windchime-Project

For the course Principles of repurposing of electronics, I had to create an electronic device out of recycled and repurposed electronics. 
I am originally a psychology student with no knowledge of electronics, so it was I really challenged myself with this course. 
together with the teacher I discussed what might be a project that is on a level that I could understand and learn it easily and quickly.

In my project, I created a Windchime device. in the picture below you can see how the prototype looks.![WhatsApp Image 2022-12-28 at 14 36 05](https://user-images.githubusercontent.com/121553579/209814721-6d9a0c35-7d71-42e9-a177-73df867d03d9.jpeg)

# Parts used

- Old used cooking pan.

![WhatsApp Image 2022-12-28 at 14 36 10](https://user-images.githubusercontent.com/121553579/209816692-9450c4c7-0f04-4d24-8177-716842147d89.jpeg)

- Old used corkscrew.
- Old sword-shaped metal.
- Old used windchime 
Down below you see all three: corkscrew, sword, and windchime.

![WhatsApp Image 2022-12-28 at 14 36 08](https://user-images.githubusercontent.com/121553579/209816564-32651d87-b8fb-4667-bbbe-6a6186f93c74.jpeg)

- Old working cell phone.

![WhatsApp Image 2022-12-28 at 14 36 00 (2)](https://user-images.githubusercontent.com/121553579/209816704-b6c4a25c-c5c1-4840-aa46-9d5d3ae7301c.jpeg)

- Used computer fan.

![WhatsApp Image 2022-12-28 at 14 35 57](https://user-images.githubusercontent.com/121553579/209816485-8e425b6a-dd06-4d2e-bc2f-d9a0934e4bfe.jpeg)

- Old decoration (beanie and leaf crown)
- Tape

# Electrical parts used

- Arduino 12v adapter. 
![WhatsApp Image 2022-12-28 at 14 35 59](https://user-images.githubusercontent.com/121553579/209816395-46ab2d93-5781-4f0a-a46e-ad047a4cd7c0.jpeg)

- Joy-it mega

![image](https://user-images.githubusercontent.com/121553579/209836505-cbfb4a69-7ac0-4017-bc72-2b0ed78c50ab.png)


- Breadboard

![image](https://user-images.githubusercontent.com/121553579/209836441-bf4771b6-b304-4ffc-9cc0-56c5354460a4.png)

- Conductor BC547B

![image](https://user-images.githubusercontent.com/121553579/209837267-f5642846-94ac-4223-ab5e-8fd22f25cca3.png)


- Resistors 10 kohm
- Transistor irf540n
- Photo resistor

Down here you see the three: photoresistor, transistor and resistor
![image](https://user-images.githubusercontent.com/121553579/209834156-413e4426-be45-44be-9163-e2733aeaeb7c.png)



# Arduino 
![overwview](https://user-images.githubusercontent.com/121553579/209814876-22cf98eb-8fba-4687-8494-975da17d1075.jpeg)

In this picture you see the how i connected the boards together and finally how the fan is connected.
The code I used can be found here:  https://github.com/YorwinVanPraet/Remote-Windchime-Project/issues/2#issue-1512796448





# Design procedure and explanation


When I had to think of what kind of thing I was going to create I wanted to implement my psychological background into the project.
I thought of a product that creates a feeling of recognition, validation, and warmth.
the first idea that I had was to create a remote candle/light. which implies that when I am in the Amsterdam and the person that has this candle at home is in Bucharest.
then when I call the number that is connected to that candle/light it would light up.
after some discussion with my tutor for this course, we came to the conclusion that it is nice to replace the candle/light with a fan that is stimulating a windchime.

So how am I going to build this device? First of all, I needed to understand Arduino, it was for me more difficult than I expected. I looked up tutorials on YouTube and at some point, I got a bit of the hang of it. I used thinker cad to simulate the Arduino. with the tutorials, I first learned how to create and use the Photo resistor as an (input) to decide the volume of the light (output). with being able to make this the only thing I had to change was the output from a small led to a fan. 
  
  To make the fan work I needed a 12v power source. The Joy-it mega only was capable of 5V and only has a 5V output. Therefore, I needed to sold an extra cable to the bottom of the Joy-it mega, and connect this with a direct connection to the fan. 
   
   After I managed this, it was time to program the code. What I wanted to code is that when the photoresistor receives light a sequence is started which takes 5 minutes. First, my thoughts were to do it longer but after listing to the windchime and getting feedback from others I decided to shorten the time to 5 minutes. What I also wanted to implement is that the fan is not blowing constantly at the same speed. I wrote a code that makes the frequencies of the voltages input of the fan random. by doing this the fan will constantly swift between speeds.
   
When I finished the code and the physical electronics. I started to create the design of the Indoor Windchime.

Down here you see the first sketch of the product:
![6806A9C4-9610-4564-8371-A624D0FEF399](https://user-images.githubusercontent.com/121553579/209830583-4187ba1a-4e12-4192-acb5-dab1ab316ba4.jpg)

With the sketch in mind, I started to search for materials. The windchime I found it on the Facebook marketplace. The pan, the sword-shaped metal, and the corkscrew I found in the storage room of my apartment. my original thought was to use a wooden sauna bucket as the bowl (the base in the picture) but unfortunately, I was not able to obtain a used one for an affordable price. So, with all the materials, I started building. I mostly used tape. because I thought a prototype does not has to be the most beautiful thing. After a few days, I finished the process of building it. it did definitely not deserve the beauty price but it worked. 

   
   

# The product

The product works as followed.
- You call the number connected to the small cell phone in the device.
- By calling this phone the screen of the phone lights up.
- The light of the phone gives a signal to the photoresistor.
- The photoresistor sends a signal to the Joy-it Mega.
- The Joy-it Mega sends a signal which included a code that implies that the fan will run a sequence random frequency for the remainder of 5 min.  after this, the fan shuts off.
- During these 5 minutes the fan will create a wind flow that impacts the windchime.
- The wind chime will make for 5 minutes at random times during these 5 minutes soft sounds.


# Reflection and further development
When I look back at the course, I am very happy that I took it without having any previous knowledge of the topic. The tutor was able to give me good support with my project and understood as well that with my background it can be very challenging. Sometimes it was very challenging but at the weekly meeting we had, I could ask for help. the tutor organized also some 1 on 1 session that gave me more confidence in the work I did for my project.

Now looking at the project I did. What are things that could be revised or improved? In my opinion, there are a lot of things that could be revised and improved. For example, in the prototype, I have now there is only 1 mode that is activated by the phone call. I think this is very limited and would suggest that there would be multiple sequences. Another thing that could be revised is how the prototype looks. Of course, it is a prototype, but it could have been more refined. 


Besides the thing that could be revised or improved, I have a lot of ideas for further development.  The first is to add another fan. At the moment the airflow only comes from the bottom. If a fan could be placed in like a 30 degrees position. There would be different airflow that might change the sound and frequency of the windchime. Another thought could be to add a stop button.  When you activated the device you probably never know what is happening on the other side. For example, when the person is in a meeting. Next to that, a new idea arises. It would take a change in code and would introduce an app. An app that is installed on the phone I call. When the phone is called it shows one of the random videos of the white light of the app. This was also one of the ideas I had while working on the project but the level of the task was a bit too high for me. 

Overall, I think the project I created is a fun thing. I am happy that I got the possibility to do this course and I can recommend every exchange student to consider following this course. It gives you a nice introduction to the topic.





