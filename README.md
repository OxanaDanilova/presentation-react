# Transcript of the Presentation
00:02
Hi, everyone.
00:03
I am Oxana and I am going to say about React.
00:17
What is React?
00:20
React is a JavaScript library created by Facebook.
00:24
React is a tool for creating reusable UI components.
00:30
How does React work?
00:31
Instead of manipulating the browser's DOM directly,
00:33
React creates a virtual DOM in memory, where it does
00:36
all necessary manipulating, before making the changes in the browser DOM.
00:38
This process improves the performance exponentially and this entire process in React
00:51
terminology is known as Reconciliatory Algorithm.
01:02
This process consist of three simple steps.
01:09
Whenever any underlying data changes, the entire UI is re-rendered in Virtual DOM representation.
01:19
Then the difference between previous DOM representation and the new one is calculated.
01:26
Once the calculations are done, the real DOM will be updated with only things that have
01:42
actually changed.
01:44
React's goal is in many ways to render HTML in a web page.
01:57
It could be done with ReactDOM.render() function This function takes two arguments, HTML code
02:10
and an HTML element.
02:14
For example, this Html code could be displayed in specified html element with id root.
02:24
Also I want to say a few words about React JSX.
02:29
JSX allows us to write HTML in React. also it allows to create React element.
02:44
Actually JSX, a markup language similar to HTML but actually an extension to JavaScript
02:54
JSX elements can act as values for identifiers.
03:05
On this slide you can see how to declare variable with a JSX element as the value.
03:19
JSX supports all JavaScript Expressions by wrapping them in curly brackets.
03:30
JSX supports attributes the same way as HTML but also supports attributes are written in
03:50
camelCasing.
03:52
In the biginning of presentation I said that React is a tool for creating reuseble UI component.
04:04
So what are the components in React?
04:08
Components let you split the UI into independent, reusable pieces, and think about each piece
04:19
in isolation.
04:21
You can create Components with ES6 Class and Functions
04:38
On this slide you can see how to create a Class Component
04:43
The component has to include the extends React.Component statement and render() method.
04:53
On this slide you can see how to create a Function Component, which returns React element
05:13
React props.
05:14
Props are arguments passed into React components.
05:24
On this slide you can see React state.
05:28
React components has a built-in state object.
05:30
The state object is where you store property values for react component.
05:41
When the state object changes, the component re-renders.
05:55
Also I want add a few words about React in comparison with another JavaScript Library
06:08
and Framework.
06:11
For example, in comparison with Angular and Vue.
06:21
On this slide you can see that React is is more popular according to stack overflow statistics
06:36
and google trends.
06:37
And here you can see quick comparison Angular React and Vue.
06:44
Angular is a framework, Reaact and Vue are Library.
06:51
You can choose Angular if you want to use Typescript.
06:55
And you can choose React if you want to go for everything JS approach.
07:04
You should choose Vue in order to use easy JS and HTML
07:11
React was created by Facebook as I said before.
07:18
Angular was created by Google.
07:22
Vue was created by former Google employee.
07:27
Angular is ideal if you want focus on largescaled, feature reach app.
07:38
React is suitable for you if you want create native-rendered apps
07:56
Vue is ideal for web development and single page
08:07
application React and Vue are based on Virtual DOM (Document
08:12
Object Model) Angular is based on MVC (Model Vue Controller)
08:24
architecture.
08:26
Language preference for Angular is Typescript, for React is JSX (Javascript XML)
08:35
and for Vue HTML template and JS There are many companies which use Angular
08:45
(for example, Google, Forbes, wheather.com) React is used by Facebook, Netflix and others
08:56
Vue is used by Alibaba, Gitlab and other companies In conclusion I want add tha Vue and React
09:08
offer better performance and flexibility than Angular.
09:11
Vue and react are more suited for light-weight applications and angular is the best for large
09:24
UI applications.
09:28
That is actually all what I want to say about React.
09:36
Thank you for your attention.
