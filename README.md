<img src="README_imgs/github-header-image.png" width="100%"/>

<div>
  <img src="https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white"/>  
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/>  
</div>

### Login
The Login page is connected to the Sign Up one. When in the Login page teh Sign Up button is clicked, the page changes.
``` kotlin
btnSignUp.setOnClickListener {
  val intent = Intent(this, SignUp::class.java)
  startActivity(intent)
}
```
<br>To authenticate each user, Firebase gives us a lot of methods to do it. Here, we will use e-mail and password.<br>If the Login is succesful, we jump to the Chat List page, if it is not, a message appears to notify the error.
``` kotlin
...
```
<img src="README_imgs/login.png"/>

### Sign Up
For the Sign Up we collect an extra value: the name.
``` kotlin
...
```
<br>We also need to add a node to the Database to create a new user
``` kotlin
...
```
<img src="README_imgs/signup.png"/>

### Realtime Database


### Chat List
In this part all the users are shown.
``` kotlin
... RecyclerView
```
<img src="README_imgs/chat_list.png"/>

### Chat
What is wrote in the typing box is added to the Database. Next, the sent message is added to the message list.
<br>The getItemViewType returns an integer depending on who sent the message. According to the number the function returned, the corresponding layout is decided.
``` kotlin
...
```
<img src="README_imgs/chat.png"/>
