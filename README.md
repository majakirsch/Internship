## Internship diary
### 22.05.2018
* getting started and organizing stuff
* installing PyCharm, GitHub Desktop and Anaconda
* successfully had lunch 
* learning a bit python with codecademy
* explanation of the Project ("Law to Action") by Bruno
* decided to work on machine learning this and also next week
* researched machine learning and read an artical
* still have to figure out the thing with the WLAN
* it's a good thing to make a clear plan what you want to do to get things done
* getting stuck on codecademy (Functions and Lists)
--------------------------------------------------------------------------------------------------------------------
### 23.05.2018
* figured out how to use WLAN on the smartphone
* started with machine learning introduction and took notes
* registrated for the Daimler Customer Speak on monday the 28th of May
* started with "Working with Text Data" and getting stuck
* after lunch worked on learning python -> it was better as yesterday and I'm much happier :)
--------------------------------------------------------------------------------------------------------------------
### 24.05.2018
* started watching ML recipes with J. G. from Google -> understandable and very helpful
* tried again to get on with "Working with Text Data"
* asking yt for help is always a good idea
* installed sci-kit learn successfully
* always ask for help if you get stuck...what do you have to lose...you could waste a lot of time sitting in front of the problem that doesn't deserve so much time and energy
* steps in tutorial work as they should on my computer
--------------------------------------------------------------------------------------------------------------------
### 25.05.2018
* finished watching Josh Gorden
* tried to get an overlook on outlook
* learning how to get started with jupyter notebooks
* cloned repository "ml-assets" and opened it kind of in jupyter notebook
* installed mongo db and pymongo
* connected my computer with the database 
* went through the code of "All models training"
* asked Vivek for help with the exercise bruno gave me
* at a certain point of time your brain isn't able to absorb any more information
* nevertheless I somehow understood what Vivek was showing me and I think it still needs time to settle
* I believe I did good today
* there is still a lot of stuff to learn
* motto for the next week is: try, try try! Just do it! ;)
--------------------------------------------------------------------------------------------------------------------
### 28.05.17
* came late to the office because of my drivers license test 
* got a task to solve from Bruno: instead of predict method and boolean, other method and interger
* participated in the Customer Speak from Daimler: show how business can improve the world and how they use SAP technology to work more efficiently and stay competetive 
* really showed me that big businesses have to rely on technologies that computer engineers develope
* the speaker pointed out that they need to work on the relationship/bridge/connection between developers and users
* work a little bit on the task after the talk
* task: how can we actually rank the documents? true and false don't show how relevant or irrelevant a document is
* goal: an integer output that shows the relevance
--------------------------------------------------------------------------------------------------------------------
### 29.05.17
* task from yesterday finished: predict -> predict_proba

>__before:__
```python
text = ["It is friday"]

X_m = vect.transform(text)
print(mnb.predict(X_m))
print(sgd.predict(X_m))
print(svc.predict(X_m))
```
_output:_  
[ True]  
[False]  
[False]


>__after:__  
```python
text = ["It is friday"]

X_m = vect.transform(text)
print(mnb.predict_proba(X_m))
print(sgd.predict_proba(X_m))
print(svc.predict_proba(X_m))
```
_output:_  
[[0.17656191 0.82343809]]  
[[0.65355647 0.34644353]]  
[[0.62920383 0.37079617]]
        
* loading models into a new notebook with joblib
* creating a web application with flask so that 'my' models are accessible at all time and from everywhere
* tried to start with flask and immediatly got stuck
* problem was that Pycharm used a different Python and not the one from Anaconda so flask wasn't included
* watched first video of a series of flask tutorials
--------------------------------------------------------------------------------------------------------------------
### 30.05.17
* continued with flask
* after yesterdays erros with the interpreter today the port made problems and also pycharm itself because it seems to have its own python and stopped code was still running
* also making change was problematic
* now I use a different port
* the code is starting to look good and not everything I did was wrong :D
* now my tasks to finish the code is in the code as comments
* getting stuck at if statement: problem with checking if the variable is not None or empty
--------------------------------------------------------------------------------------------------------------------
### 01.06.17
* good python cheat sheet: https://github.com/wilfredinni/python-cheatsheet/blob/master/python_cheat_sheet.ipynb
* finish all my task and the webapplication now works
* Bruno reviced what I've done in the two weeks and said that it was a lot and that he is proud of me
* we visted Walldorf today and had lunch with Andre
* there was a lot to discover in Walldorf
* we visited the Inspiration Pavillion in Wdf 1, it was very cool
* lastly we dicided that I could try to do one more task before I leave
* trying to create a JSON file
* want to work with "Postman" -> methods 'GET' and 'POST'
* good page for learning things: https://www.w3schools.com/
