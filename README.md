 <p align="center"><img src="https://i.imgur.com/61ZghpN.png" width="155" height="85"> </p>
<h1 align="center"> Novel </h1>
<br>
<p align="center">Novel is an quick-and-dirty framework used for designing user interfaces.</p>
<br>
<h2> Installation</h2>
<p>You can pull this repository get the newest version (but this is maybe not the stable variant). You also can install our NPM package:
<pre>
npm i novelapp</pre>
<br>
After you created your project with Novel you can start building your app. If you made changes and you want to check if everything is still working, we advise:
<pre>
npx webpack</pre>
And after you have created a succesfull build you can use this for a quick peek at your website/app:
<pre>
npm start</pre>
<h2> Example</h2>
<p>A example of the functionality of Novel:</p>

```jsx
const HelloComponent = () => {
    return <h1>Welcome to Novel</h1>;
}

ReactDOM.render(<HelloComponent />, document.getElementById('root'));
```

<p>This example will render "Welcome to Novel" into a container on the page.</p>
 
