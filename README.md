# Android Interview Guidelines

Finding the right candidate for the job is not simple. You have small window to evaluate whether the candidate is competent enough for the role at hand and even after they answer a gruesome series of questions, there's never a guarantee. Sometimes a candidate is really good at giving interviews but unable to contribute once hired. At the same time, there are folks that are horrible at interviews but are amazing people to work with. 

This document hopes to assist anyone taking a domain interview, specifically, Android Development. The interview process covers different aspects like work done, reasoning abilities, experience and knowledge. 

**Note: These are guidelines. This is in no way a definitive way to pick a candidate, the guidelines mentioned here have helped me and I hope they help you.**


## Job Description

Depending on the role the candidate is interviewing for:

### Fresher
- Learning Ability - Someone who is capable of learning concepts quickly
- Reasoning Skills - Ability to reason as to why one approach is better than the other
- Android Basics - Familiar with the basic building blocks of android
- Communication Skills - Ability to explain his intentions and thought process clearly                                        
### Software Engineer
- Self-starter: Someone who can be assigned a task and can figure out how to get it done without much hand holding.
- Self- study: Someone who shows a capacity for learning more advanced tools on his/her own and applied it in some project.
- Production apps: Someone who has had experience with applications launched to the play store
- Debugging: Someone who can debug and identify issues in code.
- Build Complex UI: Knows how to design apps w.r.t to UI well 

### Senior Software Engineer 
- Capable of coaching and mentoring
- Has shown expertise in some form
- Someone familiar with different architectures and good code practises. Preferably someone who has written tests, written clean code and applied some architecture design pattern before. 


## Interview Process

The interview is usually broken down into the following phases:

1. YOUR STORY
2. DESIGN PROBLEM
3. ADVANCED TOPICS
4. ANDROID RAPIDFIRE Q&A

### 1. YOUR STORY
The first part of the interview goes into understanding the individual and why he got into Android App Development. To a large extent, it will also help understand how compatible he would be as a team member and what all he has had a hands-on experience with in the past. 

Ask for:
- Brief Introduction about yourself
- Ask about some of the work done. Any feature you’ve developed and would like to brag about?
- Show your work. Any apps published on the Play Store? Any personal/side project? Ask him to show his work. 
- Libraries & Tools. Ask about which tools, libraries and android domains he’s worked on in the past.  
- Your role and responsibilities. What was the team size in previous organization? What role did you play? What projects were you responsible for?                                                                                                                                                                                            
### 2. DESIGN PROBLEM 
The second part of the interview goes into observing how the candidate deals with a problem. We present a problem statement that a product manager may have for a developer. 

For example, we could ask him to design a calculator with an additional page that shows a history of all the calculations made. This should be synced with the web.

Then we ask the candidate to solve for the problem according to the following parts.
1. **UI/Design**: How he would design the UI of the app? Irrespective of the creativity involved, he will be asked on the reasoning behind his choices and his implementation. Some product sense is expected from the candidate as he’d be designing the solution to cater to the needs of a user. 
2. **Architectural Patterns** - How he would architect the code, which architectural pattern he’d prefer to use, etc. There should be a  separation of concerns. 
3. **Data Flow**: How the different layers would communicate with one another and how he’d implement the logic. 

While his approach is observed, we’d also ask a number of questions regarding his implementation such as:
- The logic and libraries he’d use to implement the UI, Network and Business Logic layer. 
- How he’d build the complex UI with RecyclerViews 
- Why he’s chosen to use activities over fragments
- How he intends to listen for user events and act on it, etc. 
- Why he picked an architectural pattern: MVVM v/s MVP v/s MVC

### 3. ADVANCED TOPICS 
This phase focuses on asking a couple of questions that require thoughtful answers. We don’t need specifics, just proof that there’s a strong understanding of the concepts. The specifics can always be googled. 

#### ANDROID APP PERFORMANCE
- Mention a few ways to avoid memory leaks in android? Write a program that would leak memory. 
- What are the causes of ANR?
- How do you measure?

#### ANDROID TOPICS
- What is Deep Linking? Can you explain how it works?
- How does the Android Notification system work? 
- Background processes get killed by OS. How to ensure it runs once the app is closed?
- Name and explain the different activity launch modes?
- What happens when you rotate your device? Handling rotations in android?

#### NEW DEVELOPMENTS
- What changes did Oreo bring in that required so many changes to the app?
- Are you familiar with ConstraintLayout? What advantages do they bring over RelativeLayout?

#### BACKGROUND PROCESSING
- How do you periodically update the app? 
- How can two threads communicate with one another?
- How would you debug while using threads?

#### ANDROID TEST DEVELOPMENT
- Why do we write tests?
- What kind of testing tools do you use? Why Expresso?

### 4. ANDROID RAPIDFIRE Q&A 
This phase focuses on asking a series of basic questions in android and expects the candidate to answer them with relative ease. They touch only the basics and the developer should have some idea about each topic. 

For example:
- What are intents? What are the different types of intents?
- Importance of Android OS Versions? Familiar with OS Fragmentation?
- What are runtime permissions? 
- Difference  between intentService and Service?
- Different ways to handle storage/persistence in the app?
- What are Build Variants and Flavours?
- Lifecycle of an Activity/Fragment?

Plenty of such questions available online:
- https://android.jlelse.eu/android-interview-questions-cheat-sheet-96ea01c88def                                                                                                                                                                           
