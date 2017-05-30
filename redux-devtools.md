# Redux DevTools

## React Hotloader
It works by taking your methods, storing them separately, and instead replacing the methods on your class with proxies that call those stored methods.

Every time you save a file, it replaces the stored methods, so that the proxies now point to the new versions.

## From Flux to Redux
It's difficult to make an effective developer tool if state is constantly mutating. This is part of the reason for the Redux implementation of the reducer.
