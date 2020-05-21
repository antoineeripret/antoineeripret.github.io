---
layout: post
permalink: ctr-yield-curve
title: What is the CTR Yield Curve and why should you care?
subtitle: Discover one of the least used metrics. 
comments: true
---



The CTR Yield Curve is not a new concept, but it became more important with the load of modules that Google released within its SERPs during the last months. 

In this article, I will walk you through the definition of the concept, why it matters more than ever and how you can apply it to your SEO strategy to really focus your effort on the content that can bring more traffic. 



## What the heck is a CTR Yield curve? 

If you are working in SEO, you already know what a yield curve is, you may just not know that yet. I'm sure that you you've seen this kind of graph at some point in your career: 

![](C:\Users\antoi\Documents\GitHub\antoineeripret.github.io\assets\img\ctr-yield-curve-advanced-web-rankings.PNG)

*Source:https://www.advancedwebranking.com/ctrstudy/*

There are a lot of diferent studies on this subject, but the reality is that your CTR always depends on your position. It is true since the beginning of Google and it still stands today. 

Well, gues what? **This is a yield curve, showing the relation between the position and the CTR**. This relation is always negative: the higher (which actually means lower in term of SERP) your position, the lower your CTR will be.   



# Why does it matter?

Let's go back some years ago. If you were to search something on Google, you would observe a webpage like the following: 



![](https://3.bp.blogspot.com/-AvJv7Ij7o88/TgoeVDpPU7I/AAAAAAAAAUc/YsFxRhQmc6k/s400/Kennedy+Space+Center.png)



*Source: [Google Search Blog](https://search.googleblog.com/2011/06/some-updates-to-design-of-search.html)*

The famous ten blue links with some aditional information on the left, on the right and at the top, but a good CTR for the first organic results anyway. If you perform the same search today, the amount of information included in the search result page by Google is higher. In some cases, you have to scroll more than 1.000px to get to the first organic results.

This new reality happened for several reasons but mainly because Google is greedy (let's be real for one second) and shifted its strategy from a search engine to a result engine. Nevertheless, depending on the industry you are working in, you may still have some clean SERPs for some of your queries and this is where the CTR yield curve will be important. 

Let's imagine that you are working as a SEO for a company offering two services: 

* Travel packages 
* Flight tickets 



You are perfectly aware of the CTR yield curve concept, and you know that in flight related queries, Google promotes its own solution, Google Flights, and the competition is fierce. **Hence, you may expect a lower CTR for the first organic results than in the travel packages vertical, where Google doesn't yet promote its own solution. **

Some years ago, if you had to priorize one of these two verticals, you would have taken into account search volume and business metrics like margins etc... to decide which one to choose. CTR were more or less the same amongst industries. Now, you have to take into account the CTR yield curve for your vertical, as the CTR for any given industry can differ a lot. 

How can you do that? In the following section, I will walk you through the full process. 



## How to calculate the CTR yield curve for your vertical

To realize this analysis, you will need an access to a Google Search Account for a website that is already ranking, at least at some extent, in your verticals. Indeed, no external study provide trustworthy CTR data, and you will have to use yours. 

What we will do is to basically create a table estimating the CTR per position for our vertical, based on our data. 

### Tools 

Ok, so let's start with the tools you need. You have several option: 

1. Use [this extension](https://searchanalyticsforsheets.com/) for Google Sheets to retrieve your Google Search Console data directly in Google Sheets. Handy if you have a small to medium website or if you have a powerful computer. Indeed, for big webstes where the number of rows to be retrieved by the tool can be large, a bit of extra RAM can be useful. 
2. Use [Supermetrics](https://supermetrics.com/), which is a great tool to extract your data. It costs 99$ per month though, but really worth the investment if you want to automate your reporting. Not the only company to do that, but the only tool I used at some point . 
3. Use whatever programming language your are the more comfortable with to query directly the API. I personnaly use Python, but you can achieve the same with R, Java, PHP etc... 



What really matters here is the process, the way of getting there is really a matter of personal preference. 



### Filter your GSC data 

The first step is to filter your GSC data to match the vertical you want to analyze. If we stick to our previous example, let's imagine that: 

*  The flight content is located in the /flights folder
* The travel packages content is located in the /travel folder

Using GSC filters, you can include only data for URLs including a specific pattern, so this part of fairly easy. I would also suggest to exclude any data where the average position is higher than 10. We want to analyze the CTR for the first page only. **You will also want to retrieve the data for a specific month, because SERPs evolve during time and you whould account for that in your analysis.**

At this stage, you should end up with a table like this: 

| URL                                      | Impressions | Clicks | Avg. Position |
| ---------------------------------------- | ----------- | ------ | ------------- |
| https://www.mywebsite.com/flights/france | 100.000     | 2.000  | 2             |
| https://www.mywebsite.com/flights/spain  | 365.000     | 10.000 | 5             |
| https://www.mywebsite.com/flights/greece | 500.000     | 50.000 | 1             |



Easy? Yes, but not so fast. If we just filter using this methodology, we leave several major flaws: 

* Branded and non-branded terms usually have huge differences in CTR. We must exclude them as well. 
* URLs can show up as sitelinks on some big queries, messing with the CTR we will calculate. We should exclude these cases as well. 



The first case is easy, the second one is trickier.  



 