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


## Intro to analytics - Segment Academy

* Good metrics offer two things: 1) They help you identify how your business is doing and 2) They tell you what to focus on.

* Your dashboard metrics should make it impossible to hide from failure.

* There's one place where totals make sense, and that's major company goals.

* Having a metric that's controlled by two different teams is a problem because it lets one team's failure hide in another's success.

* Every metric on our dashboard is intended to focus our attention on a specific business process we need to optimize.

* Analytics is about learning. First, you have to decide what you want to learn. Then, you figure out how you're going to measure it. And only after that do you build your experiment.

* Before you build anything — product, marketing campaigns, whatever, decide what you're going to learn from building it.

* In order to avoid falling into vanity trap:  All metrics should be actionable, accessible, and auditable.

* Retention cohorts are the most important metric to measure product-market fit. Retention cohorts show whether the same cohort of users comes back week over week to derive value from your new product.


## Google Analytics Academy - Advanced

* Tag Manager lets you make updates to your tracking code from a centralized location, rather than having to manually update the code on every page of your website.

* Three most common types of hits are pageview, event and transaction hits (ecommerce hit). There are also other types of hits like : social hits (likes, shares, tweet data...) and “page timing hits” that allow you to report on page timings

* Event hits, pass 4 parameters in the url: action, category, label and value

* Note that if you install the same default tracking code on pages with different domains, Analytics will count these users and sessions separately. If you need to track users across different domains, you will need to set up cross-domain tracking. 

* Google analytics processes data taking these first steps: First, Analytics determines new vs. returning users (unique cid). Then it categorizes hits into session (or periods in which the user engaged with the site). Next, it joins data from the tracking code with other data sources. 

* If you wish to track users across devices, you’ll need to turn on the User ID feature

* Google Analytics groups user hits based on the time in which they were generated. To measure these periods, Analytics uses a metric called “sessions.”

* A site with a goal to get users to watch videos might want to extend session timeout to the average watch time of the videos on the site.

* If you want to send hits from external sources to GA you should use the measurement protocol 

* You can setup data configuration rules that determine how your data will be processed. This includes implementing features like data filters, goals, data grouping, Custom Dimensions, Custom Metrics, and imported data. 

* There are four types of Goals in Google Analytics: Destination (or Pageview) Goals, Event Goals, Duration Goals, Pages or Screens per Session.

* Channel Groupings let you organize your data into customized channels, while Content Grouping lets you aggregate metrics within reports based on the organization of your website.

* Custom Dimensions can be used as a secondary dimension in standard reports, a primary dimension in a Custom Report, or as a segment. “Custom Metrics” can be collected for any standard dimension or Custom Dimension that can’t be measured by any predefined metric in Google Analytics.

* When Analytics creates dimensions and metrics during processing, it has to determine the scope of those dimensions and metrics in order to know how broadly applicable they are to your data. Some of them might organize data about a single hit and some of them might apply to data across an entire session or individual user. 

* Dimensions and metrics can have one of three scopes: hit-level, session-level and user-level. You can only pair metrics with dimensions if they are both in the same scope.

* It’s possible to access your Analytics data using the Google Analytics Core Reporting API.

* In order to come up with a measurement strategy you need to take some time to define your business objectives and how you expect to measure those outcomes. We have to first define out macro and micro conversions. 

*  A measurement plan is a way for you to align your business objectives with your Google Analytics configuration settings. Your measurement plan should include an overall business objective, different strategies that support that objective, and tactics that will help you achieve your strategies. Each tactic will have key performance indicators (or KPIs) that help you measure your macro- or micro-conversions.

* Macro conversions usually measure the tactics that support your various strategies. Micro conversions are metrics that help you better understand the user behavior that leads to macro conversions. 

* A measurement plan is a great way to document the data that is most important to your business. 

* If you have two related websites with different URLs or subdomains that you want to track in a single property, you can set up what’s called “cross-domain tracking.” To set up cross-domain tracking, you’ll need to modify the Analytics tracking code on every page of every site you want to track. Google Tag Manager can make updating that code a lot easier.

* You can create user segments or session segments. User segments can span multiple sessions with a maximum date range of 90 days. Session segments are confined to user behavior within a single session.

* Note that segments are applied after sampling. So if the data being shown in your reports is a sample, the data shown in your segments will also be a sample.

* Attribution modeling is a set of rules that determine how sales and conversions get attributed to your marketing campaigns.

* A channel that contributed to a conversion prior to the final interaction would be credited with an “assisted conversion.”

* "The Top Conversions Paths report" shows conversions and conversion value grouped by the channel combinations that led to conversion. "The Time Lag report" shows conversions grouped by the number of days it took from initial interest to conversion. "The Path Length report" also shows how many interactions on average it took to convert and how much each series of interactions was worth.

* You can use channel analysis to better understand what channels work for your business and which are most responsible for facilitating conversions.

* Note that Audiences that include the Google Display Network's demographics dimensions “Age, Gender, Interests” are not eligible for Search remarketing.

* Collect data, Create report, Analyze reports and finally Test solutions. 

* Analysis is the process of developing hypotheses based on your expectations and figuring out why your metrics match or don’t match those expectations. When you find data that doesn’t align with your expectations, your analysis can help you figure out the cause.

* Because the Cohort Analysis Report is user-based, if you apply segments based on sessions, you can get unexpected results that do not include 100% of users on Day 0 as you would expect. Also note that filters that exclude Day-0 users can affect the data for subsequent days. For example, if you apply a filter that excludes Day-0 sessions for some users but includes sessions for those same users on subsequent days, then the values for those subsequent days can exceed 100%.

## Google Analytics Help Center

* When interpreting cohort charts, remember to look into both micro and macro trends as might lose some micro trends if you only check macro trends.

* By simply comparing the values in a single column, you can see whether there’s consistent behavior among your cohorts, or whether performance improves or deteriorates.

* Goals measure how effectively your application or website supports your business objectives. A goal represents a completed activity, called a conversion, that contributes to the success of your business.

## Misc

* Improving your load time by 0.1s can boost conversion rates by 8%.

* Don't deploy gtag.js as a custom tag through the Google Tag Manager interface. Instead, use Google Tag Manager's native tag templates for Google Ads, Analytics, and Floodlight.

* Always links Google Ads and Google Search Console to your GA account. 

* When Setting up new properties for your acount (adding new websites), don't forget to also activate Universal Analytics alongside GA4. 

* Purchasing patterns can help you identify the right time to promote the right products.

* Attribution is simply the science (or, too often, the art) of distributing credit for conversions across your various marketing channels.

* Ecommerce standard reporting vs enhanced reporting: what happend vs what happend and how it happend.

* 5 pillars of a robust measurement plan: 1- Leverage first-party data 2- Cross-platform tools 3- Be transparent 4- Fill in measurement gaps with model data 5- Cloud-based solutions

### Custom dimension examples

#### [From online metrics blog post on custom dimensions](https://online-metrics.com/custom-dimensions/)

* **user-level**: Customer ID, lead, member type, fan level (reader, commenter, subscriber, customer)
* **session-level**: Logged in, time of day, coupon code, chat
* **hit-level**: author, blog or product category, word count
* **product-level**: availability, product type, profit margin, color

#### [From simo blog post on custom dimensions](https://www.simoahava.com/analytics/13-useful-custom-dimensions-for-google-analytics/)

* **user-level**: client ID, user ID, 
* **session-level**: session ID, 
* **hit-level**: hit timestamp, hit type (event, pageview, timing), full referrer (document.referrer), payload length, gtm container ID, redirect count, navigate type (reload, back/forward, writing site address, ...), tab type (a new tab or existing tab), tabs open (number of open tabs), tab ID


### From [keen.io blog post about how to think about event data](https://keen.io/blog/analytics-for-hackers-how-to-think-about-event-data/)

* Event data has three key pieces of information: 1. Action, 2. Timestamp, 3. State.

* The state refers to all of the other relevant information we know about this event, including information about entities related to the event

* Entity data captures the current state of things. Event data captures the history of actions that happen over time:

![entity data vs event data source: keen.io/blog](https://github.com/saeed-sufi/GA/blob/main/entity-vs-event.png?raw=true)

### From [thoughtbot.com blog post about north star metric](https://thoughtbot.com/blog/north-star-metric)

* Numbers identify the “what.” We identify the “why.”

### From the [vanity metrics article on Harvard Business Review](https://hbr.org/2010/02/entrepreneurs-beware-of-vanity-metrics)

* All metrics should be actionable, accessible, and auditable.
  - **Actionable**: When an employee sees a report about a specific metric, it’s essential that they have some idea how to replicate the result in the report. Techniques like split-testing are the gold-standard here.
  - **Accessable**: Reports shouldn't be complicated. 1. Everyone in the company understand how to read them. 2. Everyone in the company has easy access to the latest data. Also, key data should be available to any employee, anytime, in a matter of minutes. In order to achieve that goal, the reports themselves have to be extremely simple.
  - **Auditable**: The biggest benefit of actionable metrics is that they can be used to reap the biggest savings in all of product development, when they tell you that you don’t need to do something. Also, It’s important that skeptics can audit a report.

* Remember, metrics are really reports on people. This is where most off-the-shelf metrics packages fail. For example, consider a report that claims in a split-test between two proposed features, feature A generated more revenue than feature B. Which people used feature A? Which people used feature B?...  


## Common pitfalls

* Using UA transaction tag works only with the Standard Ecommerce. For Enhanced Ecommerce tag use either pageview or event tag.

* Try to include both product name and ID. If you don’t include the Product ID, then product list attribution will not work (of course, if you are tracking the performance of the product list in the first place). 

## GTM

* Click Classes returns the value of the class attribute of the HTML element that was the target of the action. Click Element returns the HTML element that was the target of the action. "Matches CSS Selector" is a check whether any given element matches a given CSS selector.

* `element visibility` is a heavy task for the browser. Use it with caution.

* You can set custom events as trigger for Hotjar recording or heatmap. 

* You can set priority for tag. A higher number has a higher priority.

* If `dataLayer` is used before google tag manager code, then it would run before the container loaded event happens.

* Always make sure that the data is being sent to GA. Go to network tab of devtools and search for `/collect`.

* A quick way to check the css selector you need to use is to `document.querySelectorAll()` to see if the css class you want to use is specific enough.

* Use `JSON.parse()` to extract variables out of strings that look like objects for example form strings. This is also useful when working with cookies because they are always used as strings. 

* When checking if `gtm.js` is installed correctly, check `sources` tab in the devtools and search for `gtm.js`. It might have been inserted in the js file of the website. 


## CXL

### Google Analytics

* If the user naturally criss cross between two domains in one session, then put those two domains in one `property`, if not, then you can put them in separate properties.

* When you want to check if you are a user with enough access in a GA view, go to admin and check `goals` and `filter` on the `view` column. If the `New Goal` or `Filter` buttons are active, then you can do anything you want in this view. 

* Set your timezone to where your servers that are runnig your cart system are located.

* Always consider the first property in an account, as a decoy property for spam bots and for your real site make a second property. 

* The main use case of real time reporting is to check if the GA is working as expected. 

* In `affinity categories` section of `interests` in `audience` section, you can see that in what other fields your users are interested so that you will consider site which promote those products to place an ad on. 

* source / medium => brand / type

* Channels are a larger category than brand / type categoriyes. Ex: Social is a channel which includes facebook as a brand. 

* Search Console data is incompatible with Google Analytics segments. If you apply segments to the Search Console reports, the Analytics metrics are segmented, but the Search Console metrics are not, and return values of 0.

* A large number of "direct" users may indicate untracked landing pages.

* Standard ecommerce answers what was purchased whereas Enhanced ecommerce answers how was purchased.

* `Real Time` reports are about testing, `audience reports` answers `who`, `acquisition reports` answers `where`, `behavior reports` answers `action`, `conversion reports` answers `results`. 

* With bounce rates, you have to compare different bounce rates of different pages. Bounce rate shouldn't be interpreted as an absolute value. There's no good or bad bounce rate. 

* When you are looking at the landing page reports, ask yourself if that makes sense.

* At least 3 views are needed: Raw Data View, Production View: this is the one you use to answer your questions, Test View.

* Add the following filters to your views:
	Create a `show domain` filter. 
	Create a `add a slash` filter to prevent fractured pages. 
	Create a filter to only recieve traficc from your own domains (not spam domains). 
	Create a filter to make all the traffic names lower case.
	Create a filter to make search terms lower case. 
	
* You should use the `All Filters` section of the account column to remove extra filters. Always keep it clean. 

* Does the filter match the purpose of the view? If yes, use it. 

* When creating a UTM, for the campaign part you should ask yourself what's the purpose of the campaign? 

* 3 rules to keep in mind when creating UTMs: 1- use dash instead of spaces 2- all letters lowercase 3- no punctuation.
