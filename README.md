# About this module

This module exports Common [Flow](https://flow.org/) types for Redux Actions and Reducers,

# Installation:

```bash
npm install --save redux-common-types-flow
```
or

```bash
yarn add redux-common-types-flow
```
# What and How

This module exports the following common Flow types for Redux Actions and Reducers.

- `APIAction<Payload>`
- `APIAction<Payload>`
- `ActionCreator<Params, Payload>`
- `APIActionCreator<Params, Payload>`
- `Reducer<State, Payload>`

Import the types as:

```javascript
import {type APIActionCreator} from 'redux-common-types-flow';
import {type Action} from 'redux-common-types-flow';
// ....
```

For more information and examples read 
[this article](http://nikgrozev.com/2017/09/16/redux-common-types/).
