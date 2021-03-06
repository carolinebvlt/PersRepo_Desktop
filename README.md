![Logo BePlug](assets/img/myLogo.png)
# ```Be</plug>```
This application aims to optimize communication and information sharing at BeCode.

*Created with NodeJS*
_____
## Contents :

* ### [Features](#features)
  * [Registration](#registration)
  * [Home](#home)
  * [Notifications](#notifications)
  * [Calendar](#calendar)
  * [Links](#links)
  * [Forums](#forums)
  * [Chatbox](#chatbox)
  * [PrivateMsgs](#privateMsgs)
  * [Users](#users)

* ### [DataBase](#database)

* ### [Sessions](#sessions)
_____

### Features

* #### Registration
  * user = {firstName:" ", lastName: " ", pseudo:" ", pass:" ", email:" ", startup:" "}
  * ```addUser()```
  * ```updateUser()```
  * ```deleteUser()```

* #### Home
  Summaries of the last updates :
  * notifications
  * calendar
  * links
  * forums

* #### Notifications
  Short and important messages/notices sent to everybody
  * logs + AJAX for "more..."
  * notification = {exp:" ", title:" ", msg:" ", date:" "}
  * ```sendNotif()```

* #### Calendar
  * event = {date:" ", hour:" ", title:" ", description:" ", exp:" "}
  * display :
    - day
    - week
    - month
  * ```addEvent()```
  * ```updateEvent()```
  * ```deleteEvent()```


* #### Links
  Useful links :
  * link = {exp: " ", date:" ", category:" ", description:" ", link:" "}
  * categories :
    - articles
    - documentation (by language?)
    - tools
  * ```addCategory()```
  * ```addLink()```
  * ```updateLink()```
  * ```deleteLink()```

* #### Forums
  Discussions, mutual help, ...
  * message = {exp:" ", date:" ", category:" ", topic:" ", msg:" "}
  * ```addCategory()```
  * ```addTopic()```
  * ```addMsg()```
  * ```updateMsg()```
  * ```deleteMsg()```

* #### Chatbox
  * message = {exp:" ", msg:" ", date:" "}
  * ```sendMsg()```

* #### PrivateMsgs
  * message = {exp:" ", rec:" ", msg:" ", date:" "}
  * ```sendMsg()```

* #### Users
  * users ON
  * all the users (by startup?)
_____

### DataBase
* users.json
* usersON.json
* notifications.json
* calendar.json
* links.json
* forums.json
* chatbox.json
* privateMsgs.json

_____

### Sessions
