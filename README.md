# CS230-Operating-Platforms
The Gaming Room
# CS 230 Operating Platforms

## The Gaming Room

The Gaming Room was the client for this project. They had an existing Android game called *Draw It or Lose It* and wanted to expand it into a web-based application that could support users across multiple operating platforms. The software needed to support multiple games, teams, and players while ensuring that game and team names remained unique. The design also needed to account for scalability, security, storage, memory management, and communication between the clients and server.

### What did you do particularly well in developing this documentation?

I think I did particularly well at comparing the different operating platforms and connecting their advantages and disadvantages back to what The Gaming Room actually needed. Instead of just describing Windows, macOS, and Linux, I considered things like cost, scalability, development tools, security, and how each platform would work in a distributed environment. This helped me make a recommendation based on the actual requirements of the application rather than simply choosing the operating system I was most familiar with.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand why certain decisions needed to be made before beginning development. Breaking the application down into requirements, constraints, the domain model, platform evaluations, and recommendations made the overall project easier to understand. It also helped me connect concepts like the Singleton and Iterator design patterns to actual client requirements. I could see how planning the structure of an application first can prevent unnecessary changes later in development.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part, I would improve my original recommendations. Earlier in the course, I understood the general differences between operating systems, but I did not have as much knowledge about memory management, storage, distributed systems, networking, and security. After completing the later modules, I was able to make a much more detailed recommendation and explain why Linux would be a strong server platform for this application. In the future, I would consider these areas earlier in the design process.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I interpreted the user's needs by taking each requirement and determining what it meant from a technical perspective. For example, supporting users across different operating systems led to a web-based client-server design rather than creating a completely separate application for every platform. Requirements for unique games, teams, and players also influenced the class design and use of unique identifiers. Considering the user's needs is important because software can technically function correctly and still fail if it does not solve the problem the client or users actually have. The requirements should guide the design instead of forcing users to adapt to whatever is easiest to develop.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to start with the client's requirements and then break the problem into smaller areas such as application structure, platform compatibility, storage, memory, networking, and security. I also used object-oriented design principles and design patterns to avoid unnecessary duplication and make the application easier to maintain. In the future, I would continue using this approach, but I would spend even more time identifying requirements and constraints before beginning development. I would also compare possible architectures and platforms early, create diagrams to visualize relationships between components, and continue checking my design decisions against the client's requirements throughout development.
