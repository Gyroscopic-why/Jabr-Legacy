# Jabr
This is an Indie-software tool - **encryptor/decryptor.**

UI is currently only on russian, however the program **DOES support english** (also almost all UTF-8 characters in the latest version) inputs.

This is **no longer a small program** that I have been working on, it _quickly_ turned into one one my favourite projects that I have been developing alone **since August 2024.**

It is capable of **encrypting and decrypting messages** with almost any **UTF-8** caracters.


# _Why is this program important?_
- Because in Jabr, the encryption and decryption processes happen via **my own algorithm** (called RE for short)
- which almost has millitary grade security
- are super compact
- and you won't find them anywhere else as of now.

**Currently the algorithms uses** an Shift-code, and an **alphabet which must follow these rules:**
 -     Must include all the UTF-8 characters from the message including dots, spaces etc.
 -     Every symbol must only be used once in the alphabet.
 -     It may also contain other UTF-8 characters, if the user wants so (also used only once).
 -     The open key must be a natural number between 0 and the chosen alphabet length.

The program was made for fun and educational purposes, and is not meant to hurt anyone.
**New features will be added as time passes.**

Fell free to ask questions, and use the algorithm/program/code, 
Just **please add a dedication/credit/github link to my original work :D**




# Different versions and progress:

## **Gen 1 (first prototypes)**
**Versions:**
- _v1.0_ - Lost in time
- _v1.1_ - Lost in time






## **Gen 2 (26.10.2024)**

- **v1.2 New features:**
    - **Full UI rework**
    - Optimisation
    - Minor bug fixes

**Versions:**
- _v1.2 alpha_ --- unfinished
- _v1.2 beta_  ---- New UI, has dev info
- _v1.2.1_ -------- Improved UI, has dev info, minor bug fixes






## **Gen 3 (26.10.2024)**

- **v1.3 New features:**
    - **Split the encryptiom and decryption part into reusable functions :D**
    - Code refactoring
    - Improved UI
    - Minor bug fixes

**Versions:**
- _v1.3 beta_ --- Unfinished, has dev info
- _v1.3_C_ ------ finished & clean version, has dev info
- _v1.3_O_ ------ optimised version, without dev info, works faster than other Gen 3 variants






## **Gen 4 (22.11.2024 - 11.3.2025)**

- **v1.4 New features: (22.11.2024)**
    - **New and improved encryption/decryption algorith version with improved security (RE4)**
    - **Ability to change ciphers (RE1,  RE2,  RE3,  and  RE4)** (RE2 is curently only accessible in v1.4.2 beta)
    - **Added switchable settings**
    - **Fixed advanced info display bug about the encryption/decryption process**
    - Improved UI
    - Massive optimisation
    - Fixed spelling mistakes
    
- **For developers/enthusiasts:**
    - **Split the project into 3 files**
    - **Made a test chamber with extra debugging info and simple UI**
    - Cleaned the code
    - Removed old useless libraries




- **v1.4.1 QOL patch - New features: (20.1.2025)**
    - **New settings option: switchable input style for better user experience**
    - Changed settings UI for future scaleability
    - Improved info output
    - Improved performance
    - Fixed inconsistent spacing issue
    - Fixed spelling mistakes

- **For developers/enthusiasts:**
    - **Massive code refactoring for easier integrations**
    - Removed old useless code
    - Test chamber code cleaning




**v1.4.2 beta Medium update:**
- **New features:**
    - **New settings feature: enabling using of shortcuts for fast encrypting/decrypting**
    - **Added shortcut parsing for user inputs in the task selection menu**
    - **Fixed info output**
    - Added primitive error output for parsing shortcuts
    - Improved performance
    - Fixed spelling mistakes
    - Changed the writing in some places


- **For developers/enthusiasts:**
    - **Massive code refactoring for easier integrations (although a bit unfinished)**
    - **Added a lot of comments (also for old code)**
    - Removed old useless code

**Versions:**
- _v1.4_
- _v1.4 TestChamber_
- _v1.4.1_
- _v1.4.1 TestChamber_
- _v1.4.2 beta_


## **Gen 5**
_*Work in progress,_ est. finish date - end of april 2025



# **Expected features (Not exclusively for Gen 5):**
- **Implemented from this list:**
    + (+)  Settings menu ----------------------------------------------------------------- Implemented in v1.4
    + (+)  Other ciphers to chose from in settings (?) ----------------------------------- Implemented in v1.4
    + (+)  Fast base encryption/decryption options (simplified version of the UI) ----- Implemented in v1.4.1
    + (+)  Fast input system (v1.4.2 beta exclusive feature) ----------------------------- Implemented in v1.4.2 beta
      
**Currently in development:**
- Randomly generating codes & cipher parameters
- English UI
- Advanced settings menu
- Hashing for encryption/decryption option
- File encryption/decryption
- Custom cipher options
- Multi-layer encryption/decryption
- Persistent settings
- Better installation guide (after persistent settings)

**"(+)": Currently already implemented in the latest version (v1.4.2 beta)**






## **Not defined future plans:**

- Add multiple encryption/decryption at the same time
- Integrate other ciphers in the program (not RE algorithms)
- Add optional parameter bruteforcing using a bit of known information
- Add graphical interface 
- Enable creating of encryption/decryption .txt files

