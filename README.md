# Developer-Led Landscape
This is a list of every company whose products were sold to, purchase-influenced by, or consumed by software developers.

I call this the Developer-Led Landscape. 

While there is a significant overlap with DevOps, the developer-led landscape looks at businesses that developers depend upon while DevOps excludes developer tools and includes operations products that are not part of a developer's workflow.

This work is never finished. If you uncover an error, or want to make a contribution, please open a pull request. 

# Definitions and Criteria
## What Is Measured

This landscape only includes products that generate revenues. 

The companies that make these products may (or not) have raised venture capital. This landscape does not include open source technologies, so the cumulative segment activity is broader than the landscape suggests.

The landscape does not include System Integrators; however, it does include hosted offerings that impact developer productivity, such as Stack Overflow and a number of developer managed service offerings.

## Category and Segment Definitions
The major buckets are called categories: Software Delivery Lifecycle (SDLC), Developer Tools (DT), Developer Infrastructure (DI), and Developer Platforms (DP).  

The segments were defined by grouping products that provided similar capabilities. Segmentation is not a exact science. Some segments are granular enough that products can exist in multiple segments. When a product can logically exist in multiple segments, it is listed in one segment (and therefore its revenues estimated once) that is the closesnt to the product's value propositions.

We include segment definitions on this page for segments whose definition is not broadly understood.

#### Category: Software Delivery Lifecycle (SDLC)
Process solutions that coordinate how teams design, develop and test software. SDLC contains segments that create products - and in many cases services / solutions - that impact developers across the entire lifecycle of development. Conceptually, SDLC offerings are leveraged across DT, DI, and DP. 

SDLC vendors monetize by selling corporate and individual SaaS subscriptions, on-premises software licenses and subscriptions, influence marketing such as recruiting and impression advertising, project and recurring professional services.

#### Category: Developer Tools (DT)
Individual (used by a single engineer) instruments used to facilitate software construction. 

DT vendors monetize by selling vendor and individual SaaS subscriptions, on-premises software licenses and subscriptions, various open source software strategies including open core and extended support, and freemium models that charge for upgrades (or in many cases for purchasing other products often times in the DI / DP categories).

#### Category: Developer Infrastructure (DI)
Hardware and software that support the distributed, repeatable construction of software. Some analysts call this the Software Delivery Supply Chain. If DT contains products targeted for the benefit of an individual developer, DI would be those solutions that a team of engineers would depend upon.

DI vendors monetize by selling SaaS subscriptions measured across a variety of criteria (seats, servers, sockets, containers, projects, source code repositories, pipelines, compute consumption, storage consumption, etc), on-premises software licenses and subscriptions, various open source software strategies including open core and extended support, and freemium models that charge for upgrades. Of special note, there are estimates that the cost to operate the underlying infrastructure stack that is running DI products are up to 15% of the global compute / storage consumption. Companies that sell DI products and with an already-profitable compute / storage offering can drive (mostly) free DI offerings compensated as loss leaders compensated through higher compute consumption.

#### Category: Developer Platforms (DP)
Developer-interfacing, code-first, and API-only runtimes. These are runtime products where the interface requires a software engineer, or the "assets" that are deployed into the runtime must be created by a developer.

DP vendors monetize by selling pay-as-you go measured across a variety of criteria (per request, compute consumption, etc.), SaaS subscriptions measured across a variety of criteria (seats, servers, sockets, containers, projects, compute consumption, storage consumption, etc), on-premises software licenses and subscriptions, various open source software strategies including open core and extended support, and freemium models that charge for upgrades.

#### Segment: RPA for DevOps
Solutions that automate the deployment and operations of developer tooling to increase the velocity of code to release while lowering the overhead associated with maintaining increasingly complex developer infrastructure.

#### Segment: Code & Application Security
The combination of Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), fuzzing, Software Composition Analysis (SCA), and Interactive Application Security Testing (IAST). These tools, while also used by security engineers, are often times developer-first.

#### Segment: Engineering Efficiency
Solutions that provide engineering intelligence to bring visibility and suggestions to improve software delivery. These solutions deliver insights that are consumed by all stakeholders, from engineers to product managers to business constituents to executives.

## Segment Overlaps
#### SDKs + Application Servers
I've included SDKs within this category as it's a broad term that encompasses many of the libraries and frameworks that developers include as they create software. Many SDK vendors choose to monetize in production, and while there is no duplicative vendors in SDKs vs. Application Servers, my selection of a product going into one category vs. the other is subjectively determined.

#### CI + CD + Build Automation
We keep track of these three segments separately. However, it is increasingly the case that these products have overlapping functionality and it's getting harder to distinguish between the differences, though they do exist. 

#### CI + CD + GitOps
Increasingly, the CI/CD vendors are adding in forms of GitOps into their offerings. And many of the GitOps vendors describe their solutions as forms of CD. There seems to be a convergence of configuration management and CI/CD platforms. Currently, we keep the categories separated.

#### Code and Application Security + Config + GitOps + CI + CD
Code and Application Security contains numerous sub-segments related to validating and testing code and systems. The market considers Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), fuzzing, Software Composition Analysis (SCA), and Interactive Application Security Testing (IAST). We do not include Runtime Application Security Protection (RASP) in our categories. These capabilities are often lightly provided within products that also offer configuration management, GitOps, CI, or CD. Companies that primarily provide code and application security solutions are placed into this category, whereas companies that tangentially offer these solutions are listed in other categories. 

## What Is Not Included (and Why)
#### System Integrators (SIs) and Consultants. 
This is a large and complex market. Measuring this would be ideal as it would offer various indicators on which technologies and products are growing or waning in influence.

#### Data and Databases
While many data products are selected by software engineers and architects as part of their application's design, and therefore, should be included in such a study, it is a heavily covered segment by many investors and analysts that I'd do poorly at reflecting. Additionally, it would be challenging to split hairs between those data products which are developer chosen, such as MySQL, often as part of product creation and those that are not developer-driven, such as Snowflake as a corporate cloud data warehouse.

#### Managed Service Providers
Vendors that host other vendors' products as a managed service are not included. While many SaaS offerings are included (and leverage other vendors technologies), those vendors are included if I felt there was a meaningful amount of intellectual property created to deliver the service. I understand that my interpretation can be arbitrary.

#### Open Source Projects & Foundations
Any individual segment might have 100s of additional open source projects that are shaping how it's evolving. Tracking these efforts would be challenging as the rate of change is high. This effort is a way to facilitate making better corporate decisions regarding developers and investments. Tracking for profit companies is a reflection of commitment and risk-taking which is a reflection on the overall impact similar technologies have on the industry.

#### Training Outfits
Organizations that are dedicated to training, whether instructor-led, Web-based, or other forms are not included in Developer Enablement. Developer Enablement speaks to non-traditional forms of developer engagement, usually tied to forms of community buidling like Stack Overflow or Product Hunt.

#### No Code Offerings
There are some analysts that include products which include advanced forms of configuration, scripting, or macros as a form of low code or no code. For example, a SaaS app that generates marketing landing pages automatically without coding. This a great offering and many companies should buy this, but that is not a Low Code system for building apps or other business systems. 

#### Data Science
Most data science notebooks require models to be programmed. Data scientists are building their own significant technology and programmatic muscles, but are not included here for simplification. There are a number of startups which are working to make it simple for data science engineers to deliver machine learning capabilities as part of a software project. It may be appropriate to eventually incorporate these companies which are working to blend software engineering practices with data science workflows.

#### MLOps
Along the same vein as Data Science, MLOps is a new segment of vendors that automate the construction, deployment, monitoring and governance of ML models. The architecture and workflows of MLOps solutions are similar to the technologies provided in the Dev Infrastructure and DevOps segments, but oriented to the workflow of data science teams and the construction and maintenance of machine learning models. These offerings often intersect with the developer workflow and tooling, but are not developer-led within an organization. Organizations are seeing the rise of ML operations professionals who specialize in this area. For some interesting takes on MLOps landscape see LF AI Foundation, Fiddler's blog, Google's blog, Blumberg Capital, Toward Data Science, and TopBots.

#### Some Vendor Products
Some companies publish multiple products that perform similar, but different capabilities for a single segment. In some cases, the overlaps are significant enough where I count them as a single vendor / product. In other cases, the product's are distinct enough where a vendor would appear multiple times in a single category. For example, Cloudbees, has different CI and CD products, and each product is given its own line item in the same category. Cloudbees as a vendor would count as a single vendor for the segment, but there would be multiple products. In the case of CA, now owned by Broadcom, they positioning their offerings as solutions, using broad brand definition to span many different pieces of IP, and so I have to infer best demarcation judgment in determining where product boundaries exist.

#### M&A Events
As developer-led businesses merge with other businesses (or discontinue operation), that is an industry change event. The number of vendors for a category may shrink, revenue allocations may change, and so on. While I update the database to reflect the new normal, I haven't kept an append log of each event, the date it occurred, and specific impacts. This would be a wonderful thing to add.

#### Graphic Design
Alas, while I have many talents, making things look good isn't one of them.

## Segment Revenues and Growth
In most segments, we have a (fairly) complete list of companies that have revenue-generating product(s). In these segments, we use the aggregate revenues from across all of the vendors to determine the segment's revenue. 

We make an estimate of only recurring revenue, and where possible, try to exclude one-time revenue such as the professional services attached to selling a product. To calculate the growth rate, we compare the segment's total current annually recurring revenue with the same measure from a year ago. I only use public sources of information (# of employees, investment raised, and corporate blog posts) to make an ARR estimate for a company. 

If a vendor sells a single product whose features span multiple segments, we count the revenues for that single product in a single segment. For example, Gitlab, which sells a single platform offering which covers many of the segments across Dev Infrastructure.

There are some segments where it's difficult to make an estimate or to get a complete list of vendors. It's fortunate that these segments are usually (very well) covered by industry analysts. In these limited cases, we use the totals provided by the analysts and note the categories where appropriate.

Of special note is the Application Server and Platform as a Service categories, both of which have analysts that have been tracking those revenues for an extended period of time. In the case of Gartner, they have been tracking the Application Server segment annually for over 20 years. Much of the recurring revenues are generated by support and maintenance on legacy runtimes, so while the highlight number may be worth some skepticism, it's makeup and evolution since 2000 is grounded in a careful study of the market.

## Vendor Count
The number of companies in a segment is measured only through our bottoms-up collection of vendors that have a product in that segment.

The same vendor can (and often does) show up in multiple segments. 

We've worked to avoid double counting revenues, even though the same vendor can appear in multiple segments. 

In the categories where we report analyst-provided revenues instead of our bottoms-up calculation, the total number of companies is still calculated from our bottoms-up analysis. In situations where the analysts are reporting recurring revenues much higher than our own, we may be dramatically under reporting the total number of companies on the market, including Test Automation, Application Servers, Platform-as-a-Service, Low Code.

## Analyst-Estimated Revenues vs. Bottoms-Up Estimations
These are the segments where analyst-provided total revenues were taken instead of my bottoms-up estimation.

#### Test Automation
Most analysts indicate that the products that drive test automation are anywhere from $8B to $15B in annual recurring revenues. We currently include those, however, my individual assessment of the vendors is roughly $3B annually. This is a huge difference that likely represents the value of professional services and outsourcing QE professionals that are being masked as recurring product revenues. For now, I am using the analyst's estimates, but will eventually replace the analyst's numbers with my own if I cannot uncover a more plausible reason for the discrepancy.

#### Application Servers
Gartner has been tracking this for two decades and has a more comprehensive look then I can right now.

#### Platform-as-a-Service
Similar reasons.

#### APIs
Remarkably, my bottoms-up analysis of revenues for businesses that monetize an API is almost identical to what the analysts count. However, we may both be significantly off as the total number of companies that I am tracking in this space is probably off significantly due to the long tail of offerings available but not easily discovered. I had hoped that someone like ProgrammableWeb, a directory of APIs, might have tagged APIs which are monetizable, but in consulting with their team, they found that APIs changed their nature too often and stopped tracking the monetization orientation of an individual API.

#### Special Case: Low Code
In this case, I am using my bottoms-up analysis and not the values provided by analysts, which is $10-$12B higher than my estimates. Low Code is often applied to a wide range of products that have advanced scripting or configuration, which are not specific to application construction and this causes analysts to over inflate the nature of this market. For example, some analysts include Microsoft Excel in their calculations because of its macro language. This is silly.

## Attributions
There are many people who influence my thinking on the subject, and in many cases, have also directly contributed to this research. Thank you for the support, intellectual thoughts, and any future contributions you might make.

In particular, Diana Kontsevaia deserves a special call out as she has (joyously) spent numerous hours identifying potential gaps, applying thoughtful critiques, and pursuing primary research to add to this effort. 

**My Dell Technologies Capital Colleagues**: Ryan Wexler, Daniel Docter, Raman Khanna, Chris Hillock, Scott Bevan, Alon Weinberg, Annie Tran, Deepak Jeevankumar, Frank Wang, Gregg Adkin, and Yair Snir.

**My VMWare Colleagues**: ….

**Other Industry Colleagues**: Brad Murdoch (EVP, Lightbend), Tracy Ragan (CEO @ DeployHub), Paul Fremantle (Founder @ WSO2). Brad Micklea (VP @ RedHat).

## Learn About Developer Markets
If you want to dive deeper into the developer rabbit hole, I recommend:

1. *"The New Kingmakers: How Developers Conquered the World"* by Stephen O'Grady. Stephen's articulation on how the power dynamic has shifted in IT due to the underlying shift in cloud, purchasing dynamics, and developer idiosyncratic behaviors is excellent. 

2. *"Agility Now: The Coming Battle for DevOps Supremacy"* by William Blair, published in November 2019 with contributions from Jason Ader, Bhavan Suri, Arjun Bhatia, David Griffin, Jonathan Ho, and Sebastien Naji. They have the most comprehensive articulation of the foundational technologies that are driving the DevOps movement. They also dwell more on the dynamics of "Last Mile" delivery with Continuous Delivery, how automation is driving a "Shift Left" in the toolchain, and the emergence of DevSecOps.

3. The Redmonk blog and research feed. A small group of talented analysts out of Europe who write frequently on trends in programming languages, open source, and vendor dynamics. Most of their clients are vendors that are captured in this landscape.

4. TheNewStack.io has emerged as one of my favorite reading spots to get a feel for how different vendors are positioning underlying shifts in the industry. They are one of the few analyst publications focused on infrastructure that has a dedicated section to development.
