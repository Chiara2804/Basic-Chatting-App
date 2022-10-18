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
<img src="README_imgs/login.png"/>

### Sign Up
<img src="README_imgs/signup.png"/>

### Realtime Database


### Chat List
<img src="README_imgs/chat_list.png"/>

### Chat
<img src="README_imgs/chat.png"/>
