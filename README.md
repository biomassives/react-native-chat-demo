# react-native-chat-demo
React Native demo used while learning Redux, NavigationExperimental. Uses GiftedChat lib.

![Screencast of navigating demo app](screencast.gif?raw=true "Screencast of functionality")

Also an attempt at app structuring by app feature/content type (chatrooms, chatmessages), rather
than the usual structure by different react and redux components (actions, components, containers,
reducers). This way all of the feature functionality contained as a single module. index.js at
the root of the module (eg. chatrooms/index.js) can then act as an API interface exposing public
parts of the feature to the rest of the app.

For more detailed discussion structuring react redux apps by feature see -
* http://jaysoo.ca/2016/02/28/organizing-redux-application
* http://marmelab.com/blog/2015/12/17/react-directory-structure.html

api calls are mocked in api/mockChatApi.js with some mock delay to exercise handling
'data is fetching' state.
