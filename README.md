# Adapter-2-in-1

Some time ago i was reading diferent post on the subreddit r/ErgiMechBoards I soaw people that liked more split ergo keyboards but because how they place the keyboard they wanted a unibody ergo keyboard. An idea occurred to me that we could use one retracteable centre that hide the cable (like the retractable earphones) and grab the two parts so it easy to write.

So after some thinking I decided to make a prototype to know if it was possible. I only want split, so I will not develope anymore but, because I didn't see anything like this, I wanted to put it on the internet in case someone need it and want to develope it.

This prototype has four features that I wanted to include.
  1: Retractable cable. 
  This was easy, we can find some people that have already solved the problem, with springs, like LiorS5 (https://www.instructables.com/3D-Printed-Retractable-Earphones/), or, manually retractable, manabun (https://www.instructables.com/3D-Printed-Retractable-Earphones/). Just a reel to roll the cable and the microprocessor would rotate in the middle. 
  But that would be too easy. There were additional problems with the third and fourth features, which are optional for some people. In addition, I decided not to optimize the dimensions, because it would be too much work for just an idea I would not use.
  
  2: Keep the two halves together. 
  I decided to not develop it much. the idea is to use a screw. In my prototype, I used a 3d filament shard to not use metal or 3d print screws. But you could search for some other solutions like clip or buckle. Because of the hight of the adapter you get enough rigidity 
  
  3: Include a wireless charger.
  In case you want to make it wireless with Bluetooth you need to charge it. To charge it with less interaction and less cable problems I wanted to include a wireless charger pad like seen in Linus tech video: https://youtu.be/4y-qF7Ga_W0?si=fOBTW9TyLPHXSCqa
  But as statated before, there would be problems with the first feature because the micro processor would also rotate and may create stresses on the cable. My first solution was to create a little space so the pad could also rotate. But this solution would clash with the fourth feature as this one can't rotate.

  4: Pointing device.
  At first, I was imagining a circular adapter and there are a lot of people that use a trackball or a cirque trackpad in their keyboards, so circular and circular, made sense they need each other. I decided on a cirque 40mm trackpad because is the one I had available. 
  But in both cases you need to progame where is up and down and right and left. But if I let it rotate it with the microprocessor, the directions would change or the cable would rotate and the cable could break with tension. 
  My first idea was to incluse a trrs connector to connect the spi adapter for the cirque trackpad. because of the circular nature of the trrs conector there would be no tensions in the cable and you could rotate the cirque independently from the rotation of the microcontroler.
  But of course, if you need more than 4 cable or you want to also include some keys at the center this solution would not work. So the next solution would be to rotate the exterior of the adapter instead of the center. Then it enters with conflict with the second featured and would have problems with the cable. So I made it a three part core with a static centre and exterior and a rotating middle ground.
  To have more room I decided for a four floors adapter. The bottom flour its for the microcontroller, the battery and the wireless charger pad. (you cna make a climer floor if you want to put the microcontroller in the center, or eliminated complately if you dont want the wireless charge.) The next floor is for the cable to roll in itself. I use a 10 ribbon cable that may be too much thin, so it is beter if you can addapt the dimensions. The next floor is for the wheel to rotate the middle rotating part from the floor just under. And the top floor is for the pointing device. 


As can be seen, the additional features are the ones that complicate more the design. 

Challenges to solve:
  1: retractable cable.
  Its is dificult with my solution to calculate the best dimensions for your cable separation and it is beneficial to use a ribbon cable compared to individual cables.

  2: Improve how to grab the 2 halves. 
  It would be better tot adapt to each preference.

  3: Lowering the high/portability.
  To improve the portability it would be important to lower the 
