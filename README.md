# SpaceX Mission Control - Running Instructions
##### By: Dawson Jung, Everett Yee
## ⚠ Windows Only (for now) ⚠
## ⚠ Known scaling issues with screens that are not 1920x1080 ⚠
### Method 1
#### Clone the repository using: ```git clone https://github.com/eyee19/SpaceXMissionControl```
#### In GIT Bash, navigate to the SpaceXMissionControl directory, and run using: ```./run.sh```
###### Window may appear small when opening application, maximize window as needed
### Method 1.1
### Manually in command line from within dist folder
#### Change to SpaceXMissionControl directory, and then do:  ```cd dist```
#### Run using: ```java -jar SpaceXMissionControl.jar```
###### Window may appear small when opening application, maximize window as needed

---

# Project Description

This application implements several APIs into one dashboard application to aid SpaceX fans in following a SpaceX rocket launch.
# Application Features
### Webcast
View the latest webcast on the SpaceX YouTube channel.

### Twitter/Reddit
View the latest tweets from SpaceX, as well as a Reddit stream of the launch thread.

### Launch Information
View information about the latest launch, including things like launch date, flight number, and launch details.

### Linkbot
A very simple chatbot that will provide you with any links you need related the the launch. It can provide you with:
- A link to the mission patch
- A link to the launch campaign thread on Reddit
- A link to the official launch day thread on Reddit
- A link to the media thread on Reddit
- A link to the official press kit for the launch
- A link to an article on the launch
- A link to the YouTube stream
- A link to the current weather at launch locations (Canaveral, SLC-40, Vandenberg, LC-4E, Kennedy, LC-39A)
- A link to the launch manifest

It will also copy whichever link you choose to your clipboard!

---

## Application Instructions
#### 1. View the latest launch webcast (webcast link will automatically update for future launches).

![](https://github.com/eyee19/SpaceXMissionControl/blob/master/webcast.png "Webcast")

#### 2. View all tweets from the SpaceX Twitter account.

![](https://github.com/eyee19/SpaceXMissionControl/blob/master/twitter.png "Twitter")

#### 3. View the latest launch details (details will automatically update for future launches).

![](https://github.com/eyee19/SpaceXMissionControl/blob/master/details.png "Details")

#### 4. View a live Reddit stream of the launch thread.

![](https://github.com/eyee19/SpaceXMissionControl/blob/master/reddit.png "Reddit")

#### 5. Mention a keyword to Linkbot and it will provide you with a link in the right-side box, and will also copy the link to your clipboard. Type keyword 'help' to see all available keywords.

![](https://github.com/eyee19/SpaceXMissionControl/blob/master/linkbot.png "Linkbot")

---

### Resources: 

SpaceX API<br>
https://github.com/r-spacex/SpaceX-API<br>
Scene Builder<br>
http://gluonhq.com/products/scene-builder/<br>
http://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html<br>
JavaFX<br>
http://www.oracle.com/technetwork/java/javafx/overview/index.html<br>
Twitter4J<br>
http://twitter4j.org/en/index.html<br>
GSON<br>
https://github.com/google/gson<br>
NetBeans IDE<br>
https://netbeans.org/<br>
