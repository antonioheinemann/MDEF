---
hide:
    - toc
---
#
## Tech Beyond the Myth

"Select an object to tear apart."

A genuinly exciting way to start a course on hardware and electronics. Having little previous experience or knowledge on the subject, I came to understand concepts and information that truly blew my mind and opened a door to a whole new world. Technology stops being a black box, and comfort arises exploring how products work and what their true purpose really is. We learned the basic principles of electronics and coding by breaking an already broken electronic device. We also learned the theory behind translating physics to information, why we use binary and how computers think.

Our team chose to tear down a broken all-in-one (combination fax, printer, scanner, copier) inkjet printer.

<img src="https://antonioheinemann.github.io/MDEF/images/printerok.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/Whats-App-Image-2022-11-09-at-1-40-11-PM.jpg" width="500" />

We got together and began to understand how the device worked through reverse engineering of its models, components, and systems. As we disassembled, we learned and explored first hand the content on electronics and hardware and could actually visualize how things interacted with each other. We had to understand each of the pieces and how their functions complement each other in the execution of printing, scanning, or fax. Moreover, we explored possibilities as to why the device stopped working or where things could have gone wrong. Perhaps the most interesting aspect was the conversation around the true intentions behind the design of the printer. That is, which parts were easier or difficult to dissasemble (is there something to hide?), or what insights around unusual behavior can unfold?

<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum4.jpg" width="350" />


**See the complete forensics report**
https://hackmd.io/@8sCwEDXZRLu279SP363xRQ/SkVrxUbHj


<img src="https://antonioheinemann.github.io/MDEF/images/inksys.png" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/pump.jpg" width="500" />


_Ink pump ~ how much are you really pumping?_

Next in line was creating a new device from the useful pieces that remained after disassembling the printer. We identified components or working systems that could be valuable, and then brainstormed a number of possibilities for our creation.

Although the number of components we could use was surprisingly high, we quickly realized that reconfiguring some of the components would be too difficult and decided to keep it simple. We decided to use the power motors and sensors to create device that knocks doors. That is, when a sensor detects that the door is closed, it will begin to knock. When the sensor detects that the door is open, the device will stop working. The idea behind the concept is humurous and intended to be a pranking device. In a more advanced prototype, this device could be used by kids when running around the block knocking on the neighbourhood doors.

<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum4.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum2.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum1.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum3.jpg" width="500" />


 Building the device was really fun. We programmed in arduino, assembled a breadbord and configured the entire system together. The logic was simple ~ sensor:on > knock door. sensor:off > stop knocking. Not only the electronics and programming aspect was entertaining, but also we created an actual door. Cutting wood and building things from nothing is truly a pleasure. I come to think that instead of building a device that knocks doors, we actually built a door that never stops knocking.

<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/MT01/aum5.jpg" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/door.png" width="500" />


<img src="https://antonioheinemann.github.io/MDEF/images/closingdoor.gif" />


<iframe width="560" height="315" src="https://www.youtube.com/embed/1F_JKIxENr4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
