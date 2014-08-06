# Meteor: Nested Blaze Layout

Currently results in:

```js
Exception from Deps recompute function: RangeError: Maximum call stack size exceeded
    at HTML.TransformingVisitor.def.visitAttribute (http://localhost:3000/packages/htmljs.js:241:22)
    at Blaze.HTMLJSExpander.def.visitAttribute (http://localhost:3000/packages/blaze.js:1973:62)
    at HTML.TransformingVisitor.def.visitAttributes (http://localhost:3000/packages/htmljs.js:226:44)
    at Blaze.HTMLJSExpander.def.visitAttributes (http://localhost:3000/packages/blaze.js:1965:63)
    at Object.Blaze._expandAttributes (http://localhost:3000/packages/blaze.js:1994:32)
    at updateAttributes (http://localhost:3000/packages/blaze.js:1416:35)
    at http://localhost:3000/packages/blaze.js:1805:16
    at Object.Blaze.withCurrentView (http://localhost:3000/packages/blaze.js:2038:12)
    at viewAutorun (http://localhost:3000/packages/blaze.js:1804:18)
    at Deps.Computation._compute (http://localhost:3000/packages/deps.js:214:36)
```
