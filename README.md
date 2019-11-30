# Memory Stash Alzheimer’s Aid - Android App for the 2019 IEEEmadC Mobile Application Development Contest

Alzheimer's is the most common cause of dementia, a general term for memory loss and other cognitive abilities serious enough to interfere with daily life. Our idea is to develop an application (Memory Stash Alzheimer Aid) that helps them in their daily routine tasks, focusing on the problems they face in every stage.

![pic1](https://user-images.githubusercontent.com/38161609/69905184-14b9c400-13d2-11ea-8f8f-bbdc34631f25.jpg)

There are 7 stages of Alzheimer disease each stage has its own symptoms. As the stage increases the condition of patient become worse over time. In the initial 4 to  5 stages, patient will face the memory loss issue, inability to solve the cognitive problems ,inability to respond the environment and loss of thinking and reasoning power. In 6 and 7 stage, patient will enter the most severe stage (i.e. dementia) where patient will be unable to perform daily routine tasks independently (i.e. drink water, eat food, take pills, etc. ). They will be fully dependent on their loved ones  or care taker.

# Features

The features which we have incorporated are:
- Take Emergency Details
- Patient can analyze the stage of disease
- Add People for recognition
- Speech to Text conversion for recognizing people (Through AI)
- Set Food, Water, and Custom Reminders
- Text To Speech conversion to alert patients for specific reminders (Through AI)
- Emergency Message And Call (sent current location)
- Mind Games for maintaining the memory, processing power or analyzing the things properly
- Reading Portion (Novels, Motivational Stories, News, Sports, Technologies, Health Tips)
- Chatbot for interaction (using AI)
- Care taker module (contact through number in case of Emergency). 

# Future Work
- Image Recognition to identify people (using AI) --- In progress
- Switch between Day / Night Mode 
- Auto back up data functionality
- Suggestion According to user Reading Interest 

# Permissions
1.	INTERNET
2.	ACCESS_FINE_LOCATION 
3.	ACCESS_COARSE_LOCATION 
4.	RECEIVE_BOOT_COMPLETED
5.	FOREGROUND_SERVICE
6.	RECEIVE_BOOT_COMPLETED
7.	WAKE_LOC

# Dependencies
//Location
- implementation 'com.google.android.gms:play-services-location:11.2.0' 

//Room persistent
- implementation 'android.arch.persistence.room:runtime:1.1.1'
- annotationProcessor 'android.arch.persistence.room:compiler:1.1.1'
- testImplementation 'android.arch.persistence.room:testing:1.1.1'

  //tensor flow
- implementation 'org.tensorflow:tensorflow-android:+'

//Chat View
- implementation 'com.github.bassaer:chatmessageview:1.8.6'


# Graphics
![pic2](https://user-images.githubusercontent.com/38161609/69905272-f6a09380-13d2-11ea-82b1-e26edd2e1296.jpg)
![pic3](https://user-images.githubusercontent.com/38161609/69905274-fb654780-13d2-11ea-8409-ee0e2277e33b.jpg)
![pic4](https://user-images.githubusercontent.com/38161609/69905276-fdc7a180-13d2-11ea-9cfb-9fc3bc574a35.jpg)

![pic5](https://user-images.githubusercontent.com/38161609/69905296-38c9d500-13d3-11ea-958f-43f3ac72d575.jpg)
![pic6](https://user-images.githubusercontent.com/38161609/69905294-38313e80-13d3-11ea-855c-b6b9bc40bbcd.jpg)
![pic7](https://user-images.githubusercontent.com/38161609/69905297-3a939880-13d3-11ea-843a-3252aa7e912b.jpg)

# The coderBoost++ Team
Memory Stash Alzheimer’s Aid is the collaborative effort of the members of coderBoost++ Bhagia Sheri [bhagiasheri24@gmail.com](url) and PoojaKumari11228 [poojakumari11228@gmail.com](url). We used to analyze real world problems and solve them through software. Therefore, after analyzing the problems faced by the Alzheimer’s patients we came up with an idea to make mobile app for them and worked as developer and designer as well.

# Note
We have uploaded the same format file in the repository named IEEEmadC ReadMe File [IEEEmadC ReadMe.docx](url).
