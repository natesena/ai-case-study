## <center>Module 1 Challenge</center>

# <center>Clay.com Case Study</center>

## Introduction

Clay is a Brooklyn based B2B SAAS company that uses the power of AI to help build out Customer Relationship Management systems (CRMs) and send personalized outreach.

Clay has seed funding from boldstart ventures and 2 other investors, but other funding information is not publicly available<sup>3</sup>.

## Landscape

The telephone book could be considered the first CRM, but CRMs' popularity largely grew with the advent of the personal computer in the 1980s<sup>8</sup>. Today, titans like Salesforce and Hubspot bring in billions of dollars in revenue each year helping businesses organize their "database marketing".

As the technological landscape of our everyday lives has changed, so have CRMs. The addition of new data fields and programatic elements to this "database marketing" has steadily increased. What once may have been a tool to record just contact information has expanded to include functionalities like robocalls and "drip campaigns". The sheer amount of data and possibilities in which to market with has led to a very saturated space in which there are many notable players. The following is a short list of Clay's direct competitors:

- [Luna AI](https://luna.ai/email-personalization-platform/?utm_source=search&utm_medium=cpc&utm_campaign=ai_campaign_2023&gclid=CjwKCAiAjrarBhAWEiwA2qWdCKiNYhbd9aIh7TBJLvphLvlJE5PlOLIycnUwCjR_gN0mTeHoBZpu_RoCKN0QAvD_BwE)

- [Salesforce](https://www.salesforce.com/)

- [Klaviyo](https://www.klaviyo.com/)

- [Customer.io](https://customer.io/)

Today, the landscape continues to change at rapid pace as companies fight to give their clients an edge in a world saturated with customer outreach. AI is poised to make waves in this space by giving these companies new ways to both capture customer data as well as most effectively reach them.

Clay is creating their own niche in this space by giving prospectors new methods to capture the data that fuels engagement they demand.

## Background

Clay was founded in 2014 by CEO Kareem Amin and cofounder Nicolae Rusan. Prior to starting Clay, Kareem and Nicolae both studied at McGill University in Montreal, Canada. Kareem earned a bachelors in physics and electrical engineering while Nicolae got degrees in economics, political science, and computer science. Both Nicolae and Kareem spent time working for Microsoft and Sailthru prior to starting Clay. They both currently reside in Brooklyn though Nicolae currently is focusing on his next venture, Toolkit AI.

The idea for Clay came about as a response to the realization that most tools that store data for professional use, and the most common being a spreadsheet, are "blissfully unaware of the kind of data that they store. Columns think in [just] terms of strings and numbers"<sup>4</sup>. The basis for the creation of Clay would be to make sense of all this data, structured or not.

## Problem Statement

Clay is approaching three main problems with respect to CRMs: data entry at scale, semantic understanding of unstructured data, and personalization of messaging.

#### Data Entry at Scale

In the CRM space, data is largely input into spreadsheets or databases
by humans. This is a very manual process which typically can only be facilitated by data aggregators which are not robust with the results they can produce from limited input queries. In many cases, data will be missing, incomplete, out of date, or simply incorrect. Having accurate and complete data is vital to the functionality of a CRM.

#### Semantic Understanding

While data aggregators can alieve some of the difficulty with inputting data into spreadsheets and databases, they are very rudimentary in their function and may have very limited types of data to contribute. Data aggregators also often rely on private databases which means if a particular aggregator is missing some of the desired data, it may not be able to assist in the data entry. This issue is largely worsened by the absence of semantic understanding of the data itself. Essentially, data aggregators are often limited to understanding the value of column headers like "email" or "name" for which a direct string match can be used to look up further data. This limited understanding of what the data should be makes it very difficult to understand what is missing.

#### Personalization of Messaging

In the world of prospecting and customer outreach, getting a response can be extremely difficult and is largely be predicated on relevance and specificity to the target. The specific information needed to capture the reader's attention can take a long amount of time to assemble, often requiring looking up news articles, visiting a company website, and scouring other sources like LinkedIn.

## Objectives

As a lead generation and marketing product, Clay aims to simplify the task of prospecting. Valuable metrics for this would include open or response rates of their messages, and also increasing volume of messages sent while decreasing the time spent to send these messages.

## Methodology

Clay's product combines web scraping and AI to "build leads, enrich leads, use AI to write emails"<sup>6</sup>. Clay aggregates information from 50+ data sources, 10 "built in sources", and 150 "providers"<sup>6</sup>.

From their Youtube channel it is clear that you can add your own OpenAPI API key, implying the usage of OpenAI products. OpenAI's ChatGPT solves the problem of hand writing messages to the user's prospects at scale. With ChatGPT, Clay's products can generate coherent messages magnitudes faster than a human, increasing the productivity and outreach that user would otherwise create.

Clay's _"Claygents"_ ease the work of finding the unstructured data that is not typically held by competitors' data aggregators. Common examples of this unstructured data can be news articles from Google, blog posts on their website, and more. Where a human would otherwise have to look for this information and fill it in by hand to increase message relevancy, these Claygents can instead do the work of finding this information for the user, increasing the productivity and relevancy of the messages. This in turn reduces the time users need to spend doing research, increasing their productivity and even the success of their messaging like open or response rates.

Beyond their core technologies, Clay allows the CRM mappings of their customers to be made public, which further templatizes the work their customers might do<sup>4</sup>. This further increases the efficiency of their product as users may not need to further specify the type of information they may need to personalize messages.

Further details on their web application can be gleaned from an interview with their engineering team in it they say:

> "We built our own tech for rate-limiting, timeouts, and caching. We use Redis as a dedicated database for real-time interactions, and store this information later on to Postgres." ... "Integrations are implemented as independent packages and run as isolated lambda functions. This allows a separate customer engineering team to add and change integrations even if they have less experience and at a faster pace, without risking a bug that affects the whole system."<sup>4</sup>

## Analysis

As the world of sales and marketing becomes more sophisticated, it has become harder to have your messaging stick out from the crowd. Those in roles where performance is predicated on statistics like number of replies and overall response rate need tools to increase their volume and improve the quality of their message.

Clay's website markets their product to "book more meetings"<sup>6</sup>. Their product tackles the problems of data entry, semantic understanding, and scraping of unstructured data with ChatGPT and "Claygents". Solving these issues paired with the other features their product offers allows users to efficiently fill in CRMs and create effective personalized messaging.

## Results

Based off of a Crunchbase profile, it looks like they have been profitable for some time<sup>3</sup>, and considering the size of the company, they likely make millions in annual revenue.

Clay's website lists some of their customers on their site, which are other business in a variety of fields. On LinkedIn, Clay is most often referenced by those in sales who must do regular outreach, particularly those with titles like "Account Executive"(AE) or "Sales Development Representative"(SDR).

While any SAAS company would gauge their success based on ARR/MRR,# of users/subscribers, there is no publicly available data on their success. Clay's website features a section with accolades and other positive messaging from their customers, but this subjective data is not easily compared to that of their peers, who are likely also not publicly accessible companies. One might be able to determine this based off of employee count (~50)<sup>7</sup>, LinkedIn follower count (~8k), or some other metric.

## Recommendations

I personally want to use this tool to do email outreach to get a job by emailing recruiters. As an example, on Clay's Youtube channel, they demonstrate established CRM automations for finding recruiter emails, open job listings, and industry focuses<sup>5</sup>. These same work flows can be a valuable tool to automate some job search functions.

In order to capture this new market, Clay may have to update their product to have a new pricing tier as all of their subscriptions are fairly expensive starting at $149/month, and job seekers may not have that kind of capital to spare. The high cost might not be worthwhile for someone who is not using Clay to generate new business or reestablish the income that a full time job provides. Having a lower price tier would allow Clay to service this new category of customers, and further adjustments like limiting more costly components of their product could be used to target this new market.

## Works Cited

1.[Information on Kareem Amin](https://www.linkedin.com/in/kareemamin/)  
2.[Information on Nicolae Rusan](https://www.linkedin.com/in/nicolaerusan/)  
3.[Funding Information](https://www.crunchbase.com/organization/clay-953f)  
4.[Interview with Kareem Amin](https://refactoring.fm/p/clay)  
5.[Clay's Youtube Channel](https://www.youtube.com/@clay-prospecting)  
6.[Clay's Website](https://www.clay.com/)  
7.[Clay's LinkedIn Profile](https://www.linkedin.com/company/clay-hq/)  
8.[CRM History](https://www.salesforce.com/ap/hub/crm/the-complete-crm-history/)
