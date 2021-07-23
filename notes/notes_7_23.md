# Notes 7/23

## Exam Facts

- 90min
- 70-90 questions
  - Simulation + multiple choice :(3 - 5 simulation questions)

---

## CIA Triad

1. Confidentiality
    - Information has not been disclosed to unauthorized people.
    - __Example:__ Encryption
2. Integrity
    - Information has not been modified or altered, except for when
      done by authorized parties.
    - Foreshadowing of hashes.
3. Availability
    - Information is able to be stored, accessed, or protected at all
      times.

---

## AAA of Security

1. Authentication(AuthN)
    - Person's identity is provided _with_ proof, and confirmed by the
      system.
    - __Example:__ Logging in to a system.
    - __5 Methods of AuthN:__
      1. Something you know
          - Password, username, etc.
      2. Something you are
          - Biometrics
      3. Something you have
          - Token, OTP, License, etc.
      4. Something you do
          - Speech pattern, signature, etc.
      5. Somewhere you are
          - Geographical location, IP, etc.

2. Authorization(AuthZ)
    - When a user is given access to a specific piece of data, or
      certain areas of a building.
3. Accounting(uhhh...)
    - Tracking of data/network usage and access.

---

## Security Threats

1. Malware
    - Malicious software.
      - Virus
      - Worm
      - Spyware
      - Trojan Horse
      - Root Kits
      - AdWare
      - RansomWare
2. Unauthorized Access
    - Access of data w/o consent and/or knowledge of authorized parties.
3. System Failure
    - When a computer or application crashes
    - Blue screen of death!
4. Social Engineering
    - Act of manipulating users into fucking themselves.
    - Facebook quizzes.
    - Phishing.

---

## Mitigating Threats

1. Physical Controls
    - Alarms, locks, id pads, security guards, __bionic sabre tooth tigers__.
2. Technical Controls
    - Smart cards, encryption, access control lists, instrusion detection systems,
      network authN.
3. Administrative Controls
    - Policies, procedures, training, contingency plans, disaster recovery
    - User training is the most cost effective security control.
    - Administrative = Managerial

---

## Hackers

1. White Hat
    - Non-malicious hackers who attempt to break into a company's
      systems at their request.
    - Ethical Hackers/Penetration Testers ... ;)
2. Black Hat
    - Malicious hackers who break into computer systems and networks
      without authorization or permission.
3. Grey Hat
    - Hackers w/o any affiliation to a company that attempt to break into a
      company's network but risks the law in doing so.
4. Blue Hat
    - Hackers who attempt to hack into a network with permission of the company
      but are not employed by the company.
5. Elite
    - Hackers who find and exploit vulnerabilities before anyone else does.
    - 1 in 10k

__Honorable Mention:__

- Script Kiddie: limited skill. Only use other people's tools.

---

## Threat Actors

1. Script Kiddie
    - N00bs
2. Hacktivists
    - Hackers who are driven by a cause like social change, political agendas,
      or terrorism.
    - Anonymous.
3. Organized Crime
    - Hackers who are part of a crime group that is well-funded and highly
      sophisticated.
4. Advanced Persistent Threats
    - Highly trained and funded groups of hackers (often by nation states) with
      covert and open-source intelligence at their disposal.

---

## Threat Intelligence and Sources

1. Timeliness
    - Property of an intelligence source that ensures it is up-to-date.
2. Relevancy
    - Property of an intelligence source that ensures it matches the use case intended for it.
3. Accuracy
    - Property of an intelligence source that ensures it produces effective results.
4. Confidence Level
    - Property of an intelligence source that ensures it produces qualified statements
    about reliability.

- Admiralty Scale: Scale by which intelligence sources are rated based on content and reliability.

### Open Source Sources of Intelligence

- US-Cert
- UK's NCSC
- AT&T Security (OTX)
- MISP
- VirusTotal
- Spamhaus
- SANS ISC Suspicious Domains

---

## Threat Hunting

- __Threat Hunting__
  - A CyberSecurity technique designed to detect presence of threats that have not been
    discovered by normal security monitoring.
  - Proactive instead of reactive.
  - Potentially less disruptive.
  - Analyze data within system.
  - Consumes lots of time and resources.

__Steps:__

  1. Establish a Hypothesis
    - Think of why someone would want to take action against you.
  2. Profile threat actors and activities
    - Think of the who and how.
  3. Threat hunt
    - Assume existing rules have failed. 

---

## Attack Frameworks

1. Lockheed Martin Kill Chain
    - Model that describes the stages by which a threat actor progresses a network intrusion.
    - Lil bit old.
    - 7 step program:
      1. Recon
          - Attacker determines what methods needed to complete subsequent phases
      2. Weaponization
          - Attacker couples payload code that will enable access with exploit code that will
            use a vulnerability to execute on the target system.
      3. Delivery
          - Attacker identifies a vector by which to transmit the weaponized code to the
            target environment.
      4. Exploitation
          - Weaponized code is executed on the target system.
      5. Installation
          - Mechanism enables the weaponized code to run a remote access tool and achieve
            persistence on target system.
      6. C2
          - Weaponized code establishes an outbound channel to a remote server that can
            then be used to control the remote access tool and possibly download additional
            tool to progress the attack.
      7. Actions on Objectives
          - Attacker typically uses the access achieve to covertly collect info
            from the target systems and transfer it to the remote system.
    - __Kill Chain Analysis__
      - Observing each stage to come up with a counter for each one.
2. MITRE ATT&CK Framework
    - A Knowledge base maintained by the MITRE Corporation for listing and explaining specific
      adversary tactics, techniques, and common knowledge or procedures. (attack.mitre.org)
3. Diamond Model of Intrusion Analysis
    - A framework for analyzing cybersecurity incidents and intrusions by exploring the
      relationships between four core features: adversary, capability, infra, and victim.

---

## Terms

- __Information Security__
  - Act of protecting data and information from unauthorized access, unlawful
    modification and disruption, disclosure, corruption, and destruction.
- __Information Systems Security__
  - Act of protecting the systems that hold and process our critical data.
- __Non Repudiation__
  - Having proof that someone has taken an action
- __Open-Source Intelligence (OSINT)__
  - Methods of obtaining information about a person or organization through
    public records, websites, and social media.
- __Threat Hunting__
  - A CyberSecurity technique designed to detect presence of threats that have not been
    discovered by normal security monitoring.
- __SIEM__
  - Security Information and Event Management System
- __Kill Chain Analysis__
  - Observing each stage to come up with a counter for each one.
