# The Gaming Room – Software Design Document

This repo contains the final software design document for the *Gaming Room* project. The client wanted to expand their game *Draw It or Lose It* to multiple platforms—Android, iOS, Windows, and web. This document breaks down the architecture, tools, and design decisions I made to help make that happen.

---

## Portfolio Journal Entry

### Who’s the client and what did they want?  
The Gaming Room already had a working trivia game and wanted to take it cross-platform without rebuilding everything from scratch. My job was to figure out how to make that possible—designing something modular, scalable, and easy to maintain.

### What I did well  
I kept the architecture clean and layered. Each part of the system has a clear role, and I used standard terminology to make the doc readable for both devs and non-devs. The design is easy to follow and makes scaling the game straightforward.

### What helped during the process  
Writing everything out before touching code helped me catch issues early. It made me think through platform-specific problems and how to keep the logic reusable. This saved a ton of time later.

### What I’d revise  
If I had more time, I’d go back and beef up the section on security—especially authentication, user data handling, and potential threats. It’s there, but it could go deeper.

### How I addressed the user’s needs  
The users need the game to feel the same no matter what device they’re on. I kept that in mind by focusing on a shared codebase with platform-specific UI layers. Building around user needs early means fewer headaches later.

### My design approach  
I used a layered structure with modular components and stuck with patterns like MVC to keep things organized. Going forward, I’d use the same general approach—start with diagrams, get client feedback early, and build something that’s easy to test and scale.

## Instructor Access
My instructor has been added as a collaborator on this repo.
