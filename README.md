# reactSetup


1. In terminal type `npx create-react-app my-app-name-here`
2. In terminal type `cd my-app-name-here`
3. Go to github and create a new repository without a readme
4. Follow the directions github(start at command 5 branch renaming)  renaming the branch from master to main
4. git branch -M main (you can just copy and paste)
5. Copy and paste YOUR remote and add it to origin `git remote add origin https://github.com/**YourURLHERE**/**YourREPO**t.git`(do not copy this one copy yours)
6. git push -u origin main
7. convert your App component in app.js to a class. Use other classes you made as a model

```javascript
  class Car extends React.Component {
    constructor() {
      super();
      this.state = {color: "red"};
    }
    render() {
      return <h2>I am a Car!</h2>;
    }
  }

```


Check success
`git remote -v`
