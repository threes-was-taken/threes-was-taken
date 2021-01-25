<h2>Hi, Good to see you here! :relaxed:</h2>
<img align='right' src="https://media.giphy.com/media/l46ChKeGsmsfE3Un6/source.gif" width="230" />

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://codepen.io/threes-was-taken" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/codepen.svg" alt="threes-was-taken" height="30" width="40" /></a>
<a href="https://twitter.com/_droes_" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="_droes_" height="30" width="40" /></a>
<a href="https://linkedin.com/in/dries-verelst" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="dries-verelst" height="30" width="40" /></a>
</p>
<br />
<br />
<br />

<p align="left"><a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=threes-was-taken" alt="threes-was-taken"></a></p>

<br />
<br />
<br />

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

  getSkills() {
    return {
      'languages':[
      'Javascript ES6',
      'Java',
      'NodeJS',
      'markup':[
        'HTML',
        'CSS',  
        ],
      'frameworks':[
        'ReactJS',
      ],
      ],
      'databases':[
        'MSSQL Server',
        'MongoDB',
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
        'Figma',
      ]
    }
  }

  getTools() {
    return ['Visual Studio Code', 'GitKraken', 'CodePen.io', 'Postman']
  }

  getFutureGoals() {
    return {
      OpenSource:'I want to become a open sourcerer in my free time',
      Growth:'As a developer and as a human',
      Learn:'As an IT engineer, I am an eternal student',
      Languages_Tools_Frameworks:'Learn Typescript, Less, SASS & Figma'
    }
  }

  getFunFacts(){
    return[
      'I enjoy building LEGO',
      'I love working in the garden',
      'I enjoy taking care of my two dogs',
      'I enjoy watching animes like DBZ, One Piece, Naruto, Demon Slayer,...'
    ]
  }
}

export default User
```

[![Visits Badge](https://badges.pufler.dev/visits/threes-was-taken/threes-was-taken)](https://github.com/threes-was-taken)
