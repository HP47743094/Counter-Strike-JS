# Counter-Strike JS

Counter-Strike 1.6 implementation in TypeScript utilizing state of the art browser APIs.

*Uses https://github.com/MathiasVP/CS as the base.*

### Current state
* Parses and renders .bsp files (version 30) containing map data
* Parses and renders .mdl files (version 10) with textures
* Camera movement, yaw and pitch fully implemented
* Collision detection implemented
* Naive gravity implemented

### Develop
***Please note: No actual data (maps, models, textures, etc.) is included in the project, due to copyright reasons!***

Install dependencies
```
npm install
```

Then start webpack
```
npm start
```

Open [http://localhost:9000](http://localhost:9000)


![Screenshot](http://i.imgur.com/9kMVte7.png)
