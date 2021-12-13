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

* My recommendation is that going forward all your segments should focus on users first and sessions second. Because if you focus on a relationship, rather than a connection, you will get better business results.

* Google analytics report `event value` as a `metric` in its reports. 	

* Use unique `action names` while creating events. 

* Add annotations using the Admin interface since you can set a future date there. 

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
	* Create a `show domain` filter. 
	* Create a `add a slash` filter to prevent fractured pages. 
	* Create a filter to only recieve traffic from your own domains (not spam domains). 
	* Create a filter to make all the traffic names lower case.
	* Create a filter to make search terms lower case. 
	
* You should use the `All Filters` section of the account column to remove extra filters. Always keep it clean. 

* Does the filter match the purpose of the view? If yes, use it. 

* When creating a UTM, for the campaign part you should ask yourself what's the purpose of the campaign? 

* 3 rules to keep in mind when creating UTMs: 1- use dash instead of spaces 2- all letters lowercase 3- no punctuation.

* There are three types of goals you want to keep an eye on: Remember the A.C.E model: Awareness, Completion, Engagement.

* Goals are counted per session in Google Analytics.

* If your funnels are not working correctly, chances are they are in need of some love touch of regex.

* Duration goals and pages per session goals do not show up on real time reports. 

* To track engagement, you can set pages per session goals.

* **Destination Goals**: When a visitor lands on a specific page, the Goal is triggered. These are perfect for building funnels.
* **Duration Goals**: When a visitor spends X amount of time on your site, the Goal is triggered. These are perfect for measuring engagement.
* **Pages/Screens Per Session Goals**: When a visitor lands on X amount of pages in a single session, the Goal is triggered. Again, these are perfect for measuring engagement.
* **Event Goals**: Whenever a certain condition (or set of conditions) is met, the Goal is triggered. These are the most flexible.

* “The Truth is in the Trend; The Power is in the Pattern”.

* Spam traffic will typically show as a Referral report while the bot traffic will usually show as Direct traffic in Google Analytics.

* Transactions with no value (i.e. $0) and cancelled transactions do not appear in Google Analytics.

* Be carefull with `include filters` as you might accidentally end up filtering all data from your reports

* Data is useful only if you can action on it.

* Create horizontal funnels to have higher flexibility. 

* Apply cross-domain tracking by inserting your other domains in `auto link domains` setting of the tag manager setting variable. 

* you can group your macro conversions into one goal set, and your micro conversions into another goal set, it would make using GA easier

* A unique pageview represents the number of sessions during which that page was viewed one or more times.

* Entrances is incremented on the first pageview or screenview hit of a session. In contrast, Sessions is incremented on the first hit of a session, regardless of hit type. Thus, there may be a discrepancy between Entrances and Pageviews or Screenviews for properties where the first hit of a session can be an event hit.

* time on page is calculated as the difference between the initiation of successive pageviews: pageview 3 - pageview 2

* There are two methods by which a session ends:

	* Time-based expiration:
		* After 30 minutes of inactivity
		* At midnight
	* Campaign change:
		* If a user arrives via one campaign, leaves, and then comes back via a different campaign.

* Each search term updates the campaign, so each keyword corresponds to a new session.

* manually tagged campaign parameter values remain the same for every click so the campaign isn’t updated for each click. This makes it possible to have multiple ad clicks and only one session.

### GA4

* Versioning of Google analytics:
	* Urchin = GA1
	* Classic analytics = GA2
	* Universal analytics = GA3
	* GA4

* Firebase uses event-driven data model. Likewise, GA4 uses event-driven data model. In contrast, Universal analytics is hit-based. 

* GA4 is an adoption of firebase with a new UI. Firebase can be easily updated to a GA4 property and all the historical data will be valid.

* Alongside `page views`, GA4 automatically measures scrolls, downloads, site search, outbound clicks, ...

## Ahref 

* Fresh index, good coverage, not get blocked: Choose two.

* Crawl budget is the number of URLs a crawler can and wants to crawl. Budget has two aspects. Rate and Demand. Rate means the number of requests crawlers can make to a site when crawling it. Page download time and website size determine the crawl rate. Crawl demand or crawl priority means the level of importance to crawl and recrawl pages on a site. 

* The more quality backlinks a page has, the higher the priority for recrawling.

* Domain Rating: the overall strength of a website's link popularity. It has the same calculation principles as URL rating except that it looks at links between domains instead of pages. 

* Discovering vs Crawling: we might discover a link but since it has a low priority it won't be crawled. 

* Ahref's Backlink Metrics: 1-Ahref rank 2- Domain rating 3- URL rating.

* Ahref's Search Traffic Metrics: 1- Search traffic estimation 2- Traffic value

* Ahref's Keyword Metrics: 1- Search volume 2- Keyword difficulty 3- Total organic keyword rankings 4- Top keyword

* Main data sources: 1- Crawler 2- Keyword 3- Clickstream 4- Search results data 

* The only data source to get backlinks and referring domain stats is crawlers.

* The total number of backlinks and referring domains is the `bottom level metric`. It is used to make second level metrics like url metrics.

* URL rating represents the overall strength of a page's backlink profile. It's a logarithmic scale. 

* Ahref URL rating is similar to the calculation of Google's PageRank formula. Some of the influential parameters include: 

	* Counting links between pages
	* Looking at both internal and external links pointing at a target. 
	* Weightinh the links differently
	* Respecting the "nofollow" attribute
	* Using a damping factor.

The goal of these calculations is to try to determine a rough estimate of how important a page is.

* Ahref Rank is basically all websites in their database ordered by their raw DR values. Think of Ahref Rank as a granular version of Domain Rating.

* Ahref Rank is unrelated to Google Rankings oe search traffic.

* Google keyword data: base for search volume calculations.

* Clickstream data: refine numbers and find new keyword ideas.

* Search reasults data: ranking positions + track SERP features.

* Search volume: the average number of times people search for a query in a target country. 

* Total keywords: Calculated by counting all search queries a URL, subfolder, or domain ranks for in the top 100.

* Organic traffic: Estimates the total number of monthly search visits to a website, subsection or page. It's calculated as CTR * Search volume of keyword.

* Traffic value: The value of the organic search traffic, if it were to be acquired via PPC in Google Ads. 

* Top keyword: The query that brings the most search traffic to a URL.

* Keyword difficulty: Estimates how hard it'll be to rank in the top 10 organic search results in a specific location. Best to use KD as a filter when working with large datasets. 

 Crawl credit: In ahref, it is consumed only if we crawl an internal HTML page that returns a 200 response code. Resource files, external pages, pages that redirect 404 pages do not count as crawl credits. 

* A Seed URL in web crawling is a url from which a web crawler will begin to traverse a site.

* Crawler can crawl if: 1. rules in robots.txt are respected. 2- At least one seed URL which returns 200 ok, exist 3- Your hosting company or CDN has not blocked ahref IPs. 4- Your website configuraions on redirecting pages is also important.

* Verifying ownership: 1- Increase the crawl speed, 2- Adjust the number of parallel requests. 3- can ignore the robots.txt rules. 

* Seed URLs are decided when looking at sitemap_index.xml. Any URLs that are considered seeds will have a crawl depth of 0. 

* Check HTTP status of external links to check for Broken external links and URLs that redirect  to a destination you may not want to link to. 

* Max folder depth counts the number of slashes in the URL.

* Use SiteAudit bot to run on-demand crawls on smaller scale to crawl a single domain and its external links.

* SiteAudit bot will also store server-related data such as HTTP status codes, page size and page download times. 

* Page rating: representing the relative 'rank' of a URL based on the internal linking structure for a crawl.

* 301 redirect VS Canonical 
	* 301: okay, google (or any other search engine), my page isn't there anymore and it's been permanently moved to a new URL. Please, delete the old link from the index, and pass the link juice to the new page.

	* Canonical: okay, google, I've got multiple versions of the same page (or its content), so, please, index only the canonical version. I will keep the other versions for people to see, but don't index them, please, and pass the link juice to the canonical page.

* Regex to determine Folder depth: https.\/\/ahrefs.com/([^/]+/){2}[^/]* : number 2 indicates the depth of the folder.

* Use page explorer to create custom issues if you need them. 

* Structure Explorer shows you the distribution of URLs based on specific categories. 

* Websub protocol helps in indexing new changes in just seconds.

* Use XSLT to style sitemaps to make them readable (wordpress plugins).

* A technical SEO audddit fall into 3 categories: 1. technical errors, 2. UX error, 3. Ranking opportunities.

* Technical errors include: crawling issues, broken links, slow site speed, and duplicate content.

* Technical SEO include topics like: Meta (robots, description, canonical), structured data, sitemaps, accelerated mobile pages, speed, heading (H1-H6), URL structures, internal link structures, redirects, status codes, HTTP(s), SEO experimentation, translations,International SEO: sitemaps, HREFLang

* Do a technical SEO audit at least once a quarter. 

* Technical SEO is often for the Big sites. Sites with more than 50000 pages, with multiple people involved in SEO, SEO is understood and part of a bigger organization.

* Analyzing impact of technical SEO: Use web analytics to measure impact on a template-level. Measure clicks, impressions, CTR and position by using custom dimensions, goals, organic traffic, segmentation and custom metrics. 

* In order to decide what is the right URL structure, use keyword data. 

* If 302 has been in place for longer than three months, it’s worth making it a 301.

* Page speed: How long it takes for a page to load. Site speed: The average time it takes for a sample of pageviews to load.

* Aim for PNG image formats as they tend to achieve the best quality to compression ratio.

* In general, only add hreflang tags to your web pages that have self referencing canonicals.

* You can ping Google or Bing about the new/updated content: https://google.com/ping?sitemap={Url to sitemap}

* Stick to lowercase, always when it comes to SEO.

* If the site has different subdomains for mobile and desktop, add the rel=”alternate” tag to the sitemap.

* 410: page permanently deleted, 429: Too many server requests in a short space of time

* You’ll also want to cross-check the crawl stats in Google Search Console with average load time in Google Analytics to see if there is a correlation between time spent downloading and the pages crawled per day.

* Create a segment in Google Analytics based on the most searched keyword on your site to see which pages are ranking for that particular search term. 

* To check if your page is cached by google: http://webcache.googleusercontent.com/search?q=cache:https://www.searchenginejournal.com/pubcon-day-3-women-in-digital-amazon-analytics/176005/

* To check if a website has subdomains in google: `site:https://pruneyardcinemas.com/ -inurl:https://pruneyardcinemas.com/`.

* Google checks these 3 to guess if the content is duplicate: 1- Page title 2- Page URL and 3- h1 tag

* For noindexing issues always do these checks first: 1- Noindex meta tags 2- robots.txt 3. sitemaps 4. redirects 5. canonical tag

* Here’s an example of some of the things included in an **technical audit**. (Not exhaustive)
• Crawling issues
• Indexation issues
• JavaScript rendering Issues
• Unexpected URLs in the Search results
• Canonical tag configuration
• URL Structure
• Redirects
• Redirect/canonical chains
• Broken Links
• robots tag configuration (noindex/nofollow)
• Localisation
• hreflang tag configuration
• Google Search Console settings and Errors
• Content Structure Issues
• XML Sitemap configuration
• Secure HTTPS setup
• Page Speed
• Structured data data/schema implementation
• Image Optimisation
• Internal links status
• Internal linking
• Duplicate Pages
• Duplicate Content
• Mobile setup (including amp, PWA, dynamic serving, app indexing)
• Thin Content
• Robots.txt configuration
• Meta tag issues (page title, Meta descriptions, etc.)
• Webmaster Tools / Google Search Console Issues
• Spam/Malware
• Orphan Pages
• Spider Traps
• Issues with E-A-T
• Server Log Analysis: Find out exactly what Google is and isn’t crawling compared to the structure of the website.


