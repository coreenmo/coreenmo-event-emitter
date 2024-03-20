

## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
// Import EventEmitter from the package
const EventEmitter = require('./src/EventEmitter');

// Create an instance of EventEmitter
const emitter = new EventEmitter();

// Define a listener function
const listener = (data) => {
  console.log('Event triggered with data:', data);
};

// Register the listener for the 'customEvent' event
emitter.on('customEvent', listener);

// Emit the 'customEvent' event with some data
emitter.emit('customEvent', 'Hello, World!');

// Remove the listener for the 'customEvent' event
emitter.off('customEvent', listener);
```

#### Explanation

* The "Event Emitter" package has three main methods: on, emit, and off.
* The on method is used to add a listener to an event.
* The emit method is used to emit an event with optional parameters.
* The off method is used to remove the listener from an event.

#### Return Value

* The on and off methods do not return a specific value.
* The emit method does not return a value and is only used to trigger the event.
