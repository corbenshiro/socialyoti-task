# SocialYoti case study



## Built with

* Node / Express
* React
* Redux
* Immutable
* PubNub
* Yoti


## Wins

* Real-time comunication across multiple channels
* Full Yoti integration
* Able to restrict rooms based on Yoti profile
* 1st time using React/Redux/Immutable


## Challenges to overcome

* Unable to send selfie to PubNub for chat history, URL becomes too long trying to send the base64
* Give better feedback when a user does not pass a room restriction (right now it is a console message)
* Remove the small areas of React state, switch to Redux there
* Somehow call the API in the controller (middleware) instead of Axiom (Axiom is nice though)
* Make it look nicer


## Bugs

* View not updating when changing room (but new messages ingress/egress WILL be published there)


## Running the app

Development:

```bash
$ npm run dev
```

Production:

```bash
$ npm start
```
