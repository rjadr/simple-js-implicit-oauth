# simple-js-implicit-oauth
A simple javascript application for an implicit oauth flow.
***
After having tried some javascript oauth libraries such as [jso](https://github.com/andreassolberg/jso) to implement an [implicit oauth flow](https://auth0.com/docs/api-auth/tutorials/implicit-grant) in javascript, I decided to make a simple alternative myself. This implementation uses [lscache](https://github.com/pamelafox/lscache) to solve the issue of token expiration in localstorage. 
