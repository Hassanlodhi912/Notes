 if People is doubting how far you can go,go so far that you can't hear them anymore
1  Hello World App		 (Done)
2. Simple Counter		 (Done)
3. Temperature Control App	 (In Progress)
4. Search Filter		 (Done)
5. Basic Registration Form 	 (Done)
6. React Quiz App		 (Done)
8. User Login app using Auth0    (In Progress)
9. Todo List			 (Done)
10. Gym Website 		 (Done)  
11. Simple Contact List		 (In Progress)
12. Recipe App With React js	 (In Progress)
13. Shopping list app		 (Not Started)
14. Weather App in NodeJS 	 (Not Started)
15. PORTFOLIO			 (In Progress)
16. Random Quote Generator 	 (Done) 
18. Hangman Game in React	 (Not Started)
19. Instagram Clone		 (Not Started)
20. Chat App 			 (In Progress)
21. COVID-19 Tracker		 (Not Started)
22. Slack Clone			 (Not Started)
23. Photo Gallery App 		 (Not Started)
24. Lyric Search App             (Not Started)
25. Budget Management App	 (Not Started)
26. Build an Expense Tracker	 (Not Started)
27. Building Tetris in React	 (Not Started)
28. GitHub Jobs React App	 (Not Started)
29. YouTube Clone		 (Not Started)
30. Voice Assistant App 	 (Not Started)
-----------------------------------------------------------------------------------------------------

GitHub:

1 git config --global user.name hassan				    //set the name 
2 git config --global user.email "muhammadhassanlodhi123@gmail.com" //set the email
3 touch .gitignore 						    // make a new file
4 git init						            // To create a blank repository 
5 git add . 							    // File ko staging area me move krti hain
6 git commit -m"initial commit"					    // Agr Koi Commit likhna hon
7 git status							    // status check krti hain
8 git remote add origin git@github.com:Hassanlod/Search-Filter.git  //add a link takey jo bh push karen wo is repositry me jaye
9 git push origin master					    // data yaha se push hota hain
 
///////// agr ssh generate na hon////////////////////
agr ssh key generate nh hain gooole p git doc me ja k copy kare apni email dal kr   paste kare git bash me phr enter  yes enter enter
path ko copy karo c user
 cat (path jo copy kia)
ek ssh key ajayegi is ko githb p past krna hain add ssh key krna hain  ph r is k bad step 9


 ////////// wapis push krne k liye////////
git add .
git commit -m"second commit"
git push origin master

//// agr change krna ho url////////////////
git remote set-url origin git@github.com:Hassanlodhi912/figma-shop-by-voice.git

//////////////////Agr Clone krna ho github k folder ko /////////////////////
git clone git@github.com:Hassanlodhi912/figma-shop-by-voice.git

/////////////////// agr fetch krna hon/////////////////////////
git fetch origin main:temp
git rebase tmp
/////// Agr phr bh non fast forward k error aye tu ////////////
git push --force <repositry link>

................................................................................................

React Js:

///For React App ////
npx create-react-app myapp 

////For React Redux////
npm i redux react-redux 

////For Material UI ////
npm install @mui/material @emotion/react @emotion/styled

///For Material Icon ////
npm install @mui/icons-material @mui/material @emotion/styled @emotion/react

///For React Router Dom ///
npm i react-router-dom

/////////////////////// redux Dev tool///////////////////////////
window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()

///////////////////////redux devtool refresh sahi se mujhe bhi nh pta bs kaam krpata hain kkuch ///////
cntrl + alt + shift  se  chlta hain 

/////////frame motion ///////////////
npm i framer-motion

//////// React Scrol/////////////////
npm install react-scroll
....................................................................................
Fluter:
//////////For  Creating a demo new Project ////////////////
flutter create testproject

////////For Run in Browser//////////////////
flutter run
....................................................................................................................
ReactNative:
/////////////////////////////////npx create-expo-app AwesomeProject////////////////

.........................................................................................................................................................................................
NODE.JS:
node filename.js 
.........................................................................................................................................................................................
/////Vs code shortcut////

1  cntrl + space 	 for sugestion
2 cntrl + / 		 for comment 
3 cntrl + p   		 for search between file
4 cntrl + shift + l	 for multi cursor selection
5 cntrl + d              for select
cntrl b			 for sidebar
cntl  o 		 for open file
...........................................................................................................................................

website link:

https://redux-ecomerce-app.netlify.app 
https://hassan-fitness.netlify.app
https://quizapphassan.netlify.app
https://react-redux-quote.netlify.app

.......................................................................................................................

For illustrations:

https://undraw.co/illustrations
https://drawkit.com
https://www.opendoodles.com
https://www.glazestock.com
https://blush.design
https://www.humaaans.com
...........................................................................................................................


For Picture:
https://elements.envato.com/photos
https://unsplash.com/images
https://www.freepik.com/

...................................................................................................................................... 
For Icon
https://icons8.com

...............................................................................................................................

For Redux:(Folder Structure)
1. Create folder  of store
2 In Store Create index.js file and 3 folder (action,constant,reducer) 
3 In action create file Index.js
4 In constant create file Action-Types.js
5 In reducer create file Index.js


For action-Types:
#ACTION TYPES OBJECT ///// or us k andr tamam action 


For Action :
#import 
# function {}

for Reducer:
# Create a new file of reducer
# Index.js me import Combine Reducer or jo reducer ki file createa ki hain
# new file jo import ki hian us me Action Types ko import krna hain 
Inital state create krna 
or  ek fucntion with switch 

For Indes.js File of Store
# Create Store
# Import Root Reducer

Main Index.js File me jo Chezen Add krni hain 
# import Store
# import Provide
# App Componnets ko wrap krna Provider se or ek props pass krna jo k ek store honga bs



