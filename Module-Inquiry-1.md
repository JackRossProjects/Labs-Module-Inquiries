# Module Inquiry 1

## Questions

Q1. What questions did you ask your stakeholder that helped in breaking down your tasks?

Q2. What user stories did you draw from to create your product roadmap? List them below.

Q3. Select your favorite user story. What are the tasks that need to be accomplished in order to ship that particular user story?
    - What did you do well in this task breakdown process? What were some challenges?
    
Q4. After what you've learned in this process, given a new product roadmap, how would you approach it differently?
   - What would you change about the way you go about breaking down individual tasks?
   
  
A1. 
Release 1 - will the client have metrics involved ? Quiz/rating/reading comprehension after reading the stories? (prior to release 3)

Authentication ? okta ? 
Roles ? parent account , child account.

How will UGC be managed, for example will there be administrator roles that screen content for abuse? If so are those roles also expected to be incorporated in the 1&2nd releases ?

DS : scan illustrations ? transcribe ? discard handwritten image ?

How are we measuring complexity ?
Does the SH have a specific method/metric for measuring UGC’s complexity and rank?

Handling misspellings and bad grammar ?
Is there a specific method that the SH would like to focus on for handling grammatical/spelling errors?
E.g topic modeling/ POS tagging to analyze grammar

spell - correct ? speech tagging ? 
Options if the SH doesn't have a specific answer: https://stackoverflow.com/questions/13928155/spell-checker-for-python

Pre-trained models ?
Would this be possibly driven by schools?
How much is curated content and prompts and how much is driven by the kids?
What does it mean to assign a menu to other kids?
What is ds doing on the first RC.
Avoiding unwanted users?


A2.
A Customer (Parent) can create an account
A Customer can subscribe to the service.
A Customer (Parent) can add one or multiple User(Child) account(s)
A User (child) can log into account.
A Customer/User can log out.
A User can change their password on first login.
A User can recover a password sending the Customer an email setting a temporary password.
A Customer can change their account information (username, password ect)
A User can view stories
A User can upload their hand written stories to the app
User can view their past stories
A User gets a complexity score from their UGC submission via NLP model.
Use machine learning for automated content moderation that raises a flag and it's sent to the human moderator for review.
Transcribe the user's (child) stories into text.


A3.
Transcribe the user's (child) stories into text.
- Figuring out how to transcribe a childs handwriting is going to be a very interesting challenge. Margin for error compared to adult handwriting
  will have to be much higher and the training data might even have to be labeled by hand in certain cases. 
  
 
A4.
Categorization.
Putting things into categories has sped up the process so much. From different types of users to different funciton calls for different actions.
Knowing what you're dealing with and how the pieces are differnt is so helpful when creating user stories.
