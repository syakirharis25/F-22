# F-22
Case studies of Lockheed Martin F-22 Raptor,  all-weather stealth tactical fighter aircraft developed for the United States Air Force (USAF).

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Software development.](#software)
4. [GitHub notes.](#github)
5. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="f-22 pride.jpeg" height="200"> 
The F-22 Raptor defines air dominance. The 5th Generation F-22’s unique combination of stealth, speed, agility, and situational awareness, combined with lethal long-range air-to-air and air-to-ground weaponry, makes it the best air dominance fighter in the world.
<br /><br />
The Lockheed Martin F-22 Raptor is a single-seat, twin-engine, all-weather stealth tactical fighter aircraft developed for the United States Air Force (USAF). The result of the USAF's Advanced Tactical Fighter (ATF) program, the aircraft was designed primarily as an air superiority fighter, but also has ground attack, electronic warfare, and signal intelligence capabilities. The prime contractor, Lockheed Martin, built most of the F-22's airframe and weapons systems and conducted final assembly, while Boeing provided the wings, aircraft fuselage, avionics integration, and training systems.
<br /><br />
The aircraft was variously designated F-22 and F/A-22 before it formally entered service in December 2005 as the F-22A. Despite its protracted development and various operational issues, USAF officials consider the F-22 a critical component of the service's tactical air power. Its combination of stealth, aerodynamic performance, and situational awareness enable unprecedented air combat capabilities

<a name="references"></a>
## 2. Official references websites. <br />
Official Lockheed Martin website : https://www.lockheedmartin.com <br />
Official Lockheed Martin Lockheed Martin F-22 Raptor website : https://www.lockheedmartin.com/en-us/products/f-22.html <br />

<a name="software"></a>
## 3. Software development.
The software that provides the avionics system's full functionality is composed of approximately 1.7 million lines of code. Ninety percent of the software is written in Ada, the Department of Defense's common computer language. Exceptions to the Ada requirement are granted only for special processing or maintenance requirements. The software development plan, though stretched as a result of past funding constraints, has remained essentially unchanged since the start of Engineering and Manufacturing Development.

The avionics software was integrated in three blocks, each building on the capability of the previous block. Each block cycle is a sequence of subsystem deliveries, integration testing at the Avionics Integration Lab (AIL) at Boeing (see AIL in the Test Facilities section), and then delivery to Lockheed Martin in Marietta, Ga., for final integration into the aircraft and check out, as well as support to the aircraft.

Block 1 is primarily radar capability, but Block 1 does contain more than 50 percent of the avionics suite's full functionality source lines of code (SLOC) and provides end-to-end capability for the sensor-to-pilot data flow. The fourth EMD F-22 was the first to have a full avionics suite, and it flew in mid 1999.

Block 2 is the start of sensor fusion. It adds radio frequency coordination, reconfiguration, and some electronic warfare functions. Block 2 was integrated into the aircraft in late 1999.

Block 3 encompasses full sensor fusion built on enhanced electronic warfare and CNI functions. It has an embedded training capability and provides for electronic counter-counter measures (ECCM). It was integrated into the aircraft in the spring of 2000. Block 3.1, which adds full GBU-32 Joint Direct Attack Munition (JDAM) launch capability and Joint Tactical Information Distribution System (JTIDS) receive-only capability, was integrated in April 2000.

The Block 4 software was post-Engineering and Manufacturing Development. It was integrated on the Initial Operational Capability F-22s and included helmet-mounted cueing, AIM-9X integration, and Joint Tactical Information Distribution System send capability.

CIP hardware was available well before the subsystem application software code and unit test phases began for the Block 1 software. For some of the higher risk software, such as sensor data fusion, specific algorithm testbeds have been constructed, and prototype software, which is instrumented to measure performance (correlation times, accuracy, etc.). has been operational since the start of EMD.

<a name="github"></a>
## 4. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/F-22.git
$ cd F-22/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 5. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1             13              0             45
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc

adding GitHub repository calculation
