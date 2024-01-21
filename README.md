# Adapter-2-in-1

Some time ago, I was reading different posts on the subreddit r/ErgiMechBoards (https://www.reddit.com/r/ErgoMechKeyboards/), where I saw people who liked more split ergo keyboards but because of  how they place the keyboard they wanted/get unibody ergo keyboards. An idea occurred to me that we could use some kind of center hub with a retractable center that hides the cable (like the retractable earphones) and that can grab the two parts so it is comfortable to write. Of course, an important point is, and always was, the price, so making a split with only one microcontroller can make it cheap.

So after some thinking, I decided to make a prototype to know if it was possible. I only want a split, so I will not develop it anymore but, because I didn't see anything like this, I wanted to put it on the internet in case someone needs it and wants to develop it. Also, I only know how to sketch and extract in fusion360 so it's not a good design. 
![alone](https://github.com/Fatbal/Adapter-2-in-1/assets/103590914/44be7553-58c9-41a0-99ad-7195356ccee3)






This prototype has four features that I wanted to include.
  
  1: Retractable cable. 
  
  This was easy, we can find some people that have already solved the problem, with springs, like LiorS5 (https://www.instructables.com/3D-Printed-Retractable-Earphones/), or, manually retractable, manabun (https://www.instructables.com/3D-Printed-Retractable-Earphones/). Just a reel to roll the cable and the microprocessor would rotate in the middle. 
  
  But that would be too easy. There were additional problems with the third and fourth features, which are optional for some people. In addition, I decided not to optimize the dimensions, because it would be too much work for just an idea I would not use.

  
  2: Keep the two halves together. 
  
  I decided to not develop it much. the idea is to use a screw. In my prototype, I used a piece of 3d filament to not use screws. But you could search for some other solutions like clip or buckle. Because of the height of the adapter, you get enough rigidity 

  
  3: Include a wireless charger.
  
  In case you want to make it wireless with Bluetooth you need to charge it. To charge it with less interaction and fewer cable problems I wanted to include a wireless charger pad like seen in the Linus tech video: https://youtu.be/4y-qF7Ga_W0?si=fOBTW9TyLPHXSCqa
 
  But as stated before, there would be problems with the first feature because the microprocessor would also rotate and may create stresses on the cable. My first solution was to create a little space so the pad could also rotate. But this solution would clash with the fourth feature as this one can't rotate.


  4: Pointing device.
 
  At first, I was imagining a circular adapter and there are a lot of people that use a trackball or a cirque trackpad in their keyboards, so circular and circular, made sense they need each other. I decided on a Cirque 40mm trackpad because is the one I had available. 
 
  But in both cases, you need to program where it is up and down and right and left. But if I let it rotate with the microprocessor, the directions would change or the cable would rotate and the cable could break with tension. 
  
  My first idea was to include a trrs connector to connect the spi adapter for the Cirque trackpad. because of the circular nature of the trrs connector, there would be no tensions in the cable and you could rotate the cirque independently from the rotation of the microcontroller.
  
  But of course, if you need more than 4cablese or you want to also include some keys at the center this solution would not work. So the next solution would be to rotate the exterior of the adapter instead of the center. Then it enters conflict with the second feature and would have problems with the cable. So I made it a three-part core with a static center and exterior and a rotating middle ground.
  
  To have more room I decided on a four floors adapter. The bottom floor is for the microcontroller, the battery, and the wireless charger pad. (You can make a slimmer floor if you want to put the microcontroller in the center, or eliminate it if you don't want the wireless charge.) The next floor is for the cable to roll in itself. I use a 10-ribbon cable that may be too thin, so it is better if you can adapt the dimensions. The next floor is for the wheel to rotate the middle rotating part from the floor just under. The top floor is for the pointing device. 


As can be seen, the additional features are the ones that complicate more the design. 







Challenges to solve:

  1: Retractable cable.
  It is difficult with my solution to calculate the best dimensions for your cable separation and it is beneficial to use a ribbon cable compared to individual cables.
  
  Also, there are some problems with tensions. 


  2: Improve how to grab the 2 halves. 
  It would be better to adapt to each one's preferences.


  3: Lowering the high/portability.
  To improve the portability, it would be important to lower the total height so you can put it easier in a bag.


  4: Thumbkeys that go in front.
  Self explanatory.


  5: Adapt to a PCB.
  You could have a PCB to put the microcontroller and some for the keys. You could even think of reusing some of the already popular split keyboards PCBs like Corne, Lily, or Sofle.


  6: Aesthetics.
  I don't like the boxy feeling it gives and right now it has an open frame. So it would be important to improve the aesthetics.
  
  Moreover, you need a frontal plate so you can get a  better grip on the microcontroller or extended USB port so it is easier to connect a cable.


I would like you to know that the ribbon cable I use is too small and would not support the 6X5 matrix I would need for the final print I made, Si the dimensions would need to change. But, as I stated before, I don't want to keep going with the project and I realized of this error after printing it.
