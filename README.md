# GA

## Google Analytics Academy - Beginners

* In marketing, we have the concept of a purchase funnel. There are different stages within the funnel that describe customer interactions. A basic purchase funnel includes the following steps:

  - Acquisition involves building awareness and acquiring user interest
  - Behavior is when users engage with your business
  - Conversion is when a user becomes a customer and transacts with your business

* Google Analytics groups user activity into a period of time called a “session.” A session begins when a user navigates to a page that includes the Google Analytics tracking code. A session ends after 30 minutes of inactivity. If the user returns to a page after a session ends, a new session will begin.

* When you set up your configuration, don’t exclude any data you think you might want to analyze later. Because once Analytics processes the data, it’s stored in a database where it can’t be changed.

* Analytics supports regular expressions so you can create more flexible definitions for things like view filters, goals, segments, audiences, content groups, and channel groupings. Make regex according to [this syntax](https://github.com/google/re2/wiki/Syntax).

* Tracking code collects informations like the language the browser is set to, the type of browser, the device and operating system used to access the Google Store and even the traffic source.

* Acquisition reports can provide insight about how users get to your website, and how well your digital marketing and advertising works across different channels like email, search, and display ads. You can use the Acquisition reports to compare the performance of different marketing channels and discover which sources send you the highest quality traffic and conversions.

* The Acquisition reports provide a window on your users’ Acquisition-Behavior-Conversion (ABC) cycle: how you acquire users, their behavior on your site after acquisition, and their conversion patterns.

* When a user lands on your site, the Google Analytics tracking code automatically captures the traffic medium, source, and marketing campaign name.

* You can think of the medium as the mechanism that delivered users to your site. Some common examples of mediums are “organic,” “cpc,” “referral,” “email,” and “none.”

* Ideally, traffic should be “high quality,” meaning that users who arrive from a source engage with the website or complete a conversion. A good indicator of traffic quality can be bounce rate.

* The “Content Drilldown” report under “Site Content” groups pages according to your website’s directory structure. This is especially useful if you’re trying to understand the performance of content in a particular section of your website.

* The “Exit Pages” report under “Site Content” shows the pages where users left your site. Because you don’t want users exiting from important pages like a shopping cart checkout, it’s a good idea to periodically review this report to minimize unwanted exits.

* The “Events” report tracks how users interact with specific elements of your website.

* To answer whether a pageview involves in bounce rate calculation, you only need to answer one question: "Did this session contain more than one pageview?" 

* There are five different campaign tags: Medium, Source, Campaign, Content and Term. “Medium” communicates the mechanism. “Source” communicates where the user came from. “Campaign” can communicate the name of your marketing campaign. “Content” can be used to differentiate versions of a promotion. “Term” is used to identify the keyword for paid search campaigns.

* Use [this excel file](https://docs.google.com/spreadsheets/d/1qzi-BtJ86JoOlxDlYtuEzP7LYviBl79l_1PR20iQXLA/edit?usp=sharing) to create custom urls for your campaigns. 

* There are two types of goals: Business goals and Google Analytics goals. 

* Each time a user completes one of your business goals, we call this a “conversion.” This could be signing up for a newsletter or buying a product.


## Intro to analytics - Segment

* Good metrics offer two things: 1) They help you identify how your business is doing and 2) They tell you what to focus on.

* Your dashboard metrics should make it impossible to hide from failure.

* There's one place where totals make sense, and that's major company goals.

* Having a metric that's controlled by two different teams is a problem because it lets one team's failure hide in another's success.

* Every metric on our dashboard is intended to focus our attention on a specific business process we need to optimize.

* Analytics is about learning. First, you have to decide what you want to learn. Then, you figure out how you're going to measure it. And only after that do you build your experiment.

* Before you build anything — product, marketing campaigns, whatever, decide what you're going to learn from building it.

* In order to avoid falling into vanity trap:  All metrics should be actionable, accessible, and auditable.

* Retention cohorts are the most important metric to measure product-market fit. Retention cohorts show whether the same cohort of users comes back week over week to derive value from your new product.

* Event data has three key pieces of information: 1. Action, 2. Timestamp, 3. State.

*  The state refers to all of the other relevant information we know about this event, including information about entities related to the event

* Entity data captures the current state of things. Event data captures the history of actions that happen over time:

![entity data vs event data source: keen.io/blog](https://github.com/saeed-sufi/GA/blob/main/entity-vs-event.png?raw=true)
