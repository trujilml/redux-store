Your Task
In this module, you learned how to manage global state using React’s Context API. The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open-source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application, and it’s very likely that you’ll encounter it on the job.

Your challenge this week is to refactor the e-commerce platform from the module project so that it uses Redux (Links to an external site.). You won’t need to make sweeping changes to the code, but you will need to read through the Redux documentation on your own to find the information you need. We’ve provided some guidelines to point you in the right direction in the Getting Started section below.

User Story
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem

Acceptance Criteria
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API

Getting Started
To add Redux to your application, read through the Redux basic tutorial (Links to an external site.) for instructions. Note that the docs will refer to additional packages that you'll need in order to complete this implementation.

IMPORTANT
Make sure you look through all of the documentation because there are newer methods that can make these tools much easier to implement. Keep in mind that React has gone through several iterations; as such, some React-and-Redux tutorials will assume you aren't using Hooks.
