---
layout: essay
type: essay
title: "Building Software Like Building a City"
# All dates must be YYYY-MM-DD format!
date: 2024-12-05
published: ture
labels:
  - Design Patterns
  - Software Engineering
---


### The Role of Design Patterns in Software Development
Design patterns in software engineering can be compared to city planning. When a city grows without planning, you end up with confusing streets, inefficient transportation, and buildings that don’t quite serve their purpose. The same happens with software that goes without proper design patterns - it becomes a tangled mess of code that’s difficult to navigate and maintain. 

Think of design patterns like the basic rules cities follow to stay organized. Just as cities use street grids to help people get around and put similar buildings together (like keeping shops in one area and homes in another), programmers use design patterns to keep their code neat and working smoothly. These patterns weren’t made up overnight - they came from programmers noticing that certain ways of solving problems worked really well, so they started using these solutions over and over again. 

<div style="text-align: start;">
  <img width="70%" class="rounded" src="../img/design-patterns/city_planning.jpg" alt="City Planning Picture">
</div>

<br>

In my software engineering course I have been working with applications that perfectly illustrate how these patterns work together. Let me break this down into simpler, more digestible sections: 

#### Breaking Down the MVC Pattern
Imagine a city with three main areas: homes, shops, and factories. My apps works the same way with the **MVC pattern**:
- The Models (my database schemas in the Prisma directory) are like factories, handling all the heavy data work, processing and storing
- The Views (React components in my src/components directory) are like shops where users interact with the app
- The Controllers (spread across my src/app and src/lib directory) are like the roads connecting everything together

#### Routing: A City's Main Bus Station
I used Next.js routing like a city’s main bus station - all visitors enter through one place and get directed to where they need to go. This makes it easy to keep track of everyone and keep the system secure. 

#### The Repository Pattern: A Post Office for Data
For handling data, I implemented the **repository pattern**. Think of it like a post office - mail carriers know exactly how to deliver packages, while people sending mail don’t need to know all the details of how the postal system works. 

#### The Container Pattern: Separating Looks from Functionality
In my components, I used the **container pattern** to separate how things look from how they work - like having a beautiful building facade while all the plumbing and electrical work happens behind the scenes. An app containing a form for users to submit is a good example. The part the user sees is completely different from all the behind-the-scenes work.

#### The Singleton Pattern: A Centralized Authority
For user logins, I used something called the **singleton pattern**. My apps needed a single, authoritative source to handle all user sessions. It’s like having one city hall that keeps all official records, instead of having multiple offices with different versions of the same documents - that would be chaos!

### Design Patterns Matter!
These patterns aren’t just fancy ideas - they solve real problems by bringing order to the chaos of software development. Just like a city designed with efficient transportation, clear zoning, and green spaces, well-implemented design patterns make software more intuitive, adaptable, and robust. 

Remember: using design patterns is like city planning - it’s not about following strict rules, but about using tried-and-true solutions to build something that works well for everyone. 


