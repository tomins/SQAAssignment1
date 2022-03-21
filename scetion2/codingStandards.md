# Coding standards task
## *Primary Author - Thomas Cummins*
## *Secondary Author - Denisa Rusu*

### **Task Description**        
Coding standards are a set of rules that guide developers to ensure their code is readable, safe, reliable, testable, maintainable and portable. This is vitally important as without it, a team of developers could create code that each of them cannot read, leading to massive amount of inefficiency and a high possibility of expensive mistakes that will take a long time to fix. Creating a robust set of rules and guidelines for a team to use will greatly increase current working standards and efficencies as well as future profing the project as any developer will be able to read the guidelines and understand the entire project and fix any issues much easier then before.

### Part 1: Geeks for Geeks coding standards and guidelines[^1]
#### **Key Concepts**
- have a naming convention for all elements
- indentation
- document code well
- shorten functions where possible
#### **Details**
Coding standards are shown to be vitally important in an efficent team as they improve all elements of team development. Some of the rules that are important to take out of this article are as follows:
- Limit global variables -- leads to more secure code
- Standard headers for different modules -- name, date of creation, author, sysnopsis of the reason for the module
- Naming convention for all elements -- Must be meaningful and easy to understand it's function, use camelCase
- Indentation -- proper indentation allows for much easier reading of code and de-bugging
- Error handling -- All error functions should return a 0 or 1 to simplify debugging
- Documentation -- Well documented code is vital for future users of the code and for debugging
- Short Functions -- Shorter functions allow for better code reusability and cut down on confusing logic
#### **Synopsis**
This article introduces some very important concepts that will be used in our rules and regulations, there is a strong emphasis on proper structure which helps everyone around the project to be able to understand the code much easier. They also help to cut down time when debugging, hence reducing the cost of development significantly


### Part 2: Medium Coding standards and Conventions in Software Development Team[^2]
#### **Key Concepts**
- Good standard naming
- File naming and organization
- Formatting and Documentation
- Testing
#### **Details**
Coding standards allow for many advantages such as easier team integration, increased code quality efficency and easier for maintaining, reduces code complexity & reducing code development. This means that disadvantages of not having well structured code standards include reduced engineers motivation, increased development team & complex codebase structure. Codong standards within an organization can be as detailed as needed, the more detail the better code quality, but the more complex for new users to understand so a balance is needed. Some of the key concepts that are discussed in this article include: 
- Naming Conventions: how packages, classes, methods, variables etc. should be named in the same way (camelCase).
- File and folder naming and organization: All files and folders should be formatted in the same manner.
- Formatting and Indentation: Code should be formatted and indented as necessary to aid with debugging and general ease of understanding.
- Commenting and Documentation: Makes code reviews and debugging much easier and faster.
- Classes and Functions: Code should be broken up into appropriate classes and functions so as to aid ease of reading.
- Testing: Code should be tested with appropriate tools to an approriate level.
#### **Synopsis**
Overall, code standards are a vital part of any team coding enviroment as without them the process of coding would draw to a stop for a long time anytime there was an error or when a new team member was added.

### Part 3: Svitla Why, Where And When To Use Coding Conventions[^3]
#### **Key Concepts**
- Coding standards allow for much easier reading in 5 years
- There are many generic coding standards avaliable for a team to use based on language
- Coding conventions can be implemented at many levels of the development process
#### **Details**
A coding standards is an agreed set of rules in a team to uniformly share code. Its purpose is to make code easier to create and understand code, minimize the load on memory and vision reading a program. Coding standards come in many forms, some are linked to the code language, more are based on the individual project. They take on many different issues including: 
- Name choosing and case use.
- Indentation style.
- Bracket bounding blocks.
- Comment style.
- File organization.
- Declaration of classes and interfaces.
- Programming practices.
Teams may wish to also include non-standard coding practices such as:
- Restriction of the code horizontally to keep all code on screen.
- Restriction of code vertically so all code is held in memory.
- Keep functions or methods to the size of the screen.
Coding standards are absolutely vital for the success of the team, 40%-80% of the cost of software is spent on maintanace, meaning easier to understand code would make the cost drop dramatically. Also software is almost never supported by the primary author.
#### **Synopsis**
Coding standards are yet again shown to be a hugely important part of a development team, especially in the long term where it it highly likely that a different team will have to maintain the code that has been written.



### Part 4: Coding Standards & Best Practices To Follow[^4]
In this article, some of the prime applications are defined and should be observed in order to produce cleaner, more readable and more efficient code with fewer mistakes.

#### **Focus on code readability**
- Divide code blocks into paragraphs within the same section.
- Don't employ functions that are too long. A single function should ideally perform a single task.
- Write as few lines as possible.
- Deep nesting should be avoided. Code becomes more difficult to comprehend and follow when there are too many levels of nesting.
- To distinguish SQL special terms and function names from table and column names, capitalize them.
- Use the DRY principle (Don't Repeat Yourself). When possible, automate repetitious tasks. In the script, the same line of code should not be repeated.

#### **Make daily backups second nature**
- Data loss can be caused by a variety of factors, including system crashes, dead batteries, software glitches, and hardware damage. 
- To avoid this, save your code every day and after every change, no matter how minor. 
- SVN, TFS, or any other version control system can be used to save the workflow.

#### **Attempt to systematize Exception Handling**
When exceptions occur, employ the following strategies to minimize the impact on overall performance in terms of both time and development effort:
- Maintain the code in a try-catch block.
- Verify that auto recovery is turned on and ready to utilize.
- Consider whether the problem is caused by slow software or a slow network. Allow a few moments for the essential elements to appear.
- Utilise a real-time log analysis.

#### **Don't use the same identifier for different reasons**
- Give each variable a name that accurately defines its function. 
- A single variable, of course, cannot have multiple values or be used for several functions. 
- This would be perplexing to anyone viewing the code, and future additions would be more complex to implement. 
- Assign distinctive variable names at all times.



### Part 5: 3 Good and Bad Ways to Write Team Coding Standards and Conventions[^5]

#### **The challenges of team coding conventions**
This article outlines how the absence of coding norms and standards has an impact on teamwork, quality, and production. Work is also unsustainable due to a lack of coding standards.
Here's a partial list of the issues that can arise when they are missing:

- It degrades the code's quality.
- Time is wasted.
- It makes everyone's job less enjoyable.
- Collaboration around code becomes increasingly challenging when topics are recurring.
- Depending on who developed the code, there will be inconsistencies in the style. When reading the code, this adds a little mental strain.
- Open and/or inner source is made more difficult by inconsistent and undocumented styles. People will have a harder time contributing useful pull requests.
- Additionally, the cost of common code ownership rises. It can make parts of the code the sole responsibility of a single developer in extreme instances.


## Footer
[^1]https://www.geeksforgeeks.org/coding-standards-and-guidelines/

[^2]https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05

[^3]https://svitla.com/blog/why-where-and-when-to-use-coding-conventions

[^4]https://www.browserstack.com/guide/coding-standards-best-practices

[^5]https://philippe.bourgau.net/3-good-and-bad-ways-to-write-team-coding-standards-and-conventions