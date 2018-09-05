# #100DaysOfCode Log - Round 1 - [ex7r3me]

The log of my #100DaysOfCode challenge. Started on [July 17, Monday, 2017].

## Log

### R1D1

Track user changes with update timestamp using hook. add queue manager for upcoming features. https://github.com/ex7r3me/fooname

### R1D2

I started android development for my hobby project.Init project using infinite red ignite. and played with twitter sign in button https://github.com/ex7r3me/fooname-mobile

### R1D3

Worked on adding twitter login button in react native. tried 2 library but no luck. I'll try the AppAuth tomorrow https://github.com/ex7r3me/fooname-mobile

### R1D4

Tried AppAuth and getting strange errors, I've learned about js server and bundling in react native https://github.com/ex7r3me/fooname-mobile

### R1D5

Integrated Auth0 in application, it was pretty straightforward and fun to work with. it's a proof of concept and in following days i'll work on other parts of the app and backend.
https://github.com/ex7r3me/fooname-mobile

###R1D6
Today I've read about react navigation for the react native and add a new screen to the app, now the Auth0 Authentication credentials show as a JSON in the new screen
https://github.com/ex7r3me/fooname-mobile

###R1D7
Added deeplink and open in browser linking in react-native. I have to read and learn more about my app architecture but first I wanna have a working version.
https://github.com/ex7r3me/fooname-mobile

###R1D8
I've upgraded react-navigation in the project and add a deep-link support to open a screen and show access token that created by loopback for the user that signed up with Twitter.
https://github.com/ex7r3me/fooname-mobile

###R1D9
Now the app remembers the access token. it saves the access token in AsyncStorage, I need to implement redux but it working for now and I'm happy that I've learned about it.
https://github.com/ex7r3me/fooname-mobile

###R1D10
I've tried redux-form in react native but it was overcomplicated and I may don't want to use redux in this project so I I've found formik and added it. now user can save his/her City ID in database
https://github.com/ex7r3me/fooname-mobile

###R1D11
I've played with react-native geolocation API, it was very smooth and easy. also added native-base's toast to the project. now I get the location and show a toast in case of error. https://github.com/ex7r3me/fooname-mobile

###R1D12
I've added an endpoint to get coordination and convert it to cityId using OpenWeather's API. also app sends lat and long to the this API endpoint. user updates automatically using hooks. https://github.com/ex7r3me/fooname-mobile

###R1D13
I've add the react-navigation's drawer to the app and a logout button to delete token and send logout request to server. react navigations looks like a hero in react-native! https://github.com/ex7r3me/fooname-mobile

###R1D14
I'm focusing on UI Improvements in the app. Today I've changed screen names in the drawer, change Header's layout (Add hamburger menu), linking icon library and make home screen buttons a little better. also, I've removed some unused libraries. https://github.com/ex7r3me/fooname-mobile

###R1D15
I've added the authentication flow (check for access token in AsyncStorage) and a logout button using custom drawer component in the react navigation. https://github.com/ex7r3me/fooname-mobile

###R1D16
Today I've tried to build an APK from source, so I changed some gradle and also I'm looking for a free database service, so I tried playing with firebase.
not yet sure about it, but I think I'll use firebase+now
https://github.com/ex7r3me/fooname-mobile

###R1D17
I wasn't satisfied with native-base components performance and design so I removed it and added material UI in the app and I want to learn fundamental react native flex. now the app looks better. https://github.com/ex7r3me/fooname-mobile

###R1D18
Today I had more server-side work, I've deployed the backend on now.sh and updated API calls in the app. I used an extra hour to fix nested deep links in react navigation
https://github.com/ex7r3me/fooname

###R1D19
Finally, I've found a free database service to run the pilot and testing the app. I tried firebase but loopback connector didn't work properly so I switched to mongo and mlab sandbox plan. https://github.com/ex7r3me/fooname

###R1D20
Today was the start of showing emoji's in the app. also loading profile on the component mount and adding a setting page to the app. https://github.com/ex7r3me/fooname-mobile

###R1D21
I have #OneSignal up and running in the app. I had to update gradle, build SDK and... to get it up and running. it's funny when I saw Icons doesn't show properly I knew it needs a `react-native link` command! https://github.com/ex7r3me/fooname-mobile

###R1D22
I've added an Emoji screen with emoji selector component but it needs work and I need to read more about react-native layouts. also, I've made API calls to local dev server in development mode https://github.com/ex7r3me/fooname-mobile

###R1D23
I've played with layouts in react native to fix a bug but I wasn't successful tonight. https://github.com/ex7r3me/fooname-mobile

###R1D24
After searching and trying 4 different emoji selector library I choose to use the first one based on emoji mart. now it's working, however, it needs some tweaks for layouts.
So now user can save custom emoji in database https://github.com/ex7r3me/fooname-mobile