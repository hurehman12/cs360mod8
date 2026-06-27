# cs360mod8
This repo contains the mod 8 assignment for cs360


Update 06/27/2026



1-Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

I developed a Weight Tracking App, the main goal of the app was to let users create an account, log in, set a goal weiwght, add daily weight entries, view saved entries, edit entries, delete entries, and receive an optional SMS notification when they reach their goal weight. The app was designed for users who want a simple way to track their weight over time without needing a full fitness app with a lot of extra features. The main user need was being able to record weight progress and come back later to see or update that information.

2-What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app needed a login screen and a main weight tracking screen. The login screen lets users log in with an existing account or create a new account. The main screen includes the goal weight section, daily weight entry section, weight history grid, edit and delete buttons, and the SMS notification option. I tried to keep the design simple because the user should not have to guess what to do. The layout follows the way someone would naturally use the app. They log in, set a goal, add their weight, view their history, and make changes if needed. I think the design was successful because it focused on the main purpose of the app and did not add unnecessary screens or features that would make it confusing.

3-How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the coding process by building and testing the app one feature at a time. I started with the login and account creation features, then worked on the SQLite database, then added the ability to create, read, update, and delete weight entries. After that, I worked on saving the goal weight and handling SMS permissions. Breaking the project into smaller parts made it easier to find problems and fix them before moving on. I also used comments and clear method names so the code would be easier to understand later. In the future, I would use the same approach because it is easier to develop an app in smaller pieces instead of trying to build everything at once.

4-How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the app in the Android Emulator throughout the development process. I tested creating a new account, logging in, entering the wrong login information, adding a weight entry, editing a saved entry, deleting an entry, and closing and reopening the app to make sure the saved data was still there. I also tested the SMS permission feature by allowing and denying permission. This was important because the app needed to keep working even if the user denied SMS permission. Testing revealed small things that needed to be adjusted, like making sure saved data loaded correctly and making sure the app did not depend on SMS permission to function.

5-Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One challenge I had to work through was connecting the database functionality to the user interface in a way that made sense. It was not enough to just save information in the database. The app also needed to display the information in the grid and allow the user to edit or delete individual entries. Another challenge was SMS permission because the app had to respond differently depending on whether the user allowed or denied permission. I had to make sure the SMS feature was optional and that the rest of the app still worked normally without it. This helped me think more about real user behavior instead of only focusing on the happy path where everything is allowed.

6-In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think I was most successful with the database portion of the app. The app allows the user to create an account, save weight entries, view saved data, update entries, delete entries, and keep the data after closing and reopening the app. This showed that I understood how to use SQLite for persistent storage and how to connect database records to the app’s interface. I was also proud of getting the permission handling working because it showed that the app could respond to different user choices without crashing or blocking the main features.
