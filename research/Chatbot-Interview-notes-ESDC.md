09Jan2020
## **Conversation with Malika Omar HR Business Innovation Team (ESDC)**
* Largely an onboarding chatbot
* Have tested it a few times, most recently with students in the summer
* Biggest finding is that people like the features more than the chatbot itself because it is clunky/long to talk to. 
* The chat does still have some value because it can answer your questions. (i.e. “what should I do, and it will give an answer)
* Really important to consider where you will get your data from. It has to be good for it to work well. 
* Right now it can’t take personal info (we don’t want it to learn “you”)
* Need to decide if you want to provide depth of information, or a lot of breadth.

## **Conversation with Collin Brown (ESDC-CDO)**
###### Initial objective
  * What kind of chatbot can we create using open source, and what is the use case?
  * What’s the framework, etc
  * What’s the experience like?
  * What does it look like in a production setting
###### Results: 
* It could moderately answer the question (where can I find info on my health benefits), I need to do training, what training should I do?) It could  track and recommend
* Feedback was “its cool but why do I need to do this?”  it is faster to create a list and bookmark than to keep asking the chatbot
* Good feature was the acronym dictionary 
* Strength is to use microservices (encapsulate a piece of business logic/process and expose the proces) and REST APIs
* Looked at Amazon, Apple, and Google - the way they work is that they have microservices and APIs, so job the of the chatbot is to take natural language interpret it, (convert to text - in the case of speech), and then send a request to the API
* Chatbot for Gov is useful if it works with REST APIs and microservices
* You can build in the ability to update the data
* CDO is building microservices and then deploying
* Future friendly - REST APIs and microservices are highly standardized, so you can keep adding. This means that you can build small and as more services have APIs, they can be integrated
* Strength of a chatbot is that it  makes it easier to get info
* Best if its named entity
* Chatbots fail when you have to discriminate many tasks or keep track of sequential info (not good for troubleshooting)
* Its good when it’s hard to navigate the hierarchy (get me acronyms, get me contract info, get me software list) 

##
[Link to Google Doc](https://docs.google.com/document/d/12lK8cF-ZCwKBq9mOFx6SRRT1IsUSpgLKxVwlk_2RiOs/edit?usp=sharing)
