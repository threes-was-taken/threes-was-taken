<h2>Hi, Good to see you here! :relaxed:</h2>
<img align='right' src="https://media.giphy.com/media/yYSSBtDgbbRzq/giphy.gif" width="230">

<h3>Contact</h3>
[![Twitter: Droes](https://img.shields.io/twitter/follow/_Droes_?style=social)](https://twitter.com/ThaiiBraga)  
[![Linkedin: DriesVerelst](https://img.shields.io/badge/-thaianebraga-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dries-verelst/)](https://www.linkedin.com/in/dries-verelst/)  
[![GitHub Threes](https://img.shields.io/github/followers/threes-was-taken?label=follow&style=social)](https://github.com/threes-was-taken)

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
