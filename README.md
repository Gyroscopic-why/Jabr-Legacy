# Jabr
This is an Indie-software tool - Encoder/Decoder.

UI is currently only on russian, however the program **DOES support english** inputs.

This is a **no longer a small program** that I have been working on, it _quickly_ turned into one one my favourite projects that I have been developing alone **since August 2024.**

It is capable of **encrypting and decrypting messages** with any ASCII caracters except for the _"ENTER"_ key.
The encryption and decryption processes happen via **my own algorithm** called **RE for short.**

The algorithm uses an Shift-code, and an alphabet which must follow these rules:
 -     Must include all the ASCII characters from the message including dots, spaces etc.
 -     Every symbol must only be used once in the alphabet.
 -     It may also contain other ascii characters, if the user wants so (also used only once).
 -     The open key must be a natural number between 0 and the chosen alphabet length.

The program was made for fun and educational purposes, and is not meant to hurt anyone.
**New features will be added as time passes.**

Fell free to ask questions, and use the algorithm/program/code, 
Just **please add a dedication/credit/github link to my original work :D**




---------------------- Different versions ---------------------

-======================= First prototypes =====================

v1.0 - bugged

v1.1 - semibugged

-=======================================================


-====================== Gen 2 (26.10.2024) ====================

v1.2 alpha - unfinished UI, but works fine

v1.2 beta - New UI, has dev info, works fine

v1.21 - Improved UI, has dev info, works fine, minor bug fixes

-=======================================================


-===================== Gen 3 (26.10.2024) =====================

v1.3 beta - works fine, has dev info

v1.3C - more clean code version, has dev info, works the same as v1.3 beta

v1.3_Opti - optimised version, a bit of removed dev info, works faster than other Gen_1.3 

-=======================================================


======================= Gen 4 ============================

v1.4 New features: (22.11.2024)
    - New cipher version with improved security (RE 1.4)
    - Ability to change ciphers (RE 1.0,  RE 1.3,  and  RE 1.4)  
         //although not recomended to use lower than 1.4
    - Switchable settings
    - Improved UI
    - Fixed advanced info about the encryption/decryption process
    - Improved performance
    - Fixed spelling mistakes
    
For developers/enthusiasts:
- Cleaned the code
- Removed old useless libraries
- Split the project into 3 files
- Made a test chamber with extra debugging info and simple UI


v1.4.1 QOL patch - New features: (20.1.2025)
    - New settings feature: switchable input style for better user experience
    - Changed settings UI for future scaleability
    - Improved info output
    - Improved performance
    - Fixed inconsistent spacing issue
    - Fixed spelling mistakes

For developers/enthusiasts:
    - Massive code refactoring for easier integrations
    - Removed old useless code
    - Test chamber code cleaning
    
=======================================================


======================  Gen 5  ============================

*Work in progress,
      est. finish date - 2 april 2025
      
=======================================================


Expected features:
-     More intuitive UI
-     Randomly generating codes
-     Fast encoding/decoding options
+     Settings menu
-     Advanced settings menu
+     Other ciphers to chose from (?)
-     First bruteforcing prototypes (?)

**"+":** Currently already implemented in _Gen 4_

========================================================




=-=-=-=-=-=-=-=-=-=-=-=-=-=> Future plans: 

-     Clean the UI
-     Add the option of randomly generating cipher parameters
-     Add multiple encoding/decoding at the same time
-     Integrate other ciphers in the program
-     Add optional parameter bruteforcing using a bit of known information
-     Add additional security to the main cipher
-     Add graphical interface (?)
-     Enable advanced settings menu
-     Make settings persistent (until user changes them)
-     Enable creating of encoded/decoded .txt files
