 <p align="center"><img src="https://i.imgur.com/F0Pnoho.png" width="250" height="250"> </p>
<h1 align="center"> Novel </h1>
<br>
<p align="center">Novel is an Typescript library used for designing user interfaces.</p>
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

<p>If you're using Novel as a <script> tag, read this section on integrating JSX; otherwise, the recommended JavaScript toolchains handle it automatically.</p>
 
<h2> Documentation</h2>
<table>
<thead>
<tr>
<th>Process</th>
<th>Description</th>
</tr>
</thead>
<tbody>
 
<tr>
<td>HelloComponent()</td>
<td>Sets a H1 with a welcome message to Novel</td>
</tr>
 
</tbody>
</table>
<h2> Supported</h2>

 <p>All languages down below is supported from Novel. We want to give the user/developer as easy time as possible so we want to document the languages that were are supporting in Novel atm and we also want to give you a idea what were planning ahead in the future.</p>
 <h4> Workable</h4>
        <li>Typescript</li>
        <li>Javascript</li></ul>
 <h4> Workable in the future</h4>
        <li>PHP</li></ul>
