---
layout: post
permalink: case-study-royal-canin-migration
title: What can we learn from Royal Canin's migration (Case Study)?
subtitle: A great example on impact some choices can have on your SEO. 
meta-title: What can we learn from Royal Canin's migration (Case Study)? - Antoine Eripret
meta-description: Discover a full analysis of the web migration done by Royal Canin in 2019 and its consequences. 
share-img: https://www.aeripret.com/assets/img/sistrix-comparison-royal-canin.png
comments: true
---

A migration is maybe one of the hardest projects we have to carry out as SEO professionals. 

Why? Because you must pay attention to a lot of details and if you forget something, you can end up killing a business if it relies a lot on search engine traffic. Actually, **migrations that went bad are one of the main reasons businesses look for a freelance or an agency if they have never worked with one before**. 

In this article, we are going to have a look at what Royal Canin did some months ago, migrating its local websites using ccTLD to a global domain. I will focus my analysis on the Spanish version of the website because it is the country I live in. If you are looking for a more generic article on how to plan a successful migration, [have a look at what ContentKing published ](https://www.contentkingapp.com/academy/website-migrations/) or [look at this deck from Aleyda Solis](https://es.slideshare.net/aleydasolis/winning-seo-when-doing-web-migrations-smssyd19). 

My objective is not to criticize what they did but to explain what are the consequences of some choices they have taken. In companies like this one, the SEO team may not be the team responsible of making all the calls, and I completely understand that. **I myself was involved in a migration that went pretty bad at the beginning because the decision to go live had been taken even if the team highlighted that we still had a lot to do**. You can judge by yourself:

![](..\assets\img\sistrix-visibility-comparison-royal-canin.png) 

What I want is to explain a part of the process I would have to go through if I had to work with this brand - something that can be interesting if you never audited a migration - and explain how to prioritize tasks based on business and not just SEO metrics. 



## Current situation

As I explained in the introduction, Royal Canin decided to merge its local domains into royalcanin.com, the new global domain. Each country now gets its own folder: /es/ for Spain, /at/ for Austria and so on. 

From the information I was able to retrieve from [archive.org](https://archive.org/), the project was not simply a domain change, but the design and some contents were affected as well. You can, for example, compare the homepage with its old version available [here](https://web.archive.org/web/20190702070109/https://www.royalcanin.es/). If you don’t know this tool yet, [I explained how it works in an older post. ](https://www.aeripret.com/extract-urls-wayback-archive-org)

If we look at the impact on the Spanish market, we can see an important difference in the visibility of both domains. I obviously don’t have access to their traffic data, but I’m pretty confident that the organic traffic was heavily impacted as well.

![Sistrix comparison royal canin](..\assets\img\sistrix-comparison-royal-canin.png)



So, what happened? Let’s have a deeper look and try to explain why we observe such a decrease. 



## First findings

The first step to understanding what happened is to crawl the URLs that were ranking before the migration and see if they have been redirected properly. By doing so, we will be able to see if some bad redirects may have caused this drop. 

Based on SEMRUSH’s data, we had 3.324 URLs ranked in Spain, so we are going to crawl them all using Screaming Frog. 

![](..\assets\img\semrush-domain-overview-royal-canin.png)



### Language

The first easy spot is the language used in the URLs. Even if the content is localized, URLs are not anymore. 

![URLs in English in Screaming Frog](..\assets\img\screaming-frog-urls-english.png)



I completely understand why they decided to go with an English-based structure. **It is undoubtedly easier to manage an URL structure in one language because you don’t have to translate them**. Can you rank if your URLs are not in the local language? Yes, there are countless examples. It is better to localize all your content though, as you may have guessed.



### Not migrated content

We can also see some contents redirect to the homepage, certainly because they were not available in the new platform, so they trigger what I would call a “default” redirection to the homepage. 

![Screaming Frog redirect to homepage](..\assets\img\screaming-frog-example-redirect-home.png)



It is pretty standard to prune your content during a migration, nevertheless, you would never want to remove a content ranking on some relevant keywords, **which is the case of the example I just showcased because the list we crawl is extracted from SEMRUSH**. I actually saw that the same issue is impacting 237 URLs but the impact on traffic shouldn’t be that relevant, because these weren’t the content contributing the most to Royal Canin’s online visibility. 

Nevertheless, we also observe similar behavior for some of the breed library contents. The impact is more important because the example highlighted generated almost 5.000 sessions per month, based on SEMRUSH's data. Royal Canin seems to have left out some of the breeds previously included on their website. 

![example removed content](..\assets\img\example-removed-content.png)

They also decided to remove similar content they had on dog sizes, ranking on keywords with decent search volume. 

![semrush url overview removed content](C:\Users\antoi\Documents\GitHub\antoineeripret.github.io\assets\img\semrush-url-overview-removed-content.png)

We may have found one of the big reasons they dropped after the migration: some of the best contents indeed have not been included in the migration, causing drop or disappearance for some keywords. 



### Badly redirected URLs

Even if you couldn’t buy the product directly on their website, Royal Canin did have a product section. It has been redirected massively to two URLs, as you can see below: 

![examples products urls redirects](..\assets\img\examples-product-URLS.png)



The traffic was pretty decent, so it undoubtedly affected the website. But I don’t think it is actually a big deal here and if I had to work with Royal Canin, I wouldn’t prioritize this fix that much. Let me explain why. 

When you actually look at the keywords these URLs were ranking on, they are all branded keywords, like “royal canin hypoallergenic”. **Because Royal Canin doesn’t allow you to buy from their website, not appearing on Google for these queries won’t impact their main KPI, which is their revenue.** I wouldn’t write the same if they were ranking on generic queries - where they could target customers still early in the conversion funnel - or if you could purchase on their website. 

Then, is it useful at all to have this section and to fix these redirections? Yes, because if Royal Canin wants to sell its products online at some point - something they could definitely do because they are a well-established brand - ranking on their branded queries is a minimum. 



## Why did Royal Canin dropped that much? 

Ok, so we found some flaws that explain a part of the drop we observed at the beginning, but it doesn’t seem to be enough. I mean, **the difference between the online visibility reported for both domains in Sistrix is quite important, and we can’t explain it only with what we just saw.** 

![Royal Canin online visibility in Sistrix](..\assets\img\sistrix-comparison-royal-canin.png)



If we look at the most important keywords reported in SEMRUSH in August 2019, we can easily see that some of them are linked to the breed library, like “bulldog francés” (french bulldog in english) and “shar pei”. Royal Canin was ranking within the first positions on these queries. 

![keyword overview semrush](..\assets\img\royal-canin-semrush-keywords-overview.png)



As you can see, the monthly search volume associated with these queries is sometimes higher than the brand volume itself, therefore it definitely contributed heavily to the organic traffic generated by the website. Moreover, the SERP is usually ads-free and apart of the Knowledge Panel, no other module is displayed: CTR should be quite nice for the first results. 

![serp french bulldog](..\assets\img\serp-french-bulldog.png)



But as we can see in the image below, the URL actually ranked pretty bad after the migration, even if it is almost on the first page now. 

![Sistrix evolution rankings on the keyword french bulldog](..\assets\img\keyword-ranking-french-bulldog.png)



So, what happened exactly? If we stick to the same example, **the redirection was implemented correctly, so we should expect the new URL to rank correctly as well**.

![redirect path plugin result](..\assets\img\redirect-path.png) 



We are left with two possibilities, and we will check them. 



**Did Google update the search intent - and therefore the results - for this query?**

Sometimes, your result can disappear from a query not because you did something incorrectly, but because Google now understands better the search intent behind a query. If you look for “macbook” and “french bulldog”, both very generic, results will be pretty different. In the first case, you will observe a lot of E-commerce results (because Google assumes that the intent is transactional), when the second included more informational results. 

Sometimes and because Google uses a machine-learning algorithm in the background, you can see a shift in what kind of results are displayed. Is it the case? If we compare results for the query “bulldog francés”, we can discard this theory. 

Even if we observe ranking changes, they are pretty standard and Royal Canin is one of the few to have disappeared. We definitely need to find another explication. 

![](..\assets\img\serp-comparison-french-bulldog.png)



**Was the new content as good as the old one?**

To maintain your rankings during a migration, you need to ensure that your new content is at least as good as the previous one. To check whether it has been the case, we are again going to use archive.org. 

This page is unfortunately unavailable, therefore we will be using another page to see if this theory is correct. In the following image, I included on the left the current and on the right what they had before the migration. 

Even if you can’t see correctly the text, you can clearly see that there is a major difference in the details included. In the current webpage, you have a quick summary with a little bit of extra information when the old page had a more complete description of the breed.

![content comparison before after migration](..\assets\img\content-comparison-before-after-migration.png) 



Besides, if you look at the current first results on Google, you clearly see that Royal Canin couldn’t hold its first position with this content: others are objectively better. 

Our second theory seems to be the right one because it actually explains why Royal Canin dropped in a load of keywords. **They didn’t maintain the good content they previously had, maybe because it couldn’t be included in the new template they are using, and Google decided that it was not worth ranking at the same position anymore.**

As this issue certainly affected all URLs from the breed section, something we can’t check for sure because just a part of them are archived in archive.org, it is undoubtedly the reason why the project dropped on a lot of high volume keywords and why the new visibility is so different from the old one. 



## Why should Royal Canin care? 

So, at this point this question should arise: why should Royal Canin even care about this situation? At the end of the day, they don’t sell their products online and the queries we identified as the root of their online visibility decrease are not transactional. 

First of all, I highlight that the issue mentioned for the Spanish market affect also others like France, where the situation is pretty similar. 

Then, I know that these queries are not transactional but **they allow the brand to be present on important queries linked to dogs & cats, which will eventually contribute to brand awareness and help sales**. My family owned a pet when I was in France and not even once did we change the brand we bought from: I wouldn’t be surprised that LTV is pretty high in this industry, hence working on your brand awareness is crucial to build sustainability and profitability in the long term. 



## Conclusion

Again, my objective was not to criticize what the SEO team at Royal Canin does because they may work under constraints I am not aware of. Nevertheless, this case study is interesting because it shows that ensuring that your redirects are in place is far from being enough to ensure that your new website will keep its rankings. It also shows how essential archive.org is to audit an existing website when you don't have access to the full history ! 

If you liked this article or want to share your opinion on it, don't hesitate to leave a comment.   