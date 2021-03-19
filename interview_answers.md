# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
Sharing state down a component tree.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
actions: Actions provide the information for the store. It treats that info as a payload from the application based of the type of action that is performed.
reducers: Reducers detect changes in the state, reducers recieve and action and use it and the previous state to create the next state.
store: store is a container that store the entire state of an app into an immutable object tree

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
Thunk lets you call action creators that return functions instead of action objects. It then uses dispatch from store send actions inside the function after async operations are set up.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
I really enjoyed async redux. Being able to access large apis and display the specific values that I want is fascinating to me.