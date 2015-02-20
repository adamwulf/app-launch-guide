# An App Launch Guide

## Why
This guide is aimed at indie developers who are building and launching their iOS apps largely by themselves. The guide will walk through planning, pre-launch, marketing, product dev, QA, and launch.

The goal is to help ensure that no step is missed during the process, so that you never have the "oh i wish I'd..." moment months into development.

## Who
My name is Adam Wulf, and I've worked on mobile apps both in large and also as an indie developer. I have recently launched [Loose Leaf](https://getlooseleaf.com) and am launching [Remotely](http://getremotely.com) very soon. This guide is a collection of lessons learned.

## Contribute
I missed some stuff! I'm only one guy with my own limited experience. If you see that I've missed some info or have helpful resources to share, submit an issue or PR, or just [get in touch](http://twitter.com/adamwulf)


# Step 0

## Books to read

Take a few evenings and read through these books. They're incredibly helpful for helping you understand the incentives of press/web/sites/buzz/etc, and also give concrete advice and ideas for how to market your app.

- [ ] [Trust Me I'm Lying, by Ryan Holiday](http://amzn.to/1Adie3W)
	- Awesome book describing the incentives of big press and how to "trade up" from smaller to larger sites
- [ ] [Traction, by Gabriel Weinberg](http://amzn.to/1DBn0Lo)
	- Describes 19 marketing channels any start up can use, and a process for trying them out



# Step 1: Finding the App Idea

Every good app starts with a good idea, and we all have too many ideas already. Day one helps you filter these ideas to find the right one.

- [ ] Think of a general app idea

This idea will change throughout the process, and that's ok. The only important thing is that you have a general direction you're headed. Nothing is proven, nothing is set in stone, this idea is just pointing you in a direction, any direction.

- [ ] Define your target audience

This doesn't need to be super specific yet, but you need to have a general idea of who'll use your app. Older folks? Younger? Teens? Family? Single? Professional? Occupation?

- [ ] Define the problem you solve

What problem does your audience have that your app solves? Does it them complete a task faster? more competely? Does it reduce two problems to one problem?

- [ ] Market research

Look for similar apps that are already in the store. It doesn't matter if my-idea-is-a-special-snowflake, people are already (a) solving your problem with some other app or (b) don't actually have the problem you think they do.

- [ ] Validate your idea

 - Google Surveys
 - Setup Twitter account, follow target audience, measure follow-back rate
 - Setup landing page to collect email addresses. measure converstion rate
 - Ask people in your target audience
    - friends and family will be too nice to you, get objective feedback


# Step 2: Validating the App Idea

Most startups because they can't find customers, not because they don't have a product. You need to start finding your customers right now, before you've built anything, and verify to yourself and to them that your idea from Step 1 is actually something they'd pay for and use.

## Find Your Community

- [ ] Find where your audience meets online. Twitter? Pinterest? Vine? Facebook? Forums?
- [ ] Find where your audience meets offline. Meetups? Marathons? Conferences?
- [ ] Find thought leaders in your community, start listening and entering the conversation
- [ ] Find users on Twitter/Pinterest/etc that are influential

I **cannot stress this enough**, talk to your customers as soon as you possibly can, even before you start building!
     
## Define Your MVP

Define your Minimum Viable Product - How little can you build and still provide value to your customer?

- [ ] Will it have a web site or service?
- [ ] Can you use Parse or CloudKit instead of building your own.
	- you're not worried about lock in, you can change to something else after you have the $$ from your success. Right now, you're focused on spending as little as possible on dev costs to get that initial success
- [ ] iPhone? iPad? Android? Mobile web? Native?
- [ ] "If i didn't build feature X, is it still useful?" Then don't build feature X.
	
## Build a Landing Page

Now you know who your customers are, where they are, and what you want to sell them. Build a landing page that describes exactly those things, and *start collecting email addresses*.

This website will do a few things for you:

 - these are the people most likely to buy your product on day one
 - it'll further validate that your customers actually want what you're building
 	- if you can't get their email, you defintiely can't get their money

I use [MadMimi](https://madmimi.com/short_ref/nyw) to manage my email list, but there's lots of options out there for free and for cheap.

You should aim for 5% to 10% of incoming traffic to convert into an email address.

One great way to test conversions:

1. Find influential Twitter users who have followers in your target audience.
2. Setup a Twitter account (fill out the bio + icon + etc. tweet a bit to flesh out the profile. 
3. Make sure to add a link to your landing page in your bio.)
4. and auto-follow their followers.

You should aim for roughly %5 to 10% of those people following your account back, and roughly 20% of those should be converting on your site into email addresses. If that's not the case, then you've missed your audience, missed your product, missed your pitch of the product, or all three. A/B test and try new audiences to track down the issue.

Make sure to keep your Twitter account active, no one will bother following an inactive account. A good goal is ~1 or 2 tweets a day, and a free [Buffer](http://bufferapp.com) account can make that easy to manage.


## Draft Your Business Model

This is your first best guess about how you'll make money. It's likely that this'll change in the future, and that's ok. Your community building so far should have informed you that (a) they want your product, and (b) how/if they're willing to pay for it.

Common models for apps, pick **one**:

- [ ] Sell an app for a fixed price
    - [Loose Leaf](https://itunes.apple.com/us/app/loose-leaf/id625659452?mt=8&uo=4&at=10lNUI&ct=github) launched this way, we're a dying breed
    - games were recently [featured on the App Store](http://www.wired.co.uk/news/archive/2015-02/13/pay-once-and-play-apple-apps) that followed this model
- [ ] Free app, with single fixed price IAP to unlock all features
    - many reference or productivity apps do this to effectively provide a free trial
- [ ] Free app, with multiple fixed price IAP, possibly consumables, to unlock different features
    - Paper by 53, before they went free
- [ ] Free app, with subscription IAP for recurring services
    - Dropbox, Evernote, etc
- [ ] Free app, with consumable IAP
    - most games
- [ ] 100% free app used as marketing for real world product
    - Paper by 53, after they went free, to sell more Pencil
    - Adobe mobile apps, to sell their stylus and larger Mac apps

I can't count the number of times I hear founders talk about the myriad ways they'll make money. "We'll have ads! And paid upgrade! And sell t-shirts! and of course subscription revenue from our pro users!" This is your first clue that you don't understand your audience, go back to the start of Step 2 and get more feedback from your potential customers.

You should have 1 revenue model, and be working to validate that 1 model starting right now. If that model doesn't end up working out, you'll find out soon and can iterate to a new model - that's fine. It's better to pick one => prove it wrong => move to a second model. Trying too many models at once confuses your users, confuses your dev schedule, and confuses your success metrics.

# Step 3: Define Success

We're on step 3 and we still barely built anything! I know your inner engineer is cringing, but believe me this is good news. It means you haven't wasted any of your dev time on an idea that'd otherwise fail out of the gate.

Today is the inflection point, we're nearly to the building phase, just a little further to go.

At this point, you have:
- [ ] a solid idea of your target market
- [ ] a product idea that's been validated from the above market
- [ ] a list of potential customers, and a website that's generating more
- [ ] a business model with a well defined MVP that executes that idea

You have all of the information necessary to decide "will it work?". Success is different for different people. Maybe you just want some hobby money. Maybe you just want it to break even, put it on your resume, and trade up in job. Maybe you want to go full time indie app dev, and this is your ticket. For all of these, you need to think through:

- [ ] How much $$ do I *need* to make (not want, need)
- [ ] How much $$ do I make per user (known from your business model)
- [ ] How many customers exits for my product (known from market research)
- [ ] How many customers can I convert (known from your conversion rate on your site)
	- helpful hints for estimating:
		- roughly 50% of email signups will actually get the app
		- roughly 2% of users will buy in-app purchases
		- roughly 2% of users who click through to the store will buy/download

# Step 3-∞

## Make a Prototype Quickly
- [ ] Use something like [proto.io](https://proto.io) or [popapp.in](https://popapp.in) to make a quick prototype
- [ ] Show people in your audience. Validate you're on the right track


- [ ] Build the app (It's your MVP remember, keep it small!)
- [ ] Behavior tracking, I use [Mixpanel](http://mixpanel.com)
- [ ] Crash Reporting, I use [Crashlytics](http://crashlytics.com)
- [ ] QA the app
	- [ ] Manual regression tests. These are high cost but difficult to automate
	- [ ] Automated unit tests. write these for high value and tricky code.
	- [ ] Automated UI tests. I haven't done these for mobile, but have been super helpful for past web work. Xcode has tools for this.
- [ ] Get beta users asap
	- excited beta users are best, the fall off rate for beta users can be high, so always be finding and adding new testers


# Step 4-∞

## Collect inbound links

The goal here is to start getting 3rd party people talking about you, even if just to say that you exist. Inbound links to your site from credible 3rd parties helps increase rankings in Google, and also helps validate you to press as you start pitching later.

- [ ] Sign up for [HARO](http://www.helpareporter.com)
	- this site connects reporters to sources, and is an easy way to get quoted in the press.
	- They send you daily email(s) with pitches from press. Simply reply w/ your response and info for a chance to be included in the story with a link to your site
- [ ] Start a company/dev blog
	- Start posting interesting content about anything. some ideas:
		- how/why you started the company
		- the problems of your current target audience
		- interesting tech you've created as you built your product
	- I've recieved lots of traction from [Loose Leaf's dev blog](http://blog.getlooseleaf.com), it's been great for inbound links
	
	

## Public Buzz Building Beta

- [ ] Submit to BetaList
- [ ] Submit to PreApps
- [ ] continue building community, and feed those people into your beta signups
- [ ] Get Feedback Feedback Feedback!

At this point you're very close to launch. The app is "ready" but not ready. The most important thing to do now is make sure that new users are effective when they start up your app for the first time.

- [ ] What makes a new user "successful" when they use your app?
	- take a photo? post a comment? signup for an account? invite a friend? spend 5 minutes in app?
	- there should be 1 thing a user does that's your goal for every user
- [ ] Track success rate of beta testers getting to this success point
- [ ] Optimize your new-user flow to minimize drop off for new users

Beta will help you catch user confusion and awkward onboarding flows that you weren't able to catch in the prototype / survey phase. You're goal here isn't building new features, it's making sure new users understand your current features and can be effective.



# Step 5-∞

Nearly there! Now submit to the store

## App Store Optimization

- [ ] [Find the right keywords](http://blog.getlooseleaf.com/post/109888977759/step-by-step-app-store-optimization-an-objective)
- [ ] Title, Keywords, Description
- [ ] Screenshots w/ context
- [ ] [Make an App Preview video](http://blog.getlooseleaf.com/post/107205893655/step-by-step-making-an-itunes-app-preview)

## Pitch to Review Sites

- [ ] You should have connected w/ some by this point, reach back out and let them know you've submitted
- [ ] Keep your email brief, bullet point list
- important info:
	- [ ] Name and iTunes URL of app
	- [ ] Date it'll be live (You should already be approved + set this in itunes connect)
	- [ ] Links to promo videos / app preview video
	- [ ] link to .zip press kit that includes screenshots and logo

## App Submission

- [ ] Set your go-live date to sometime in the future, don't let it auto-go-live
- [ ] List of sites to submit your app as you enter Beta
- [ ] Lits of sites to submit your app the few weeks before launch

