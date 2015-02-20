# angular-fqueue
Javascript implementation of Array with fixed size (Fixed Queue) for AngularJS<br/>
The implementation is based on Ben Nadel's [Gist](https://gist.github.com/bennadel/9760671)

## Installation

#### Bower
```
bower install angular-fqueue
```
#### NPM
```
npm install angular-fqueue
```

## Dependencies
FixedQueue depends on Angular only.

## Usage
Add 'fqueue' as a dependency to your app and inject FixedQueue into your controller or service.

````javascript
angular.module('myApp', ['fqueue']);

angular.module('myApp').controller('MyController', function($scope, FixedQueue) {
  // ...
});
````