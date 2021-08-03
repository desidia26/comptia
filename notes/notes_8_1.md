# Notes 8/1

---

## Malware

- Bad software mkay

---

## Viruses

- Malicious code that runs on a machine without the user's knowledge and
  infects the computer when executed.
- Viruses require user action
- Types of Viruses
  1. Boot Sector
    - Stored int he first sector of a hard drive and are loaded into memory upon boot up
    - Nice because typical antivirus won't find them, as they are not stored in the traditional
      area considered a file system
    - Usually spread by hardware
  2. Macro
    - Virus embedded into a document and is executed when the document is opened by the user.
  3. Program
    - Targets executable and parasites onto those to run alongside
  4. Multipartite
    - Virus that combines boot and program viruses to the boot sector and system files
      before attacking other files on the computer.
    - Able to place self in boot, and spread to rest of computer. What a bitch.
  6. Polymorphic
    - Encrypted virus that changes its encryption up every now and then to evade detection
  7. Metamorphic
    - Changes *itself* completely, functionality and all.
  8. Stealth
    - Any virus that avoids detection through the above means
  9. Armored
    - Have a layer of protection to confuse a program or person analyzing it.
  10. Hoax
    - Not really a virus
    - Trick user into infecting their own machine.
---

## Worms

- Just like a virus, but it can replicate itself w/o user interaction.
- Self replicate and spread throughout network.
- Notorious for slowing down systems.
- 2001 NIMDA. Made it across entire internet
- 2009 Conficker. 9-15million machines

---

## Trojans

- Greeks m'dude.
- Perform desired AND malicious function
- RAT. Remote access trojan. Hella popular

---

## Ransomware

- Malware that restricts access to a victims computer until a ransom is received

---

## Spyware

- Malware that secretly gathers information about the user without their consent.

---

## Rootkits

- Specific type of software designed to be given admin over the target machine.
- __DLL Injection__
- __Shim__
- __Driver Manipulation__

---
## Spam



---

## Terms

- __Grayware:__ Software that isn't benign nor malicious, and tends to behave
  improperly without serious consequences.
- __DLL Injection:__ Malicious code is inserted into a running process on a
  Windows machine by takin advantage of Dynamic Link Libraries that are loaded
  at runtime.
- __Shim__:__ software placed between two components to intercept calls
  and redirect them.