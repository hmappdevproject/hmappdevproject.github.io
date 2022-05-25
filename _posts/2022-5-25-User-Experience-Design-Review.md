# The Conveniences of Horace Mann are One Tap Away


## The Team

Sawyer Scheiner, Coder; Zachary Ludwig, Writer; Sari Sladkus, Designer.

Though these were our titles, everyone pitched in and helped out where they could. We were all researchers as well.
Problem Definition and Proposed Solution Overview

At Horace Mann, it can be really hard to squeeze everyday tasks into our day while we are rushing between buildings and classes, such as printing out assignments or keeping your phone charged. Further, it can even be hard to find these aspects essential to a student's life. After a rigorous design process, we settled on a solution that helps students quickly access these conveniences at the tap of a finger: an interactive map, displaying where HM’s printers and phone chargers are located.

## Contextual Inquiry Results & Key Tasks

For our contextual inquiries, we used both an “observe and then ask” method and traditional interviews with our participants. In our “observe and ask” method, we would first ask a participant to meet and set a time and location, with the intent of getting there early. That allowed us to observe the subject in an environment of our choice, seeing their natural responses to issues of convenience. After we observe until the designated time, we would then have a conversation and ask questions relating to the topic of convenience, going deeper when we found a potential problem area that we may want to design for. Overall, this went very well, with the interviews after the observations still feeling natural and not forced, and besides alternating between the two methods, we did not change our processes much throughout the inquiries.

We decided to go though this inquiry process for three participants, capturing a diverse subset of HM students. The first participant, Hiesenberg, is a Junior who takes a very rigorous course load. We believed this would give us insight into how convenience impacted the allocation of his time. The second participant, Bob, is a Freshman at HM. We chose this participant since we believed that, in contrast to Heisenberg, they would give a response and demonstrate problems with conviction as it pertains to more social rather than academic issues. The third participant, Patrick Star, is a member of the HM faculty. We chose to interview this participant because of their experience with inconvenience due to the location of their office and classrooms, in the basement of Tillinghast. 

Some of the large themes we found included eating, stress, and location. For the first, many of our respondents spoke to how eating, whether during break or in the cafeteria, was difficult for a variety of reasons. The second theme, stress, was talked about in relation to convenience mostly by older students. With heavy workloads, anything inconvenient is hard to do in the limited amount of free time a student has, causing a certain stress in our participants. Finally, location was mentioned by all of our subjects. The field closure during the winter was very problematic given the small amount of passing time we get, and overall large distances made things like printing hard for students and getting to lunch inconvenient for teachers in specific locations. However, for faculty that spend most of their time in one location, the impact is not as large, and being far from lunch may mean being close to the subway. 

Some of these themes, but not all, led to the central tasks our design has been built to accomplish. While we came up with more, surrounding all the themes, we decided on two tasks: charging phones and printing documents. For the former, if you don’t know where they are, the chargers are not that common or obvious. Your phone running out of battery would make everything harder and more stressful, so making chargers accessible was key to preventing those catastrophes. For the latter, teachers often ask students to print materials before class, and not everyone has a printer at home. Since the library can be far away from certain places, it is important to help students find the closest printer to them.

## Paper Prototype

The design we went with, which you can see our plans for above, is a piece of software we will call the “HM Convenience Map.” On the software, users (students or teachers) will be able to first select what they are looking for, be it chargers or printers. From that point, the software will show the user the locations for these conveniences all across the school, stating the buildings, floors, and specific locations they can be found in. Once the user chooses a location, we also show a picture of the location, an aspect not included in our paper prototype. We hope the visual way of finding these conveniences will be better than the spoken advice or plain searching that place in the status quo. 

This design affords the two key tasks we decided to accomplish with our design, printing documents and charging phones. Starting with printing documents, by displaying where printers are in the school, students no longer only have to print in the library. They can print from locations closer to them, decreasing travel time and also the number of people trying to print from the library at once. As for our second task, showing where phone chargers are also helps students find a phone charger close to them that is available. Once people know where chargers are and have help to find them, they can easily leave their phones in a location close to their next class, picking it up after. In general, this design is very useful for students newer to the school, helping them get oriented within HM’s large campus.

## Usability Testing Process & Results

For our usability testing, we did not have users use our basic paper prototype. Instead, they used the digital mockup of the software that we made with Figma, that you can explore below.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2F0sDymTKhM6aTb8PMz2g6EJ%2FMap%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

During those tests, we selected three different participants. Our participants were all Horace Mann students, one Junior in our class who was aware of our project and the process, one Junior who was not in the class and was not aware of the process we were doing, and one Freshman new to the school who did not know about our project and was not as familiar with the school as a Junior. The reason we chose these people, especially the freshman, is that he would give us the most useful observations as someone who might actually need to use our prototype to find a printer or charger. We instructed these students to use our prototype to navigate to various chargers and printers around the school, and then took notes on their actions and comments.

Throughout our three usability tests, we had a few takeaways: first, we discovered that the flow of our design worked very well among all of our participants. Second, the only discrepancies that occurred throughout these tests were ones based on poor wording, vocabulary, or caused by the medium-fidelity nature of our prototype. 

## Digital Mockup & Testing Results

Using our usability testing data, we made two revisions: first, since one of our participants was confused at the place-holder images we had in our prototype, we replaced them with real images of the locations: Second, since our participant was confused by the wording of the library charger location page in two of the tests, we realized that vocabulary such as “rotunda,” is not very common and may be confusing. We thus revised this issue by going over the vocabulary in our descriptions and made it more simple.

We also made two more changes as a result of our accessibility discussion: we first made brighter buttons, and we then added verbal instructions on what to click for those less experienced with technology.

## Discussion & Implementation Plan

To summarize our extensive research, we found that convincing at Horace Mann was a big enough problem to solve, and that helping students quickly find the locations of chargers and printers is a big step in finding that. After we developed a prototype “HM Convenience Map,” we tested the design with students around the school and found that it did, in fact, help them efficiently find the nearest chargers and printers. We thus decided to move forward with developing a beta version of our design as a way to publish our results to the community.

We chose HTML5 and CSS to implement our prototype because it is a simple website building platform that we can use to customize elements, create links, and organize our information. We researched many different tech stacks we could have used, and we considered others such as React or Vanilla JS. The reason we decided on HTML5 and CSS over these options is because it is very easy to write and the code is easy to follow, meaning our teammates who are less experienced with code can understand.

To implement a working web-based version of our Figma prototype as a beta version, we decided that a simple HTML and CSS interface using links would be sufficient, as the functionality of our prototype is fairly simple and simple links and buttons can be created. To begin, we researched ways to turn our figma designs into functional HTML, as manually writing and copying each element on every one of our pages would be extremely arduous and inefficient. We settled on using a free Figma plugin that converts a given page in Figma to HTML and CSS code, but this does not implement the links and functionality of our design. We began working on this, but we were so far not able to finish and have run into a couple formatting errors. With the method we have at the moment, the work we have left is continuing to export our pages, adding links and fixing formatting when needed.

Finally, on to some more general takeaways from the process of iterative design and future plans we can implement if we wish to further develop this design. The largest takeaway about iterative design itself is the importance of constant improvement. Rather than taking big leaps once in a while, seeing our project develop over the course of the year kept up our motivation since we knew that every small step was working to a larger goal that kept coming closer. Another takeaway on iterative design is how we were able to get feedback at every step, meaning that problems were stopped before they became too large and we always had a sense of how certain design aspects would be perceived.

If we were to fully implement this project to the public, we would need to either find a new way to efficiently convert our prototype to a site, or just continue working and polish the errors. In addition, it may be beneficial to obtain a domain name for our project, one that is memorable for users and descriptive of our product. As a group, we may also consider moving our design from a website to an application, so that one does not always need the internet to access it, and so that it can be viewed from one click on a smartphone.

## Appendix

Team Contract and Group Project Proposal
Contextual Inquiry Check-In
Contextual Inquiry Review
Task Analysis
Design Check-In
Usability Testing Lab
