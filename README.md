# learning-journal-capstone-f23

## My Learning Accomplishments & Resources:

-   Completed the [Learn Bootstrap course on Codecademy](https://www.codecademy.com/learn/learn-bootstrap)
-   Followed [this youtube tutorial on building a personal portfolio page](https://www.youtube.com/watch?v=0YFrGy_mzjY&ab_channel=GreatStack)
-   [Personal Portfolio Website](https://github.com/benspector-mls/personal-website) repository
-   Followed [this tutorial](https://www.youtube.com/watch?v=k68j9xlbHHk&ab_channel=PedroTech) and created [this repo](https://github.com/benspector-mls/redux-todo-practice) with the todo app
-   [Learn TypsScript guide](https://www.freecodecamp.org/news/learn-typescript-beginners-guide/) on FreeCodeCamp    

## Learning Log

Tuesday Aug 15, 2023
-   YouTube Video Tutorial: [T3: TRPC, Prisma and NextAuth Done Right](https://www.youtube.com/watch?v=J1gzN1SAhyM&t=10s&ab_channel=JackHerrington)

----------

Monday, Aug 14, 2023

-   I learned about Google's oauth feature, starting with [this tutorial](https://youtu.be/HtJKUQXmtok)
-   I built a small Vite app (and accidentally deleted my other demo apps… oops!) to show off the feature.
-   I then expanded the app to include a back-end so that I could store any user that signs up in my database. The model is much simpler now that I don't need to do any authentication on the backend.
-   Typescript is still something I need to work on incorporating into all of my applications

----------  

Thursday, Aug 10, 2023

-   Yesterday I learned about [Nextjs 13](https://www.youtube.com/watch?v=8pzIuLFuv6U&ab_channel=PedroTech) by watching a tutorial video. My key learnings were
-   The three different ways to provide a website to clients
    -   Client-Side Rendering (CSR) - this is what React does. It serves the client an empty index.html file which loads a JS script that generates HTML elements on page load. This is slower (because of the need to load in the elements via JS) and it doesn't allow for web bots to index the website because the index.html file itself is empty.
    -   Static Site Generation (SSG) - this is when HTML files are generated at build time using templates or, in the case of Nextjs, React. The benefit of this is that the load time for clients is much faster - the HTML is directly served to the client. However, if the page needs to be updated at all, this doesn't work as well. This is best for things like blogs or static websites.
    -   Server-Side Rendering (SSR) - this is when HTML files are generated at request time. The benefit of this is that webpages load more quickly because data fetching occurs on the server, not on the client. The downside is that there are more server requests required and the website cannot be deployed to a static CDN.
-   Nextjs 13

----------

Tuesday, Jul 25, 2023

-   Affirmations:
    -   I am a caring and competent teacher
    -   I am a valuable asset to my team
    -   I am a caring and reliable friend
-   Accomplishments
    -   Yesterday, I set a new working intention for my group, giving an opportunity for my fellows to review units 7 and 8 while building a personal project
    -   I initialized a conversation around getting to know the incoming F23 class
-   Goals for today:
    -   I want to make sure that the attendance tracker is set up properly
    -   I want to lead a productive morning and afternoon seminar
    -   Review Redux blogs    

----------

Monday Jul 24, 2023

-   Following this [Learn TypsScript guide](https://www.freecodecamp.org/news/learn-typescript-beginners-guide/) on FreeCodeCamp
    
----------

Thursday, Jul 20, 2023

-   Followed [this tutorial](https://www.youtube.com/watch?v=k68j9xlbHHk&ab_channel=PedroTech) to create a simple profile page.
-   I learned about how to use the createSlice function. There were a number of confusing aspects to this function
    - Each slice of state has a value. For example: state.todos.value and state.user.value
    - The reducer is written as a series of functions. Because of this, the action.type is almost never relevant within the reducer itself
  -   You never even create actions. They are made automatically for you for each reducer function.
  -   The reducer functions can actually mutate the state.
-   At first, I found it confusing that the actions and reducers were hidden inside of the slice being created but I started to understand it after doing it a couple of times.
-   I started following the portion that introduced a color-based them but I veered off and figured out how to make a light/dark theme switcher for the whole app
-   Once I felt like I understood how making slices worked, I made a more complex example with a Todo list  

----------

Monday, Jul 17, 2023

-   Starting my research on Redux
-   Using the [docs](https://redux.js.org/introduction/getting-started) and going through the getting started
-   Used the suggested Vite starting template
-   Okay this template uses Typescript and has a lot of things in it that are a bit confusing
-   I might try building something of my own from scratch instead of using the template
-   Switching over to the [React Essentials learning section of the docs](https://redux.js.org/tutorials/essentials/part-1-overview-concepts)
-   Ah this is much nicer
-   [My Notes](https://docs.google.com/document/d/1HtnLyB95hELTQGMKmMr-PUm7O2xjLquq32FW6BlXi7o/edit)
-   Going to try out the [learn redux course](https://www.codecademy.com/enrolled/courses/learn-redux) to see if I understood those essential topics
    
----------

Wednesday, Jul 12, 2023

-   Today I [finally finished building it](https://github.com/benspector-mls/personal-website) using just HTML, CSS, and JavaScript!
-   Trying to simplify things, I found this simple [md-block](https://md-block.verou.me/) package which I can use with plain HTML but I found that it didn't render things the way I wanted to.
-   FINALLY, I landed on the solution of writing blogs on Medium. Pulling articles directly from Medium is really easy since the fetched articles are already formatted as HTML, making it seamless to embed with basic DOM manipulation.
-   RSS feed    
-   I also was able to practice using Bootstrap to make everything look nice!
    

----------

Tuesday, Jul 11, 2023

-   I have wanted to make a personal portfolio website where I can show articles written in markdown to showcase my writing.    
-   At first I had looked into using Jeckyll but I found that it wasn't actually going to do what I wanted it to. It also ran into a seemingly [common issue](https://github.com/rbenv/ruby-build/discussions/1961) related to installing Ruby on Macs which required me to change course.
-   Then, I tried a solution using React and I found this [npm package called ReactMarkdown](https://github.com/remarkjs/react-markdown#api). It worked well at first but became complicated when I tried building a backend server to store the files in the first place and found that I can't store entire markdown files in a database.
-   I'll keep looking for another solution tomorrow…