
<p align="center"><a href="https://rjnitt.github.io/roso.github.io/"><img src="./assets/wedding.gif" width="150px" height="150px"/></a></p>
<h1 align="center"><a href="https://rjnitt.github.io/roso.github.io/">Wedding Invitation</a> :ring: <br> <br> SAVE THE DATE: 11th June, 2022 <br> <a href="https://rjnitt.github.io/roso.github.io/">https://rjnitt.github.io/roso.github.io/</a></h1>

[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vinitshahdeo/Wedding-Invitation?logo=github)](https://rjnitt.github.io/roso.github.io/) [![Netlify Status](https://api.netlify.com/api/v1/badges/e945f101-f434-45e6-8c33-df855c6b2082/deploy-status)](https://app.netlify.com/sites/sonali/deploys) [![GitHub license](https://img.shields.io/github/license/vinitshahdeo/Wedding-Invitation?logo=github)](https://github.com/vinitshahdeo/Wedding-Invitation)

## Wedding Invitation :ring:

<details>
  <summary><strong>View Invitation</strong></summary>
  <a href="https://rjnitt.github.io/roso.github.io/"><img src="./assets/img/sonali.jpeg" /></a>
</details>

With the divine grace of the almighty,
inviting you and your family to elder sister's wedding to be held on **11th June at [Diamond Palace](https://goo.gl/maps/Xw372J735w6YQKdM7), Tikamgarh from 7:00 PM** onwards.

- [Download](https://github.com/rjnitt/roso.github.io/raw/master/invitation/roso-wedding-invite.pdf) the Invitation card

- Find [venue](https://goo.gl/maps/Xw372J735w6YQKdM7) on Google map


```js

const newCouple = 'Rohit & Sonam';

// 11th June, 2022
const weddingDate = new Date(2022, 6, 11);

// Wedding venue: https://goo.gl/maps/Xw372J735w6YQKdM7
const weddingVenue = new Location('Diamond Palace, Tikamgarh');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://rjnitt.github.io/roso.github.io/')
    );
})();


```

## Are you or your loved ones a *bride-to-be* or *groom-to-be*? 
> Feel free to use this template to build your wedding website!

To reuse this, follow the steps:

- *Replace the date in [script.js](https://github.com/vinitshahdeo/Wedding-Invitation/blob/master/js/script.js#L29) to have a timer running for your big day!*

```js
// Set the date we're counting down to
var countDownDate = new Date("11th June, 2022 00:00:00").getTime();
```

- *If you wish to change the track which plays on click, edit the `src` in [index.html](https://github.com/vinitshahdeo/Wedding-Invitation/blob/760c4aa437115fc365f5cb86a4b428b0e292b5ba/index.html#L69)*

```html
<div class="music">
   <audio src="./assets/mp3/song.mp3" id="my_audio" loop="loop"></audio> 
</div>
```
