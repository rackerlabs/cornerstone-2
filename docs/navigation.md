---
layout: default
title: Navigation
---

##Eyebrow

The most common interactions for a web site are provided to the site viewer at the top of each page.

###When to Use

Include an eyebrow when creating a child page on a website. Use the eyebrow element that was created for a given website. When creating a new website you will need to decide if creating a new eyebrow element is required.  

###How to use

An eyebrow element applies is applied to a website landing page and all subsequent child pages. The eyebrow is placed at the top of each page found in the website. The eyebrow containing branding information for the website and actions to highlight for the site visitor. These can include github source code, calls to action such as a signup and chat, and links to site resources.

###Design Rationale

The eyebrow element promotes consistency across a website. Mental capactiy is used as the brain processes information. Ensuring all pages within a given website have the same eye brow element frees up mental capacity for the site visitor. The site visitor is tasked with only processing new information on a page as they traverse the site. Important tasks are brought to the forefront of a site visitors experience when placed in the eyebrow element.

###Example

Eyebrow for rackspace.com properties

<img style="width:760px; border: solid 1px black;" src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/eyebrow.png">

##Global Navigation

The site visitor needs to quickly and easily path to a given section of a web site. We use the global navigation in conjunction with the hero banner as a general way finding device to assist in our site visitors pathing throughout the site.

###When to Use

Apply the global navigation element to all pages within a given website. If you're working on a marketing landing page (e.g., for a pay-per-click (PPC) campaign, display ad campaign, etc.) that is not incorporated into the global website,  please do not use this element.

###How to use

Global navigation is the second element on the website and is placed directly below the eyebrow. On desktop, a way finding carrot appears to help the site visitor understand where they are within the site.

###Design Rationale

Consistent global navigation allows customers to safely explore our product offerings. By presenting a consistent navigation element at the top of the screen a customer is able to delve deeper into the task they want to accomplish. As they move through various product screens they are provided a visual anchor. This is especially important when dealing with the technical information displayed on our screen as it gives them a way to navigate back to a friendly page if they find themselves in uncharted territories

##Hamburger

When viewing a web site on small screens it becomes difficult to display all navigation interactions in the limited space. 

###When to Use

When preparing a site for interaction for a mobile or small screen viewing experience.

###How to use

Move navigation interactions behind the hamburger element. The hamburger will act as a gate keeper for displaying these interactions. These interactions can include call to action buttons and dropdown navigation elements. When the hambuger is opened the navigation interactions will be displayed. These interactions will hidden when the hamburger is closed.

###Design Rationale

Toggling these interactions below a hamburger element maximizes screen real estate at small view ports without limiting the available site interactions. Including a hamburger element allows for a cleaner mobile experience with easier navigation.

###Example

Hamburger element closed

<img style="border: solid 1px black;" src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/hamburger.png">

Hamburger element expanded

<img style="border: solid 1px black;" src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/hamburger_expanded.png">

##Item Pagination

The site viewer is accessing a large set of data that cannot be displayed on a single page.

###When to Use

Use when a large data set is being returned to a site viewer. This data set contains more information / results than is capable of being displayed on a single page. Pagination provides the site viewer with a means by which to interact with the data set and gives the feeling of being a single page.

###How to use

Implement pagination on the bottom or top of the data set. Include an interaction scheme to path between first and last pages as well as pages in between

###User Story

Mary has purchased the Cloud Servers product and is attempting to load her ecommerce solution on to her Cloud Server. She is eager to switch her site but wants to ensure that she has configured her Cloud Server in as secure a manner as possible. She browses the Rackspace Knowledge Center and searches the knowledge center for security information. She receives a multitude of search results that relate to her topic. She understands the pagination displayed above and below her search results provide her access to browse through the information housed in the Rackspace Knowledge Center.

###Design Rationale

Pagination segments the amount of data provided to a site view. By providing the data in consumable chunks it allows the site viewer to gain a better understanding of the scope of the data. The site viewer understands the size of the data set and offers a decision as to wither or not to continue viewing the data.

###Example

<img src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/pagination.png">

##Main Footer

All site visitors require access to a specific feature or link regardless of the currently rendered page.

###When to Use

Use when you need to add uniformity to a webpage from both a layout and feature perspective. Each page on which the footer appears will act as a secondary level of navigation through which a site visitor can explore the site and access feature. If a footer is implemented upon the top level page of a web site it should appear on subsequent pages similar to the Eyebrow element.

###How to use

Include the footer at the bottom of each page created. Include relevent links to additional information or interactions from which a site viewer can benefit.

###User Story

While exploring rackspace.com Mary finds herself reading the Cloud Servers product page. She consumes the content on the page by reading and scrolling down the page to access additional content. She realizes she has reached the end of the page because she is greeted with the footer that was displayed on the home page. After reaching the end of the page she is interested in Cloud Load Balancers which was referenced in a list bullet point. The footer provides her an easy avenue to explore the Cloud Load Balancers product page without the need to scroll to the top of the product page. She selects the Cloud Load Balancers text link in the footer and continues browsing the site.

###Design Rationale

By providing easy access to a footer element you give visual consistency to a web site. This consistency is important as it helps explain to a site viewer they reached the end of a page. The footer acts as a secondary method for navigating the web site interactions.

###Example

Footer from rackspace.com

<img style="width:760px; border: solid 1px black;" src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/footer.png">


##Navigation drop Down

Navigation drop downs empower site viewers to view sub categories at their leisure. 

###When to Use

Use when displaying large navigation schemes that cannot be easily displayed on the screen. Use to isolate and bucket navigation into a scheme that fits the site viewers goals.

###How to use

Include the top level category as the interaction point from which to launch a drop down. When a customer hovers or clicks the interaction point, sub categories are displayed.

###User Story

Tom is starting a side project at this company that requires web hosting. Tom has learned about Rackspace from a work associate who recommends their cloud services. He starts browsing rackspace.com looking for a solution. He interacts with the 'Solutions' drop down menu from the top navigation. The drop down displays categories of solutions and he selects the one that fits his side project.

###Design Rationale

Displaying all interaction paths user can lead to option paralysis if the options are to great. Navigation drop downs remove this added cognitive lifting 

###Example

<img style="border: solid 1px black;" src="http://e6e61b233bcecd895fdb-74f5ac90bad95964d53ac3322f7d0dec.r76.cf1.rackcdn.com/nav_drop_down.png">
