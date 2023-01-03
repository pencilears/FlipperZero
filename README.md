# FlipperZero
just a place to put flipper projects and ideas

my current project ideas:

make games for flipper:
reason: fun way to show off hardware without spooking people
also: winning games makes the dolphinscore go up, but currently nobody cares about this


game ideas:
---

rock paper sissors 
  flipper should be able to play a game with other flippers by pointing the IR sensor at each other and pushing buttons
  
  RPS is the classic beginner programer project
  
  * problem: needs to send and receive almost simultaniously and then beep with the result
  * work: currently I'm just making art for this in paint because I am a scrub

pokewalker emulator
--

  flipper should be able to talk in IR to your SS/HG game but the existing emulator makes it easy to just put in max steps and get everything, 
  
  might be cool to have some reason to actualy play with it...
  
  * problem: how to get step data
 
    * idea: flipper can also talk in bluetooth to your phone, therefore we should be able to import stepcout data for use rather than just fudging the numbers
    problem: more fucking programming
  
    * idea: build a little accelerometer board and plug that shit in directly
    problem: chip shortage
    
    * idea: charge pokewalker via dolphinscore
    problem: makes dolphinscore relivant, whole point of making games is to up the score
    
  * work I can do: pokewalker screen is 96X64 will be interesting to make a useful interface for it

  * resources:
  http://dmitry.gr/?r=05.Projects&proj=28.%20pokewalker 
