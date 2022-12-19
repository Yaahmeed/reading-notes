# Foundations  

## Why these topics matter as it relates to this this module  

Local data storage is important to save certain data in case someone leaves the page and wants to come back and resume at a later time.  

### Local Storage  

1. HTTP is stateless, so by using local storage we can store the state of our interface somewhere, so that if someone closes the page/app and reopens it, the state is restored, instead of restarting entirely.  
2. Local storage should NOT be used to store user(s) sensitive information/data.  
3. Local storage can store strings. You can get around this by using the native `JSON.stringify()` and `JSON.parse()` methods.  

## Things I want to know more about

- I would like an example of how to use local storage to store previously selected results over multiple rounds.
