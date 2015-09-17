# Using-different-Android-Libraries
Basic Rule of the game :

Use Retrofit if you are communicating with a Web service. Use the peer library Picasso if you are downloading images. Use OkHTTP if you need to do HTTP operations that lie outside of Retrofit/Picasso.

Volley roughly competes with Retrofit + Picasso. On the plus side, it is one library. On the minus side, it is one undocumented, unsupported, "throw the code over the wall and do an I|O presentation on it" library.
source: http://stackoverflow.com/questions/16902716/comparison-of-android-networking-libraries-okhttp-retrofit-volley

1) OkHttp:
http://square.github.io/okhttp/

http://www.vogella.com/tutorials/JavaLibrary-OkHttp/article.html

1.1) Retrofit:
http://themakeinfo.com/2015/04/retrofit-android-tutorial/

2) Picasso:
https://github.com/square/picasso

http://code.tutsplus.com/tutorials/android-sdk-working-with-picasso--cms-22149


2) Stetho : Facebook.
Usage : Stetho is a debug bridge for Android applications, enabling the powerful Chrome Developer Tools and much more. More useful if used with okHttp. okHttp allows easy integration. 
Website: https://code.facebook.com/projects/850857854981379

Basic Tutorial.
http://code.tutsplus.com/tutorials/debugging-android-apps-with-facebooks-stetho--cms-24205
