# Jabr
Encoder/Decoder Rus/(English text supported but the UI does not have a translation)

This is a relatively small program that i have been working on for not a very long time.

It is supposed to encrypt or decrypt messages with any ASCII caracters except for the "ENTER" key.
The encryption and decryption process happen via my own algorithm called RE for short.

The algorithm uses an open key, and a set alphabet which must follow these rules:
 -     Must include all the ASCII characters from the message including dots, spaces etc.
 -     Every symbol must only be used once in the alphabet.
 -     It may also contain other ascii characters, if the user wants so (also used only once).
 -     The open key must be a natural number between 0 and the chosen alphabet length.

The program was made for fun and educational purposes, it is not meant to hurt anyone.
New features will be added as time passes.

Fell free to ask questions, and use the algorithm/program/code, 
Just please add a dedication/credit to my original work :D




------------------------------------- Current versions ---------------------------------------

-======================= First prototypes ========================

v1.0 - bugged

v1.1 - semibugged

-=================================================================


-=========================== Gen 1.2 =============================

v1.2 alpha - unfinished UI, but works fine

v1.2 beta - New UI, has dev info, works fine

v1.21 - Improved UI, has dev info, works fine, minor bug fixes

-=================================================================


-=========================== Gen 1.3 ======================================================

v1.3 beta - works fine, has dev info

v1.3C - more clean code version, has dev info, works the same as v1.3 beta

v1.3_Opti - optimised version, a bit of removed dev info, works faster than other Gen_1.3 

-==========================================================================================


============================ Gen 1.4 ======================================================

v1.4 New features:
    - New cipher version with improved security (RE 1.4)
    - Ability to change ciphers (RE 1.0,  RE 1.3,  and  RE 1.4)  //although not recomended to use lower than 1.4
    - Switchable settings
    - Improved UI
    - Fixed advanced info about the encryption/decryption process
    - Improved performance
    - Fixed spelling mistakes
===========================================================================================


============================ Gen 1.5 =============================
*Work in progress,
      est. finish date - 7 jan 2025
==================================================================


Expected features:
-     More intuitive UI
-     Randomly generating codes
-     Fast encoding/decoding options
+     Settings menu
-     Advanced settings menu
+     Other ciphers to chose from (?)
-     First bruteforcing prototypes (?)

"+" added in Gen 4
==================================================================




=-=-=-=-=-=-=-=-=-=-=-=-=-=> Future plans: 

-     Clean the UI
-     Add the option of randomly generating cipher parameters
-     Add multiple encoding/decoding at the same time
-     Integrate other ciphers in the program
-     Add optional parameter bruteforcing using a bit of known information
-     Add additional security to the main cipher
-     Add graphical interface (?)
-     Enable advanced settings menu
-     Make settings persistent through every launch (until user changes them)
-     Enable creating of encoded/decoded .txt files
