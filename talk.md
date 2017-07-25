# Workshop intro

Hello; and welcome! I’m Brian Donohue; but you can all call me Dono - and I’m a solutions engineer at Shopify.  

My job is to concept out integrations that scale for our largest customers, and to help determine fit for new customers. I have a deep understanding of the platform, it’s quirks, behaviours and surprises.

A little about me: I started at Shopify nearly 3 years ago. Before that was in broadcasting, and prior to that - the forces as a naval electronics technician.

Before we get too far along - why don’t we get to know each other a little bit.

Group off, I don’t really care how many - 4 or 5, whatever is good for a productive discussion. You don’t even have to move - just choose the people closest to you.

What we’re going to do next in our groups is think of ONE WORD that describes life in Waterloo - feel free to discuss and choose a champion; ultimately only one word per group can be shared. 

You have 5 minutes to discuss!

[5 minute break]

OK! Let’s go around the room; starting with this group - tell me your word!
And how did you get there - what were some other words you thought of?

N+1 this until done.

[My Most Effective One Word Icebreaker](https://www.thebalance.com/my-best-one-word-icebreaker-1918427)

Again, thank you so much for joining - we’re going to get started now, with a little background - and then we’ll be ready to dive right in and interact with Shopify using Shopify’s API.

Let’s back it up a bit - here’s what we’ll cover today:

BACKGROUND SLIDE

API stands for application programming interface. There’s multiple different formats, and APIs can be found inside large apps, for connecting different types of software - and in the context of Shopify, often expanding functionality for the merchant.

This will be something we can learn to use TODAY to get building.

Shopify’s API is where our focus will be today. Shopify’s API is in pretty CONSTANT use from thousands of 3rd parties who have created amazing apps and services that help Shopify customers continue to succeed and grow. Check these out:




 
OK - back to the API. Shopify adhere’s pretty well to the RESTFUL API group of standards… 

REST is an acryoym for Representational State transfer, and sends 4 easy transactions via HTTP to do different actions.

GET |  PUT | POST | DELETE

GET: This is what we use to receive data - in this case, if we want to pull data out of Shopify.

PUT: This is what we use to UPDATE data; so if you have a customer, or an order, or a product and you want to add or amend the information - you’ll use a PUT

POST: This is what is used to create a NEW object or data within Shopify

And DELETE: This one is pretty straight forward.

These 4 transactions make up the ways you can interact with a RestFUL API! 

OKAY - together, let’s head to help.shopify.com/api - these our our API docs, and will help you complete the tasks today. If you’re already familiar with an API; I’d still go through the different early tasks to get a handle on what interacting with Shopify looks like.

Our endpoints are standard URLs - and they’re set up to listen for these transactions from authenticated sources.

For example; if we want to GET some information - which brings us to task one; we need to determine WHICH endpoint, or URL we should use.

In this case - we’re going to start with customers - so lets head to the docs; and find out how to create a customer.

Pretty straightforward, let’s just type the word CUSTOMER into the search box and see what we get.

Scroll down a bit - and we have the URL we need to use!

OK - turn to your card!

We’re going to construct our full request URL

Take your store domain (techyon-workshop-1.myshopify.com) and add the endpoint path to it!

You should have something that looks like this: tachyon-workshop-1.myshopify.com/admin/customers.json

Now we can get started!

:MOVE OVER TO TASK 1 AND FOLLOW ALONG.
