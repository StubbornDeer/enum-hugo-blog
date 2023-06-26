---
title: "How to beat your competitors: a really untapped area"
date: 2023-05-25
tags: ["business", "startups"]
image : "https://github.com/StubbornDeer/public-media-files/assets/91156314/394c01ff-e949-4634-8e67-7b611c27af8b"

Description  : "Let's talk about one of the multiple but unknown, unpopular, and mostly poorly implemented ways to find new and retain existing users."
featured: true
---

### What is the problem?
Users churn. It's the reality we all face some day. And we all keep asking "Why? Why do the hell they go?" What do they need? There are some researches done by independent investigators (mostly businesses) revealing the reasons for it.

For example, Paddle thinks there are 8 reasons for user churn. [They are](https://www.paddle.com/resources/churn-causes):

1. Attracting wrong customers
2. Lacking desired outcomes
3. Poor customer support
4. Lure of competitors
5. Bugs, glitches, downtime
6. Weak value proposition
7. Pricing isn't right
8. Expired credit cards

We agree with them but would like to add that usually, it's not something one, but rather a combination of the reasons. For example, a user faces a glitch and starts looking for another solution - that is cheaper, less glitchy, maybe faster. And if you are restricted by a technology, or some limits of your solution, or even budget, it may be hard to beat the competitors by, say, a speed. Especially if the competitor is a huge corporation (like Google or Microsoft). They have more fastest servers, they have more people to fix all the bugs, they may set up much lower pricing.

So, there is no exit (at the first glance).

But there it is. Because most of big players (and most of all the players no matter how big they are) lacks something very important, something that many users really need from time to time: the support. Yes, it may sound crazy for someone who doesn't know the industry: despite all the effor any company put into the business, the support is still the weakest area.

### How do businesses solve it (disclaimer: usually wrong)?
Let's review how usually the businesses solves this problem. Of course, different businesses have different products, and there are many factors that can affect how the support is organized but let's just review all possible solutions, starting from the worst one:

1. No support at all. May have a community-driven forum where people can ask a question, but nobody will dig into your problem.
2. Support only for the "selected", or for paid accounts (CloudFlare), or have a paid support (Amazon AWS).
3. Support by email (or tickets), can solve a problem but need to wait.
4. Fast and effective support by chat (Namecheap).

As we can see the immediate communication with support may be the most effective way to solve a problem. Unfortunately, it's not easy to organize. First, you need to have some solution (often paid) for chatting, and secondly, what's most important, if your team is small or if you just started you may not be able to provide 24/7 support. As result, frustrated users may see the following messages:

![image](https://github.com/StubbornDeer/public-media-files/assets/91156314/51d2a046-5368-4acb-a492-4da1c649478c)

Another way to help with a problem is to provide as much information as possible. The documentation, guides, articles, how-tos - all this stuff works. But it's still not perfect, and this is why...

### What is the common problem users face

The more documenation and other materials a business has the harder to find an answer. How can someone to find an answer? There are several ways to do it:

1. Google search
2. Website search
3. Download white papers and search on their own

All these solutions are still not perfect as search is usually done by words, and often not by words in the article's content but rather with presence it in the title, or description. So, in many cases, user may not need a direct communication with support but just some way to find a piece of information that may be relevant to his/her case. But how? 

### How to solve this problem (and beat your competitors)
These days we have a very powerful tool that can help - it's LLM, or [A large language model](https://en.wikipedia.org/wiki/Large_language_model). In two words, it's a machine learning model built with using of neural network and huge (really, really huge) amount of text information. One of the application LLM is looking for a relevant information based on the new data (that is data that LLM doesn't know yet), and it can be done with several ways, one of them is context prompting. 

#### How does it work?

There are several steps:

1. Prepare data - textual information should be read, divided by chunks, and stored with the possibility to find the relevant chunks.
2. Look for relevant chunks - the way how it's usually done is not as magic as say, the forming a human-like answer, but still requires special algorithms.
3. Based on those chunks, form a human-like response.

This looks pretty simple but actually, it requires a lot of work, for example:

1. Organizing loading data (websites? documents? how?)
2. indexing textual information and following search
3. feeding it to some LLM and get the response
4. organizing the interaction between this system and a user.

Fortunately, these days we already have tools and frameworks that can help with all these task:

1. [LlamaIndex Library](https://github.com/jerryjliu/llama_index) to help with indexing the textual data and forming the context to be fed to LLM.
2. vector database (like [Qdrant](https://qdrant.tech/)) helping with searching the relevant pieces of text, fast and accurate
3. [ChatGPT](https://openai.com/chatgpt) - to find the accurate answer and form a human-like response.
4. chatbox online service like [Crisp](https://crisp.chat) that organize the interactive communication - by humans or bots, with a lot of possibilities to adjust the chatbox UI, have the full story, connect to your favorite CMS and many others.
5. a connector to join all these parts. [Enum](https://enumhq.com) connects all these parts that you don't need to to. 

It's still a beginning. ChatGPT is wrong sometimes, the answers are not relevant sometimes and users don't get what they want. But it's still a huge step towards more successful retaining users and make them your friends, not enemies. But just because this approach is a very fresh and new, many business don't use the power of modern technologies and lose their existing and future clients. Don't be like them, start researching. Here are several useful links to check:

- [How Enum works](https://www.enumhq.com/docs/how-it-works)
- [How to use our free Crisp plugin](https://www.enumhq.com/docs/chat-plugins/crisp)
- [F.A.Q.](https://www.enumhq.com/#faq)

### Photo credits

Photo by <a href="https://unsplash.com/@clemono?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Clem Onojeghuo</a> on <a href="https://unsplash.com/photos/tca2Hfz1cvY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  