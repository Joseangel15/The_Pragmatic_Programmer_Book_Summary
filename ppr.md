# The Pragmatic Programmer - Summary of Concepts and Tips.
## By David Thomas and Andrew Hunt

- 💡 Tip 1: Care About Your Craft
Why spend your life developing software unless you care about doing it well?

- 💡 Tip 2: Think! About Your Work
Turn off the autopilot and take control. Constantly critique and appraise your work.

## Chapter 1: A Pragmatic Philosophy

### 1 - It's Your Life

- 💡 Tip 3: You Have Agency
It's your life. Grab hold of it and make it what you want.

### 2 - The Cat Ate My Source Code

#### Team Trust
#### Take Responsibilty

- 💡 Tip 4: Provide Options, Don't Make Lame Excuses
Instead of excuses, provide options. Don't say it can't be done; explain what can be done. 

### 3 - Software Entropy

- 💡 Tip 5: Don't Live With Broken Windows
Fix bad designs, wrong decisions, and poor code when you see them.

#### First, Do No Harm

### 4 - Stone Soup and Boiled Frogs

-  Tip 6: Be a Catalyst for Change
You can't force change on people. Instead, show them how the future might be and help them participate in creating it.

#### The Villager's Side

- Tip 7: Remember the Big Picture
Don't get so engrossed in the details that you forget to check what's happening around you.

### 5 - Good-Enough Software

#### Involve Your Users in the Trade-Off

- Tip 8: Make Quality a Requirements Issue
Involve your users in determining the project's real quality requirements. 

#### Know When to Stop

### 6 - Your Knowledge Portfolio

#### Your Knowledge Portfolio
#### Building Your Portfolio

- Invest Regularly
- Diversify
- Manage Risk
- Buy low, sell high
- Review and rebalance

- Tip 9: Invest Regularly in Your Knowledge Portfolio
Make learning a habit.

#### Goals

- Learn at least a new language every year
- Read a technical book each month
- Read nontechnical books too
- Take classes
- Participate in local user groups and meetups
- Experiment with different environments
- Stay current

#### Opportunities for Learning
#### Critical Thinking

- Tip 10: Critically Analyze What You Read and Hear
Don't be swayed by vendors, media hype, or dogma. Analyze information in terms of you and your project.

- Ask the "Five Whys"
- Whos does this benefit?
- What's the context?
- When or Where would this work?
- Why is this a problem?

### 7 - Communicate!

- Tip 11: English is Just Another Programming Language
Treat English as Just Another Programming Language. Write documents as you would write code: honor the DRY principle, ETC, automation, and so on.

#### Know Your Audience
#### Know What You Want To Say
#### Choose Your Moment
#### Choose a Style
#### Make It Look Good
#### Involve Your Audience
#### Be a Listener
#### Get Back to People
#### Documentation

- Tip 12: It's Both What You Say and the Way You Say It
There's no point in having great ideas if you don't communicate them effectively.

- Tip 13: Built Documentation In, Don't Bolt It On
Documentation created separately from code is less likely to be correct and up to date.

## Chapter 2: A Pragmatic Approach

### 8 - The Essence of Good Design

- Tip 14: Good Design is Easier to Change Than Bad Design
A thing is well designed if it adapts to the people who use it. For code, that means it must adapt by changing.

#### ETC Is a Value, Not a Rule

### 9 - DRY--The Evils of Duplication

- Tip 15: DRY--Don't Repeat Yourself
Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.

#### DRY is More Than Code
#### Duplication in Code
#### Duplication in Documentation
#### Representational Duplication
 
- Duplication Across Internal APIs
- Duplication Across External APIs
- Duplication with Data Sources

#### Interdeveloper Duplication

- Tip 16: Make it Easy to Reuse
If it's easy to reuse, people will. Create an environment that supports reuse.

### 10 - Orthogonality

#### What is Orthogonality?
#### Benefits or Orthogonality

- Gain Productivity
- Reduce Risk

- Tip 17: Eliminate Effects Between Unrelated Things
Design components that are self-contained, independent, and have a single, well-defined purpose.

#### Design
#### Coding

- Keep your code decoupled
- Avoid global data
- Avoid Similar Functions

#### Testing
#### Documentation
#### Living with Orthogonality

### 11 - Reversibility

#### Reversibility

- Tip 18: There Are No Final Decisions
No decision is cast in stone. Instead, consider each as being written in the sand at the beach, and plan for change. 

#### Flexible Architecture

- Tip 19: Forgo Following Fads
Neal Ford says, "Yesterday's Best Practice Becomes Tomorrow's Antipattern." Choose arquitectures based on fundamentals, not fashion.

### 12 - Tracer Bullets

#### Code That Glows in the Dark

- Users get to see something working early
- You have an integration platform
- You have something to demonstrate
- You have a better feel for progress

- Tip 20: Use Tracer Bullets to Find the Target
Tracer bullets let you home in on your target by trying things and seeing how close they land.

#### Tracer Bullets Don't Always Hit Their Target
#### Tracer Code versus Prototyping

### 13 - Prototypes and Post-it Notes

#### Things to Prototype

- Architecture
- New functionality in an existing system
- Structure or contents of external data
- Third-party tools or components
- User interface design

- Tip 21: Prototype to Learn
Prototyping is a learning experience. Its value lies not in the code you produce, but in the lessons you learn.

#### How to Use Prototypes

- Correctness
- Completeness
- Robustness
- Style

#### Prototyping Architecture
#### How Not To Use Prototypes

### 14 - Domain Languages

- Tip 22: Program Close to the Problem Domain
Design and code in the language of the problem domain.

#### Some Real-World Domain Languages
#### Characteristics of Domain Languages
#### Trade-Offs Between Internal and External Languages
#### An Internal Domain Language on the Cheap

### 15 - Estimating

- Tip 23: Estimate to Avoid Surprises
Estimate before you start. You'll spot potential problems up front.

#### How Accurate is Accurate Enough?
#### Where Do Estimates Come From?

- Understand What's Being Asked
- Build a Model of the System
- Break the Model into Components
- Give Each Parameter a Value
- Calculate the Answers
- Keep Track of Your Estimating Prowess

#### Estimating Project Schedules

- Painting the Missile
- Eating the Elephant

- Tip 24: Iterate the Schedule with the Code
Use experience you gain as you implement to refine the project time scales.

#### What to Say When Asked for an Estimate

## Chapter 3: The Basic Tools

### 16 - The Power of Plain Text

#### What is Plain Text?

- Tip 25: Keep Knowledge in Plain Text
Plain text won't become obsolete. It helps leverage your work and simplifies debugging and testing.

#### The Power of Text

- Insurance Against Obsolescence
- Leverage
- Easier Testing

#### Lowest Common Denominator

### 17 - Shell Games

- Tip 26: Use the Power of Command Shells
Use the shell when graphical user interfaces don't cut it.

#### A Shell of Your Own

### 18 - Power Editing

- Tip 27: Achieve Editor Fluency
An editor is your most important tool. Know how to make it do what you need, quickly and accurate.

#### What Does "Fluent" Mean?
#### Moving Toward Fluency

- Growing Your Editor

### 19 - Version Control

#### It Starts at the Source

- Tip 28: Always Use Version Control
Version control is a time machine for your work; you can go back.

#### Branching Out
#### Version Control as a Project Hub

### 20 - Debugging

#### Psychology of Debugging

- Tip 29: Fix the Problem, Not the Blame
It doesn't really matter wether the bug is your fault or someone else's--it is still your problem, and it still needs to be fixed.

#### A Debugging Mindset

- Tip 30: Don't Panic
This is true for galactic hitchhikers and for developers.

#### Where to Start
#### Debugging Strategies

- Tip 31: Failing Test Before Fixing Code
Create a focussed test that reveals the bug before you try fixing it.

#### Code in a Strange Land

- Bad Results
- Sensitivity to input Values
- Regression Across Releases

- Tip 32: Read the Damn Error Message
Most exceptions tell both what failed and where it failed. If you're lucky you might even get parameter values.

#### The Binary Chop

- Logging and/or Tracing
- Rubber Ducking
- Process of Elimination

- Tip 33: "select" Isn't Broken
It is rare to find a bug in the OS or the compiler, or even a third-party product or library. The bug is most likely in the application.

#### The Element of Surprise

- Tip 34: Don't Assume It--Prove It
Prove your assumptions ijn the actual environment with real data and boundary conditions.

### 21 - Text Manipulation

- Tip 35: Learn a Text Manipulation Language
You spend a large part of each day working with text. Why not have the computer do some of it for you?

### 22 - Engineering Daybooks

## Chapter 4: Pragmatic Paranoia

- Tip 36: You Can't Write Perfect Software
Software can't be perfect. Protect your code and users from the inveitable errors.

### 23 - Design by Contract

#### DBC

- Preconditions
- Postconditions
- Class Invariants

- Tip 37: Design with Contracts
Use contracts to document and verify that code does no more and no less than it claims to do.

#### Implementing DBC

- Assertions

#### DBC and Crashing Early
#### Semantic Invariants
#### Dynamic Contracts and Agents

### 24 - Dead Programs Tell No Lies

#### Catch and Release Is for Fish

- Tip 38: Crash Early
A dead program normally does a lot less damage than a crippled one.

#### Crash, Don't Trash

### 25 - Assertive Programming

- Tip 39: Use Assertions to Prevent the Impossible
If it can't happen, use assertions to ensure that it won't. Assertions validate your assumptions. Use them to protect your code from an uncertain world.

#### Assertions and Side Effects
#### Leave Assertions Turned On

### 26 - How to Balance Resources

- Tip 40: Finish What You Start
Where possible, the function or object that allocates a resource should be responsible for deallocating it.

- Tip 41: Act Locally
Keep the scope of mutable variables and open resources short and easily visible.

#### Nest Allocations
#### Objects and Exceptions
#### Ballancing and exceptions
#### When You Can't Balance Resources
#### Checking the Balance

### 27 - Don't Outrun Your Headlights

- Tip 42: Take Small Steps--Always
Small steps always; check the feedback; and adjust before proceeding

#### Black Swans

- Tip 43: Avoid Fortune-Telling
Only look ahead as far as you can see. 

## Chapter 5: Bend , or Break

### 28 - Decoupling

