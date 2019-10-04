- [x] Why would you use class component over function components (removing hooks from the question)?

    You end up with less code and they are easier to test and read. 

- [x] Name three lifecycle methods and their purposes.

    -render(): Renders component to the ui and is needed on all methods within class components.
    -componentDidMount(): You call this as soon as the component is ready to be mounted. Usually used when you are ready to call your api. 
    -componentDidUpdate(): Is invoked when updating happens. Used in response for when prop or state is changed in the DOM.

- [x] What is the purpose of a custom hook?

    Allows you to extract component logic into a reusable function.

- [x] Why is it important to test our apps?

    Makes sure that bugs and usability issues are almost nonexsistent. Improves app ratings and overall customer statisfaction.