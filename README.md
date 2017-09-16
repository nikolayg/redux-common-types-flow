# redux-common-types-flow
Common Flow types for Redux Actions and Reducers

This module exports common Flow types for Redux Actions and Reducers.

Here are the definitions:

```javascript
export interface Action<Payload> {
  type: string;
  payload: Payload;
}

export type APIAction<Payload> = Action<Promise<Payload>>;

export type ActionCreator<Params, Payload> = (params: Params) => Action<Payload>;

export type APIActionCreator<Params, Payload> = (params: Params) => APIAction<Payload>;

export type Reducer<State, Payload> = (state: State, action: Action<Payload>) => State;
```

For more documentation and examples visit http://nikgrozev.com/2017/09/16/redux-common-types/
