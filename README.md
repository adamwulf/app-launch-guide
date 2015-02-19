# An App Launch Guide

## Why
This guide is aimed at indie developers who are building and launching their iOS apps largely by themselves. The guide will walk through planning, pre-launch, marketing, product dev, QA, and launch.

The goal is to help ensure that no step is missed during the process, so that you never have the "oh i wish I'd..." moment months into development.

## Who
My name is Adam Wulf, and I've worked on mobile apps both in large and also as an indie developer. I have recently launched [Loose Leaf](https://getlooseleaf.com) and am launching [Remotely](http://getremotely.com) very soon. This guide is a collection of lessons learned.

## Contribute
I missed some stuff! I'm only one guy with my own limited experience. If you see that I've missed some info or have helpful resources to share, submit an issue or PR, or just [get in touch](http://twitter.com/adamwulf)


# Step 1

## The app idea

Every good app starts with a good idea, and we all have too many ideas already. Day one helps you filter these ideas to find the right one.

[ ] Think of a general app idea

This idea will change throughout the process, and that's ok. The only important thing is that you have a general direction you're headed. Nothing is proven, nothing is set in stone, this idea is just pointing you in a direction, any direction.

[ ] Define your target audience

This doesn't need to be super specific yet, but you need to have a general idea of who'll use your app. Older folks? Younger? Teens? Family? Single? Professional? Occupation?

[ ] Define the problem you solve

What problem does your audience have that your app solves? Does it them complete a task faster? more competely? Does it reduce two problems to one problem?

[ ] Market research

Look for similar apps that are already in the store. It doesn't matter if my-idea-is-a-special-snowflake, people are already (a) solving your problem with some other app or (b) don't actually have the problem you think they do.

[ ] Validate your idea

 - Google Surveys
 - Setup Twitter account, follow target audience, measure follow-back rate
 - Setup landing page to collect email addresses. measure converstion rate
 - Ask people in your target audience
    - friends and family will be too nice to you, get objective feedback


# Step 2-∞
The content below is placeholder, I'll be organizing and adding to this over the next few days. Pull Requests welcome!

## Building Community

- [ ] Find where your audience meets online. Twitter? Pinterest? Vine? Facebook? Forums?
- [ ] Find where your audience meets offline. Meetups? Gym? Marathons? Conferences?
- [ ] Find thought leaders in your community, start listening and entering the conversation
     - I **cannot stress this enough**, talk to your customers as soon as you possibly can, even before you start building!
     
## Defining MVP

Define your Minimum Viable Product - How little can you build and still provide value to your customer?

- [ ] Will it have a web site or service?
- [ ] Can you use Parse or CloudKit instead of building your own.
	- you're not worried about lock in, you can change to something else after you have the $$ from your success. Right now, you're focused on spending as little as possible on dev costs to get that initial success
- [ ] iPhone? iPad? Android? Mobile web? Native?
- [ ] "If i didn't build feature X, is it still useful?" Then don't build feature X.
	

## Business Model

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


## Make a Prototype Quickly
- [ ] Use something like [proto.io](https://proto.io) to make a quick prototype
- [ ] Show people in your audience. Validate you're on the right track

# Step 3-∞

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

