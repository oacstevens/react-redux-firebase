<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [firebaseReducer][1]

## firebaseReducer

Main reducer for react-redux-firebase. This function is called
automatically by redux every time an action is fired. Based on which action
is called and its payload, the reducer will update redux state with relevant
changes. `firebaseReducer` is made up of multiple "slice reducers"
([outlined in reducers docs][2]) combined using
[`combineReducers`][3]
following the patterns outlined in
[the redux docs][4].

**Parameters**

-   `state` **[Object][5]** Current Firebase Redux State (state.firebase)
-   `action` **[Object][5]** Action which will modify state
    -   `action.type` **[String][6]** Type of Action being called
    -   `action.path` **[String][6]** Path of action that was dispatched
    -   `action.data` **[String][6]** Data associated with action

Returns **[Object][5]** Firebase redux state

[1]: #firebasereducer

[2]: /docs/recipes/reducers.md

[3]: https://redux.js.org/docs/api/combineReducers.html

[4]: https://redux.js.org/docs/recipes/StructuringReducers.html

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String
