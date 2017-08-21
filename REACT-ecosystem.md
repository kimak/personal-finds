
# Frond Side

## COMMON

- Performance  
    - [Fiber](http://isfiberreadyyet.com)
    - [React under the hood](https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/)
    - [Inferno](https://github.com/infernojs/inferno)
    - [Preact](https://github.com/developit/preact)

- Architecture
    - [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
    - [Import NODE_PATH](https://twitter.com/dan_abramov/status/867125756710850560)
    - [React pattern](http://reactpatterns.com/#render-callback)

- Tests
    - [Jest](https://facebook.github.io/jest/blog/2016/07/27/jest-14.html)

---


## WEB

- Teaching

    - [React faq](https://github.com/timarney/react-faq#start)
    - [11 Lessons Learned: Dec 13, 2016](https://hackernoon.com/11-lessons-learned-as-a-react-contractor-f515cd0491cf#.hqreilwxf)
    [Intro to React Workshop](https://vimeo.com/213710634)
    [Timeline for React](https://daveceddia.com/timeline-for-learning-react/?utm_campaign=welcome&utm_medium=email)
- Style
    - [Styled component](https://medium.com/styled-components/announcing-primitives-support-for-truly-universal-component-systems-5772c7d14bc7)
    - [Polished](https://github.com/styled-components/polished)
- Animation
    - [React Transition Group](https://github.com/reactjs/react-transition-group)
    - [Tween + transition group](https://medium.com/appifycanada/animations-with-reacttransitiongroup-4972ad7da286)
- Performance 
    - [React Loadable](https://github.com/thejameskyle/react-loadable)
    - [React perimeter](https://github.com/aweary/react-perimeter)
    - List
        - [ReactVirtualized](https://github.com/bvaughn/react-virtualized)

    - Data Visualisation
        - [Victory](https://github.com/FormidableLabs/victory)
- Doc
    - [Styleguidist](https://github.com/styleguidist/react-styleguidist)
    - [Snapguidist](https://github.com/styleguidist/snapguidist)
    - [JS.coach](https://js.coach/)
    - [Native directory](https://www.native.directory/)
---

## NATIVE

- LEARNING
    - Showcase [Apps](https://facebook.github.io/react-native/showcase.html)
    - Ecosystem
        - React Word [Redocx](https://github.com/nitin42/redocx)
        - React presentation [Spectacle](https://github.com/FormidableLabs/spectacle)
        - React for CLI [React Ink](https://github.com/vadimdemedes/ink)
    - Course [React Native Express](http://www.reactnativeexpress.com )
    - Turing [React Native Intro](http://frontend.turing.io/lessons/react-native-intro.html)
    - Animation
        - [react-native-animation-book](http://browniefed.com/react-native-animation-book)
        - [react-native-animations-revisited-part I](https://blog.callstack.io/react-native-animations-revisited-part-i-783143d4884#.2s1sntb93)
        - [react-native-animations-revisited-part II](https://blog.callstack.io/react-native-animations-revisited-part-ii-8314a97162b0#.h7ob0xx2h)
        - [React Flight](http://www.react-flight.io/)
    
    - [Flexbox](https://facebook.github.io/react-native/docs/flexbox.html)
    
        > Flexbox works the same way in React Native as it does in CSS on the web, with a few exceptions.
 The defaults are different:

        - flexDirection defaulting to column instead of row 
        - alignItems defaulting to stretch instead of flex-start
        - the flex parameter only supports a single number.

    - Icon et Splashscreen
        - [How to Add a Splash Screen to a React Native App (iOS and Android)](https://medium.com/handlebar-labs/how-to-add-a-splash-screen-to-a-react-native-app-ios-and-android-30a3cec835ae)
    
    - Native Modules

        - [IOS](https://facebook.github.io/react-native/docs/native-modules-ios.html)
        - [Android](https://facebook.github.io/react-native/docs/native-modules-ios.html)
            - [Building custom Android module](https://hashnode.com/post/building-the-custom-android-module-for-react-native-ciqcba1hj00phaj53f9u4laww)
            - Out of Memory Exceptions
                > React Native Android is based on Fresco for loading and displaying images. Downsampling is disabled for PNGs in React Native, since it is still experimental. So, we have started using JPG images whenever possible.

    - Animation
        - useNativeDriver
            > [Using Native Driver](https://facebook.github.io/react-native/blog/2017/02/14/using-native-driver-for-animated.html)
        - Slow page transition

            > We started scheduling the animation using the InteractionManager. While making the transition, we load lesser content and render the remaining content, once the transition is complete. It helped us provide a smoother experience to our users.
            - [Interaction Manager](https://facebook.github.io/react-native/docs/interactionmanager.html)
            
        - [Offload JS thread, better performance](https://productpains.com/post/react-native/offload-some-animations-from-js-thread-for-better-perf)

- LINKS
    
    - Performance: 
        - [a year experience](https://hashnode.com/post/what-we-learned-after-using-react-native-for-a-year-civdr8zv6058l3853wqud7hqp)
        - [ListView](https://facebook.github.io/react-native/docs/using-a-listview.html)
            - [react-native-sglistview](https://github.com/sghiassy/react-native-sglistview)
            - [react-native-table-view](https://github.com/aksonov/react-native-tableview)
        - [Swift vs ReactNative](https://medium.com/the-react-native-log/comparing-the-performance-between-native-ios-swift-and-react-native-7b5490d363e2)
        - Android
            - [Profiling Android UI with Systrace](https://facebook.github.io/react-native/docs/android-ui-performance.html)
    - IOS
        - [CocoaPods](https://cocoapods.org/pods/React)

    - Starter
        - [Create React Native App](https://facebook.github.io/react-native/blog/2017/03/13/introducing-create-react-native-app.html)
    
    - Animation

        - [GLReact](https://github.com/ProjectSeptemberInc/gl-react)
        - [Lottie](https://medium.com/airbnb-engineering/introducing-lottie-4ff4a0afac0e#.3e16r9e53)

    - Debugging
        - [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
        - [Reactotron](https://github.com/reactotron/reactotron)

    - Deployment
      - IOS deployment: [Deploy IOS part 1](https://medium.com/react-native-development/deploying-a-react-native-app-for-ios-pt-1-a79dfd15acb8)
      - Immediate deployment 
        > Using Codepush or AppHub, you can easily push instantaneous updates to the users' devices.
      
        - [React Native CodePush](https://github.com/Microsoft/react-native-code-push)
        - [React Native AppHub](https://apphub.io)

      - TestFlight 
        > Send TestFlight invites to beta testers automatically
            
        - [Boardingbot](https://www.producthunt.com/tech/boardingbot)
        
      - [FastLane](https://fastlane.tools/)
          > Fastlane is the tool to release your iOS and Android app 🚀

      - [bitrise](https://www.bitrise.io/)
          > Continuous integration and delivry mobile
It handles all tedious tasks, like generating screenshots, dealing with code signing, and releasing your application.

      - [Hokeyapp](https://hockeyapp.net/#s)
      - [Appetize.io](https://appetize.io/)

    - React Native updates
        - ProductPains [Features discussion](https://productpains.com/product/react-native)
        - [react-native upgrade](https://facebook.github.io/react-native/docs/upgrading.html)


    - Open source App
        - [GitterMobile](https://github.com/JSSolutions/GitterMobile)
        - Uber Chat [Mattermost](https://github.com/mattermost/mattermost-mobile)
- FAQ

    - How to manage View and Keyboard with TextField ?
        - [KeyboardAvoidingView](https://facebook.github.io/react-native/docs/keyboardavoidingview.html)

    - Could i code background tasks in javascript with ReactNative ?
        > No.

        > Unfortunately, these things can't be done with Javascript alone. So, you need to explore the bridges provided by React Native. Swift for iOS, and Java for Android; for the development of background tasks.

# Back Side

- Server Side rendering
    - [React Snapshot](https://github.com/geelen/react-snapshot)
    - [Razzle](https://github.com/jaredpalmer/razzle/blob/master/README.md#creating-an-app)
    - [Hypernova](https://github.com/airbnb/hypernova)
    - [Next](https://github.com/zeit/next.js)

- GraphQl

    - [HelloGraphQl](https://github.com/exponentjs/hello-graphql)
    - [GraphQL as a service](https://graph.cool)

---

Other resources:

https://github.com/markerikson/react-redux-links
