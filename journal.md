


# 14/03/2026 Started a new BOM 1.5h

Originally i had been planning for this to be a corexy belted printer
however i had a change of mind and want to try make a croxy belted 3d printer, which will probably make things harder

if i run out of time, this might get turned into a voron 0.1 size croxy 3d printer, it really depends how things go.

Back to what i actually did


# 18/03/2026 started on a parametric frame 2 hours 

Really just getting back into the swing of parametric CAD.
Last time i did a bunch of things in ways that fusion didnt like, so this time im trying to do things as proper as i can to stop fusion getting annoyed at me.




I then realised mounting rails on the bottom would be wayyy smarter so changed that. 
<img width="998" height="601" alt="image" src="https://github.com/user-attachments/assets/8075db3d-6b44-4262-a55c-fbf9b2f6674b" />

It was much quicker having allready done it once and knowing exactly what i need to use to achive the alignment. That being not the align too, but the constrain component tool.
Last time i tried to make a parametric printer i made the mistake of using the alignt tool a bunch, but i didnt realise that that didnt work well with parametric models.


<img width="1734" height="1040" alt="image" src="https://github.com/user-attachments/assets/76d35a78-d925-45ba-a522-4b33df623c9e" />

im quite pleased with some of the parametric stuff i did to add the right ammount of holes to the rails.

<img width="2164" height="1082" alt="image" src="https://github.com/user-attachments/assets/39898e8b-5d39-439e-97bc-72e819e9c3de"/>
Was there an easier way? Probably.
Did i have fun? yes!

My next task is to try figure out motor, and pulley mounting.

I will probably take inspiration from the Annex K3 for parts of the gantry
<img width="1345" height="1051" alt="image" src="https://github.com/user-attachments/assets/63dc8cae-d287-4995-a8eb-acb58437abfc" />

i loved this method for tensioning the belts, its so elegant and compact 
<img width="749" height="705" alt="image" src="https://github.com/user-attachments/assets/d1bdd392-942c-4d0e-9373-1e92f8af87f8" />


# 21/03/2026 1 hour

You probably cant tell, but when i constrained all of rails, that was done relative to the extrusions, which werent propely constrained. 
So i had to make sure everything was constrained
<img width="1203" height="925" alt="image" src="https://github.com/user-attachments/assets/b2668aa3-34a5-499b-aab7-c264caa66fd4" />


## well, it still wasnt properly constrained oops


i tried moving a carridge, and it was NOT happy
<img width="1728" height="946" alt="image (1)" src="https://github.com/user-attachments/assets/3fca792a-3ab7-45d3-9255-4cbcbb5d88bd" />
so i tried to fix that, which then resulted in 
<img width="1067" height="999" alt="image" src="https://github.com/user-attachments/assets/8ff57477-2e11-4a81-9e27-051501437bc3" />

So i figured, since i should have constrained the frame, THEN the rails, and my rails and frame were both super cooked, I should remove all the constraints on the rails, and re constrain them on the bottom instead of building it all upside down.
Wow the above sentence needed more punctuation.

Anyway YIPEEEEEEEEEEEEEEEEEEEE
<img width="1445" height="781" alt="image" src="https://github.com/user-attachments/assets/65123228-6cfe-4921-8fa7-17cb6ff83e27" />


# 23/03/2026 gantry part 1, 1.5 hour

modelling in anything with gt2 belts is allways interesting, not difficult , it just looks messy 
<img width="837" height="762" alt="image" src="https://github.com/user-attachments/assets/4c983689-3163-4080-ab27-992a2a10c5ac" />


i think ive gotten somewhere with belt mounting, i didnt want to make a 1 for 1 copy of the anex K3 , however this is heavily inspired by it

<img width="759" height="717" alt="image" src="https://github.com/user-attachments/assets/73881704-50af-4041-96c4-986ed2f35a7c" />
<img width="647" height="602" alt="image" src="https://github.com/user-attachments/assets/13c63887-1490-4cd3-a1f1-96b8e0da8e77" />

below is an image of the crossection of the annex k3
<img width="548" height="383" alt="image" src="https://github.com/user-attachments/assets/258a3d78-c412-4bcd-871c-6e1ee51a9326" />

i still need to model in screws on mine, the key difference is that mine is in a bit of a smaller footprint , and also the anex team wrapped the belt arround an m3 bolt, i added a 0.8mm wall thickness hollow cylinder arround a bolt because i feared the bolt cutting into or damaging the belt.

# 23/03/2026 gantry part 2, 

Im currently working on finalising which hardware i use and exactly how i mount the rail.

in the previous entry i was mainly focussing on making sure that everything went perfectly with the belts, this time im making sure everything goes perfectly with the rails, i REALYY need to make sure i grip these rails well.

So i plan on having 6 bolts to hold each rail in
<img width="556" height="367" alt="image" src="https://github.com/user-attachments/assets/3242e76a-8ca3-4f67-8357-9d30b4047da0" />

a little detail i like was making sure that the heat set inserts on the bottom that some of those bolts screw into, are recessed so that they dont stick out and cause a misalignment against the carridge of the linear rail.
<img width="1076" height="946" alt="image" src="https://github.com/user-attachments/assets/e3c756de-a7fa-4710-bbff-99402caadd87" />

8 screws of varying length later and we have a hopefully well screwed together little assembly
<img width="745" height="740" alt="image" src="https://github.com/user-attachments/assets/63dc047f-e258-40fe-b654-fa556ecdfc90" />

a mirror and some constraints later
and we get this!

<img width="1673" height="907" alt="image" src="https://github.com/user-attachments/assets/25509371-bd7d-411a-a7d4-8288755284a7" />



## WOOO

im so happy its comming together
<img width="1252" height="938" alt="image" src="https://github.com/user-attachments/assets/2de3e820-9f49-4c57-827c-09da444f947a" />

Some of the things im aiming to achive with the cad are
- have the gantry be parametric, so i could scale it from 120x120 to 350x350 or whatever else i want
- have all the constraints modelled in properly so that you can move it arround in CAD and check for interference issues

part of the reason im actually making it parametric is because im not exactly sure what my travel distances will be, since some area will be lost depending on the size of my toolhead, so i want to be able to compensate for that

<img width="1386" height="936" alt="image" src="https://github.com/user-attachments/assets/ba9e4391-7f00-433f-b07f-75dee35d845a" />

the parametric aspect of the CAD works arround 40% of the time
when it doesnt work re defining a handful of the rigid groups seems fix it which is odd to say the least





## 26/03/2026 5 hours

Trying to speed up the build a lot now

i threw together the mounting for the 625 bearings

i had been delaying this for quite a while because i wasnt sure where i was going to place the lower belt which would throw off everything.

<img width="965" height="676" alt="image" src="https://github.com/user-attachments/assets/41c4e42d-e504-414c-adc0-3180f979d8f8" />

the design wouldnt print the best in one peice , also wouldnt be very easy to use a vice to press fit the bearings

so ive split it into two parts
<img width="1294" height="704" alt="image" src="https://github.com/user-attachments/assets/4375ba53-b467-4ca7-accd-9b488f81c9fb" />
<img width="810" height="689" alt="image" src="https://github.com/user-attachments/assets/0ccfcefd-ee16-48d3-ac19-d02b0c02f867" />

but i also believe alignment of these two parts is quite important , so in addition to the m4 bolts that will hold the halves together there will also be locating features 
<img width="1027" height="822" alt="image" src="https://github.com/user-attachments/assets/68d463c0-7687-4025-a8f9-3ab92b7f05ef" />
<img width="1232" height="889" alt="image" src="https://github.com/user-attachments/assets/89014941-9cc5-4cd5-9b6f-9f6ce605cbf1" />

Ive added 0.2mm of clearance between the locating geometries so hopefully they should fit okay

oh yeah
<img width="1076" height="843" alt="image" src="https://github.com/user-attachments/assets/42e75715-940a-49ea-8384-926116f5f2f2" />
shoutout to autodesk for making custom length bolts a payed feature

i get the mild inconvenince of making my own parametric bolts, which really doesnt take long

It should be able to be copied and used for all the other once since i have "A config" and "B config" which flip which is the idler , and which is the pulley
<img width="934" height="891" alt="image" src="https://github.com/user-attachments/assets/30a03ecb-727b-46ea-a456-5506ea1a6022" />
<img width="762" height="644" alt="image" src="https://github.com/user-attachments/assets/6ff68f8d-cc68-4d39-9411-e01a3acb4fc4" />

spotting this wasnt great
<img width="870" height="955" alt="image" src="https://github.com/user-attachments/assets/16bdc0d9-3674-48b4-ba73-eed562f60db6" />

however couplers like these exist
<img width="1927" height="876" alt="image" src="https://github.com/user-attachments/assets/9e430d2c-4dc5-41c8-b2fc-02e8104fdaa2" />
which mean i dont need to redesign anything which is amazing



<img width="1323" height="1059" alt="image" src="https://github.com/user-attachments/assets/77d8dd44-2303-4e4c-8a0b-15cd79ee27fc" />

Realised i need to rework this as theses are far to close
<img width="1162" height="959" alt="image" src="https://github.com/user-attachments/assets/a4d511f1-b8fe-4185-8465-5d78dd1d053b" />
In the process of fixing the above issue i also discovered the holes for the motor attachment were slightly ofset, meaning i had to remove and readd the motor mounting holes. I am however glad that it was simply the motor mounting holes and not the motor which is aligned with a bunch of other stuff

ah this is a lot of errors
<img width="945" height="924" alt="image" src="https://github.com/user-attachments/assets/aeadb14d-1aac-4404-80f9-8cfb40820360" />

Given the ammount of errors i was getting I decided the best course of action would be to export the completed assemblies, like the ones for the motor / pulley mounting. Then go back to an earlier version of the file without the errors and import the assemblies to get a much cleaner doc,
<img width="1687" height="1026" alt="image" src="https://github.com/user-attachments/assets/c0a194c7-a82c-44cd-b9e6-dcfc1465ee1b" />

i still need to import the rail holders again, but this looks a lot better, and takes way less time to compute when changing perameters


# AHHHH 27/03/2026

lovely how in fusion its shown as <img width="551" height="130" alt="image" src="https://github.com/user-attachments/assets/a353b3d0-2d27-4183-ade3-40085bd145aa" />
but once you dare to look at it
it turns into this AHH
fussssiiioonnnnn 

<img width="2357" height="1079" alt="image" src="https://github.com/user-attachments/assets/6cfbcf9f-e0f8-4926-a7df-792e1ada78f8" />


it appears exporting as a step
and then importing fixes the issues?
im not exactly sure how that works but ok fusion


if we ignore bits of floating here and there its starting to look quite good
<img width="1421" height="1029" alt="image" src="https://github.com/user-attachments/assets/22f98b70-ae70-4ebe-9a47-15d7a6d87c8e" />

time to fix the floaties

Screws first
<img width="1202" height="969" alt="image" src="https://github.com/user-attachments/assets/ca2d1893-1099-427c-8825-874b5f007ba0" />


i could have just made a block, and i did
but i felt like doing something a little fun just because ive been doing CAD for 6 hours straight at this point
<img width="1185" height="728" alt="image" src="https://github.com/user-attachments/assets/a3436d73-d60d-45da-8a14-0e7c2e78b5a2" />
i know infil could have reduced the weight, but i just like hexagons

wow this is definetly comming together quickly now
<img width="1693" height="938" alt="image" src="https://github.com/user-attachments/assets/4e86d047-c066-48f5-b682-b0f6ecf486ec" />



