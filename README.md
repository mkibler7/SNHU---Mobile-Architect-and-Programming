# SNHU---Mobile-Architect-and-Programming

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The main purpose of this mobile application was to provide an easy, intuitive way for users to track their health more closely. It in tracks daily weigh-ins and then takes that data and compares it to the user's goal, and then notifies the user via text message when they have reached their goal.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

We needed a login screen, for the user to login to their account, or register for one if they don't have one already. It also included a data display screen, where user's could see all of the data they have recorded in the database so far. And lastly we needed and SMS screen where users would be asked if they would like to sign up for text message notifications, during the registration process.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My main strategy when approacing this application was modularity, and trying to break things up into smaller pieces that may be reused. Isolating each task or function made it easier to pinpoint trouble areas in the code. I could apply this strategy to future projects by making a more clear roadmap of what I want from each piece of the code, as I would have done things slightly differently if I were to remake the application over from scratch.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Lots and lots of logs. I logged pretty much everything using the "Log.d()" command to keep track of where my code was breaking, when I was having issues. I also used the Toast object to notify me with bigger functions, such as a user trying to log in without user credentials. I would constantly restart my application in the emulator to test whatever I was working on from the user's perspective.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

The part of the application I had the most problems with was the SMS notifcation system. Figuring out how to clear permissions with a shell command and how to retest the SMS permissions request was the biggest headache I dealt with. 

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think the SQLite database was where I had the most success in this application, and it's also where I most of my time. Learning how to manipulate SQL data using java code was extremely interesting to me. This was the first time I have actually felt like I am building a real program, as I was able to set up a dynamic UI system and database that users can interact with on the front and back end. 

