

# StoneOceanConfirmed

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a0b36049271740afba544b65d17b30d1)](https://app.codacy.com/app/RogerFerraro256/StoneOceanConfirmed?utm_source=github.com&utm_medium=referral&utm_content=RogerFerraro256/StoneOceanConfirmed&utm_campaign=Badge_Grade_Dashboard)

  

this is a project for an autonomous Twitter posting bot, this don't need to be pretty or have an actual site, this will work on Heroku, and this repository is just to save my code

  

  ```sh
I commented the code to don't have problems during the tests, 
again,to make it work you should put your twitter keys in the 
configuration file
```

# To begin:
```sh
install dependencys
$ npm install
execute it, theres others ways to do it,
$ npm start
for this project i use
$ node bot.js
```






## math operations

There isn't too much to explain about how the math in this project works, but i wanted to use this on the update 

Basically the only things that are important is the operation where we pick the time

![equation](https://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20one%20day%20%3D24*60*60*1000)

then we pick the difference between the two days

![equation](https://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20dif%3DfirstDay-secondDay)

and finally we transform the dif into a number of days

![equation](https://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20x%3Ddif/oneday)


## About the packages i used:

### Twit

Twit is a package that simplify the interation with twitter API, using lines like post, get and stream you can tweet the way you want, Twit is made by ttezel
  

### date-and-time

Date and time is a package that helps when we use time, before this, i was using the setInterval to tweet, but due some problems with heroku, i decided to use the date and time package.
On this project, since i have to post on the right time, i use this, if you don't need to worry about it, just leave it

## License

MIT


**Free Software, Hell Yeah!**
