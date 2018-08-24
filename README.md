<p align=center>
<img src="https://i.imgur.com/zy3X2wS.png">
</p>
<p align=center>

<a target="_blank" href="http://nodejs.org/download/" title="Node version"><img src="https://img.shields.io/badge/node.js-%3E=_6.0-green.svg"></a>
<a target="_blank" href="https://opensource.org/licenses/MIT" title="License: MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>

</p>

## Node.js-Facebook-Anonymous-Post

Simple Facebook anonymous post to fan page timeline system, Fast to submit user post content, And using Firebase authentication to identify.

## Features

*  🕑 Real time to submit user post.
*  🖼️ Support user submit post with picture.
*  🧖 Firebase authentication to avoid spamming.
*  📝 Record remote user submit content, IP and User-Agent.

## Install 

```Shell
$ git clone git@github.com:stu01509/Node.js-Facebook-Anonymous-Post.git
$ cd Node.js-Facebook-Anonymous-Post
$ npm install 

```

## Setting 

1. Setting Facebook Graph API Access Token.

  📌Note: Post to fan page require publish_pages and manage_pages [permission](https://developers.facebook.com/docs/facebook-login/permissions).

```Shell
  1. Open .env File.

  2. Find Facebook_Access_Token = Your_Access_Token #2

  3. Paste your Facebook Graph API Token to Replace Your Access_Token.

```

2. Setting Firebase confing.

Go to [Firebase](https://console.firebase.google.com/u/0/) cretae a new project, And add Firebase config, Then click authentication enable sign-in method.

```Shell
  1. Open .env File.

  2. Find apiKey = Your_apiKey  #5;

  3. Paste your Firebase config to Replace All Value.

```

3. Setiing Post Tag Number.

```Shell
  1. Open .env File.

  2. Find tag =  #13;

  3. Replace to Your Number.

```
<img width="600" src="https://imgur.com/eqgCPaY">

## Usage

In project directory using node index.js, The app will listen on 3000 port, Running in localhost:3000

```Shell
$ node index.js

```
<img width="600" src="https://i.imgur.com/5Er18jy.gif">

## Demo

This project deploy on Azure free plan, Need a some time to wake up the app.  
🌐[Demo](https://nodejs-facebook-anonymous-post.azurewebsites.net/)

### Text Post

<img width="600" src="https://i.imgur.com/7DU6R7P.gif">

### Text and Picture Post

<img width="600" src="https://i.imgur.com/Jpr1uZ1.gif">

## Lisense
MIT
