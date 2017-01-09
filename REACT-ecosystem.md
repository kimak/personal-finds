
# Frond Side

## COMMON

- Performance  
    - [Fiber](http://isfiberreadyyet.com)
    - [Inferno](https://github.com/infernojs/inferno)
    - [Preact](https://github.com/developit/preact)

- Tests
    - [Jest](https://facebook.github.io/jest/blog/2016/07/27/jest-14.html)

---


## WEB

- Teaching

    - [11 Lessons Learned: Dec 13, 2016](https://hackernoon.com/11-lessons-learned-as-a-react-contractor-f515cd0491cf#.hqreilwxf)

- Performance 
    - List
        - [ReactVirtualized](https://github.com/bvaughn/react-virtualized)

    - Data Visualisation
        - [Victory](https://github.com/FormidableLabs/victory)

---

## NATIVE

- LEARNING
    - Showcase [Apps](https://facebook.github.io/react-native/showcase.html)
    - React presentation [Spectacle](https://github.com/FormidableLabs/spectacle)
    - Course [React Native Express](http://www.reactnativeexpress.com )
    
    - [Flexbox](https://facebook.github.io/react-native/docs/flexbox.html)
    
        > Flexbox works the same way in React Native as it does in CSS on the web, with a few exceptions.
 The defaults are different:

        - flexDirection defaulting to column instead of row 
        - alignItems defaulting to stretch instead of flex-start
        - the flex parameter only supports a single number.
    
    - Native Modules

        - [IOS](https://facebook.github.io/react-native/docs/native-modules-ios.html)
        - [Android](https://facebook.github.io/react-native/docs/native-modules-ios.html)
            - [Building custom Android module](https://hashnode.com/post/building-the-custom-android-module-for-react-native-ciqcba1hj00phaj53f9u4laww)
            - Out of Memory Exceptions
                > React Native Android is based on Fresco for loading and displaying images. Downsampling is disabled for PNGs in React Native, since it is still experimental. So, we have started using JPG images whenever possible.

    - Animation
        - Slow page transition

            > We started scheduling the animation using the InteractionManager. While making the transition, we load lesser content and render the remaining content, once the transition is complete. It helped us provide a smoother experience to our users.
            - [Interaction Manager](https://facebook.github.io/react-native/docs/interactionmanager.html)
            
        - [Offload JS thread, better performance](https://productpains.com/post/react-native/offload-some-animations-from-js-thread-for-better-perf)

- LINKS
    
    - Performance: [a year experience](https://hashnode.com/post/what-we-learned-after-using-react-native-for-a-year-civdr8zv6058l3853wqud7hqp)
        - [ListView](https://facebook.github.io/react-native/docs/using-a-listview.html)
            - [react-native-sglistview](https://github.com/sghiassy/react-native-sglistview)
            - [react-native-table-view](https://github.com/aksonov/react-native-tableview)
        - Android
            - [Profiling Android UI with Systrace](https://facebook.github.io/react-native/docs/android-ui-performance.html)
    - IOS
        - [CocoaPods](https://cocoapods.org/pods/React)
    
    - Animation

        - [GLReact](https://github.com/ProjectSeptemberInc/gl-react)

    - Debugging
        - [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
        - [Reactotron](https://github.com/reactotron/reactotron)

    - Deployment
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

    - React Native updates
        - ProductPains [Features discussion](https://productpains.com/product/react-native)
        - [react-native upgrade](https://facebook.github.io/react-native/docs/upgrading.html)

- FAQ

    - How to manage View and Keyboard with TextField ?
        - [KeyboardAvoidingView](https://facebook.github.io/react-native/docs/keyboardavoidingview.html)

    - Could i code background tasks in javascript with ReactNative ?
        > No.

        > Unfortunately, these things can't be done with Javascript alone. So, you need to explore the bridges provided by React Native. Swift for iOS, and Java for Android; for the development of background tasks.

# Back Side

- Server Side rendering
    - [Hypernova](https://github.com/airbnb/hypernova)
    - [Next](https://github.com/zeit/next.js)

- GraphQl

    - [HelloGraphQl](https://github.com/exponentjs/hello-graphql)
    - [GraphQL as a service](https://graph.cool)

---

Other resources:

https://github.com/markerikson/react-redux-links
