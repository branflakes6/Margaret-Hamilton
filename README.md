# Margaret-Hamilton
### Introduction 
Margaret Hamilton is a Computer Scientist and a pioneer of Software Engineering who made major contributions to the Apollo 11 program and helped establish the field of Software Engineering. 
Her most notable achievements came at the MIT Draper Laboratory where she led the Command Module team and was responsible for critical pieces of software that landed a man on the moon. 

### Education
Hamilton was born on the 17th of August 1936 in Paoli, Indiana. She earned a degree in mathematics from Earlham College in 1958 and had intended to peruse a graduate degree in abstract mathematics with the intention of becoming a professor of mathematics. 
During the summer of 1959 Hamilton got a job in the meteorology department of MIT writing software to predict weather. It was here that she developed her passion for software engineering and made the decision to pursue it professionally instead of her desired graduate degree. During this time computer science was an emerging field and was not offered at major universities, instead developers learned their skills through hands on experience. 

### Sage
Hamilton’s first major project at MIT was the Semi-Automatic Ground Environment (SAGE) which was initially developed to predict weather but was adapted by the US Military as an anti-aircraft defence system against a protentional Soviet attack. Here she was developing on the system at the Lincoln Labs the first system in the world to have real-time computers. Due to the nature of this project Hamilton began thinking about the reliability of software and ways to improve it, a failure of her code could lead to a potential global disaster. This was the beginning of a lifelong interest in creating reliable software


>*“SAGE was one of the first jumping off points where I became interested in the subject of software reliability.  When the computer crashed during the execution of your program, >there was no hiding. Lights would be flashing, bells would be ringing and everyone, the developers and computer operators, would come running to find out whose program was >doing something bad to the system.”*
>-**Margaret Hamilton**


Hamilton’s success on the SAGE project allowed her to gain recognition within MIT and led to her being chosen to join the Draper Laboratory at MIT which was working on the Apollo mission.

### Draper Laboratory 
Initially hired as a programmer Hamilton quickly moved into system design and began rising up the ranks until she found herself in charge of all Command Module software at the Draper Laboratory. She was now in charge of over 100 Engineers and Mathematicians developing software for the Apollo program and Skylab. Her team was responsible for developing the in-flight software as well as the systems software that would do error detection and recovery. 
It was here that Hamilton began to develop many new ideas and technologies such a Priority Displays, asynchronous software, priority scheduling and software reuse.  As well as continuing to develop her ideas of reliable software and error handling.
During preparation for the Apollo 8 launch Margaret’s daughter Lauren was playing around with a command module simulator and accidentally triggered an error causing a crash by trying to launch a prelaunch program mid-flight. Hamilton’s obsession with being prepared for all possible errors led to her wanting to add a fix for this crash but she was overruled by NASA as they believed no astronaut would make this mistake. 


>*“We had been told many times that astronauts would not make any mistakes, they were trained to be perfect.”* – **Hamilton**

However, five days into the Apollo 8 mission astronaut Jim Lovell did just that, accidentally launching the same prefight program mid flight causing the computer to crash and lose all navigation data. This could have been potentially disastrous as it left the ship stranded with no way home but fortunately Hamilton and her team were able to come up with a fix within 9 hours. This incident gave huge credibility to the ideas that Hamilton had been preaching about reliable software and designing for all possible errors. 

### Apollo 11

Hamilton’s work for NASA on the Apollo 11 project laid the foundation for a lot of modern software engineering practices used today. Hamilton realised that a project of this importance with such high stakes and the possibility of the loss of human life required much more rigorous and well-defined practices than what existed at the time. The most important of which was testing, the possibility of error in such a complex project was extremely high and needed to be reduced to zero, lessons had been learned from Apollo 8 and Hamilton was insistent that all possible errors should be handled this time. 
The code written by Hamilton and her team had to be flawless, it could not contain a single bug or have even the slightest possibility of failure. In order to achieve this she established hard requirements on the engineering of all components and subsystems to eliminate interface errors with the flight software at the system level, the debugging and testing of all components and full simulation of all possible situations that could occur at the system level. Hamilton insisted every line of code worked the first time as “There was no second chance”. This had to be done on all 40,000 lines of LEM code and as a result not a single bug has ever been found in the code written by her and the team.
This obsession with identifying and dealing with every possible error proved critical during the landing sequence of Apollo 11
Three minutes before the landing of Apollo 11 several computer alarms went off and interrupted the astronauts with Hamilton’s new Priority Displays. The issue was that due to a fault in the operations script provided to the astronauts a rendezvous switch had been left on and the computer was now overloaded with tasks. Fortunately, Hamilton had prepared for this and the computer could detect that it was being asked to perform more tasks than it was capable off. The software set off alarms to alert the astronauts of this problem and then began to eliminate lower priority tasks and focus on its most important task of landing the ship. If it wasn’t for this error detection and correction system, it is very likely the overloaded computer would have crashed and ended in disaster.
The entire Apollo 11 software was written on punch cards with only 72 kilobytes of memory, yet not a single bug occurred at any stage during the mission and the software even managed to correct errors made by the astronauts to avoid failure. It is extremely unlikely that any of this would have been possible without Margaret Hamilton’s meticulous focus on reliable software.

### Other Endeavours 

After her work at MIT and NASA Hamilton went on to found two software engineering companies, Higher Order Software (HOS) and Hamilton Technologies. At HOS she further developed her idea of error detection and prevention, developing methodology that would be implemented by various government projects. 

### Impact on Software Engineering

Hamilton is one of the most important pioneers of software engineering, her contributions to the field when it was in its infancy helped pave the way for many of the practices still used today. Apollo 11 helped legitimise the industry and was the first time that “real engineers” and scientists began to see the value and skill behind it. 
Hamilton started the conversation of reliable software and error free code, creating many of the techniques used to identify and fix it. She realised that if you want to write bug free code you must start with a rigid set of rules that your whole team follows and you must test every component as you go before you deploy any of it. 
She developed many of the foundations of ultra-reliable software design such as of asynchronous software, priority scheduling, software reuse, and man-in-the-loop decision capability such as priority displays. 
Hamilton is also credited with coining the term “Software Engineering” to define programming as a legitimate science and a branch of engineering. While we may take the term for granted nowadays there is no doubt that having a name like this was extremely important in the early days of the field, it gave outsiders some insight in to the kind of work that was being done and helped cement software as a powerful and complex tool.
Without Hamilton it is very possible that Apollo 11 would have crashed during landing, a disaster that would have not only been a great tragedy and setback for humanity but could have also done incredible damage to the idea of software engineering. If Apollo 11 crashed killing all aboard due to a computer failure it would have cast a shadow over the entire field, the public would have developed a distrust of computing and it would have provided a platform for those inside the scientific community who deemed it a hobby rather than a science. 

### Sources 

The NASA Heritage of Creativity 2003 Annual Report of the NASA Inventions & Contributions Board
https://www.nasa.gov/pdf/251093main_The_NASA_Heritage_Of_Creativity.pdf

Technical Innovation in American History
https://books.google.ie/books?id=aWGHDwAAQBAJ&pg=RA2-PA62&redir_esc=y#v=onepage&q&f=false

“Her Code Got Humans on the Moon—And Invented Software Itself” – Wired.com 
https://www.wired.com/2015/10/margaret-hamilton-nasa-apollo/

“Margaret Hamilton Led the NASA Software Team That Landed Astronauts on the Moon” – smithsonianmag.com
https://www.smithsonianmag.com/smithsonian-institution/margaret-hamilton-led-nasa-software-team-landed-astronauts-moon-180971575/

American Women of Science 1900 – Tiffany K Wayne
https://books.google.ie/books?id=gPGZJ_YuMwgC&pg=PA480&redir_esc=y#v=onepage&q&f=false

“2017 CHM Fellow Margaret Hamilton” computerhistory.org
https://computerhistory.org/blog/2017-chm-fellow-margaret-hamilton/?key=2017-chm-fellow-margaret-hamilton




