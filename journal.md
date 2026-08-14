Day one
the first step of this massive project was creating a schematic, essentially the base of a breadboard(the green chips you see everywhere), that tell it where to put a wire, which makes every part function properly. I used 60 input keys and a raspberry Pi pico and wired them all together here. This stage took about 2 days (YEAH I KNOW FORGIVE ME)
<img width="1223" height="830" alt="image" src="https://github.com/user-attachments/assets/b226f4c5-8190-49b7-9573-3bbc8c0b5227" />
I encountered many issues in this stage that were all quickly resolved after binge watching around 30% of youtube :)
After this, i ran the ERC (electrical rule checker) and BINGO! no errors!
<img width="119" height="31" alt="image" src="https://github.com/user-attachments/assets/5e175ace-bb6f-4b5c-9453-c89f246bbd52" />
This Step combined with the PCB took me a total of 4 hours

The next step was the MOST painful, as it isnt very well documented anywhere, mainly because of the fact that KiCAD (the software im using) gets updated a lot
This step was designing the PCB (the printed circuit board) this is just the breadboard lol
this stage is when i encounters the most problems ive ever had(aside from being born)
first, when i arranged everything, the wires were ALL messed up
<img width="1203" height="832" alt="Screenshot 2026-08-11 150314" src="https://github.com/user-attachments/assets/971ddcd5-d3d8-4869-98d0-5084f8fcd105" />
while it might look quite awesome and organised it is HELL for the next step, which is routing the wires via copper lines
after much trial and error, i managed to finish that too!
<img width="1498" height="699" alt="image" src="https://github.com/user-attachments/assets/5e3a4e0a-17f5-4445-a411-0b3b6bb44b45" />
Now i can show u a 3d render bc at this stage the mapping of everything was done and i added 3d models for the board!
here it is!
<img width="1157" height="463" alt="Screenshot 2026-08-13 080711" src="https://github.com/user-attachments/assets/76ad7ef1-9b6d-4b90-bef7-f97b54ebb201" />
pretty cool right! I'm so proud of me yay
the next step was to make a 3d case using blender

Its been another day!
I just finished the case 
<img width="1474" height="886" alt="Screenshot 2026-08-14 214806" src="https://github.com/user-attachments/assets/9a0ed4af-3a1a-4652-815e-0b42080cfcc7" />
as you can see, its quite simple and nice! it took me like 2 hours and thirty minutes
before i move on, im gonna make sure the scale is good enough and im gonna update the repo
the next and final step is writing the firmware. I'll be doing this with github actions

