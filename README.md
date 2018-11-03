# Tank-Go-V5 (Table Tank)
The project is build on Linkit-7697 and Robot-Shield-V2.0 board
It support LBT and Wi-Fi connections on IOS and Android of mobileibility devices to control it
The Robot shield is extend board with 2 of 750F capacitor as batteries and full charge by 30-40 mins  

I would like to call it as "Table Tank" instead - It is very funny to play with family and friends.
Huge Tahnks for George Chiou for his great work and contribution for Tank-Go sirious stuffs 
Please visit his Github to download 3D printing files https://github.com/GeorgeChiou/Robot-Shield-V2.0 and 
the instrutions has show on his Youtube channel https://youtu.be/rpaQaJ1GmJE
Meanwhile, all of H/W BOM list on the film description as well

For this update version are based on personal preference, include:
  - Optimize the RC lanscape and those buttons on left and right side 
  - Add MP3 play list up to 15 songs on middle of screen 
  - Insert "Backfill AMMO" message when bullets is zero and player still push fire button 
  - Add "repair" voice when Tank damage and the life turn to zero
  - Turret turn left and right angle consistant
  - Add "chu" sound when AMMO volume is zero and the player still push "Fire" button
  - Add AMMO LED and the indicator will light when AMMO QTY is zero and delight when backfil AMMO
  - Add Life LED and the indicator light when "Tank life" is zero and turn to dark when tank repair finished 
  - The user' button on LinkIT7697 board is test functionalify. It will play AMMO and life alarm 
    voice and those 2 external LED indicators light by 0.5 seconds on each. 
  - we also can use this user' button to test IR singal if it workable as well
  
  Attentions
    - The AMMO indicator connect P15 pin to Robot shield and the 2nd IR LED had move to P3 pin. 
      If you adopt the dual turret on your tank and connect the 2nd IR LED from original P15 IR LED had to plug 
      into P3 pin on robot shield board   
    - Need manual cut pice of Turret supporter as screwdriver show it on attach picture before plug connector to P3 pin
    - Please create mp3 folder on TF card then insert to DFPLAYER module. 
    - The github package include system voice which reserved by 0001 - 0010. 
      If you want to put your prefer songs then the file name will go from 0011 - 0025.mp3 by sequence.
    
Enjoy and have fun. Thanks.  
Niko Yang 2018, Oct 
