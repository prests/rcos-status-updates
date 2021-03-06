#### Status Report

This semester I expanded my horizons, and I went into a field of Computer Science that I've never explored before. I piloted the development of RushMe's Android app. While I had plenty of experience coding in java, I did not have any experience programming in java for an app. There was a big learning curve for me and I had to watch a lot of videos and read through a lot of documentation to start going. I started using Android Studio which was a new IDE that was intimidating at first. Android Studio allows you not only to code java classes and methods to perform certain tasks but to edit XML files on the fly which are the setup for all the pages seen in an Android app. XML files are similar structure to that of HTML files but customization can be done right on the file and not need something like CSS.

When I first started I primarily made static apps that didn't do much other than add things together and print on a screen. This was just so I learned how to link an element in an XML file to a variable in a java file. With this link I could make edits in the java file and then have them appear on the app's XML page.

The next step was to learn about XML styling with Android Studio's built in editor. In the editor I learned about different views and what they were used for. I learned about setting up constraints on elements so they will loard where you wants and not just on top of one another. I also learned about setting up ID's so it's easy to get XML values to java quickly. 

Then I started to move away from the static apps that I once had and start going back to more Object Oriented Programming which I was used to. With a little bit of a grasp on Android Studio I started creating classes that would house data to be displayed dynamically. I changed all the buttons for each fraternity to be displayed from data assigned by classes that I created and not hard coded in the XML file. Now the app was starting to look more like an app.

Towards the end of the semester I started to work with passing information between pages. Each page in Android is called an activity and the way data is sent is with intent. Intents are objects that store primitive datatypes and can exchange them to a directed activity. This worked well because I wouldn't have to make 29 fraternity profile pages I could just have 1 page and just pass data to that page. The problem that arose with this was that pictures play a key role in our app and sending that bytes of the picture between intents is very inefficient and caused strange results, this led me to where I am now.

With the close of this semester I am working with a package called glide that is used for taking images and loading them. Glide also applies edits to images if you want them to have certain shapes and sizes. I am currently working with glide to try and learn about it so I can implement this into the app. Once this is done I will start making calls to our AWS S3 bucket so we can get real images and real data for fraternities.

This was my first semester of RCOS and I plan to work on the RushMe app over break and during next spring. It's a lot of fun having a class where you can pick a problem you want and just work on it with no need to match teaching styles and extra documentation for teachers. I look forward to doing this more in the future.

#### Technologies Learned
+ Android Studio UI
+ Android Studio XML Editor
+ Android Studio Activities
+ Android Studio Intents

#### Are you going to continue with the project?

Yes
