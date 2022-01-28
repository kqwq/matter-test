# Matter.js Test

Compiling matter.js project to Khan Academy using Webpack 5 

### Run locally
First, navigate to the root of the project.<br>
\> `git clone https://github.com/kqwq/matter-test.git .`<br>
\> `npm install`<br>
\> `npm run build`<br>

### Run on Khan Academy
\> Create a new webpage <br>
\> Copy the contents of the `main.bundle.js` file into a `<script type> ... </script>` tag<br>
\> Save and append ?width=800&height=600 to the URL<br>

### Develop locally
\> `npm run dev`<br>
This should open a new page of the url `http://localhost:8080/`<br>
Edit ./src/index.js to change the source code.
With over 1.3 million npm packages, the possibilities are endless.
Run `npm install <name of package>` to install a package. I've tested three.js, d3.js, simple-peer, etc. on Khan Academy. Works flawlessly.