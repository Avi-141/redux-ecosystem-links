### Middleware


#### Promises

- **redux-promise**  
  https://github.com/acdlite/redux-promise  
  FSA-compliant promise middleware for Redux.
  
- **redux-simple-promise**  
  https://github.com/alanrubin/redux-simple-promise  
  FSA-compliant promise middleware for Redux with simple behaviour with minimal boilerplate declarations.
  
- **redux-catch-promise**  
  https://github.com/DenisIzmaylov/redux-catch-promise  
  Extended replacement of redux-thunk middleware to supporting async-await functions and implement server-side rendering for React components with asynchronous state.
  
- **redux-async**  
  https://github.com/symbiont-io/redux-async  
  RSA-compliant actions which resolve when any prop is a promise middleware for Redux.
  
- **redux-promise-middleware**  
  https://github.com/pburtchaell/redux-promise-middleware  
  Redux middleware for resolving and rejecting promises with conditional optimistic updates
  
- **redux-deferred**  
  https://github.com/wyvernnot/redux-deferred  
  Redux middleware for jQuery Deferred object
  
- **redux-promises**  
  https://github.com/CrocoDillon/redux-promises  
  Promise based middleware for Redux to deal with asynchronous actions. redux-promises is backwards compatible with redux-thunk.
  
- **redux-optimist-promise**  
  https://github.com/mathieudutour/redux-optimist-promise  
  FSA-compliant promise middleware middleware for Redux and automatically add necessary for redux-optimist.
  
- **redux-async-middleware**  
  https://github.com/reducks/redux-async-middleware  
  Provides a middleware for handling asynchronous actions.
  
- **redux-pending**  
  https://github.com/adriancooney/redux-pending  
  A promise middleware that you add to your store and will handle resolving the promises and dispatching pending actions. It's based heavily around redux-promise.
  
- **redux-promised**  
  https://github.com/bobmonteverde/redux-promised  
  FSA-compliant promise middleware for redux with optimistic update support
  
- **redux-await-middleware**  
  https://github.com/zenato/redux-await-middleware  
  Await(Promise) middleware for Redux.  Await middleware supprorts FSA actions.
  
  
#### Timeouts and Delays

- **redux-timeout**  
  https://github.com/gpfunk/redux-timeout  
  Gives ability to call functions if certain actions have not been dispatched in x amount of time.
  
- **redux-trigger**  
  https://github.com/coderkevin/redux-trigger  
  a Redux middleware which allows delayed dispatching of an action based on a trigger state in the Redux store.
  
- **redux-debounced**  
  https://github.com/ryanseddon/redux-debounced  
  Debounce allows you to discard a fast paced action from updating your state until a certain period of time passes after the last action is fired.
  
- **redux-delay**  
  https://github.com/Laiff/redux-delay  
  Delay redux actions
  
- **Redux Action Buffer**  
  https://github.com/rt2zz/redux-action-buffer  
  A middleware for redux that buffers all actions into a queue until a breaker condition is met, at which point the queue is released (i.e. actions are triggered).
  
- **Quince**  
  https://github.com/defact/quince  
  Queueing middleware for Redux.
  
- **redux-throttle-actions**  
  https://github.com/pirosikick/redux-throttle-actions  
  A Redux middleware which throttles actions.
  
- **redux-debounce**  
  https://github.com/wyze/redux-debounce  
  A middleware for Redux to debounce actions.
  
  
#### Other Async Actions
  
- **redux-await**  
  https://github.com/kolodny/redux-await  
  Manage async redux actions sanely.  This module exposes a middleware, reducer, and connector to take care of async state in a redux app.
  
- **Redux Async Initial State**  
  https://github.com/KELiON/redux-async-initial-state  
  Redux middleware for async loading of initial app state.

- **redux-future**  
  https://github.com/stoeffel/redux-future  
  FSA-compliant future monad middleware for Redux, based on redux-promise.
  
- **redux-io**  
  https://github.com/stoeffel/redux-io  
  FSA-compliant io monad middleware for Redux, based on redux-future.
  
- **redux-either**  
  https://github.com/stoeffel/redux-either  
  FSA-compliant either monad middleware for Redux, based on redux-future.
  
- **redux-wait**  
  https://github.com/ForbesLindesay/redux-wait  
  A helper to let you wait for redux actions to be processed in a universal app.
  
- **redux-save**  
  https://github.com/Legitcode/redux-save  
  Full featured middleware for handling async actions and automagically saving data (For RN & Web)
  
- **redux-notify**  
  https://github.com/zalmoxisus/redux-notify  
  Redux middleware to notify when an action from the list is dispatched.
  
- **redux-co**  
  https://github.com/kilianc/redux-co  
  redux-co is a drop-in replacement for redux-thunk (and indeed passes its test suite). It's meant to support async actions through yieldables as well as plain thunk functions.
  

#### Action Grouping and Interception

- **redux-combine-actions**  
  https://github.com/itsmepetrov/redux-combine-actions  
  A Redux middleware that allows you to easily combine async actions and dispatch them either sequentially or in parallel.
  
- **redux-batch-middleware**  
  https://github.com/mrydengren/redux-batch-middleware  
  Batch middleware for Redux. Inspired by redux-batched-actions.
  
- **redux-sequence-action**  
  https://github.com/jasonslyvia/redux-sequence-action  
  A middleware enabling sequential action dispatch for Redux.
  
- **redux-multi**  
  https://github.com/ashaffer/redux-multi  
  Dispatch multiple actions from one action creator
  
- **redux-next**  
  https://github.com/RnbWd/redux-next  
  Recurse Redux actions
  
- **redux-signals**  
  https://github.com/itaylor/redux-signals  
  A redux middleware that allows the creation of 'signal' actions that don't have reducers of their own, but instead dispatch other actions.
  
- **redux-action-listeners**  
  https://github.com/rhythnic/redux-action-listeners  
  This is Redux middleware for listening to actions. The middleware is configured with actionListeners, and those action listeners are called after the reducer runs. The action listeners receive the action and the store.
  
- **redux-handle-actions**  
  https://github.com/joshrtay/redux-handle-actions  
  Redux middleware for handling actions.
  
- **redux-white-black**  
  https://github.com/rnsloan/redux-white-black  
  Redux middleware to execute a callback on action types using a whitelist or blacklist approach
  
 
  
  
  
#### Sockets and Adapters

- **redux-socket**  
  https://github.com/quirinpa/redux-socket  
  A redux middleware that allows you to trigger a socket request on the client-side and dispatch an action in response.
  
- **redux-observable-middleware**  
  https://github.com/d6u/redux-observable-middleware  
  Redux middleware for subscribing to observables in action creators.
  
- **redux-via**  
  https://github.com/rstuven/redux-via  
  redux-via provides a basis for using Redux across boundaries with Flux Standard Actions.
  
- **redux-streams**  
  https://github.com/Industrial/redux-streams  
  Store middleware for Redux that lets you dispatch streams of actions.
  
- **cape-redux-socket**  
  https://github.com/cape-io/cape-redux-socket  
  Socket middleware, reducer, actions, constants
  
- **redux-middleware-oneshot**  
  https://github.com/michaelcontento/redux-middleware-oneshot  
  Create Redux actions from arbitrary sources out of middlewares.
  
- **redux-socket-middleware**  
  https://github.com/madewithlove/redux-socket-middleware  
  Redux middleware that dispatches an action to all connected clients
  
- **socket.io-redux**  
  https://github.com/sergiodxa/socket.io-redux  
  Redux middleware to emit actions to a socket.io server
  
- **redux-ws**  
  https://github.com/arturmuller/redux-ws  
  Redux middleware for WebSockets communication.
  
- **twiliojs-redux**  
  https://github.com/yarcub/twiliojs-redux  
  Twilio's javascript SDK middleware for Redux.
  
- **redux-action-emit-middleware**  
  https://github.com/pafciu17/redux-action-emit-middleware  
  Middleware for emitting redux actions over socket
  
- **redux-loopback**  
  https://github.com/TimPerry/redux-loopback  
  Loopback middleware for redux
  
- **redux-zmq**  
  https://github.com/code-mancers/redux-zmq  
  A redux middleware for zeromq
  
- **redux-matter**  
  https://github.com/KyperTech/redux-matter  
  Redux middleware, actions, and reducer for Matter.
  
- **redux-effects-socketio**  
  https://github.com/alexjg/redux-effects-socketio  
  Redux effects middleware for socketio
  
- **redux-socket-io**  
  https://github.com/nkt/redux-socket-io  
  Socket.io middleware for Redux.
  
- **redux-ddp**  
  https://github.com/rclai/redux-ddp  
  Get DDP collection data synced straight into a Redux store instead of minimongo and attempting optimistic updates.
  
  
#### Network Requests

- **redux-request**  
  https://github.com/TossShinHwa/redux-request  
  Uses either fetch or superagent to make requests.
  
- **reduxr-async**  
  https://github.com/chrisdavies/reduxr-async  
  Easily and cleanly handle AJAX in Redux.
  
- **redux-api-middleware**  
  https://github.com/agraboso/redux-api-middleware  
  Redux middleware for calling an API.
  
- **redux-axios-middleware**  
  https://github.com/svrcekmichal/redux-axios-middleware  
  Redux middleware for fetching data with axios HTTP client
  
- **redux-callApi-middleware**  
  https://github.com/fskinner/redux-callApi-middleware  
  Redux middleware for API calls through Axios
  
- **redux-request-middleware**  
  https://github.com/founderlab/redux-request-middleware  
  Works like redux promise middleware. Resolves request objects from superagent or BackboneORM models. Can work with anything with a similar callback style api.
  
- **redux-fetch-middleware**  
  https://github.com/LuckyZhou880808/redux-fetch-middleware  
  A middleware for redux that help to fetch data from rest API
  
- **redux-axios-api-middleware**  
  https://github.com/mikeyamadeo/redux-axios-api-middleware  
  redux middleware using axios making api calls with redux easy
  
- **rictus**  
  https://github.com/defact/rictus  
  Redux middleware for promise-based resource requests
  
  
#### Analytics

- **redux-analytics**  
  https://github.com/markdalgleish/redux-analytics  
  Analytics middleware for Redux.
  
- **rn-redux-mixpanel**  
  https://github.com/danscan/rn-redux-mixpanel  
  Configurable redux middleware that sends your actions & user profile data to Mixpanel. It also works with React Native.
  
- **redux-keen**  
  https://github.com/pavelvolek/redux-keen  
  Redux middleware for sending analytics to Keen.
  
  
#### Data Management

- **redux-normalizr-middleware**  
  https://github.com/wbinnssmith/redux-normalizr-middleware  
  Combines redux middleware and normalizr to make flattening nested data a snap
  
- **redux-make-immutable**  
  https://github.com/kwhitaker/redux-make-immutable  
  Redux middleware to coerce native javascript types into the equivalent Immutable.js types. Works with both Flux Standard Actions and non-standard actions.
  
- **redux-make-mori**  
  https://github.com/kwhitaker/redux-make-mori  
  Redux middleware to coerce native javascript types into the equivalent Mori types. 
  
- **Redux Provider Middleware**  
  https://github.com/reduxible/redux-provider-middleware  
  A redux middleware which provides Angular-like providers.
  
- **redux-inject**  
  https://github.com/bradharms/redux-inject  
  Redux middleware generator that allows dependencies to be injected into action creators.
  
  
#### Other
  
- **redux-action-tracker**  
  https://github.com/gfogle/redux-action-tracker  
  Set of middlewares for Redux to instrument and track actions and their corresponding child actions.
  
- **redux-string**  
  https://github.com/igl/redux-string  
  Allow dispatching of a string as action-type
  
- **redux-favicon**  
  https://github.com/joshwcomeau/redux-favicon  
  Redux middleware that displays colourful notification badges in the favicon area.
  
- **Redux Worker Middleware**  
  https://github.com/keyanzhang/redux-worker-middleware  
  The goal of the middleware is to provide an unopinionated workflow that delegates expensive operations to Web Workers. 
  
- **Redux Sounds**  
  https://github.com/joshwcomeau/redux-sounds  
  Redux middleware that lets you easily trigger sound effects on actions. Makes it completely trivial to do so, by adding a meta property to any action.
  
- **redux-auth**  
  https://github.com/Nicktho/redux-auth  
  A simple redux middleware for JWT based authorization.  Works with any async store middleware.
  
- **postal-redux-middleware**  
  https://github.com/dehamilton/postal-redux-middleware  
  Middleware to interact with Postal.js
  