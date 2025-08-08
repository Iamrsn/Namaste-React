# Namaste React

# Parcel
- Dev Build
- Local Server
- HMR = Hot Module Replacement
- File Watching Algorithm - Written in C++
- Catching - Faster Builds
- Image Optimization
- Minification
- Bundling
- Compressing
- Consistent Hashing
- Code Splitting
- Differential Bundling - Support Older Browser
- Diagnostic
- Good Error Handling
- Better Error Suggestion
- HTTPs
- Tree Shaking - remove unused Code
- Different dev and production bundles
  

# Two types of Export/Import

- Default Export/Import

export default Component;
import Component from "path";

- Named Export/Import
export const Component;
import {component} from "path";

# React Hooks
- Normal JS utility function
- useState() - SuperPowerful State Variables in react
- useEffect()

What is reconciliation?
reconciliation
The algorithm React uses to diff one tree with another to determine which parts need to be changed.
update
A change in the data used to render a React app. Usually the result of `setState`. Eventually results in a re-render.
