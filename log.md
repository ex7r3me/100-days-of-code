# 100 Days Of Code - Log

### Day 1: August 12, 2018
**Today's Progress**: Track user changes with update timestamp using hook. add queue manager for upcoming features. 

**Thoughts:** I had a hard time setting environment again for this project as I was moving to vscode from webstorm. changes was simple but after days they make features.

**Link to work:** [fooName](https://github.com/ex7r3me/fooname)

### Day 2: August 13, 2018
**Today's Progress**: Start android (react-native) app development using ignite. apply for twitter developer account. add native base component and tried to add twitter signing button

**Thoughts:** as I used ignite for another project it was straight forward to make it work, but there was problem with gradle of sign in button and I may need to write or modify some library code tomorrow.

**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)

### Day 3: August 14, 2018
**Today's Progress**: Tried 2 libraries for twitter login and there was no luck. I've found another from formidable labs that I'll try tomorrow.

**Thoughts:** I need to read more in depth about react native library linking and project structure. I've read ignite documentation but I feel my fundamental knowledge on react native is not enough. I like to try basic things without library then understand what it do when I use it. it can reduce abstraction leak too.

**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)

### Day 4: August 15, 2018
**Today's Progress**: Tried appAuth, faced strange error and tried 3 versions of it. I may fallback to auth0

**Thoughts:** I'm not happy that there's nothing to commit. the example of appAuth seems to work (didn't had time to check the twitter oauth). as I go forward I learn more about react native.

**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)

### Day 5: August 16, 2018
**Today's Progress**: Added Auth0 and it works, it's somehow a proof of concept but now we have a working twitter authentication. 

**Thoughts:** Today I also flashed an old tablet to test builds on it and make the workflow faster. it was fun and made me happy that there's more memmory for IDE and build server :D. Auth0 documentations and samples are very good and I was up and running with not much hassle. still not sure about this solution and the user experience but going with it for the MVP and complete other parts of app and may update login process later.

**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)

### Day 6: August 17, 2018
**Today's Progress**: Added new screen and showing JSON data returned from Auth0

**Thoughts:** I've learned about react navigation and tried to understand it instead of just using. I think it's better for learning and reduce further problems
**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)

### Day 7: August 19, 2018
**Today's Progress**: Learned more about Auth0 and Deep linking in android, tried deep linking and add user without using third party and only browser. 

**Thoughts:** I'm a little confused about authentication flow, cause I need to store twitter credentials in the backend while able to login using mobile app. I thought I need a login with twitter button or Auth0. but now I think I may only need to open the backend api in a webview and on the callback redirect a session to app. I'll read and plan for it tomorrow.
**Link to work:** [fooName-mobile](https://github.com/ex7r3me/fooname-mobile)