# vue-js-interview-study

project to review important topics of vue, tests and ci/cd

## Some interview questions that might be asked

### What is vue.js? What do you understand by vue.js?

**Answer:** Vue.js is a progressive framework of JavaScript used to create Dynamic User Interfaces and single-page applications

### Why is vue.js called a progressive framework?

**Answer:** Vue.js is a progressive framework because it is being changed and developed continually.

### Whay is vue.js supposed to be a competitor of angular in upcoming days?

**Answer:** Vue.js is also used to build User Interfaces and single-page applications like Angular. Nowadays, it is evolving very fast, and with time, new libraries and extensions are coming to existence.

Many developers' are using Vue.js and the popularity of this JS language is increasing day by day. Tha'ts why it is supposed to be a potential competitor of Angular.

### Who is the founder/ inventor of Vue.js?

**Answer:** Evan You is the founder of Vue.js. He was working at Google on several Angular projects when he founded and developed Vue.js.

### What is the vue-resource?

**Answer:** The vue-resource is a plug-in for Vue.js. This plug-in is used with Vue.js to make web requests and handle responses in which XHMLHttpRequests or JSONP is used.

### How can you install Vue.js in your project?

**Answer:** There is 4 main methods:

1. Using CDN by including <script> tag into the HTML file.
2. By NPM/Yarn.
3. By Bower.
4. Using Vue-cli.

### How to create a Vue instance?

```vue.js
let vue = new Vue({
  //options
})
```

### What is Vuex?

**Answer:** Vuex is a state management pattern + library for Vue.js applications. It serves as a centralized store for all the components in an application, with rules ensuring that the state can only be mutated in a predictable fashion. It also integrates with Vue's official devtools extension to provide advanced features such as zero-config time-travel debugging and state snapshot export / import.

### What are Vue.js filters?

**Answer:** Vue.js allows you to define filters that can be used to apply common text formatting. Filters are usable in two places: mustache interpolations and

```vue.js
v-bind expressions (the latter supported in 2.1.0+).
<!-- in mustaches -->
{{ message | capitalize }}

<!-- in v-bind -->
<div v-bind:id="rawId | formatId"></div>
```

### React x Vue

**Answer:** There's a few important differences:

- The modification of a React component state triggers the re-rendering of all of the components in its subtree.
- In Vue, these dependencies are tracked—so unnecessary re-rendering is prevented.
- Among the two, Vue can handle high frames rate—10 frames/second, as compared to React with 1 FPS.
- Both have State Management libraries.
  - React has Redux
  - Vue has Vuex
- React has JSX (which in my opinion is a lot harder to learn)
- Vue has separated CSS, HTML and JS, using HTML, JSX.
- Both have component life cycles, but vue is simpler and more intuitive.

### Popularity

![image](https://user-images.githubusercontent.com/47605309/144344499-c528458c-ed06-4b6f-bc34-5d75ce1351ed.png)
As you can see, ever since 2017, Vue has been right there with React among the most popular frameworks.

As of 2021, Vue has 181K Github stars—and can be considered the most popular JavaScript framework. In the second place, React runs close with 165K stars-continuing to grow.

According to Google Trends, over the past 12 months, companies were looking to hire React developers, followed by Vue and Angular in a neck-to-neck battle. Having this in mind, React jobs are the most popular, followed by Angular, and then Vue—that’s how the job market looked like in 2020.

### In conclusion

Vue is better if:

- You need a solution that works as soon as possible.
- Your app isn’t very complex or you need it to be extremely fast
- You want to migrate an existing project to a new technology, but have limited resources and time
- Your team is mostly HTML or junior developers
- You prefer clean code and HTML templates

React is better if:

- You want to develop a complex application or SPA
- You plan on expanding the functionalities of your applications to a great extent in the future
- You need a mobile app
- Your team prefers JavaScript over HTML
- You have experienced React developers on your team
