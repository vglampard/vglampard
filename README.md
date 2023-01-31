#Progress notes for my School of Code Bootcamp 13 learning. #100DaysofCode

NOTE: It’s a big ol’ doc, but there's 11 hackathons and 2 extended group projects in there. I've labelled them with a little '🛠️' if you fancy digging them out - fuller write ups are on the way...

Day 1: Computational thinking and an introduction to pair programming

Day 2: Computational thinking in practice - applying the concept to word games through pair programming. Then, consolidation of cloning, pulling, and pushing via github.

Day 3: Variables and functions. We looked at translating Scratch blocks into JavaScript code, and then put together a simple password authentication function in pair programming using 'while' and 'if/else'.

Day 4: Had a mindset seminar about how, when, and why seeking feedback helps growth, both professionally and personally. Discussed the best ways of both receiving and giving feedback. Then moved onto objects and arrays. We looked at what they are, how we do things with them (like select, change, and add items). I also looked into how to remove items using the pop and splice methods. 

🛠️ Day 5: HACKATHON 1 - ROCK PAPER SCISSORS. Created a simple rock paper scissors game, using player's name (10 character limit, and used REGEX to ensure it begins with upper case letter) and input (rock, paper, or scissors) to play against randomised moves from the computer player. The game kept a running total of losses, wins, and ties, which it displayed as alerts. Player input was pulled from prompt. 

Day 6: Introduction to codewars. Introduction to the document object model, and how to manipulate it using JS. We ran through a couple of workshops where we changed, added, and removed elements, and properties of elements. For example, appending a number-doubling button to a webpage, allowing users to change the webpage h1 using an HTML form, and selecting and changing style elements. 

Day 7: Introduction to event listeners, and how to use them. We did some pair exercises, and then moved onto changing code from the rock paper scissors exercises so that instead of taking input from prompts, and displaying results in the console and via alerts, all this was done through interacting with the webpage itself. 

Day 8: Introduction to asynchronous code. We used setInterval, clearInterval, and event listeners to build automatic counters you can stop by interacting with the browser. We built a simple clock, where the minute second and hour hands ticked by with the seconds like an analogue clock. We learned about the call stack and event loop. We created an async function to call Kanye West tweets from an API, and display these in a pre-fab browser template as a list. 

Day 9: We started with a mindset session looking at the importance of cognitive diversity in teams and problem-solving. We looked into what our Myers-Briggs personality types help us bring to a team, and where we might face conflict and challenges. Then we practised navigating structured data, and extracting information so we could use it - in this case, printing it to the browser and console. Then we spent time researching further topics - in our group, we looked at Chrome dev tools we haven't touched upon yet during the bootcamp. I looked at the uses of recorder, the performance tab, and the subsequent performance insights panel.  

🛠️ Day 10: HACKATHON 2 - TRIVIA QUIZ. We used a trivia question API to build a trivia quiz page. It pulled 50 true/false questions, and players cycle through them one by one. Each question must be answered, with navigation buttons to move between them and a score counter to keep track of wins. I polished this up over the weekend, and am in the process of adding extra features like CSS and 'help'. 

Day 11: Began the day working independently on coding, then in pairs on codewars. Then had a series of introductions to the agile work method (including importance of MVP and early feedback - the 'shift left'), and UX/UI. We also spent time working on an elevator pitch for our personal career trajectories, reflecting on how our unusual entries to the field work in our favour. We blind-coded a replica of Google's homepage, and wrapped up with an intro to Frontend Master. 

Day 12: Looked at design thinking in closer detail. For this, we came up with an idea for a new bootcamp, and worked on the first three steps of the design thinking process: empathise, define, and ideate. 

Day 13: Employer/career talk from Javaid and Alex at Nester, looking at the value of a good portfolio and what to expect in our first tech jobs. We then put together a wireframe for our bootcamp application process, and looked into design theory areas like colour theory, balance, user flow, and hierarchy of attention. Then we studied CSS style specificity, and how the cascade part of the CSS will affect which style is ultimately used when there’s conflict. 

Day 14: Mindset talk about identifying our listening styles and being attentive to how we work with others. Plus, a look at how developing alter egos can help cultivate traits and habits we aspire to - e.g., confident public speaking. We also heard from Paavan Buddhdev from AND Digital, who walked us through key UI/UX concepts like: don't make the user think, inject wonder into the product, and design it according to what the user expects. We also looked at using > in CSS selections to avoid the overuse of classes, and the value of building responsive design into a page from the beginning. In our research teams, we ran an accessibility audit for Hotwire holiday booking website, looking at its use of space and balance, blocks of text, colour schemes, and how navigable it would be for users with reduced mobility. 

🛠️ Day 15: HACKATHON 3 - BOOTCAMP DESIGN. We refined and polished the user personas, user stories, and ideas that we'd come up with for our bootcamp. We took our low fidelity wireframe and improved upon it, then embellished this and turned it into a high fidelity mockup on figma. 

Day 16: Introduction to NodeJS. We started following up on last week's recap task - using the design process to mock up a personal portfolio page. Then we got an overview of what NodeJS is and how it works. We made a simple module that produces a greeting using three different variables from a separate document. Then we moved onto adding a second functionality that picks a random user from the bootcamper list.  

Day 17: Instead of custom modules, today we looked at native modules .We used fs to read/write files in our user data app. Then we imported a third party package, express, to build a basic server. This server used UUID to assign a random ID to user objects, which we would then read and add to - e.g., adding a new user to our userData array. We also looked at how we can use destructuring to more efficiently pull out items from an imported array.

Day 18: We practised using Postman to simulate simple requests of different types. We imported Nodemon as a dev dependency to make building our API easier. Then we did a deeper dive into APIs by building out functionality for a simple API - cwissy.API. FOr this, we coded route handlers.

Day 19: Mindset talk on the importance of listening to your inner champion, and co-operating with your inner critic. Then we moved onto the role of middleware, and imported Morgan to add logs to all incoming requests in our API backend. Then we looked at how to put together the HTML, JS, and CSS files that constitute the front end, and serve these static files when the URL is pasted into the browser. Finally, we separated out our backend logic into different locations (models and routes) to separate concerns, make the code more readable, and easier to work with and edit. 

🛠️ Day 20: HACKATHON 4 - CRUDDY RECIPES. We put together a backend for a new API that allowed users to create, read, update, and delete data from a list of recipes stored in recipes.json file in our IDE. 

Day 21: Recap task from the weekend - repeating the hackathon tickets but for a new data file that contained user information. So, creating helper functions, route handlers, and testing them (for me using curl commands). Then we had a career talk from Stuart Langridge about things to watch out for as a new dev (companies asking for work in exchange for exposure, companies looking for extensive overtime without fair compensation), and the importance of playing around with interesting code on personal projects. Then, introduction to databases. We are learning the basics of PostgreSQL, and spent the afternoon looking over how tables are set up and how to carry out CRUD style requests on them. We learned basic PostgreSQL query syntax and how to generate automatic integers as identity: INT GENERATED ALWAYS AS IDENTITY PRIMARY KEY. 

Day 22: We looked at inner, outer, left, and right joins. Left and inner being the most common, and right and outer rare. We did exercises combining more complex queries pg exercises, looking at linking up tables, concatenating columns into single columns, creating columns to display calculations using data from other columns, etc. Looked at using conditional statements with CASE, and limiting results with SELECT count(n) FROM table. Completed SQL murder mystery task navigating databases to solve crime. 
 
Day 23: Codewars to begin. Then learned about how we can use databases to store our data somewhere where it PERSISTS - as opposed to in a local .json file. We looked into railway, and then Elephant SQL. environment variables and how to set them up in .env, tweaking references in other files accordingly.
Learned about node-postgres (PG) and its function as a kind of ‘translator’ between the node.js and SQL server/clients. Query, which we get from pg, is imported to allow us to insert SQL queries directly into node.js as strings, and send them (via a key saved as a URL in .env) to our SQL database to return us data. Pool allows us to more rapidly handle connection security.Learned about SQL injections, and how we can shore our app up against them by sanitising our queries: using prepared statements and parameterised queries. We practised using them in our API SQL queries.

Day 24: Mindset talk from Joseph about different methods of group decision making - roman voting, testing the room, etc. We looked at how personal values can manifest in group work, and the positive and negative effects our own values could have on our teams. I had a good progress meeting with my SoC mentors. 
  
🛠️ Day 25: HACKATHON 5 - ART COLLECTOR'S DATABASE. Building an API using Express, Morgan, pg. and ElephantSQL that interacts with a database using SQL queries, as opposed to last week's use of a recipes.json file. We built a simple art catalogue database that users could use to look up and add different artefacts. 

  
  Day 26: Recap task: taking the CSJ modules in our previous workshops and hackathons and converting them to ESM, by changing the way files are imported, exported, and referenced within the app. Then, industry talk from Nadeem at Talis, focusing on the importance of testing and coding with testing in mind. Introduction to automated testing, Jest, and unit testing. Unit tests should be many and small: reliable, quick, and testing isolated portions of code. We looked at simple Jest test syntax and wrote simple tests of our own.
  
  Day 27: We looked at the red green refactor approach in TDD (test driven development): make a test that assesses a small component of what you want to do; write code that fails it; write JUST enough code that it passes the test, and then refactor afterwards without making the code fail the test. Paul Jaffré came in from Cypress to talk through end-to-end (e2e) testing. It’s one way of identifying something to test: instead of focusing on one unit, or the integration of different units, you focus on one user flow. e.g., logging in. Paul gave us a Cypress walkthrough, then we began a cypress workshop on writing tests to check functionality of a simple list app: how to simulate elements clicked and data inputted by user, and then check with assertions. As homework, looked at the difference between spread and rest operators and ways to free up disk space. Learned that I can delete .deb and .exe files after installation is completed. Learned that the chromebook sliding disk-space option in settings is as easy as it looks to use - just make sure the space you allocate to Linux doesn’t exceed the available space on the computer.
  
  Day 28: Started with some codewars - looked at using for(let X of str) as an alternative way of iterating over a string. I prefer it - more concise! We continued work on cypress workshop - learned how to use data-cy=”X” tagging in html so we could more accurately and reliably target elements we wanted to include in the test simulation. Chained commands together like .get and .click., and looked more closely at the pros and cons of using this as a complement to other kinds of testing: it’s more time consuming to execute and build, but can help test core functionality better than other methods. Then we looked at the third kind of testing in the pyramid: integrated testing. Specifically: API testing using SuperTest. We built tests for async functions that were making get requests to a specific API URL from our VS Code app. We can do this instead of using postman, or in my case curl commands.
  
Day 29: Revisited API endpoint testing with Supertest, then had a seminar on Couchbase and NoSQL from the team at Couchbase. Looked at the function and unique features of: key-Value databases (used mainly for caching: you get low-latency access to simple vales, and can combine this with, for example, SQL relational databases), document databases (the most commonly used NoSQL database, with a flexible schema that allows for changing database structure), column-family databases(groups data according to loose column similarities) and graph databases(stores entities as nodes, with edges that represent relationships between them). Then, spent the afternoon building our own code-war Katas with accompanying Jest tests. 
 
🛠️ Day 30: HACKATHON 6 - TEST-A-THON. Used Cypress to build and run end-to-end testing on a simple user app, then used Jest and Supertest to build and run API endpoint tests. 
 
 Day 31: Introduction to React. Looked at how React allows us to offload a lot of the manual updating code involved in making dynamic front ends - uses a virtual DOM, and diffs between that and the browser DOM, subsequently  updating only the parts that have changed (and their children!). Looked at Babel and JSX, and spent time coding up elements with and without JSX to demonstrate what's going on underneath - and why JSX is so useful. Then moved onto how we pass in props to make dynamic components. SPent time afterwards looking into conditional rendering, 'rules of react', how the separation of concerns is different to what we've done to date, and brushing up on JS.
 
 Day 32: Talk from Nick Truby, front end developer at BT, to get a sense of what enterprise scale react apps look like in terms of structure and complexity. Looked at mutating/immutable array methods like filter() and some(), prop destructuring, and parent/child component structures. Sketched out the component tree for the netflix page and mocked it up by spinning up a simple react app with card components inside.
 
 Day 33: Intro to react hook useState: what it's for, how to use it, where it should go. Looked at lifting state, and how props and state-setting functions get passed around the component tree. 
 
 Day 34: Mindset talk from Will Peachy about communication styles, and the value of knowing yours in teams (especially agile ones). Practised combining immutable array methods with the spread operator, and spreading nested objects to avoid making shallow copies. Continued to cover spread/slice and array.map to render multiple components dynamically - and adding unique identifiers with UUID or Math.random(). 
 
 🛠️ Day 35: HACKATHON 7 - TO-DO LIST REDUX. Use useState and react to build a simple to-do lists app.
 
 Day 36: Refresher talk from Nadeem and Camille Fenton from Talis about API and restful restrictions. Then, useEffect hook and the importance of catching any DOM changes that don't go via react app somewhere they can be controlled. It's a way of keeping component functions pure! And is only a last resort - where possible, use event listeners. Useful for API calls, and dependencies can be added to control when a rerender is triggered.  
 
 Day 37: A closer look at git branching, pull requests, and conflict resolution. Then, looked at useReducer: allows us to control state changes by creating a finite state machine, and works with dispatch and actions. 
 
 Day 38: Talk from Will Peachy about the employment process and market patterns to watch out for. Then, deeper dive into the react testing library (and a refresher on the pros/cons of testing). The importance of prioritising query methods that are most exposed on the accessibility tree (getByRole, aria labels). We're not testing the actual DOM, just a lightweight and very similar rendering of it - there will be drawbacks. Looked at conditional rendering using switch. 
 
 Day 39: Mindset talk about team dynamics, conflict protocol, team manifestos, and decision making frameworks. Reflection upon my own teamwork strengths, weaknesses, and values. Then moved onto how to test react functions using react testing library and jests.fn(). 
 
🛠️ Day 40: HACKATHON 8 - GO-GLE SEARCH ENGINE: Built a React app search engine that displays results as image tiles - tagretted at instagram-inclined younger generations, as well as the visually impaired who may find it tough to process screens of text.
 
🛠️ Day 41: PROJECT WEEK day 1. Set up agile framework, team manifesto, and values. Discussed possible areas of weakness and strength and ways to manage. Brainstormed from project brief; settled on concept; completed disney ideation and completed user stories and MVP requirements. Broke down project into stories, tasks, and stretch goals, and drew up lo-fi wireframe on figma. Created component tree with information flow and functions. Set up database and back-end skeleton. 
 
🛠️ Day 42: PROJECT WEEK day 2. DevOps talk from Rik Marselis looking at high performance IT delivery, and the different kinds of preventative quality measures and test coverages that can be used - and when you'd use them (including regression testing bs progression testing). Built trello board with kanban task breakdown, then finished backend CRUD routes (with extra for stretch goals) and continued work on front end.  
 
🛠️ Day 43:  PROJECT WEEK day 3. Tweaked database to ensure back end and front end were working with the same data. Continued to add back end testing, then added drop down menus and completed the front end MVP using custom form hook. Linked up the front and backend, using the CORS middleware. 
 
🛠️ Day 44:  PROJECT WEEK day 4. Code review to identify functional weak points which we then cleaned up. Here, commented through our code to keep things legible and well defined. Then, high-fidelity wireframe with accessibility and branding in mind so we could spend the remainder of the day on front-end testing and CSS. 
 
🛠️ Day 45:  PROJECT WEEK day 5. Put together and polished presentation of final app: page displaying cards that detail resources shared by other bootcampers and coaches on the SoC course - with form so that users can contribute their own. The resource cards have a topic image (conditionally rendered based on topic input), H1 title that opens a new tab to the resource; tag identifying who contributed the resource, and a difficulty rating rendered as one, two, or three images based on the level of difficulty. Input form gathers data using a custom form hook.
 
 Day 46: PROJECT WEEK retro. Pros: great team communication, completion of polished and fully functional app. To improve: even tighter time management could have led to completion of smaller stretch goals. Shared, reviewed, and discussed project week code with another team - began polishing up documentation and fleshing out more front end testing. 
 
 Day 47: Added JSDocs comments to code, and linked this up with their automatic documentation tools to spin up good-looking docs. Polished off front end testing!
 
 Day 48: Cracked the front end testing issue I'd been trying to work out during project week - namely, how to target the correct elements using the container method, when getting by Aria labels and roles surprisingly didn't work. 
 
 Day 49: Dove into authentication and authorisation: its purpose, and the pros and cons of building out personal security systems instead of using auth-as-a-service. Used the Auth0 docs to build front end authentication and back end authorisation. In the process of using the Auth0 docs, really had the value of good docs hammered home... 

🛠️ Day 50: HACKATHON 9 - CONSPIRACY WEBSITE WITH AUTH. Used Auth0 to build a nondescript looking website which, when you find the hidden login button, grants access to a protected route with conspiracy theory content. 
 
 Day 51: Full stack deployment! Used Render for both front and backend so we could manage them both from the same console. Takeaways: really make sure those scripts are correct, and work through it step by step. Get the back end up and running, check it with Postman, and only then move onto the front end. 
 
 Day 52: DevOps talk from Rik Marselis, then a deeper dive into React hooks. Today: useContext and how it helps avoid prop drilling. Create the context (factory function), provide the function (using provide method on context object - essentially a wrapper), then import and use the context. Contexts are good to abstract into their own files. We also looked at building custom hooks and how they're a useful way to preserve variables between renders.  
 
 Day 53: Looked at the useFetch hook and how it can be applied in two different kinds of API call. A little late to the game in noticing that you can conditionally render variables, which I look forward to taking advantage of. Also practised technical interview questions, and had another guest workshop from the team at Couchbase about database building and accessing through key, query, and full text searches - including indexing. 
 
 Day 54:
 
🛠️ Day 55: HACKATHON 10 - JUMPER FUNTIME. Built a mix-and-match picture app that allows you to put different bootcamper heads on top of different christmas jumpers using randomised (with custom useRandonNumber hook) fetch calls (with useFetch hook) to our ElephantSQL database. Themed using useContext.  
 
 Day 56: Talk from Camille Fenton and Nadeem Shabir at Talis on different nuts and bolts of company coding practices. Design languages and systems help standardise the look and processes of company code to remove ambiguities (which I can see the value of given following our week long project!). “Teamwork is all about velocity and cadence”. Following that, Couchbase workshop continued: taking a closer look at the database cluster breakdown, practice in how to connect and carry out CRUD operations , and an introduction to SQL++.
 
 Day 57: Hands-on with Typescript, a superset of JS. Following 50+ days of coding and errors, this is something that seems especially valuable, if tricky to get the hang of - especially getting early config right. Looked at using interfaces to define object shapes and types, including optionally, and touched on TS generics. Then, using const before enums AND afterwards to create a constant object of constant values, instead of variable ones - which can also be used across non-TS projects.

 Day 58: Using React App with Typescript. Typing prop objects, including making props optional; typing functions including ones that take events. This can be done inline automatically (React just knows!), but if it’s separately defined you can fake it as inline so that VSCode serves it up for you - then just copy and paste that.

 Day 59: Bit more codewars, then looked at the value of being a good debugger: isolate it, create a profile for it, outline a solution and timeline, and document it. Looked at how to build a good bug report! Then practised with the VSCode debugger. Practise technical interview with mentor and SoC staff - encouraging feedback, and some good tips on how to refactor and polish up our project week codebase. 
 
🛠️ Day 60: HACKATHON 11 - Weather App. Used typescript and a weather API to build an app that visually displays the weather in a given city. Used TSParticles to create rain and snow effects, and added this to our other conditional weather rendering. 
 
Day 61: CI/CD talk from Dave Adams at anyPets. Looked at using GitHub Branch Protection rules. Then moved onto AWS: set up a basic account and explored the different services, for example using Amplify. 

Day 62: Talk from Lily-Lou Lewis about how to construct a CV, and what to focus on. Then, split off into research groups to look at CRA alternatives. Focused on Gatsby: not that great if you’re looking for frequent database updates, but good for SEO and deploying on sites like Netlify. It’s a static site generator (contains site contents in HTML) but has a deferred static generation option to prioritise the most important page builds. So it’s a hybrid combination of server-side rendering, with hydration taking over once the initial HTML is rendered. Looked into Next.js (looks good for page routing!) and Remix (all the bells and whistles).

Day 63: Lily-Lou back for the recruiters’ view on how to build LinkedIn into an employment asset. Went back over course content to review what we’ve learned, and build out a coding practice plan for the Christmas break. Reconvened the project week team to refactor code based on technical interview feedback, and review what to take away from our experience: “peaks and pits”.

Day 64: Looked into Svelte as an alternative to CRA. Then, started sketching out logic for and building out a simple card-flipping image-matching game in React. 

Day 65: In anticipation of project month, followed tutorials on Next.js to get a feeling for how page routing and data fetching works differently. I like the way pages can be dynamically created - I suspect this will come in handy. 

🛠️🛠️🛠️ PROJECT MONTH 🛠️🛠️🛠️
 
Day 66: Project month WEEK 1 - Planning and ideation. Completed pre-mortem, shared personality and working types with team, worked out manifesto and recovery principles. Agreed on a problem to solve: no travel app really takes you to the authentic and left-field places!

Day 67: PMW1 - Put together and distributed survey to test how much appetite there is for a solution, and what kind of things users would value. Discussed working principles, what kind of tech stack we’d all be interested in / comfortable with pursuing. Working in a team of 6 is likely to prove challenging, so we discussed the kind of culture we want to create. 
  
Day 68: PMW1 Went through Disney ideation process and compiled a list of possible app features, selected a shortlist, and looked for online resources to help explore how we could implement  the different features. Timings are on track but we’ll have to be careful with scheduling!

Day 69: PMW1 - Looked over 40 responses from the user survey - nice, people largely agree that they’ll buy what we’re selling. Finalised MVP features and stretch goals, and built low-fidelity wireframes using Figma, which extended a little into the beginnings of hi-fi wireframes. Tentatively arrived at a colour scheme. Completed three user stores covering a pretty diverse cross-section - travellers come from all over the shop.

Day 70: PMW1 - Analysed API data coming through - decided to test API hypothesis: is it feasible to do 3x API calls without severely hampering performance? Will it still be a useable app? Smaller teamwork is working better today, as we were feeling the drag of 6 during the planning phase. Worked on component tree and data flow. Decided on branch protection on main, and strategy or merging completed code at the end of each day as a team. 

Day 71: Project Month WEEK 2 - Reviewed the prototype from the weekend, and the sequence of API calls is doable. It needs throttling because of limits on the free tier, but we can put in some loading animations / features. Agreed on how to use the MVP that was built over the weekend - we’ll reference it, but build one out ourselves as a team. Put in place sprint goals and broke down sprints into smaller tasks ready for coding tomorrow. 

Day 72: PMW2 - First full day coding! Split into front/backend to sketch out the basics: backend DB table creation / seeding functions, a couple of initial routes/models, set up the ElephantSQL instance. Front end: worked on putting in place NextJS skeleton in typescript but it was LENGTHY. Coaches warned of Next/TS pitfalls to come, so we pivoted back to JS so we could make progress with development. Built out JS front end in about a quarter of the time it had taken in TS. 

Day 73: PMW2 - Built out back end routes and models for added functionality, testing in place and passing, it’s ready to deploy! Front end is also making good progress, using Axios for the first time is proving very satisfying. We’re using Tailwind and getting this started early, and good progress is being made here too. Vertical slice methodology is feeling productive. 

Day 74: PMW2 - Back end is now deployed! And API results are coming through to display on the homepage. Decided to switch from separate results page to conditionally rendering results on the home page: faster user experience, and makes things easier for us to code. 

Day 75: PMW2 - Mid-project presentation day. Turns out we were supposed to do a sprint presentation, not a full-project presentation - lesson learned! But it was useful to take a step back and analyse our progress, what’s working and not working, and polish up our spring planning. 

Day 76: Project Month WEEK 3 - Decided to use Firebase because Auth0 has been a pain in the past, and it still provides a good level of security. We mobbed on researching it, how react firebase hooks work. Got search results displaying on tiles, and added heart buttons that link up to our post resources endpoint. 

Day 77: PMW3 - We worked on implementing basic auth using firebase and are getting there. Favourites page is also well underway, and the code for our cards component is actually getting pretty bloated so we’ll be pulling out the heart button as a separate component. 

Day 78:  PMW3 - Switched to using the uid provided by google login as our user id in the database - this means we can avoid doing an extra API call to pull and post an ElephantSQL-generated user id when needed. It’s also more secure as it’s not just a single integer. It took some retooling to get this in place, but now that’s wrapped up it’s going to save us (and users) time. Auth is now functional with username/password!

Day 79: PMW3 - Lots of guest talks etc today that left us with only a couple of hours to code. We didn’t get around to front end employment but auth got a nice bit of polish - custom login page, login with google account, all adding nice functionality. Wound up overlapping on tickets which held us back and took a while to unpick. 

Day 80:   PMW3 - Teased through a bunch of conflicts from the overlap yesterday, merged code, and implemented a new policy of taking extra time to clearly delineate the tickets in detail to avoid this happening again. Front end functionality is on the way with post/delete request rewiring. Gave a small presentation to our wider group!

Day 81: Project Month WEEK 4 - Final week, so we went on a thorough bug-hunt and ticketed it all out on the Trello board. Functionality is now all in place, if a little wobbly in places, and styling has taken a drastic pivot in light of some useful feedback from mentors and test users. It took some wrangling and there were some disagreements about the details, but now it is looking much better!

Day 82: PMW4 - Final bug-fixing day: eliminated all major bugs and most of the minor ones! Worked on performance improvements (e.g., will removing useEffect help us out). Deployed the front end finally, and learned that deployment usually happens on Linux containers - these are case sensitive, unlike Windows/Mac, so it will throw case sensitivity errors even if they don’t show up on the local machine. 

Day 83: PMW4 - Hunted down some more bugs, and implemented a filter that stops incompleted results (without image or descriptive paragraph) coming through and throwing errors - it also allowed us to remove some cumbersome and ugly optional chaining that we’d initially installed. Reviewed and discussed previous cohorts’ demo day videos to get inspiration for ours.

Day 84: PMW4 - Reviewed final bits on navbar styling which was causing some issues - good to finally crack the nut! It’s pulled the app together really nicely. Began working on final presentation, and pre-recorded videos to be spliced into the final version. 

Day 85: PMW4 - Video editing and bug fixing for most of the day. Then, final graduation wrap up!

Day 86: Demo Day

  

