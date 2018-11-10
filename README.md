# Tank-Go-V5 (Battle Tank)
The project is build on Linkit-7697 and Robot-Shield-V2.0 boards. 
According to Tank size, I would like to call it as "Table Tank" instead, it is very funny to play with family or friends.
It is MTK LinkIT-7697 and Robot-Shield 2.0 is expansion board 
  - It support LBT and Wi-Fi connections on PCs, IOS, Android or any mobileibility devices 
  - Two of 750F capacitor (full charge by 30-40 mins) on Robot-shield board as batteries
----------------------------------------------------------------------------------------------------------------
Huge Tahnks to George Chiou on his great work and contribution
  - Please visit his Github to download 3D printing files https://github.com/GeorgeChiou/Robot-Shield-V2.0 and 
  - The assembly of instrutions show on his Youtube channel https://youtu.be/rpaQaJ1GmJE
  - Meanwhile, all of H/W BOM list on the film description and Github link as well
  - Facebook https://www.facebook.com/miniPlanrobot/
  - MTK & Robot Shield https://docs.labs.mediatek.com/resource/linkit7697-arduino/en/kits-and-shields/robot-shield
  - This version of software: https://github.com/yangniko137/Tank-Go-V5
----------------------------------------------------------------------------------------------------------------
For this update version are based on personal preference, include:
  - Optimize the RC lanscape and those buttons on left and right side 
  - Update defalut voice volume from 6-28 by 2 / step and defalut is 22 
  - Add MP3 play list up to 15 songs on middle of screen 
  - Insert "Backfill AMMO" message when bullets is zero QTY 
  - Add "repair" voice when Tank damage and the life turn to zero
  - Turret turn left and right angle consistant
  - Add "chu" sound when AMMO volume is zero and the player still push "Fire" button
  - Add AMMO LED and the indicator will light when AMMO QTY is zero and delight when backfil AMMO
  - Add Life LED and the indicator light when "Tank life" is zero and turn to dark when tank repair finished 
  - The user' button on LinkIT7697 board is test functionalify. It will play AMMO and life alarm 
    voice and those 2 external LED indicators light by 0.5 seconds on each. 
  - we also can use this "user button" to test IR singal if it workable as plan
  - Update Tank naming rules
  - Change P15 for AMMO LED and move IR2 to P3
----------------------------------------------------------------------------------------------------------------
Attentions
  - The AMMO indicator connect P15 pin to Robot shield and the 2nd IR LED had move to P3 pin. 
    If you adopt the dual turret on your tank and connect the 2nd IR LED from original P15 IR LED had to plug 
    into P3 pin on robot shield board. Also, try to manual cut pice of Turret supporter as screwdriver show as 
    attach picture before plug connector to P3 pin
  - Please create mp3 folder and copy all of mp3 files (for system) into TF card then insert to DFPLAYER module. 
  - The github package include system mp3 files and the file names range reserved from 0001 - 0010.mp3 
    If you want to put your prefer songs then the file name will be 0011 - 0025.mp3 (total 15 songs) by sequence.
----------------------------------------------------------------------------------------------------------------
Enjoy and have fun. Thanks.  
Niko Yang 2018, Oct 
