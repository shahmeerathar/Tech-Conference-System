THIS PROJECT WAS COMPLETED IN TWO PHASES. THE FINISHED CODE CAN BE FOUND IN THE SRC FOLDER IN PHASE 2.
CONSIDERABLE IMPROVEMENTS WERE MADE BETWEEN PHASE 1 AND PHASE 2, INCLUDING MAJOR DESIGN CHANGES.

To test the user interface, RUN DEMO.JAVA located in the UserLogin package. You will be 
prompted to input a valid email address and a password. Existing users and their log in credentials are 
stored in Users.json in the Resources package. If the inputted credentials do not match any existing user, 
you will be prompted to try again.

Once logged in, a main menu will be presented, where there are several options to choose from (to view 
messages, scheduling, or to log out). Input the index corresponding to the function
you would like to test; whatever actions you perform (including messages sent, events signed up for, etc.)
will be saved to several categorized JSON files once the account is LOGGED OUT OF THE PROGRAM. 

Functionality will vary based on the type of user account logged in: Speaker, Organizer, or Attendee. The 
type of each user is specified in Users.json, which you can refer to if you would like to test a specific 
type of user account.

IF YOU WOULD LIKE TO TEST ALL FUNCTIONALITIES FROM SCRATCH:

1. Log in as an Organizer (Preset Organizer Login: email: ac, password: ac).
2. Then, create a new user by going to Schedules -> Request to Register a User. You will then be prompted for the information for the new
   user. Note that you will be able to set an Attendee to a VIP later on in the user creation process. 
3. Create a new instance of an Organizer, Speaker, and Attendee (VIP and non-VIP). You do not have to remember the login credentials, since
   they will be stored in the Users.json file upon logging out of the program, but it is recommended to keep the names and emails short for 
   ease of use later on in testing.
4. Log out of this Organizer Account by typing 0 to return to the main menu and type 0 again to Log Out.
5. Now, you can test the functionality of all of the users you have just created. This includes, but is not limited to:
  - creating more users with your Organizer
  - creating new events with your Organizer
  - register for events as an Organizer or Attendee
  - message other users (messaging restrictions vary between types of users)
  - archive and set read/unread status for messages
  - message all attendees registered for your events as a Speaker
  - add personal requests as an Attendee
  - approve/reject Attendee requests as an Organizer
  - and much more!
6. DO NOT FORGET TO LOG OUT IF YOU WANT TO SAVE YOUR CHANGES (WRITE TO THE JSON FILES). The system will prompt you to log back in immediately,
   if you would like to continue testing.
