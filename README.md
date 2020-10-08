# Developer-Led Landscape
This is a list of every company whose products were sold to, purchase-influenced by, or consumed by software developers.

I call this the Developer-Led Landscape. 

While there is a significant overlap with DevOps, many DevOps usually excludes developer tooling (like design IDEs) while also including IT Operations not part of a developer's workflow (like network monitoring).

This work is never finished. If you uncover an error, or want to make a contribution, please open a pull request. 

# Definitions and Criteria
## What Is Measured

This landscape only includes products that generate (or intend to generate) revenues. 

The companies that make these products may (or not) have raised venture capital. This landscape does not include open source projects, so the cumulative segment activity is broader than the landscape suggests.

Products listed may be downloadable, hosted as Software as a Service, or provided as a managed service offering. 

## Category, Segment, and Specialization Definitions
The major buckets are called 'categories': Software Delivery Lifecycle (SDLC), Developer Tools (DT), Developer Infrastructure (DI), and Developer Platforms (DP).

Products that provide similar capabilities are grouped into 'specializations'. Depending upon the nature of the specialization, we sometimes can apply verticalization (ie, what was done for API as a Product), or can apply horizontally (ie, what was done for App Servers). Specialization is not an exact science. Some are granular enough that products can exist in multiple specializations and categories. When a product can logically exist in multiple places, it is listed in one place that we feel is closest to the product's value proposition.

'segments' are groupings of products across different specializations used for aggregate reporting. When different specializations are closely related, they are grouped into a segment. 

We provide definitions for categories, segments, and specializations when they are not already widely accepted, or where our definition deviates from norms.

#### Category: Software Delivery Lifecycle (SDLC)
Process solutions that coordinate how teams design, develop and test software. SDLC contains segments that create products - and in many cases services / solutions - that impact developers across the entire lifecycle of development. Conceptually, SDLC offerings are leveraged across Developer Tooling, Developer Infrastructure, and Developer Platforms. 

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

#### Segment: Code + Application Security
The combination of Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), fuzzing, Software Composition Analysis (SCA), and Interactive Application Security Testing (IAST). These tools, while also used by security engineers, are often times developer-first.

#### Segment: Engineering Efficiency
Solutions that provide engineering intelligence to bring visibility and suggestions to improve software delivery. These solutions deliver insights that are consumed by all stakeholders, from engineers to product managers to business constituents to executives.

#### Segment: Value Stream Management
'Value Stream' is a term from the Lean Movement to describe the material and information flow to create value. It's the sequence of activities an organization undertakes to deliver on a customer need. Value stream management vendors provide solutions that increase the rate of flow for items moving through a value stream, usually by connecting and integrating numerous underlying developer and operations solutions. 

## Segment Overlaps
#### SDKs + Application Servers
I've included SDKs within this category as it's a broad term that encompasses many of the libraries and frameworks that developers include as they create software. Many SDK vendors choose to monetize in production, and while there is no duplicative vendors in SDKs vs. Application Servers, my selection of a product going into one category vs. the other is subjectively determined.

#### CI + CD + Build Automation
We keep track of these three segments separately. However, it is increasingly the case that these products have overlapping functionality and it's getting harder to distinguish between the differences, though they do exist. 

#### CI + CD + GitOps
Increasingly, the CI/CD vendors are adding in forms of GitOps into their offerings. And many of the GitOps vendors describe their solutions as forms of CD. There seems to be a convergence of configuration management and CI/CD platforms. Currently, we keep the categories separated.

#### Code and Application Security + Config + GitOps + CI + CD
Code and Application Security contains numerous sub-segments related to validating and testing code and systems. The market considers Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), fuzzing, Software Composition Analysis (SCA), and Interactive Application Security Testing (IAST). We do not include Runtime Application Security Protection (RASP) in our categories. These capabilities are often lightly provided within products that also offer configuration management, GitOps, CI, or CD. Companies that primarily provide code and application security solutions are placed into this category, whereas companies that tangentially offer these solutions are listed in other categories.

#### Application Servers + PaaS
The lines between hosted offering and downloadable software have blurred. Application servers are platforms for developers to build and run their applications in any environment. Platform as a Service products are hosted platforms for building and running those same applications. Many vendors are increasingly providing both - a downloadable application server that is also hosted as a PaaS. There are many companies that could arguably fit in either segment. A company ends up in the segment where we think most of their revenues are generated.

#### API as a Product + PaaS
A number of the vendors that provide an API as a Product offering are also a PaaS, especially in the integration PaaS and communication PaaS areas. Most of the iPaaS vendors are included in the PaaS segment because they require customers to create software systems deployed and hosted within the vendor's cloud. Most of the cPaaS vendors are included in the API as a Product segment because most of the software leverages callable APIs. This dynamic also appears frequently with headless CMS vendors, which are providing forms of APIs for managing content and PaaS for hosting content.

#### Low Code + PaaS
A few vendors are providing low code workflow solutions optimized for integration. This looks a lot like an iPaaS. Some of the iPaaS vendors are increasingly suggesting tha they are low code or no code. It could be subjective as to whether a product lands in the Low Code or PaaS segment.

#### Special Case: API Specializations
We noticed that many of the vendors provide functional products that specialize exclusively in APIs. This exists for IDEs, test automation, security, gateways. We provide specializations in these segments for the vendors that deliver API-only variants.

## What Is Not Included
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

#### Blockchain
For the same reasons that data science and MLOps are excluded. 

#### Some Vendor Products
Some companies publish multiple products that perform similar, but different capabilities for a single segment. In some cases, the overlaps are significant enough where I count them as a single vendor / product. In other cases, the product's are distinct enough where a vendor would appear multiple times in a single category. For example, Cloudbees, has different CI and CD products, and each product is given its own line item in the same category. Cloudbees as a vendor would count as a single vendor for the segment, but there would be multiple products. In the case of CA, now owned by Broadcom, they positioning their offerings as solutions, using broad brand definition to span many different pieces of IP, and so I have to infer best demarcation judgment in determining where product boundaries exist.

#### M&A Events
As developer-led businesses merge with other businesses (or discontinue operation), that is an industry change event. The number of vendors for a category may shrink, revenue allocations may change, and so on. While I update the database to reflect the new normal, I haven't kept an append log of each event, the date it occurred, and specific impacts. This would be a wonderful thing to add.

#### Graphic Design
Alas, while I have many talents, making things look good isn't one of them.

## Revenue and Growth Estimations
In most segments, we have a (fairly) complete list of companies that have revenue-generating product(s). In these segments, we use the aggregate revenues from across all products to determine a segment's revenue. 

We make an estimate of recurring revenue, and where possible, try to exclude one-time revenue such as the professional services attached to selling a product. To calculate the growth rate, we compare the segment's total current annually recurring revenue with the same measure from a year ago. I only use public sources of information (# of employees, investment raised, and corporate blog posts) to make an ARR estimate for a company. 

If a vendor sells a single product whose features span multiple segments, we count the revenues for that single product in a single segment. For example, Gitlab, which sells a single platform offering which covers many of the segments across Dev Infrastructure.

Any analysis that references a publicly traded company is either a company that is listed directly on a public stock exchange or is owned by a publicly traded company and still doing business under it's original brand. So, GitHub would be listed as a publicly traded company, but Pivotal would not.

There are some segments where the major analysts have estimates which are significant deviations (much higher!) from ours. We note and discuss the segments where major deviations exist.

#### Test Automation: $2.6B (us) vs. $12.6B (analysts)
Holy guacamole, Batman! Despite our best efforts, we couldn't find more than $2.6B in software sales related to testing. We think the analysts are including large consultancies (body shops) in their numbers. The $10B discrepancy is a reflection of how much automation can still contribute to software construction.

#### Application Servers: $12.5B (us) vs. $32B (analysts)
Aye Carumba! $20B could buy a lot of salsa for Taco Tuesday. Gartner's definition of application servers includes some PaaS, blockchain, digital experience, MLOps, and databases. If you included data warehouses and data lakes as part of the database category, that would explain a large chunk of the $20B. 

Gartner has been tracking the Application Server segment annually for over 20 years. Much of the recurring revenues are generated by support and maintenance on legacy runtimes. It's possible that we are dramatically under counting some legacy revenues. Oracle and IBM have a lot of old, proprietary stuff hanging around that customers must still pay for.

#### PaaS: $5.26B (us) vs. $19B (analysts)
Don't spit out those Wheaties! The analysts include infrastructure cloud services such as compute, storage, and ingres/egres capabilities which are programmable by developers, but not part of the classic definition of a PaaS. 

#### Low Code: $2.2B (us) vs. $15B (analysts)
Hotter than blue blazes! No code is included in analyst estimates, which might account for some of the revenues. But we think that a lot of productivity solutions like Google Sheets, which have macro capabilities are increasingly getting lumped into the analyst numbers as a way to inflate or exaggerate the importance of the low code phenomenon. 

## Vendor Count
The number of companies in a segment is measured through our bottoms-up collection of vendors that have a product in that segment.

The same vendor can (and often does) show up in multiple segments. 

We've worked to avoid double counting revenues, even though the same vendor can appear in multiple segments. 

## Attributions
There are many people who influence my thinking on the subject, and in many cases, have also directly contributed to this research. Thank you for the support, intellectual thoughts, and any future contributions you might make.

In particular, Diana Kontsevaia deserves a special call out as she has (joyously) spent numerous hours identifying potential gaps, applying thoughtful critiques, and pursuing primary research to add to this effort. 

**My Dell Technologies Capital Colleagues**: Ryan Wexler, Daniel Docter, Raman Khanna, Chris Hillock, Scott Bevan, Alon Weinberg, Annie Tran, Deepak Jeevankumar, Frank Wang, Gregg Adkin, and Yair Snir.

**My VMWare Colleagues**: ….

**Other Industry Colleagues**: Brad Murdoch (EVP, Lightbend), Tracy Ragan (CEO @ DeployHub), Paul Fremantle (Founder @ WSO2), Brad Micklea (VP @ RedHat), Helen Beal (DevOps Institute), Richard MacManus (TheNewStack), Nish Bhalla (Angel Investor).

## Learn About Developer Markets
If you want to dive deeper into the developer rabbit hole, I recommend:

1. *"The New Kingmakers: How Developers Conquered the World"* by Stephen O'Grady. Stephen's articulation on how the power dynamic has shifted in IT due to the underlying shift in cloud, purchasing dynamics, and developer idiosyncratic behaviors is excellent. 

2. *"Agility Now: The Coming Battle for DevOps Supremacy"* by William Blair, published in November 2019 with contributions from Jason Ader, Bhavan Suri, Arjun Bhatia, David Griffin, Jonathan Ho, and Sebastien Naji. They have the most comprehensive articulation of the foundational technologies that are driving the DevOps movement. They also dwell more on the dynamics of "Last Mile" delivery with Continuous Delivery, how automation is driving a "Shift Left" in the toolchain, and the emergence of DevSecOps.

3. The [Redmonk blog and research feed](https://redmonk.com). A small group of talented analysts out of Europe who write frequently on trends in programming languages, open source, and vendor dynamics. Most of their clients are vendors that are captured in this landscape.

4. [TheNewStack.io](https://TheNewStack.io) has emerged as one of my favorite reading spots to get a feel for how different vendors are positioning underlying shifts in the industry. They are one of the few analyst publications focused on infrastructure that has a dedicated section to development.

5. The [APIDays API Landscape by Mehdi Medjaoui](https://www.apidays.co/wp-content/uploads/2020/07/API-Landscape-2020.pdf) does an excellent job of capturing the different categories of infrastructre that go into supporting the API lifecycle.

6. There are other VCs that sometimes write about developer markets, and their writings can offer insights not commonly seen elsewhere. This includes [Assaf Araki on Autonomous Software Development](https://www.linkedin.com/pulse/software-20-takes-shape-assaf-araki/?trackingId=BXbKWfcyRQOoKMQJU4dCOw%3D%3D), [Astasia Meyers' Memory Leak](https://medium.com/memory-leak/3-devops-trends-to-watch-in-2020-827f69475ff0) and [Nnamdi Iregbulem's WhoIsNnamdi](https://whoisnnamdi.com/).
