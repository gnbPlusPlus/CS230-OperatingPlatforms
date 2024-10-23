Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
-- 

The Gaming room is a fictional company that wanted to expand their Android-based web game, Draw It or Lose It, to more desktop and mobile operating systems (i.e., Mac, Windows, Linux, iOS). Their web-based game needed to function well on both mobile and desktop devices, fulfill technical requirements like rendering high-definition images speedily, and check for players' unique names, to name some of the requirements.

What did you do particularly well in developing this documentation?
--

I gave strong recommendations that weaved together the logic of using Linux plus a cloud-based platform like AWS. I had to do extra research for that part (part three), but that means I got to learn more! Using containerized microservices (dockers and kubernetes) in a cloud-based setup made the most sense to me, given how the game is based on a library of large, HD images. I was happy to receive positive feedback praising my work for this part, because it confirmed that I wasn't totally off track! As a beginner, it's often hard to know if I'm thinking in the right direction or accidentally cutting corners.

What about the process of working through a design document did you find helpful when developing the code?
--

It helped me modularize the code, meaning I could break it up into logical chunks based on function. The UML diagram was especially helpful for this because it documented every variable and function needed to make the game work as intended (at least for the scope of this project). I could clearly see the singleton and iterator pieces that I had to fill in-- functions like getInstance() and addGame() cued me in to adding an iterator element in GameService.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
--

Definitely the Evaluation section (part two)! That was the piece I got the lowest score on. I struggled with my research, and it took many attempts to get relevant information through DuckDuckGo searches. I did my best to make the information substantial enough, but it was still lacking, and I should've reached out for help instead of "roughing it". So, if I had a do-over, I would've started part two sooner and asked my professor (a.k.a. you!) for guidance on the specifics. I might've missed relevant information in one of the 'Resources' sections in the modules that would've been enlightening. Basically, I would seek help finding more relevant information so that I could fill out each section with more detailed, comprehensive answers. There's a lot of overlap between what I wrote, but I'm sure there were more specifics that I just missed. If I'd figured out what docker and kubernetes were when I did part two (as opposed to discovering them in part three), those would've been great additions for the Development Tools section under Linux.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
-- 

I found myself running off with my focus at times, since I'm a beginner. My scope was too broad because I was afraid of missing things. Once I remembered to narrow my thinking to the client, my work started to make more sense. I considered the hefty storage and rendering needed for the image processing-- that influenced my recommendation for a cloud-based platform. Knowing that only one game instance could exist in memory at a time was a crucial requirement that I emphasized repeatedly because it was important to the client.
Considering the user separately from the client then shifted my focus to development and what it would take, given the client's wishes. The user experience made me realize that the images would need to gradually reveal themselves at the speed of the round (30 or 15 seconds) exactly, or the gameplay would be unbalanced. Cloud-based storage and image retrieval seemed like the best option to ensure smooth gameplay.
It's so important to consider the user's needs when designing because they are who the product is for. The client wanted to expand their user base, but a low-quality game would not fulfill this desire. Positive user experience is critical for retention and client satisfaction. If the user's needs aren't fulfilled (i.e., if the images didn't load properly during a round), then neither are the client's-- the two are intrinsically linked.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
-- 

I approached designing this software in pieces, as aided by how the course broke it up into parts 1, 2, and 3. This made the work a lot more manageable, so I'll be using this same strategy again (just like modularizing code). I've learned in this design to narrow my focus to my client's needs and the user's experience, and constantly keeping these things in mind will help guide me toward completing concise plans.
