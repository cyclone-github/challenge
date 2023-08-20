### Riddled History
![image](https://i.imgur.com/nBwtGaV.png)

- A fun challenge consisting of 4 main sets of challenges, each with their own set of hints, riddles and quests. 
- Challenge contains hints of fairy tails, classic movies and American history, all incorporated into hashes, encrypted files, and finishes strong with a simple, but challenging, reverse engineering "capture the flag".

Experience Required:
- hash cracking = Beginner / Intermediate
- reverse engineering = Beginner / Intermediate

Programs Used During Challenge:
- hashcat or jtr
- zip2john, office2john, pdf2john 
  - online version: https://hashes.com/en/johntheripper
- libreoffice
- notepad (or equivalent)
- pdf viewer
- 7zip (or equivalent)
- linux (for last challenge)
- Ghidra (or equivalent)

Notes:
- I would recommend running this in a linux VM (debian / ubuntu) along with with hashcat, libreoffice & Ghidra installed. 
- While you can complete all 4 challenges solely using Windows, you will not be able to run "july4th.bin" without some sort of linux terminal. However, running this binary is not required to complete the challenge. Source code to this binary is located in the walkthrough.zip.
- Only a modest GPU is required for the hash cracking challenges, but you'll need to put on your thinking cap for some of the riddles and reverse engineering challenge.

Version History:
- 2023-5-5; initial github release; 
- - sha256sum RiddledHistory.zip
4eb33564eaa845ccec47d5906c46d6655caee1ae2d13edc8198a79250a71f7f3
- 2023-5-6; fixed sha1 hash in #4 "finish.txt", added walkthrough; 
- - sha256sum RiddledHistory.zip b1dec5155c1405dd09f11a85b16cbfa31d33079dc226152d4d2cec6f0548a7eb
