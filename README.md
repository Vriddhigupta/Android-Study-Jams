NewsBit

<b> Problem Statement: </b>

Over the period of time, the importance of reading newspaper and knowing about current affairs are becoming important and sometimes your local newspaper shop forgets to deliver newspaper at your doorstep. Technology plays a vital role in day-to-day life activities which in turn made great changes in many work fields and out of them Mobile Application is one of the major developments. Mobile Application can be used effectively as a newspaper. Hnece we have come up with this idea of creating a news application wherein the user can read all latest news and also save any news article for future reference.

<b> Proposed Solution : </b>

This project proposes a “NewsBit” to keep the user updated with latest news and provide a feature of bookmarking important articles for future read. Other features include registering and logging into the application. It accepts user data allowing them to register to the application. This project takes the help of a News API to fetch and display the latest news. Users have the option of bookmarking their favourite news which is done by using Room database. The list of bookmarked articles is unique to different users. Firebase Authentication is used for register/signin feature. The project's scope is to extend it to allow users to like and comment on news articles.

<img width="559" alt="sampleimages" src="https://user-images.githubusercontent.com/18289261/142846646-a6858641-ad88-43aa-b8bb-b690fd7126f1.png">
    	  	
<b> Functionality & Concepts used : </b>

- The App has a very simple and interactive interface which helps the users to register and make an account, login into their accounts, read latest news about country and world, bookmark relevant news articles. Following are few android concepts used to achieve the functionalities in app : 
- Constraint Layout and Relative Layout : Most of the activities in the app uses a flexible constraint layout or a Relative Layout, which is easy to handle for different screen sizes and using relative layout eases the work of positioning views on the screen. 
- Simple & Easy Views Design and Navigation Componenet : Use of familiar audience EditText with hints and interactive buttons made it easier for users to register or sign in without providing any detailed instructions pages. Apps also uses App Navigation to switch between different screens. Hence a Navigation graph is created to navigate between screens.
- RecyclerView : To present the list of latest news and bookmarked articles we used the efficient recyclerview.
- News API : We are also using the News API to fetch news. Here is the link for the same. [News API](https://newsapi.org/)
- Retrofit and Moshi : They are used to fetch the data using the API and parsing it to object-oriented notion.
- Firebase Authentication : It is used to provide authentication features that is Registration and Login.
- LiveData & Room Database : We are also using LiveData to continuously update news on real-time basis. Room database is used to store the bookmarked articles in the app on the client's device.
- Coroutines : We have used Coroutines in two places : 

<b> Application Link & Future Scope : </b>

You can access the app : [YOUR APP LINK HERE](either Github link or Google Play store link of published app or .apk file).

We plan to integrate multiple news API and fetch news from different news channels and newspapers. We aim to implement a feature allowing the user to like and share their views on a news article.
