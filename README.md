## I. Core Knowledge:

- Debugging Redux in React Native:
  See post in video 160

## II. Module Notes:

1.  3rd Commit: Setting Up Redux

        - See App.js:
            +, rootReducers, store, Provider
        - ./store/reducers/meals.js

2.  4th Commit: Getting data from Store to Screen and Header: - See MealDetailScreen.js:

        - Get data from Store to Screen:
            +, useSelector like in Web

        - Get data from Store to Header:
            +, Send params from screen to header
            see useEffect in MealDetailScreen
            => this way might have some delay due to need to fully load
            the screen then the header will show up

            +, Alternative way:  Send params from another screen before
            directed to this screen

3.  5th Commit: Dispatching Actions to Store

        - useDispatch(), same as React.js

        - Check Store:
            +, store/actions/mealsAction.js
            +, store/reducers/meals.js

        - Check Dispatch Action:
            +, MealDetailScreen
            +, See useDispatch()

        => Adding and removing favorite items in store
        Stopped at video 155, skipped video 156 - 162

        NOTE: Font loading and icon loading error that havent fixed

## III. Packages:

    - $ npm install --save expo-font
    - $ npm install --save expo-app-loading
    - $ npm install --save react-navigation@latest
    - $ expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
    - $ npm install react-navigation-stack @react-native-community/masked-view react-native-safe-area-context
    - $ npm install --save react-navigation-tabs
    - $ npm install --save react-navigation-drawer
    - $ npm install --save react-navigation-header-buttons
    - $ npm install --save react-navigation-material-bottom-tabs
    - $ npm install --save react-navigation-stack
    - $ npm install --save react-navigation-tabs
    - $ npm install --save redux react-redux

    IMPORTANT: Run the commands down below before start anything
    - $ sudo npm --force update

## IV. Resources:
