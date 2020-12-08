# React-Crash-course-2019
Brad traversy's course on youtube

# what is react ?

A JS library created and maintained by Facebook. Used for building User interfaces and FE applications.

It runs on the browser or the client, there are performance upgrades to this and benefits like faster interaction times.

It's the V in MVC, it is a framework.

It is smaller than angular , thinks like router and http client are not included by default unlike angular.

# Why use it ?

* Makes FE JS much easier
  Vanilla js by itself is a pain otherwise

* Uses self contained independent components with their own state
* Much more interactive UIs
* Virtual DOM
  updates only whats needed, as opposed to the whole page.
* JSX - easily incorporates JS in html / markup
* Easy to work with teams.

# Pre-requisties
* Classes
* Destructuring
* Higher order array methods
* Arrow functions
* Fetch api and promises

# React state

Components can have state which is an object that determines how that component renders and behaves

We can also have application level state by using a  state manager like **Redux** or Reacts own **Context API**

# Create react app

* CLI tool
* Uses webpack
* Comes bundled with a dev server with hot reload
* "npm run build" will compile all your code to something that the browser can read

# Anotomy of a component

* Class based component

  ```js
  Class Post extends React.component {
    state = {
      title : '' ,
      body : ''
    }

    render() {
      return (
        <div>
          <h3> {this.state.title} </h3>
          <p> </p>
        <div>
      )
    }
  }
  ```