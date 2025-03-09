# Jabr
This is an Indie-software tool - encryptor/decryptor.

UI is currently only on russian, however the program **DOES support english** (also almost all UTF-8 characters in the latest version) inputs.

This is **no longer a small program** that I have been working on, it _quickly_ turned into one one my favourite projects that I have been developing alone **since August 2024.**

It is capable of **encrypting and decrypting messages** with almost any **UTF-8** caracters.

_Why is this program important?_
- Because in Jabr, the encryption and decryption processes happen via **my own algorithm** (called RE for short) which you won't find anywhere as of now.

Currently the algorithms use an Shift-code, and an alphabet which must follow these rules:
 -     Must include all the UTF-8 characters from the message including dots, spaces etc.
 -     Every symbol must only be used once in the alphabet.
 -     It may also contain other UTF-8 characters, if the user wants so (also used only once).
 -     The open key must be a natural number between 0 and the chosen alphabet length.

The program was made for fun and educational purposes, and is not meant to hurt anyone.
**New features will be added as time passes.**

Fell free to ask questions, and use the algorithm/program/code, 
Just **please add a dedication/credit/github link to my original work :D**




---------------------- Different versions ---------------------

-======================= First prototypes =====================

v1.0 - Lost in time

v1.1 - Lost in time

-=======================================================


-====================== Gen 2 (26.10.2024) ====================

v1.2 New features:
    - Full UI rework
    - Optimisation
    - Minor bug fixes

v1.2 alpha - unfinished

v1.2 beta - New UI, has dev info

v1.2.1 - Improved UI, has dev info, minor bug fixes

-=======================================================


-===================== Gen 3 (26.10.2024) =====================

v1.3 New features:
    - Split the encryptiom and decryption part into reusable functions :D
    - Code refactoring
    - Improved UI
    - Minor bug fixes

v1.3 beta - Unfinished, has dev info

v1.3_C - finished & clean version, has dev info

v1.3_O - optimised version, without dev info, works faster than other Gen 3 variants

-=======================================================


======================= Gen 4 ============================

v1.4 New features: (22.11.2024)
    - New and improved encryption/decryption algorith version with improved security (RE4)
    - Ability to change ciphers (RE1,  RE2,  RE3,  and  RE4)  
         //although not recomended to use lower than RE4
    - Added switchable settings
    - Improved UI
    - Fixed advanced info display bug about the encryption/decryption process
    - Massive optimisation
    - Fixed spelling mistakes
    
For developers/enthusiasts:
- Cleaned the code
- Removed old useless libraries
- Split the project into 3 files
- Made a test chamber with extra debugging info and simple UI


v1.4.1 QOL patch - New features: (20.1.2025)
    - New settings option: switchable input style for better user experience
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
-     Randomly generating codes & cipher parameters
-     English UI 
+     Fast base encryption/decryption options (simplified version of the UI)
+     (+) Settings menu
-     Advanced settings menu
-     Hashing for encryption/decryption option
-     Fast input system
-     File encryption/decryption
-     Custom cipher options
-     Multi-layer encryption/decryption
-     Persistent settings
-     Better installation guide (after persistent settings)
+     (+) Other ciphers to chose from in settings (?)

**"+": Currently already implemented in the latest version**

========================================================




=-=-=-=-=-=-=-=-=-=-=-=-=-=> Not defined future plans: 

-     Add multiple encryption/decryption at the same time
-     Integrate other ciphers in the program (not RE algorithms)
-     Add optional parameter bruteforcing using a bit of known information
-     Add graphical interface 
-     Enable creating of encryption/decryption .txt files
