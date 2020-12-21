<h2>Hi, Good to see you here! :relaxed:</h2>

<h3>Contact</h3>
<p>
  <a class="twitter-follow-button"
    href="https://twitter.com/_droes_"
    data-size="large">Follow @_Droes_</a>
</p>
[LinkedIn](https://www.linkedin.com/in/dries-verelst/)
[GitHub](https://github.com/threes-was-taken)

```javascript
import React from 'react'

class User extends React.Component {
  constructor(){
    //General info
    this.firstName = 'Dries'
    this.lastName = 'Verelst'
    this.nickName = 'Threes'
    this.dateOfBirth = new Date(1998, 6, 18) // JS counts months 0-based (0 being Jan, 11 being Dec)
    this.gender = 'Male'
    this.country = 'Belgium'
  }

  function getSkills() {
    return {
      'languages':[
      'Javascript ES6',
      'Java',
      'NodeJS',
      'markup':[
        'HTML',
        'CSS'    
        ]
      'frameworks':[
        'ReactJS'
      ]
      ],
      'databases':[
        'MSSQL Server',
        'MongoDB'
      ],
      'misc':[
        'Bash',
        'Linux',
        'VMWare',
        'Git',
        'Docker',
      ],
      'inDueTime':[
        'Typescript',
        'SASS',
        'VueJS',
        'Figma'
      ]
    }
  }

  function getTools() {
    return ['Visual Studio Code', 'IntelliJ IDEA', 'GitKraken']
  }

  function getFutureGoals() {
    return {
      OpenSource:'I want to become a open sourcerer in my free time',
      Growth:'As a developer and as a human',
      Learn:'As an IT engineer, i-I am an eternal student',
      Languages_Tools_Frameworks:'Learn Typescript, SASS, VueJS and Figma'
    }
  }
}

export default User
```
