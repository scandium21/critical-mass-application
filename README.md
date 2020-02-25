## Work / Project Examples

I'm one month away from completing the full stack development program at EvolveU (https://www.evolveu.ca/). There are several full stack projects I'm building to become proficient in both frontend and backend development. Below is a list of selected work:

### 1. Fitness Club Membership Website (ongoing)
  - This is my final project for the bootcamp. Work in progress. 
  - The idea comes from a friend who asked me to build a website for her local gym store. She is using Excel now to track all the data. 
  - Backend is written in Python Flask and SQLite (required by the program)  
  Github: https://github.com/scandium21/cohort3/tree/master/src/python/comp240/api 
  - Frontend is to be finished using React.

### 2. Budget Tracker - https://budget-tracker-sc.herokuapp.com/
  - This is the first full stack app I built using React + Redux + Firebase + Node.js.  
  Github: https://github.com/scandium21/budget-tracker
  - I gained a lot experience in working with React + Redux thunk, connecting frontend to backend, implementing database to persist user data and deloying on Heroku.
  - The frontend is built in React, state is managed using Redux. 
  - Backend routing is written in Node.js (not a lot).
  - Firebase is chosen as database.

### 3. Transformation Game (ongoing) - https://jmoore-code.github.io/mindFuelProject/
  - This is the bootcamp's group project. The aim of this project is to serve as a teaching tool to help students learn transformations through strategically moving triangle to its destination.
  Github: https://github.com/jmoore-code/mindFuelProject
  - Our group consists of 6 members, we don't have a group/project leader, different tasks were taken by members based on their interests. I am interested in writing game logic, thus implemented triangle rendering and its movement on the grid. I'm working on the backend now to allow user login and continuation of game.
  - The project's frontend is written in React, game graphics are done using html5 canvas.

## Inspiration

### 1. Kyle Simpson's *You don't know JS* (https://github.com/getify/You-Dont-Know-JS)

JavaScript, despite of its wide use in web development, can have "weird" behaviors at times. This is the impression I get when I first started out learning the language. I wish there could be a teacher who can explain the weird parts about JS in a clear way. Kyle's series of *You don't know JS* do that. He breaks down concepts to its fundamentals and explain them really well. I'm inspired by his approach of understanding and using a language, below are some of highlights I found specially inspirational:
- Language specification is the single source of truth, consult it for clearification when in doubt
- Whenever there's a divergence between what your brain thinks is happening, and what the computer does, that's where bugs enter the code. 
- A quality JS program embraces coercions, making sure the types involved in every operation are clear. Thus, corner cases are safely managed.
- If you're trying to understand your code, it's critical you learn to think like JS.

### 2. Paulina Hetman's website (https://pehaa.com/)

This website is just beautiful. The design, color, animation, font, and layout blend in perfectly to make this little personal site stand out. It differs from the conventional CSS examples I learned in tutorials and shows how you can make great modern design with CSS and some design knowledge. I'm inspired by the quality of the work and motivated to improve my CSS and design skills.


### 3. MobX (https://mobx.js.org/README.html)

MobX is a state managing tool that is a lot easier to use than Redux. Redux saves the state of an entire app as a giant object, thus removing the restriction of React's own state management where states are only accessed and maintained by certain components, they have to be passed down for their children to use. However, Redux can be cumbersome to use. MobX on the other hand, adopts a new strategy: State is mutable. Make sure that everything that can be derived from the state, will be derived. Automatically. I'm inspired by this new way of handling state using observables and decorators.

## Focus

I would first spend some time learning the types of work being done at Critical Mass. Since I'm interested in writing code to automate tasks and boost productivity, I would like to write some helper utility tools to help developers with their task.

## Code Challenge

https://codesandbox.io/s/2020-internship-exercise-menu-8lnx1
  