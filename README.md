# CS 230 Portfolio

## Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was The Gaming Room, and they wanted to expand their game, Draw It or Lose It, from an Android application to a game that could work on multiple platforms. The goal was to create a web-based application that users could access from computers and mobile devices. The software also needed to support multiple games, teams, and players while making sure names and IDs stayed unique. The system needed to be secure, scalable, and able to keep the game state and timers consistent for every player.

## What did you do particularly well in developing this documentation?

I think I did particularly well at comparing the different operating platforms and explaining why Linux would be the best choice for the server. I looked at Mac, Linux, Windows, and mobile devices and considered the strengths and weaknesses of each one. I also connected my recommendations back to the needs of The Gaming Room instead of only describing the technology. This helped make the document easier to understand and gave a clear reason for the choices I made.

## What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand how the different parts of the software needed to work together before writing the code. The UML diagram was especially helpful because it showed the relationships between GameService, Game, Team, Player, and Entity. It also helped me see where inheritance, encapsulation, and the singleton pattern would be used. Planning these parts first made the code easier to organize because I already had an idea of what each class was responsible for.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of the document, I would improve the system architecture section. I would add a more detailed diagram showing how the browser clients, Linux server, database, and storage system communicate with each other. I think this would make the distributed system easier to understand and would give a development team a better view of how the complete application would be deployed.

## How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I interpreted the user's needs by looking at what The Gaming Room wanted the game to do and then choosing software designs that supported those requirements. Since they wanted the game to work on different operating systems, I recommended a web-based client so users could connect through a browser instead of needing a separate application for every platform. I also used a singleton GameService and checks for duplicate names to help meet the requirements for managing games, teams, and players.

It is important to consider the user's needs because the software is being created for them. A system can be technically successful but still fail if it does not solve the client's actual problem. Keeping the user's needs in mind helps developers make better decisions about the design, security, performance, and features of the application.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the software design by first identifying the client's requirements and then breaking the system into smaller parts. I used object-oriented design, UML diagrams, software design patterns, and platform comparisons to decide how the application should be organized. I also considered areas such as storage, memory management, networking, security, and scalability before making my final recommendations.

In the future, I would use a similar process by starting with the requirements before making decisions about specific technologies. I would create diagrams early, compare multiple possible solutions, and think about how the application may need to grow in the future. I would also continue considering security and user needs throughout the design process instead of waiting until the end.
