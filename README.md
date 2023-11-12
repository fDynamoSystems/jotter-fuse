# Overview

This is a fork of [fuse.js](https://github.com/krisk/Fuse) for specific use in [Jotter](https://github.com/fDynamoSystems/jotter-app). All credits due to the original creator of fuse.js and its community.

## How to use changes here for the main Jotter repo

If you make changes here, run

```
npm run build
```

Then move dist files over to the main repo under `custom_dependencies`.

## Specific fuse.js changes

Changes made include:

- editAt function
- pseudoRemove at function
- getDoc, getDocs, and getDocSize functions
