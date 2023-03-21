# PasswordGenerator

### About
A password generator project built with JavaScript, frontend's HTML and CSS is manipulated with 'vanilla' DOM, I have then included this project in my bigger full-stack project <a href="https://github.com/Aleksandar15/password-manager-frontend">password manager</a> app. 😊
- In the <a href="https://github.com/Aleksandar15/PasswordGenerator/blob/master/index.html">index.html</a> file I used `defer` attribute on the `script` element which is similar to the `async` attribute when downloading JS content in the *background*, but the advantage is that the *script* would be executed once the HTML document has been parsed and that way it doesn't stop/pause the HTML from being loaded first.
  - Worth noting is that the `defer` attribute works very similarly if I was to add the `script` tag to the very bottom inside the `body` element -> the only advantage is that I can have the script tag on the top inside `head` element and find out much faster which *scripts* I am importing without having to scroll to the bottom to see it.

#### My live app https://aleksandar15.github.io/PasswordGenerator

#### Technologies
###### JavaScript, CSS3, HTML5

### Run my project
- Clone this project.
- In code editor like VS Code install *Live Server* extension.
- Navigate to the *index.html* file and click the "*Go live*" button.
