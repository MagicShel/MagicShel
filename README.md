# Summary
- 👋 Hi, I’m @MagicShel
- 📆 I have 24 years of experience
- 👀 I’m interested in Java, Spring, NodeJS
- 🌱 I’m currently learning cloud-specific concerns
- 📫 How to reach me:
  - gforb-github@yahoo.com
  - @Shel@ohai.social

# About Me
## Currently
I'm a senior/lead software engineer with 24 years of experience. My current technical focus is on microservices with Java / Spring. I've also dabbled in .NET, NodeJS, a lot of front-end Javascript and CSS, though I'm a much bigger fan of TypeScript. I've largely stepped away from front-end and full-stack work to focus on architecture and back-end engineering.

## Experience
I've been a contractor/consultant for most of my career. I've worked with city governments, federal government/military, hospitals, manufacturing/industrial, retail, property management, financial/banking, construction, and probably some fields I've forgotten.

I started out with Lotus (later IBM) Notes and transitioned to X-Pages (JSF) and from there to Java, which has been my primary focus for about 15 years now. I'm primarily self-taught through books, blogs, conferences, YouTube videos, and simple experimentation.

## Interests
### Architecture & Design
I've worked with a lot of bad code. In my early days, it was often mine. I'd write something I thought was particularly good and then turn around and find myself burdened by the limitations, and it took me years to figure out why. I had to discover SOLID principles, dependency injection / inversion of control, immutability, functional programming (specificially the concept of pure functions), separation of concerns, design patterns and unit testing. This is an area where I'm continuing to expand my knowledge and experience. I've learned the importance of expressing and understanding architectural intent to avoid getting caught in anti-patterns.
### Maintainability
I like to create and use code that is well documented and unit-tested. Naming of things is very difficult, but also very important. There is a lot of precedent and guidance on best-practices out there for anyone who goes looking, but few do. Code should be easy to read. Things should be done in consistent patterns where possible and documented when established patterns are poorly-suited. Where readability and performance are at odds, it is important to separate / abstract that complexity so that it doesn't need to be thoroughly understood by every developer who touches the code. Instead, that complexity should be walled-off and well documented.
### Usability
Just like user-facing applications must be useable, so much APIs and contracts. Limit the ways complexity can be interfaced with so that it can't be misused.

There is a school of thought that says if there is only one implementation of a contract, just create the class because it can easily be abstracted to an interface later if necessary. I disagree with that as an absolute philosophy. Sometimes the implementation class requires methods which should not be used 99% of the time. Sometimes you want to control the context under which a class is used, for example by exposing getters but not setters if an object is retrieved a certain way. That being said, it's not bad as a rule of thumb. Unnecessary complexity is a bad thing, but "necessity" is sometimes a perspective, not an absolute truth.


<!---
MagicShel/MagicShel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
