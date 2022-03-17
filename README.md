

Note: this is work in progress.
*********
If you like to see this project coming into reality, you could consider giving your support.

Bitcoin wallet: 1CsaNof2QRNwZ3W2jvWFhXj982ojqgLyqi

Tropipay.com: https://tppay.me/l0bgadzc (Note: Tropipay is similar to PayPal, Stripe, etc). You can create an account [here](https://www.tropipay.com/signup/0LQ4	"Create a new account").

*********

### Project Name : "Universe Objectified" (yep, Earth and all the other stuff connected, all-data-known wise)

### Parent Project: "All-We-Need Graph" (exactly that! Today we have needs and have the right to find a way to fulfil them, as smoothly, as they arise, digitally wise)

### Glimpse

Don't you like to do that below?

```java
Earth.Italy.Weather; // returns "cloudy, 13 celcius degrees, wind: 6 km/h;"
Earth.Italy.Weather.Temperature; // returns 13.
```

That was an example. You could do that to get any data you might need. You could save going to type "Italy temperature" in some search engine (SE, pronounced 'si').

Note: people related to software engineering can picture this project as if it were a database or an API.

Mmm ... one more:

```java
Moon.LightTimeToEarth; // returns ~1 sec, the time light from the Moon takes to reach us.
```

### Goal

1. To view/access any data one might be interested in, in an easy, fast and accurate way.
2. To create a standard (format) that makes point 1 possible. 
3. To push forth the concept "one source of truth" - we want it always in one place. 
4. To input the location of data: no more searching for simple data such as a numbers, dates, etc.
5. To create the conditions for creating tools that meet such standard (see point 2) in order to provide a very nice way to mark and follow up data. Hum ... offline-first, data-saving-first, and all the other "*-first" you may name.
6. To encourage adoption, interoperability, from the viewpoint of software development, the output could be in a format suitable for it, perhaps, JSON. 

### History

This is not a new concept on its own. It is the next logical step in "data access", in which sense, this standard will seat at the top of it, leading us at the gates of fulfilling one of the things what we have always dream of: having "something that knows it all and we can question".

It is like a SE's perspective about the more than 100 million websites in existence: a partially-tidy "sea" of information. UD's perspective differs from the former in that, with it, you get exactly what you are looking for, neither more nor less. Moreover, when you search, usually, you get more than what you need, therefore, you may end up looking up for some time, maybe, more than you are comfortable with and spending other resources.

Let us say you need to know how many people are alive in the World. For that, you open a browser, type an address (url), usually, of a SE, maybe Google Search's (google.com) and in its textbox you input "World population". That returns several pages, each containing up to 10 results, then you start reading in the hope of finding how many millions we are.

There is an approach alternative to the previous one. What if you could type/click/tap "World.Population.Count" (3 clicks/taps) and the result being "8 billions"? What if you are interested in following such amount for updates? Well, those things and more could be existing today. In short, all the power of the SE to a standard, an excellent accompaniment for it in our search for knowing.

### Such pillars difference:

**SE:** works on partially-structured information. For example, bloggers write without creating objects from that information.

**UD:** works on absolutely structured data, hopefully: objects created from information.

---------------------------

###  Uses

1. **Live texts:** texts will have the possibility of being updated at all times because they will be referencing instead of "hard-typing" (similar to "hard-coded"). Writers/Bloggers will not be wasting time in updating. You could type: "Today's population has reach a tremendous amount. We are {World.Population.Count} people." 
2. **Ubiquity:** it will give something very powerful to Ubiquity (omnipresence; presence everywhere): ubiquitous information*. You will be able to watch/follow information anywhere you want (computer, phone, TV, and any other device). As a consequence, the HUD/Widget will get a very special touch of importance.
3. **Text-To-Speech**: this will get a significant boost because we like to speak the things we want to know - yeah, thinking kills us too - and there will be something able to answer anything we require. We like and need to do multitasking, and speaking is an ability that does not require to interrupt anything else we might be doing. 

### Advantages:

- Easy access to any information you need to know, like the way a SE works, with the difference that you will be knowing more about the information you will get, like you have seen it before and remember something about it, being enough to identify it. The DejaVu feeling.
- It will set the course for webmasters to integrate the data of their websites into a single, structured and unified view of our Universe, objectified.
- Minimal data usage.
- Time saving.

----

[*put a picture of how it would look World -> Countries; a treeview]  

A SE does it! It is already predicting what you might mean with a search query. For example: when you need to know the distance from A to B, it shows that in a format different to the one of the following results. [*put a picture showing the latter]

A SE processes queries in Natural Language; UD processes queries using the dot notation.

The name of the language "Query To Universe" (QU).

It should become a standard in order to allow every data provider (anyone/anything publishing information) to implement it and thus make the "Universe" aware of its existence. A data provider, as the noun suggests, gives information (contextual data) about itself. It could be anyone/anything doing that. For example, a website master/service.

It could be so good that the problem of "how I get aware of the existence of information I ~~would~~ care about, affect or relate to me?" could be completed solved. Moreover, the problem of "[I am reading something and] just like that a doubt arises and I cannot kill it" would be gone.

While I was describing this project, the need for a way to know if you are interested in it arouse. I need~~ed~~ a way to capture, to know, how many people are interested in it. If this project was already implemented I could do:

Earth.Websites where website.main_goal == SERVE_AS_STORAGE and website.burdensome == false and website.developer_ready == true;

Results:
### URL                |  DESCRIPTION                                                                  | WIDGET | MUCH ... MORE INFO ...
---
soocool.com  | has a nice api to easy capture likes; no sign-up required | soocool.com/user/s4R2/widget/w5GT
prettynice.io  | has a cool api to easy capture "thumbs-up"; no sign-up required | prettynice.io/u/uRA1/link/L2AS

I would pick one website and use its widget link inside an image tag (or any tag to display a clickable item that toggle a visitor's interest in this project). So, that the goodness that this project would provide us with gets explicit. In short, any data you might need to know at the distance of a query. 

### Examples of query (without results):
---
```java
Earth.Websites.FreelancingProjects where project.budget >= 200 and project.currency == 'USD'; //returns a lot of projects, paying 200 USD or more.
```
```java
Mars.Volume; // returns xxxx km2
```
```java
Moon.SpaceDistanceToEarth; // returns ~300 000 km; 30 Earths away; the spatial distance from the Moon to Earth.
```
```java
Earth.PaymentProcessors.Tropipay.PaysTo where paidTo.main_goal contains 'top-up' and paidTo.Currencies contains 'BTC'; // returns, from services/websites that the payment processor Tropipay is connected to, those that can be used to top up your phone's balance using BTC. Put it in another, in answers "Where can I pay a top up using my Tropipay account's BTC balance?".
```
```java
Earth.PaymentProcessors processor.availables in 'Italy'; //returns the payment processors available in Italy. I do not want to sign up and do a lot of steps to end up knowing that it is not the place I will get what I seek.
```
```java
Earth.Currency.Exchange where a='usd' and b='euro'; //returns the rate between those two fiat currencies.
```
```java
Earth.Websites where url contains 'fitness' && active_users > 1000; //returns websites related to fitness that have more than a thousand active users.
```

### Examples of query (with results):
---
Earth.PaymentProcessors

Results:

PayPal
Stripe
Tropipay
...

Comparison with existing things:

### UD | SE| Website Concept
---

To improve usability I would like to change my profile (context), for example, from a high level to a lower one, from Specialist to Common Citizen. *That I know a lot and I want to behave like I do not know that much. An advantage would be that I will not be seen too many options.

I would like to choose the context, save it for later. As a result, queries will be executed after being prefixed.
Context: [Earth]
PaymentProcessors

Context: [Earth.Australia]
PaymentProcessors

---

Playground (under development)