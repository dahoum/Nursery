# Jamstack

According to Wikipedia Jamstack comes from JavaScript, something, something.

I have a better idea.

Jamstack is jam stack. The same way in jazz there are jam sessions. Jamstack is a world of services, which allows you to code and build digital products and services, w/o the need to take care of installing and running servers, because Jamstack is Serverless: all you need after you have written the code is a payment method (and in many cases not even that, most Jamstack services have a free plan, which is enough to try, develop and even run early stage projects).

## How is Jamstack different from Amazon AWS, Microsoft Azure and Google Cloud Platform?

Amazon AWS, Microsoft Azure and Google Cloud Platform, have _everything_ each. This means they compete across the board of their services.

Unlike Amazon AWS, Microsoft Azure and Google Cloud Platform, Jastack consists of individual services, run as separate, individual companies, freely combinable.

This brings forward several advantages:

1. Each service is run as an individual company, by focused individuals, which have this one goal. Focusing on one goal delivers higher quality.
2. If, despite the focus on quality, described in point 1, you are unhappy w/ a specific Jamstack service, the individual Jamstack services are easily replaceable.
3. If a service is missing, there is an enterpreneurial oportunity to create one, Jamstack is in a Klondike mode at the moment.
4. The Jamstack ecosystem is endlessly healthier than an ecosystem dominated by three global near-monopolies.

## What about Amazon AWS, Microsoft Azure and Google Cloud Platform?

The individual Jamstack services, eventually, runs on top of Amazon AWS, Microsoft Azure and/or Google Cloud Platform.

Jamstack, when done well,

* adds a layer of abstraction on top of Amazon AWS, Microsoft Azure and Google Cloud Platform,
* removes or reduces their complexity,
* adds value through tiny bits, which the major player have no time or enthusiasm to think about.

## Jamstack and Serverless

The best Jamstack is truly Serverless.

### What is Serverless?

The definition of Serverless is that after the git what you mostly need is a credit card.

There is no talk about CPU, RAM and HDD limitations on application level.

The terminology switches to execution time, number of calls and RAM per execution call and to bandwidth and storage which are billed, but scale in a linear fashion.

Switching the resource measurement from application level to the level of the individual call is very healthy for the engieneering discipline and simplifies the engineering work.

> Instead of coding and then stress testing the whole application on a limited hardware, it is enough to make sure that the individual calls are efficient and that the scaling is guaranteed by the Jamstack Service.

## What are Jamstack examples?

### Jamstack Serverless Static Frontend Hosting

* Netlify (see below)

### Jamstack Serverless Backend Hosting

* Netlify (see below)

### Serverless Static Frontend Hosting and Backend Hosting Combinations

* [Netlify](https://netlify.com)
  * A static frontend hosting that will make you purr.
    * Deploy directly from GitHub, GitLab or Bitbucket
    * Branch deploys and deploy previews on PR enable you to have N zero configuration environments.
  * Handles your AWS Lambda functions as a subfolder.
    * Enables you to have fully Serverless backends.
    * Each branch deploy and deploy preview on PR has its very own version of the backend. 
    * Centralises and simplifies the billing.
  * Rapid innovators.

### Jamstack Serverless Databases

* [Fauna](https://fauna.com)
  * Probably the most Jamstack Serverless database out there.
  * since 7 July 2021 Fauna supports [Region Groups](https://docs.fauna.com/fauna/current/api/fql/region_groups) (see the [Announcement](https://fauna.com/blog/meeting-data-residence-and-increasing-performance-with-fauna-region-groups)), which open the door for applications w/ strict compliancy restrictions on the location of the data.
  
### Search as a Service

#### Algolia

https://www.algolia.com

https://en.wikipedia.org/wiki/Algolia

Algolia is a U.S. startup company offering a web search product through a SaaS (software as a service) model.

### Jamstack Nearly-Serverless Databases

* [MongoDB Atlas](https://mongodb.com)
  * MongoDB Atlas is 100% Jamstack.
  * MongoDB Atlas is not 100% serverless based on the purity of the definition, as it deals w/ terms such as RAM and HDD.
  * MongoDB Atlas is included here nevertheless, because it fills an important niche. Fauna, for example, does not have geospatial support, while MongoDB has an excellent one.

### Jamstack Serverless Conversational Bot Management Systems

* [Blits](https://blits.ai)
  * Leading Serverless Conversational Bot Management System.
  * Allows connection to all 40+ NLP engines
  * Allows connection to all existing channels (Slack, Facebook Messenger, SMS, etc.)
  * Allows connection to the total IT Landscape of the organisation reading to power the conversations and writing data from results from the conversations.

### Jamstack Serverless CronJobs/ Job Queues

* https://repeater.dev
  * Provides heartbeat.

### Jamstack Serverless Automation of Quality

* https://auxta.live
  * Provides Peace of Mind to everyone starting w/ the C-Level through Automation of Functional Quality and Compliance Monitoring
  * 100% Serverless
  * Runs on Netlify

## Jamstack Serverless APIs

### Weather

#### Spire

https://spire.com

Reliable, high-impact insights about the Earth, oceans, and atmosphere to power your most exciting initiatives.

https://en.wikipedia.org/wiki/Spire_Global

Spire Global, Inc. is a space-to-cloud data and analytics company that specializes in the tracking of global data sets powered by a large constellation of nanosatellites, such as the tracking of maritime, aviation and weather patterns.

The company currently operates a fleet of more than 110 CubeSats, the second largest commercial constellation by number of satellites, and the largest by number of sensors. The satellites are integrally designed and built in-house. It has launched more than 140 satellites to orbit since its creation.

The company has offices in San Francisco, Boulder, Washington DC, Glasgow, Luxembourg, Singapore.

## What runs on Jamstack?

### Static Site Generators

The first thing that runs on Jamstack are the static site generators.

https://gohugo.io

https://www.gatsbyjs.com

## Jamstack Sources and Opinions

### Jamstack.org

https://jamstack.org

### Jamstack WTF

https://jamstack.wtf

### the New Dynamic

https://www.tnd.dev

## Serverless Sources and Opinions

Serverless is not Jamstack, but Serverless Jamstack is the true Jamstack.

### Serverless "Chats"

https://www.serverlesschats.com

## People

### Jeremy Daly

https://www.jeremydaly.com

https://github.com/jeremydaly

_Different opinion? Error? Ommission? Open a PR or email me at t.e.shaw@dahoum.wales_
