---
title: "Questions"
date: 2017-10-19T19:43:28-07:00
draft: false
---



# Netlify Tech Screen Q&A

### Rank your 5 favorite, and least favorite activities from this [list] (https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6)

- Favorite

1. Manage a support team

2. Work with people to figure out if Netlify's service can solve a particular workflow or integration challenge they have

3. Receive occasional phone calls requesting support from our highest-value customers

4. Suggest and champion improvements to the product and workflow to your colleagues in and out of support

5. Work with the development team to help design a new feature based on feedback from customers

- Least Favorite

1. Respond to Netlify fans on Twitter

2. Work with prospective customers to explain our service and the pricing model

3. Set up your own copy of several static site frameworks for debugging

4. Debug a customer's build using a programming language and framework that you've never seen before

5. Create video tutorials to help teach users a specific feature or use case


### What is your favorite thing about providing technical support?

I love learning new things, and every support ticket is an opportunity to discover something you didn't 
know about your product, your customer's implementation and workflow, or the most efficient way to solve
the problem presented. 


### What did you think of our service during the time you used it?

I think I have a lot more to learn about the service before I can offer a useful critique! However I thought 
it was really easy to set up, the integration with github is breathtakingly cool, and 3rd party support videos 
on YouTube abound (clearly there are a bunch of users really excited about your tool!). 

I did run into an unexplained error message when trying to deploy the site using sitegen.com which was frustrating 
("Something unexpected happened!"). 

### Tell about how you made your site and why you chose the tools you did. Briefly explain a challenge you experienced in setting up this site and how you solved it.

I chose the Hugo for my site generator because it was easy to configure on Windows (my available OS) and because the most 
support videos were available on YouTube for the Hugo/Netlify setup (along with the [step-by-step on Netlify] (https://www.netlify.com/blog/2016/09/21/a-step-by-step-guide-victor-hugo-on-netlify/). I experienced an unexplained error when trying to deploy 
the site but I found the solution quickly by googling the issue and following instructions for setup that I had previously 
neglected.

I also had some pretty significant problems applying a theme, something I am used to WordPress and Wix doing for me automatically. This was a totally different world! I still have a non-working index.html file, but since my header contains the blog links 
I gave up trying to fix it due to time constraints. 

### Could you give us a suggestion to improve this test or the job posting?
My favorite customer service question to answer is "what is your favorite book on customer service" since I get a chance to share my cultural values as reflected in my reading material.
(by the way it's [Getting Naked by Patrick Lencioni] (https://www.amazon.com/Getting-Naked-Business-Shedding-Sabotage/dp/0787976393/ref=sr_1_1?ie=UTF8&qid=1508518700&sr=8-1&keywords=getting+naked))

### Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.

I really love the Zapier [technical documentation] (https://zapier.com/developer/documentation/v2/reference/). The developer 
guide is also a checklist for publishing solutions within Zapier, which consolidates the number of places you need to reference 
in order to find answers. The Zapier staff language is incredibly clear and concise, and I never have trouble finding what I need whether
by using an index or a google search.

### Why do you think SSL/HTTPS is important?
Obviously encryption is important to protect sensitive customer data. From an e-commerce standpoint you just can't sell (from your blog, for instance) unless you have installed a certificate. 

### Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users

For non-technical customers the biggest challenge is "how do I find the answers"? If you are working with SaaS instead of coding (there are massive support communities for developers such as stckoverflow where
basically any question can be answered) you are continually running into problems or workflow issues and often have few places to turn for support. This is why SaaS companies correctly place such a high priority on their 
customer service/success teams. Basically, the best support teams are winning the customers. This isn't just traditional support tickets/calls, either. Building a community through active, well organized forums 
(and making sure that your support staff actively checks and answers questions) is vital to retaining customers. 

A related problem is "where is the information stored"?  Especially in DNS configuration the location of something as simple as the DNS-A file can be hard to discover, especially if you are building the site via 
a SaaS which has helpfully outsourced the DNS to a third party. 

### A customer writes in saying their site won't build.  Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.
Hi Joe!

Thank you for contacting the support center, and I'm sorry you are experiencing the frustration of your site not building.

We have a great overview of [How our Bots Build Sites] (https://www.netlify.com/blog/2016/10/18/how-our-build-bots-build-sites/). Under the heading "Want to try to make your own sausage?" you can see instructions for debugging your build. If you follow these instructions
you will have a logfile that we can dig into together to figure out what is going on. Please send it to me in response to this ticket. 

You will also see some information about what probably went wrong with your build - almost always a conflict in the versions between the tools you want to use and the ones we are building with! Check the version information carefully while you are examining the logfile.

Please do get back to me! I'm here to get your site up and running.

### (optional/bonus) Can you set up a redirect from /netlify/anything to https://www.google.com/search? q=anything ?


