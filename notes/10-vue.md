# MVC


Get used to reading the documentation, the docs, of frameworks when you are trying to figure out how to do something within that framework.

Vue is a nice middleground of React and Angular

SECTION Starting with Vue
  The entire app is built within the "src" folder
  Vue reactive is similar to a proxy object but it just makes it reactive
  setup() is the default of the javascript and must have a return object
    Directive = v-on OR @
    Binding = {{}}
      ref = This is something that will have something bound to it

SECTION Data binding
  Two-way - v-model=""
  One-way - 
    

SECTION Glossary
Vue - A frontend javascript framework that makes building user interfaces easier.

Component - A .vue file that contains an HTML template, script area for javascript, and a style area for css.

Page - A collection and layout of various components.

Data Binding - A connection between a property on the component(in the data() return object) and the template.

AppState - The AppState utilizes the observer pattern and a single source of truth for all components in the app using vue's reactive wrapper.

Router - The Vue Router is used to evaluate the address in the url and determine which page should be displayed.

V Directives - The special directives for Vue, all begin with a v and tell Vue to use some special behind the scene processes. Examples: v-if, v-for, v-show

Reactive - When the data on the page updates automatically based on the state of the application, the user is not required to refresh the page to get the needed data.

SECTION Props
  How we pass data from a parent to a child.
  Must pass information from the parent to the child componant in order for the componant to know what to do with it.

SECTION router
  <router-link :to="{name: '#componantName', params:'{id:#propsId }'">

  Want to put object of posts into Appstate
  posts/:id/like will "like" the post?
  Not required to edit a post
  Hint for formatting time: new Date()

SECTION  sockets
  flip sockets to true in env.js
  import socketService
    .emit
    .joinRoom
  backend socket
    socketProvider
