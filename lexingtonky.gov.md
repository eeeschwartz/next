<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.2.2/css/bootstrap.min.css" />


# LexingtonKY.gov Redesign: Discovery Report

## Executive summary

The City of Lexington is redesigning LexingontonKY.gov with the primary goal of improving service delivery to its residents and stakeholders. The team responsible for the redesign has completed the initial discovery phase aimed at understanding the current site and its associated services so that they might be improved. The following is a summary of the findings from this work performed in early 2015.

## Introduction to the redesign

The City has prioritized this project in order to address several issues with the current site that are commonly reported by residents and city employees. 

* It is structured around departmental hierarchies rather than intuitive service areas.
* It is difficult to use on mobile devices, which now account for half of traffic.
* Rather than being focused on quickly facilitating action, it is largely an information broadcast model.
* The content is lengthy, lacks structure, and often falls out of date.
* The content management system is difficult to use, even for experienced content creators.
* Updating the website is largely a secondary task that increases workload for city employees rather than creating efficiencies that make work easier.

## Goals of the redesign

In short, the mission is to make it [simple, clear, and fast](https://www.gov.uk/transformation) to interact with the City online. Below are several attributes of a successful site:

* Works well on mobile devices.
* Is beautiful and easy to use.
* Has concise information that is accessible to everyone.
* Reflects the unique character of a great city.
* Is structured around the expectations of residents.
* Gives content creators clear feedback so that they can continually improve the site.
* Is action-oriented, to get people in and out quickly.
* Is a key information sharing tool that decreases workload for city employees. As a result the site is naturally kept up-to-date.

## The role of the redesign in future digital services

Lexingtonians have come to expect a great deal from LexingontonKY.gov. The same way that they do business online with their bank, mobile phone provider, or clothing retailer, they expect to interact with city services online, quickly, and at the time of their choosing. The City has made strides in this regard but still many interactions require calling, printing, scanning, faxing or standing in line between 9am and 5pm. While transactional services are generally beyond the scope of the website redesign, their futures are very much interconnected.

LexingtonKY.gov is the jumping off point for all present and future digital servcies. The structure of the site and information about the services will play a large role in whether residents find them, understand them, and use them successfully. The redesign also defines the experience that residents will expect when interacting with associated digital services. A successful redesign produces a set of tools for integrating future components without requiring loads of expensive design and custom interface work. For this reason, the site redesign includes a deliverable known as a pattern portfolio. It's a set of LexingtonKY.gov interface components that future applications use to quickly and cheaply adopt the look and feel of the main site.

At a higher level, a core promise of the redesign lies in building the project iteratively, in manageable pieces, guided by continual feedback from real users. This agile approach is a core practice of successful organizations and is an increasingly common way for governments to improve service at less cost to taxpayers.

## Analysis from the discovery phase

When talking with people, the first comment is usually that the website is hard to navigate as it is built around the organizational chart of the government rather than around services they need. The following is an interactive tool that shows the quantity of pages in each section of the site. 

Due to the structure of the site, the City has very limited ability to bring forward commonly requested information. As an example, finding the schedule for routine trash pickup takes several well educated guesses through the drop-down menus:  `City Government` > `Environmental Quality & Public Works` > `Division of Waste Management`. Even people we talked to with deep knowledge of the government found this structure difficult to negotiate at times.

Note that the large majority of the site is nested within the City Government section.

#### Organization of the current site

Click on a section to show pages inside of it. Hover for number of pages.

<p class="chart" id="chart"></p>


#### The site in rough service categories

People that arrive at the site from Google or Bing searches comprise nearly 60% of visitors. They show a different way of thinking about the site. Rather than departments, they tend think about specific services like trash pickup or park schedules:

This view is created by finding keywords inside of search terms. For example, the search term `woodland arts fair lexington ky` was matched on the term `woodland` that we put in the `parks` category.

<p class="chart" id="chart-inverse"></p>


## Activities from the discovery phase

The primary focus of discovery was to produce actionable analytics. It also led to a couple of quick wins along the way.

* Searching within the current site was often 'down' or unavailable to users. When users were able to search, what they searched _for_ was not being recorded for analysis. We fixed these issues to help make the site more functional and to enable better performance insight.
* Several content creators highlighted that it was hard to understand content performance. The analytics for their area was mixed in with every other area of the site. We solved this problem by joining multiple data sources to create separate reports for different service areas.
* We gathered information from other cities engaged in similar work
 	* [Austin](http://austintexas.gov/page/phase-one-documentation)
	* [Oakland](http://digifrodo.tumblr.com/)
	* [Philadelphia](http://alpha.phila.gov/)
	* [San Diego](http://www.sandiego.gov/mayor/pdf/newsreleases/2014/news140826websiteannoucement.pdf)


## Redesign process at a glance

In order to build the site iteratively the project is broken into phases. By and large, in each phase the project team presents a short cyle of work to real users so that their feedback can inform next steps.

### Discovery phase (near completion)

* Perform analysis to understand the current site and ways it can likely be improved.
* Set initial key performance indicators (KPIs) for the next phase. 
* Define a set of activities for the next phase.
* Form the team necessary to continue.
* About two months long.

##### Initial Key Performance Idiciators (KPIs) for LexingtonKY.gov

Based on our analysis, we have a few initial KPIs. These may change as we gain insight but these are good starting points:

* Lower the bounce rate, or number of times that people encounter a page and immediately leave it.
* Lower the quantity of in-site searches (aside from the ones that start from the home page). In-site searches usually indicate that a user expected to find certain information but did not.
* Lower the time to complete common tasks. For example, lower the time to find a pool schedule or holiday pickup time for trash.


### Alpha phase (soon to begin)

* Show temporary, experimental pages to a wide array of users to learn what makes sense to them. Pages do not necessarily need to be created in the new CMS. The experiments should use whatever is available and quick to deploy. 
* Perform card sorting exercises to define the service categories that are intuitive to users.
* Focus on high-traffic portions of the site. Analysis highlights several service areas to start with:
	* Events, parks, pools, golf
	* Permitting for home and small business users
	* Requesting various traffic/incident reports or learning about police jobs.
* Test integrations with associated services.
* Finish with a basic working system and a good understanding of how the service should operate.
* About two months.


### Beta phase

* Create a publicly accessible version of the new site on the new CMS platform. A link from the existing site invites users to give it a try and provide feedback.
* To begin, it should be a rough draft that covers as many service areas as possible.
* The redesign team continues iterative user research with a wide variety of users.
* As the beta progresses, user feedback is continually collected as content is fleshed-out, rearranged, and improved.
* The number of users should grow as the site improves.
* City stakeholders decide when the site meets the standards to be made live.
* About three to six months.

### Live phase

* The City has continual feedback mechanisms from user research and analytics.
* The site continues to evolve based on this feedback.
* Digital services go through a similar design process in order to integrate with the site and meet the needs of residents.


<script src='http://d3js.org/d3.v3.min.js'></script>
<script src="index.js"></script>