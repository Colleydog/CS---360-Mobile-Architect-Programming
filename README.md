# CS---360-Mobile-Architect-Programming
# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

During this project we were asked to create an application that incorporated a database that is stored locally on the users device that could save an inventory of the users liking. This inventory can be manipulated after initializing. The app would also allow for a unique user login page. This page takes in the input from the user of a username and password and if the username does not exist then prompt the user to add it to the database.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The project needs a total of 2 main activity screens one for the login and one for the main inventory screen. The login screen had a simple title that said “Login” and two edit fields. These fields were used to enter the username and password. The user could then tap a Go button that could take them to the inventory and another add user button if the user didn’t exist. The inventory screen had a recyclerView for cardview that help each inventory item. It also had an add button to add more items to the inventory. The design I went with was geared more towards ease of use for the user. I wanted an experience that could be understood immediately.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

During the planning stage of the project I looked at similar applications to the one I was creating. I wanted to understand what may or may not work for the user. The android development website was a very useful resource in understanding what was even possible. While making my activities I tried to test often but booting the emulator before coding the activities and rerunning the emulator after any changes.

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?

As I’ve stated above I would start the emulator before adding anything the activities and rerunning it after making any changes. I also used toast messages throughout the development of my login screen because of how many different if statement were needed. That allowed me to ensure each pass was being triggers properly and have on screen feedback.

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

My biggest challenge was to decide how to use the databases. I couldn’t decide if I wanted unique user inventory or if I wanted all users to have access to the same inventory. I ultimately decided to have all users access the same inventory. This just made sense to me because if the inventory database was to be stored locally then the device would be used in the same location around the same users. If the data was stored remotely then It would have made sense to have unique databases for each user.

# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The organization of all files along with creating a successful login application if I had more time I would have liked to create a forgot password option.
