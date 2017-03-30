# ExampleBot

This bot retweets the latest tweet using the "#whateverhashtagyouwant" hashtag. It attempts to retweet once per second for testing.

## Installation

1. git clone 
1. `npm install twit`
1. update the config.js to your twitter keys
1. run ```node bot.js```
1.  let the good times roll

This installs some code to the `npm_modules` subdirectory, which you don't need to worry about. (It's Twit, the library that lets us talk to Twitter.)

## Connecting to Twitter

https://dev.twitter.com/apps/new



```javascript
module.exports = {
  consumer_key:         'blah',
  consumer_secret:      'blah',
  access_token:         'blah',
  access_token_secret:  'blah'
}
```



`node bot.js`

Hopefully at this point you see a message like "Success! Check your bot, it should have retweeted something." Check the Twitter account for your bot, and it should have retweeted a tweet with the #whateverhashtagyouwant hashtag.

![In Action](https://dl.dropboxusercontent.com/u/32232546/Screen%20Shot%202017-03-30%20at%202.07.45%20PM.png "In Action")


