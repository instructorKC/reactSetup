# reactSetup


1. In terminal type `npx create-react-app my-app-name-here`
2. In terminal type `cd my-app-name-here`
3. Go to github and create a new repository without a readme
4. Follow the directions github(start at command git branch -M main re-naming)  re-naming the branch from master to main

`git branch -M main`

`git remote add origin https://github.com/**YourURLHERE**/**YourREPO**t.git`   ( Copy and paste YOUR remote)

`git push -u origin main`

5. convert your App component in app.js to a class. Use this one:

```javascript
import React, {Component} from 'react';

  class App extends React.Component {
    constructor(props) {
      super(props);
      this.state = {
      
      };
    }
    render() {
      return (
          <div>
             <h2>Your component works</h2>;
          </div>
      )
    }
  }
  
  export default App;

```

