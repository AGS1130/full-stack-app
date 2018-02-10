# Purpose

This serves as a structured guide in how you can build your full stack app in case you get lost or don't know how to start.

For now, this will be written in a very high level overview. This should be language agnostic, no deep dives of frameworks or what language will optimize your app. Those decisions should be left to the programmer or team itself.

Anyone with experience in building a full stack app, whether by yourself, with a team, or having individual responsibilities such as the front-end or back-end can contribute to this repo.

This repo (so far) will dive into four common patterns I have seen when building a full stack app:
1. [Getting data] [1]
2. [Storing data] [2]
3. Retrieving and Manipulating the data
4. Presenting the data

## [1] Get data
You need data in some kind of shape or form and it can come from user responses from forms that you created or a request over an API.

Whatever you are building be a blog post, calander app, or the next Airbnb you're going to need information, facts, or data.

Have a basic understanding of the different __types of data__, and the kinds of questions you can use them to answer.

Two data types many developers should be familiar with are __quantitative and qualitative__.

### Quantitative
Simply, numbers.

* Prices for your e-Commerce site
* Temperature for your weather app
* Weight of a user for your weight loss platform
* Number of tickets avilable for your Ticketmaster clone

*How will the information change over time?*

For the sake of compressing information I will not include a detailed explanation of continuous or discrete data.
In short:

* __Continuous__: Progressively more precise scales; *meters, centimeters, millimeters, etc.*
* __Discrete__: Involves integers or whole numbers

### Qualitative
These are words.

Or moreover, responses of an inidivual that have meaning.

In most apps I built, they often come in three forms:
__Binary, Nominal, and Ordinal__

#### Binary
To me, these are assigned as booleans, __True or False__
And their meanings can be best summed as positive or negative.

In some shape of form you may have encountered this in your waking life.
* Like or Dislike on Facebook
* True or False quiz games
* Swipe right/swipe left on Tinder
* "Good" or "Bad" user experience

It is one __or__ the other.

#### Nominal
What I consider true qualitative data.
There is no order or ranking, and it can be best said as __no calculations needed to be performed__.

This data comes in the form of a user's personal information.

*Look at your next job application*

* Do you identify as male, female, or other
* What is your ethnicity
* Zipcode
* Phone Number

#### Ordinal
This is data that has value and can be ranked.

*If you ever downloaded a mobile app, you should know you can rate your experience*

The best way to sum this __on a scale of 1 to 10...__:

* Rate your mood
* Rate the pain severity
* Rate the satisfaction of the product
* etc.

## Get data Conclusion
What information is necessary for your MVP?

If it is quantitative:
You are asking for value in numbers and making sure that number is accurate.

If it is qualitative:
You are asking for value in personal responses and this can lead to phenomenal information.

When you have an idea of the data that you will be needing move on to storing that information.

## [2] Storing Data
