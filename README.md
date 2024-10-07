Your task is to debug a sample React application using the React Developer Tools browser extension or standalone application. The application contains components with state and props, and your goal is to identify and fix any issues encountered during the debugging process.

Instructions
    Set up the sample React application provided to you. You can use a simple application with multiple components, state management, and props passing.
    Install the React Developer Tools browser extension or standalone application if you haven't already.
    Open the React Developer Tools and inspect the components tree of the sample application.
    Identify any issues such as incorrect state values, missing props, or unexpected component behavior.
    Use the tools and features provided by the React Developer Tools to diagnose and fix the issues encountered.
    Document the debugging process, including any steps taken and solutions implemented to resolve the issues.
    Verify that the application functions correctly after debugging and ensure that any identified issues have been addressed successfully.

    • First Problem: The useCallback hook lacked a dependency array, which I resolved by adding the correct dependencies to the array, ensuring proper memoization of the callback function.
    • Second Problem: The useEffect hook was imported but unused, so I removed the import to resolve the ESLint warning about unused variables.