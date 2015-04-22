# An App Launch Guide

## Why
This guide is aimed at indie developers who are building and launching their iOS apps largely by themselves. The guide will walk through planning, pre-launch, marketing, product dev, QA, and launch.

The goal is to combine the concrete product development schedule with an equally concrete marketing schedule so that nothing is missed.

The outline below will combine marketing and product deadlines into a single timeline, so that you can plan for both the marketing and product cycle in tandem.

## Who
My name is [Adam Wulf](https://twitter.com/adamwulf), and I've developed mobile apps in an enterprise company, for clients at a small design agency, and currently as an indie developer. I have recently launched [Loose Leaf](https://getlooseleaf.com) and am launching [Remotely](http://getremotely.com) very soon, and I launched [Here File File](http://www.macstories.net/iphone/here-file-file/) long ago. I've also developed mobile apps at an enterprise company and also a small agency for a number of clients.

This guide is a collection of lessons learned.

## What
This guide goes through all of the necessary steps for validating, buiding, marketing, and launching your product, specifically focused on app dev. In particular, this guide covers:

0. Helpful books and resources
1. Narrowing down your app idea
2. Validating that idea
3. Defining your Busines Model
4. Validating with a Prototype
5. Building your app
6. Launch!
7. Post-launch growth

## Contribute
I missed some stuff! I'm only one guy with my own limited experience. If you see that I've missed some info or have helpful resources to share, submit an issue or PR, or just [get in touch](http://twitter.com/adamwulf)

### License
I'm providing this guide for free and releasing it into the public domain.


# Step 0: Read these Books

Take a few evenings and read through these two books. They're incredibly helpful in explaining the incentives of press/web/buzz/etc, and they also give concrete advice and ideas for marketing your app. Out of all the references I list below, these two have influenced me the most and continue to affect how I weigh nearly every other decision and resource. Read these.

- [ ] [Trust Me I'm Lying, by Ryan Holiday](http://amzn.to/1Adie3W)
	- Awesome book describing the incentives of big press and how to "trade up" from smaller to larger sites
- [ ] [Traction, by Gabriel Weinberg](http://amzn.to/1DBn0Lo)
	- Describes 19 marketing channels any start up can use, and a process for trying them out

### Additional Resource List
Throughout this guide, I'll reference a number of great resources, some free and some cheap. Here are all the resources in one place:

- Books
	- [Pitch Perfect by Erica Sadun & Steve Sande](http://www.amazon.com/Pitch-Perfect-The-Promoting-Your/dp/0321917618) - Covers the art of pitching and promoting your app on the web
- Social
	- [Buffer App](http://bufferapp.com) - Free - easy auto-post to your twitter so you dont need to baby sit it.
	- [Mad Mimi](https://madmimi.com/short_ref/nyw) - Free/Cheap - Easily manage your email list
	- [Vine](http://vine.co) - Free - Great way to show your dev progress visually to your audience
	- [TweetDeck](https://tweetdeck.twitter.com/) - Free - Easily stay on top of multiple lists of influencers so you can jump into the conversation when appropriate
- Tracking
	- [Mixpanel](http://mixpanel.com) - Free - Track user behavior to determine success/fail of onboarding
	- [Crashlytics](http://crashlytics.com) - Free - Automated crash reports and beta distribution
	- [AppFigures](https://appfigures.com) - Free/Cheap - Automated sales and app review reports
	- [iTunes Affiliate](https://www.apple.com/itunes/affiliates/) - Free - Lets you track (sort of) how links into the iTunes Store convert into sales. Also lets you scratch back some of the 30% that Apple takes
- Press / PR / Marketing
	- [HARO](http://www.helpareporter.com) - Free - Daily emails from press asking for sources for their stories
	- [Find Keywords for App Store](http://blog.getlooseleaf.com/post/109888977759/step-by-step-app-store-optimization-an-objective) - Free - Blog post detailing how to objectively find the right keywords for your App Store description
	- [SensorTower](https://sensortower.com/) - Free - Helps with competitor and keyword research
	- [ASO Keyword Spreadsheet](https://docs.google.com/spreadsheets/d/1QDlCM8Q0H_MBBef-kHb74b05DRRlLye1MFdp6GF-wdc/edit?usp=sharing) - Free - Spreadsheet to help measure keywords
- Podcasts
	- [Inquisitive](https://itunes.apple.com/us/podcast/inquisitive/id909109678?mt=2&uo=4&at=10lNUI&ct=github) with Myke Hurley from Relay FM
	- [The App Guy Podcast](https://itunes.apple.com/us/podcast/the-app-guy-podcast-the-app-guy/id771670010?mt=2&uo=4&at=10lNUI&ct=github) with Paul Kemp
	- [App Masters](https://itunes.apple.com/us/podcast/app-masters-mobile-growth/id643216602?mt=2&uo=4&at=10lNUI&ct=github) with Steve  P. Young

# Step 1: Find some App Ideas

Every good app starts with a good idea, and we all have too many ideas already. This first step will help us filter these into a short list that might work.

These ideas will change throughout the process, and that's ok. The only important thing is that you have a general direction you're headed. Nothing is proven, nothing is set in stone, this idea is just pointing you in a direction, any direction.

- [ ] List out all of your app ideas, don't filter yet, everything is a winner

Next:

- [ ] For each app idea, define the problem you solve

Each app idea should have a 1 sentence "This is the problem I solve." If you can't distill the problem into 1 sentence, then either (a) it's not really a problem, or (b) you don't actually understand the problem your idea solves. Clarify the problems, or axe it in our first filter below.

For [Loose Leaf](https://getlooseleaf.com), my problem was "All the existing apps are digital notebooks for ideas you keep, i need ditigal scratch paper for super fast and rough brainstorming."

Filter #1: Remove any app ideas with poorly defined problems

- [ ] For each app idea, define your target market

"Everyone" is not a target market. Get as specific as you can here. Each app can have multiple audiences, that's ok, but you need to make sure you have a primary and specific audience.

For [Loose Leaf](https://getlooseleaf.com), my market started as "1st level product and design managers".

This doesn't need to be super specific yet, but you need to have a general idea of who'll use your app. Older folks? Younger? Teens? Family? Single? Professional? Occupation?

- [ ] Market research

Look for similar apps that are already in the store. Don't lie to yourself that my-idea-is-a-special-snowflake; people are already (a) solving your problem with some other app or (b) don't actually have the problem you think they do.

Find out how much (a) or (b) already exist, and how.

### Next up: Validate your idea

That wasn't so bad! At this point you should have a list of ideas where you've (a) defined the problem (b) defined the audience and (c) defined your solution compared to existing solutions.

Next up we'll work on validating your ideas with your target audience. Will it float?! Let's find out!

# Step 2: Validating the App Idea

Most startups fail because they can't find customers, not because they don't have a product. You need to start finding your customers right now, before you've even built anything, and verify to yourself and to them that your idea from Step 1 is actually something they'd pay for and use.

For each idea that's made it through Step 1 filters, you'll want to follow this process until you find one that sticks.

## Confession time
I skipped this step when I was developing [Loose Leaf](https://getlooseleaf.com), and I paid the price for it. It took me nearly 4 months _post-launch_ until I had validated a proper target marketing for Loose Leaf, and that was after 2 years of development! It turns out product/design managers don't care about Loose Leaf like it'd thought, but teachers and students love the app. What a wasted opportunity - I'm still playing catch up!

This is something that we were sure to get right with [Remotely](http://gracefulmade.com/remotely/) - pre launch we already have near 5000 email subscriptions and engaged twitter followers eager for the launch.

## Find Your Community

- [ ] Find where your audience meets online. Twitter? Pinterest? Vine? Facebook? Forums?

After launch, Loose Leaf was suggested between teachers multiple times. A few times even during a [Twitter Chat](https://blog.bufferapp.com/twitter-chat-101) which helped get more visibility into that community.

- [ ] Find where your audience meets offline. Meetups? Marathons? Conferences?
- [ ] Find thought leaders in your community, start listening and entering the conversation
- [ ] Find users on Twitter/Pinterest/etc that are influential

I **cannot stress this enough**, talk to your customers as soon as you possibly can, even before you start building!

To help organize your potential audience, I suggest keeping a spreadsheet in Google. For each of my target audiences, I keep a list of influential Twitter users in that audience. I wrote some simple scripts to scrape profile information, so that I could easily sort by follower count, or search based on keywords in their profile. Then, for each market, I setup a Twitter list with a short list of influential people in each group.

You can learn so much just by listening to the conversations in each group. Twitter is ripe for complaining, so it's a great way to listen in and hear if they're ever actually complaining about the problem you're aiming to solve in the first place.

It's also a great way to jump into related conversations when it's appropriate. If you genuinely have something to add, or can anwer a question they post, it's a great way to connect and get to know your audience better.
     
## Define Your MVP

Now that you've started listening to and getting connected to your audience, you should have enough information to make a rough pass at a Minimum Viable Product. Ask yourself, "How little can I build and still provide value to this customer?"

A few questions to help you get started:

- [ ] Will it have a web site or service?
- [ ] Can you use Parse or CloudKit instead of building your own backend?
	- you're not worried about lock-in at this point, you can change to something else after you've proved traction. Right now, you're focused on spending as little money as possible on dev costs to get that initial validation
- [ ] iPhone? iPad? Android? Mobile web? Native?
- [ ] "What if i didn't build feature X?" If it'd still be useful, then don't build feature X.

## Check In

At this point, you should know:

- [ ] who your target market is
- [ ] where you can reach your target market online and offline
- [ ] a rough idea of the problem they have
- [ ] a rough idea of the solution you want to sell them

If one of those isn't true for you, look back at the previous sections and clarify until you're ready.
	
## Build a Landing Page

Now you know who your customers are, where they are, and what you want to sell them. Build a landing page that describes exactly those things, and start collecting email addresses. _If you can't get their email, you definitely can't get their money_.

This website will do a few things for you:

 - these are the people most likely to buy your product on day one
 - it'll further validate that your customers actually want what you're building

I use [Mad Mimi](https://madmimi.com/short_ref/nyw) to manage my email list, but there's lots of options out there for free and for cheap.

You should aim for 5% to 10% of incoming traffic to convert into an email address.

One simple way to test conversions:

1. Find influential Twitter users who have followers in your target audience.
2. Setup a Twitter account (fill out the bio + icon + etc. tweet a bit to flesh out the profile. 
3. Make sure to add a link to your landing page in your bio.)
4. auto-follow their followers.

You should aim for roughly %5 to 10% of those people following your account back, and roughly 20% of those that click through should be converting on your site into email addresses. If that's not the case, then you've missed your audience, missed your product, missed your pitch of the product, or all three.

No one will bother following an inactive account, so post relevant content to that account consistently - at least once a day. A free [Buffer](http://bufferapp.com) account can make that super easy to manage.


# Step 3: Connect With Your Audience

Now that you have a landing page for your app, you're ready to start sending traffic to it to build email signups.

## Collect Your Ideas

The most valuable advice I recieved from Traction: brainstorm ideas to market my app in every channel I could imagine. The book walks through 19 different marketing channels, everything from content marketing, to paid ads, to an outside sales team.

As you read through Traction, setup a simple spreadsheet and collect _all_ of your marketing ideas for each channel.

For each idea, track:

 - A short description of the idea
 - the marketing channel it fits in: content, PR, Ads, etc
 - How much it'd cost to see if it works
 - expected amount of traffic the idea could generate
 - (1-5) for how likely this idea is to work

After going through this process myself, I came away with nearly 50 ideas that might generate traffic for [Loose Leaf](https://getlooseleaf.com), and the vast majority of those ideas were free!

Remember: there is no such thing as a bad idea! Collect all of your ideas, don't let any slip away!

To get you started, here's just a few of the ideas I came up with for Loose Leaf:

 - Sign up for HARO: [http://www.helpareporter.com/](http://www.helpareporter.com/)
 - Run a sponsored ad for a week on a high profile blog
 - Open source portions of the codebase
 - Be more active in local meetups, meet more people
 - Find list of top bloggers in my target audience, and reach out for advice and/or sponsored post
 - Livestream development of the app
 - Post coding / UI status updates to Vine


## Sort Your Ideas

Now that you've got your list, sort it by how likely it is to work and how expensive it would be to implement.

Now you've got your prioritized list of marketing ideas, it's time to start executing.

## Find What Works

From now until launch you'll want to slowly work through this list. Your goal should be to execute at least 1 new idea per week.

Keep in mind that some ideas will take longer to execute than others. Running an ad for instance only takes a bit of time to write the ad and push it live - it's 100% passive after that. Some ideas will take weeks before you'll know if they pay off.

As an example: I started livestreaming iOS development in January, but it wasn't until late February that it started to pay off with any traffic - and suddenly in April [with multiple](http://money.cnn.com/2015/04/07/technology/watch-people-code-livecoding/) [news articles](http://www.itworld.com/article/2907129/think-different-by-live-streaming-your-coding-sessions.html). I had the least confidence in this idea, and so far it's generated more traffic than nearly anything else I've tried. This just reiterates that you should record _all_ of your ideas, and slowly iterate through each of them - don't leave any page unturned.


# Step 4: Your Business Model

We're on step 4 and we still barely built anything! I know your inner engineer is cringing, but believe me this is good news. It means you haven't wasted any of your dev time on an idea that'd otherwise fail out of the gate.

Today is the inflection point, we're nearly to the building phase, just a little further to go.

## Draft Your Business Model

This is your first best guess about how you'll make money. It's likely that this'll change in the future, and that's ok. Your community building so far should have informed you that (a) they want your product, and (b) how/if they're willing to pay for it.

Common models for apps, pick **one**:

- [ ] Sell an app for a fixed price
    - [Loose Leaf](https://itunes.apple.com/us/app/loose-leaf/id625659452?mt=8&uo=4&at=10lNUI&ct=github) launched this way, we're a dying breed. [I recently changed to free with IAP](http://blog.getlooseleaf.com/post/115348248184/loose-leaf-is-free).
    - games were recently [featured on the App Store](http://www.wired.co.uk/news/archive/2015-02/13/pay-once-and-play-apple-apps) that followed this model
- [ ] Free app, with single fixed price IAP to unlock all features
    - many productivity or reference apps do this to effectively provide a free trial
- [ ] Free app, with multiple fixed price IAP, possibly consumables, to unlock different features
    - Paper by 53, before they went free
- [ ] Free app, with subscription IAP for recurring services
    - Dropbox, Evernote, etc
- [ ] Free app, with consumable IAP
    - most games
- [ ] 100% free app used as marketing for real world product
    - Paper by 53, after they went free, to sell more Pencil
    - Adobe mobile apps, to sell their stylus and larger Mac apps
- [ ] Advertising    
	- I hesitate to even list this one, it's usually the cop-out business model. You should know that you need **huge** traffic to make ad revenue work. "It'll be viral and we'll make crazy ad revenue" is not a business model.

I can't count the number of times I hear founders talk about the myriad ways they'll make money. "We'll have ads! And paid upgrades! And sell t-shirts! and of course subscription revenue from our pro users!" This is your first clue that you don't understand your audience, go back to the start of Step 2 and get more feedback from your potential customers. You can expand to more revenue streams _after_ success, but for launch you need to pick _one_.

You should have 1 revenue model, and be working to validate that 1 model starting right now. If that model doesn't end up working out, you'll find out soon and can iterate to a new model - that's fine. It's better to pick one => prove it wrong => move to a second model. Trying too many models at once confuses your users, confuses your dev schedule, and confuses your success metrics.

## Estimate Lifetime Revenue / User

Everytime someone downloads your app, how much money do you make? The estimate for this number will be different for each app, category, and revenue model.

Here's a few numbers to help you estimate what your $/download might look like:

 - email addresses that you collect will convert to downloads at 50%
 - paid apps will convert traffic => downloads at roughly 3 to 5%
 - free apps will convert traffic => downloads at roughly 20-30%
 - free apps can convert users to IAP at roughly 3%
   - note that multiple IAP options will each have their own conversion rate
   - so saying (3% paid app) > (30% * 3% from free app) isn't strictly true
   - 3% conversion to monthly subscription is much more than 3% once up front paid app for instance.
 - Ads will be $1 / 1000 app launches
 - out of app conversions - hardware, desktop software, etc - will convert at < 1%

Of course these are super rough numbers, and might be dramatically different depending on your audience and model, but they should give you a good rough start.

To give you an idea how different conversion rates can be depending on product and audience, check out the [post at Sensor Tower that compares avg $/user by app store category](https://blog.sensortower.com/blog/2015/04/16/how-much-money-ios-apps-make-per-download-by-category/).


## Confession Time

Remember how I didn't properly validate my target market early on with [Loose Leaf](https://getlooseleaf.com)? That mistake compounded here.

Since I was aiming at a professional manager target audience, I launched with a up-front-paid-for app. "Professional managers won't have a problem paying a tiny amount for a professional app they'll use for work." That might've been true if I'd gotten traction from that audience, but teachers and students gave me much larger traction, and they don't have the expendable income that professional managers do.

I had the wrong audience in mind, so I chose the wrong revenue model. Oops! Four months after launch I was finally able to pivot into a free app with IAP to better target these education users. It was a costly mistake, and set me back dramatically.


## Check In

At this point, you have:

- [ ] a solid idea of your target market
- [ ] a product idea that's been validated from the above market
- [ ] a list of marketing ideas that you're slowly working through
- [ ] a business model with a well defined MVP that executes that idea


## Define Success

You have all of the information necessary to decide "will it work?". Success is different for different people. Maybe you just want some hobby money. Maybe you just want it to break even, put it on your resume, and trade up in job. Maybe you want to go full time indie app dev, and this is your ticket. For all of these, you need to think through:

- [ ] How much $$ do I *need* to make (not want, need)
- [ ] How much $$ do I make per user (known from your business model)
- [ ] How many customers exist for my product (known from market research)
- [ ] Given my conversion rates, how much traffic to I need to generate to meet these goals?

Your goal here is to figure out how many users you need to get to know if your app will be successful. This gives you a concrete goal to aim towards with your marketing. It'll take you out of "lots of users! viral! hockey stick!" and focus you towards concrete user goals.


# Step 5: Make a Prototype

- [ ] Use something like [proto.io](https://proto.io) or [popapp.in](https://popapp.in) to make a quick prototype
- [ ] Alternatively, make a video that fakes someone using a "finished" app to help you get the point across
- [ ] Show people in your audience. Validate you're on the right track

Don't spend more than a few days building out a prototype. You only want to build enough to validate that you've got the right audience <=> product match.

By this point, you (a) have an audience and (b) have a proof of concept. If people aren't lining up, then you're doing something wrong. Either your marketing is off, audience is off, or product is off.

Iterate on the idea and marketing to prove that (a) you're product is on the right track and (b) you can connect with your audience before commiting serious dev time in the next step.


# Step 6: Building the App

Throw away your prototype. Don't use that as a foundation going forward. Actually throw it away, _do not re-use any of its code_. For most engineers this is obvious, but it can be easy to think "oh look it's nearly done!" or "This can help jumpstart serious dev!" These are both lies, and you'll end up paying for it at the end of your dev cycle if you continue with prototype code.

## Planning your Timeline
Plan out roughly how long you have to build the app. However much time you give yourself, that's how long it'll take. Make sure to budget 30% of your timeline for QA.

Also remember the enginering maxim: "The first 90% of the product took the first 90% of our time, and the last 10% of the product took the last **90%** of the time!" When in doubt, double your engineering estimate for any given task.

Purposefully decide on priority of:

1. feature list
2. quality
3. timeline

You cannot have all three of these - you must prioritize your timeline, quality, or feature list at the sacrifice of the others.

Every product and development decision you make should be weighed against this priority list.

## Build It!

- [ ] Build the app (It's your MVP remember, keep it small!)
- [ ] Behavior tracking, I use [Mixpanel](http://mixpanel.com)
- [ ] Crash Reporting, I use [Crashlytics](http://crashlytics.com)
- [ ] QA the app
	- [ ] Manual regression tests. These are high cost but difficult to automate
	- [ ] Automated unit tests. write these for high value and tricky code.
	- [ ] Automated UI tests. I haven't done these for mobile, but have been super helpful for past web work. Xcode has tools for this. [KIF](https://github.com/kif-framework/KIF) is another great option.
- [ ] Get beta users ASAP
	- excited beta users are best, the fall off rate for beta users can be high, so always be finding and adding new testers

Just because you're building something doesn't mean you can forget about building your audience. Remember to stay on top of Twitter/FB/etc and stay connected to your customers.

- [ ] [Vine](http://vine.co) - Make a vine account and post short 5s videos showing your progress as you build the app
	- People love seeing progress, and sometimes you'll be surprised at what hits a nerve and gets re-shared



## Collect inbound links

The goal here is to start getting 3rd party people talking about you, even if just to say that you exist. Inbound links to your site from credible 3rd parties helps increase rankings in Google, and also helps validate you to press as you start pitching later.

You've already started this process in Step 3, and now it's really time to double down. You should've gone through a fair number of ideas from your original brainstorm, here's a few more to keep you going:

- [ ] Sign up for [HARO](http://www.helpareporter.com)
	- this site connects reporters to sources, and is an easy way to get quoted in the press.
	- They send you daily email(s) with pitches from press. Simply reply w/ your response and info for a chance to be included in the story with a link to your site
- [ ] Start a company/dev blog
	- I've recieved lots of traction from [Loose Leaf's dev blog](http://blog.getlooseleaf.com), it's been great for inbound links
	- Start posting interesting content about anything. some ideas:
		- how/why you started the company
		- the problems of your current target audience
		- interesting tech you've created as you built your product
- [ ] Brainstorm even more ideas from the channels you read about earlier in [Traction](http://amzn.to/1DBn0Lo)
	- schedule these ideas into your development schedule - even put tasks in your issue tracker
	

## Public Buzz Building Beta

- [ ] Submit to BetaList
- [ ] Submit to PreApps
- [ ] Continue building community, and feed those people into your beta signups
- [ ] Get Feedback Feedback Feedback!

At this point you're very close to launch. The app is "ready" but not ready. The most important thing to do now is make sure that new users are effective when they start up your app for the first time.

- [ ] What makes a new user "successful" when they use your app?
	- take a photo? post a comment? signup for an account? invite a friend? spend 5 minutes in app?
	- there should be 1 thing a user does that's your goal for every user
- [ ] Track success rate of beta testers getting to this success point
- [ ] Optimize your new-user flow to minimize drop off for new users

Beta will help you catch user confusion and awkward onboarding flows that you weren't able to catch in the prototype / survey phase. You're goal here isn't building new features, it's making sure new users understand your current features and can be effective.


## Confession Time

I didn't do nearly enough beta testing before launching [Loose Leaf](https://getlooseleaf.com). While I did add in lots of behavior tracking, I didn't have enough data pre-launch to see problems with my first-time user flow.

It turns out that the new-user tutorial content I had in the app was severely lacking for some features, and that translated to a pretty severe drop-off rate for new users. I've had to spend time post-launch rebuilding new tutorial content to explain some features.


## Check In

At this point, you have:

- [ ] a finished app!
- [ ] a launch website that speaks to your audience and asks for (and converts!) their email address
- [ ] a list of potential customers awaiting your launch email
- [ ] inbound links and traction from 3rd party sites linking to your product
- [ ] a short list of marketing strategies that are working, and a long list of marketing ideas still to try


# Step 7-∞

** This section has more info coming, it's incomplete **

Nearly there! Now submit to the store!

## Pitch Your App's Story
By now you've probably already learned: nobody cares about new apps or new features - People only care about how you solve their problems. You should have a 2 sentence pitch for your app describing the problem you solve, why you're the one that sovles it, and how someone can get your app.

This is the message you want to send out to your target audience at launch. As you ask for reviews from sites, it's this story that you can pitch to them. "This is why you're readers, podcast listeners, etc, will care about this."

Remember from [Trust Me I'm Lying](http://amzn.to/1Adie3W) that bloggers and press don't care about sending you traffic, they care about _you sending them traffic_! If your story resonates with their audience, then the review will generate page views on their article, and only then will they care about it.

Before you reach out to press, understand why their audience will care. And since you've already grown traction with your market with a well defined problem + solution, this should be an easy pitch!

## App Store Optimization

Over 50% of people find apps to download [just by searching the app store](http://www.businessinsider.com/chart-of-the-day-how-people-find-apps-2012-8). Not deal sites, not app reviews, not through Google - it's the App Store search. That's why it's incredibly important to spend some time on App Store Optimization (ASO).

- [ ] [Find the right keywords](http://blog.getlooseleaf.com/post/109888977759/step-by-step-app-store-optimization-an-objective)
- [ ] Write up your app's Title, Keywords, Description
- [ ] Screenshots w/ context
- [ ] [Make an App Preview video](http://blog.getlooseleaf.com/post/107205893655/step-by-step-making-an-itunes-app-preview)

## App Submission

Now that your app is done, it's time to submit to the app store!

- [ ] Set your go-live date to sometime in the future, don't let it auto-go-live
- [ ] List of sites to submit your app as you enter Beta
- [ ] List of sites to submit your app the few weeks before launch
- [ ] Line up multiple sites to write about your app when it goes live

## Pitch to Review Sites

Once your app has been reviewed by the App Store, has been approved, and has it's release date set some time in the future - now it's time to pitch all of the app review sites that you can.

- [ ] Even though your app isn't live, you can still generate promo codes to give to reviewers! This is a much easier way to get them the app to review than TestFlight or Hockey, etc
- [ ] You should have connected w/ some reviewers by this point, reach back out and let them know you've submitted
- [ ] Keep your email brief, bullet point list
- important info:
	- [ ] Name and iTunes URL of app
	- [ ] Date it'll be live (You should already be approved + set this in itunes connect)
	- [ ] Links to promo videos / app preview video
	- [ ] link to .zip press kit that includes screenshots and logo

# Launch!

And now the marathon begins!

- [ ] Email your list and let them know it's live! Ask for downloads _and reviews_.
- [ ] Track daily active users and daily new users
     - If active users isn't growing with new users, than your active users are just churning and leaving. Find out why and keep them engaged.
- [ ] Watch your Mixpanel and Crashlytics feedback for trends, and adjust the app as necessary
- [ ] Continue iterating on your marketing idea spreadsheet

# "Am I too late?"
What if you've already launched your app, or are already neck deep in product development, is it too late to start? Should you just skip the first half of this guide and pick it up somewhere in the middle?

Nope and nope!

It's never too late to start working through this marketing plan and synchronizing it into your development schedule. The most important thing is to start wherever you are now and take concrete steps toward where you want to be: connected to your target audience and building a product they're eager for.

## Redemption Time
I've confessed many of my mistakes with Loose Leaf, chief among them: I started with the wrong audience, wrong revenue model, and didn't have a marketing plan till post-launch. Oops?

However!

Shortly after launch, I buckled down and started reading, learning, and then _implementing_ a marketing plan for Loose Leaf. That was November. I pushed through the Traction spreadsheet I'd built, following everything I just wrote about in this plan, and it paid off big time in March with nearly [100k downloads in one weekend](http://blog.getlooseleaf.com/post/113969679734/100k-downloads-in-1-weekend)! And it's continued to work with another near 18k downloads over the following month!

It can be a tough road, and it can sometimes take longer than we'd like, but it works. This is a marathon, not a sprint.

# Contribute!

This guide is open for a reason - Feel free to fork and contribute your own ideas and edits back for us all to improve from. This guide is a living document, I'll continue to update it with additional info and ideas as I can, and as often as I get suggestions, feedback, and contributions from you!

As indie devs, we don't have funding, a marketing department, or golden handshakes with insiders - anything we can do to help advise each other is invaluable.

Reach out to me on twitter: [@adamwulf](https://twitter.com/adamwulf)

Follow Loose Leaf's story at: [http://blog.getlooseleaf.com](http://blog.getlooseleaf.com)

And go [download Loose Leaf](https://itunes.apple.com/us/app/loose-leaf/id625659452?mt=8&uo=4&at=10lNUI&ct=github) and show your fellow indie dev some love! ;) 