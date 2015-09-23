---
title       : Workshop on BigData
subtitle    : Focus on Streaming
author      : Dr.Muthukumaran
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## What is Big data?
- Myth About Big Data - With Big Data, We’ve Moved into a New Era of Analytics
- Big data is data that exceeds the processing capacity of traditional database systems. 
– The data doesn’t fit the gloves of traditional database architectures
– The data is too big and moves too fast 
- Big Data does not only relate to the size of data
- Its about triggering an offer while a shopper is standing on a checkout line
- Its about placing an ad on a website while someone is reading a specific article. 
- It’s about combining and analyzing data so you can take the right action, at the right time, and at the right place.

---

## What is Big Data?
– Complexity: missing information, dummy data, organization
– Processing: Software, processing power, parallel and distributed computing 
– Data Transfer: Limitations of current systems, CPU intensive
– Storage:  Data sets beyond relational database, clusters, data centers, distributed data
– User Interaction: Non-programmers need to perform complex information, real time GUI interfaces, visualization of data

---

## What is Big data?
- Big Data is all about better analytics on a broader spectrum of data, and therefore represents an opportunity to create even more differentiation among industry peers
- Walmart’s push to use RFID tags for supply chain optimization illustrates the dawn of the Big Data era. 
- RFID is a great example of machine-speed-generated data that could be collected and analyzed.

---

## What is an example for big data flow?
- Railway car has hundreds of sensors. 
- Sensors track such things as the conditions experienced by the rail car, the state of individual parts, and GPS-based data for shipment tracking and logistics. 
- During train derailments, governments introduced regulations that this kind of data be stored and analyzed to prevent future disasters.

---

## What is Big data?
- Real-time big data isn’t just a process for storing petabytes or exabytes of data in a data warehouse,” says Michael Minelli, co-author of Big Data, Big Analytics.
- It’s about the ability to make better decisions and take meaningful actions at the right time. 
- It’s about detecting fraud while someone is swiping a credit card

---

## What is Big data?

Big data Characteristics
- Velocity: Moves at very high rates (think sensor-driven systems); Valuable in its temporal, high velocity state
- Volume: Fast-moving data creates massive historical archives; Valuable for mining patterns, trends and relationships
- Variety: Structured (logs, business transactions); Semi-structured and unstructured

---

## What is Volume ?
- Most organizations were already struggling with the increasing size of their databases. 
- Firms were Creating 5 exabytes of digital data until 2003. Created  the same amount of data in two days in 2011. 
– expected to fill the same in 10 minutes

---

## What is Velocity ?
- A conventional understanding of velocity typically considers how quickly the data is arriving and stored, and its associated rates of retrieval.

- Two aspects to velocity, 
– one representing the throughput of data 
– the other representing latency

---

## What is Velocity?
- Throughput is data moving in the pipes. 
– Global mobile data is growing at a 78 percent compounded growth rate and is expected to reach 10.8 exabytes per month in 2016 as consumers share more pictures and videos. 
– To analyze this data, the corporate analytics infrastructure is seeking bigger pipes and massively parallel processing

- Latency is the other measure of velocity

---

## What is Variety?
- Variety represents all types of data – 
– a fundamental shift in analysis requirements from traditional structured data to include raw, semi-structured, and unstructured data as part of the decision-making and insight process.

---

## What is Veracity?
- Veracity represents both the credibility of the data source as well as the suitability of the data for the target audience
- Source credibility. 
– If an organization were to collect product information from third parties and offer it to their contact center employees to support customer queries, the data would have to be screened for source accuracy and credibility.

---

## What is data?
- Data is everywhere
- The word data refers to information presented in whatever form agreed upon by the parties creating and using the data.
- Data being produced today has a very short shelf-life

---

## What is data?
- Amount of data available to the enterprise is on the rise 
- Percent of data it can process, understand, and analyze is on the decline, thereby creating the blind zone
- It is easy to testify to the growing gap between the generation of data and understanding of it. 
- Lying hidden in all this data is information, potentially useful information, that is rarely made explicit or taken advantage of.

---

## What is data?
- As the volume of data increases, inexorably, the proportion of it that people understand decreases, alarmingly. 
- Organizations need to analyze this data in near real time if they hope to find insights in this data

---

## What is data?
- Ubiquitous electronics records  decisions,  choices in the supermarket, financial habits,  movements etc
- Data is often too specific to be useful to us as decision support
- Data, as such, seldom delivers line by line, fact by fact, or category by category any value to the user. 

---

## What are the properties of Raw Data?
- The raw data is only partially structured
- The raw data is written once and never changed again
- Raw data come in as streams with high throughput (hundreds of MB/s), depending on the sensor devices. 

---

## What are the properties of Raw Data?
- They have to be recorded as they come in, because in most cases there is no way of repeating the measurement.
- For the majority of applications, the raw data is not interesting. 
- What the users need are aggregates, derived values, or—in case of text fields—some kind of abstract of “what the text says”.

---

## What is structured data?
- Structured data is data that is organized into entities that have a defined format, such as XML documents or database tables that conform to a particular predefined schema.
- Semi-structured data, on the other hand, is looser, and though there may be a schema, it is often ignored.

---

## What is unstructured data?
- Unstructured data does not have any particular internal structure

- Information has gone from scarce to superabundant. That brings huge new benefits,  says Kenneth Cukier—but also big headaches

---

## Why analyze Big Data?
- Across industries it is becoming important to make sense out of this data and gain competitive advantage.  
- Below are the few use cases of Big Data:
– In the Telecom industry, Operators generate 5 to 10 TB of call record day every day. These Big Data can be mined for marketing campaign, network optimization.
– In the Retail Industry, pricing is a very important attribute. Big Data helps to compare pricing across retailers and product categories and set the optimum price.


---

## What are the Types of Data
- Social network profiles
– Tapping user profiles from Facebook, LinkedIn, Yahoo, Google, and specific-interest social or travel sites, to cull individuals’ profiles and demographic information, and extend that to capture their hopefully-like-minded networks.  
- Social influencers
– Editor, analyst and subject-matter expert blog comments, user forums, Twitter & Facebook “likes,” Yelp-style catalog and review sites, and other review-centric sites like Apple’s App Store, Amazon, ZDNet, etc.  

---

## What are the Sources of Data
- Internal Sources
– Corporate databases, company documents
- Personal Sources
– Personal thoughts, opinions, experiences
- External Sources
– Commercial databases, government reports, and corporate Web sites.

---

## What is data science?
- Data science is 
– an emerging field, 
– with rapid changes, 
– great uncertainty, and 
– exciting opportunities. 
- Data science is a discipline that combines 
– Math 
– Programming 
– Scientific instinct

---

## What is data science?
- Data science incorporates varying elements and builds on techniques and theories from many fields, including 
– math, statistics, data engineering, pattern recognition and learning, advanced computing, visualization, uncertainty modeling, data warehousing, and high performance computing 
– To extract meaning from data and creating data products.

---

## What is data science?
- Data Science
–  is a composite of a number of pre-existing disciplines
– Data science enables the creation of data products. 
- Google generates and manages data products. 
- Facebook and LinkedIn use patterns of friendship relationships to suggest relationships with frightening accuracy. 

---

## Who is a data scientist?
- A practitioner of data science is called a data scientist.
- The term was coined by DJ Patil and Jeff Hammerbacher
Who is a data scientist?
- Data scientists are the people who understand how to fish out answers to important business questions
- They bring structure to large quantities of formless data and make analysis possible.
- They identify rich data sources, join them with other, potentially incomplete data sources, and clean the resulting set

---

## Who is a data scientist?
- Data Scientist is a hybrid of data hacker, analyst, communicator, and trusted adviser The combination is extremely powerful—and rare.
- Facebook’s data team created the language Hive for programming Hadoop projects

---

## What is the need for data scientist?
- Increase in the demand for data scientists is due to the success of the major Internet companies.  
- Google , Facebook, LinkedIn, and  Amazon have all made their marks by turning data  into something of value. 
- Whether that value is a search result, a targeted advertisement, or a list of possible acquaintances, data science is producing products that people want and value.

---

## What are the traits of data scientist? 

- Technical expertise: the best data scientists typically have deep expertise in some scientific discipline.
- Curiosity: a desire to go beneath the surface and discover and distill a problem down into a very clear set of hypotheses that can be tested.
- Storytelling: the ability to use data to tell a story and to be able to communicate it effectively.
- Cleverness: the ability to look at a problem in different, creative ways.

---

## What are responsibilities of DS?
- collecting and analyzing data to evaluate existing and potential product and service markets
- Lead the design, development and deployment of a suite of products and solutions enabled by Big Data
- Guide consultative teams on early adopter engagements


---

## What is expected of a data scientist?
Future Job Ads
- To understand, 
– The future is in search of a multi skilled person
– Who understands data 
– Who understands data modeling
– Who understands business
– Who understands statistics
– Who can work at code level
– etc

Future  Job Ads
- Data scientist required.
– Must be able to work with highly diverse datasets, both structured and unstructured. 
– Top mathematical skills needed to create appropriate models, along with excellent computer science skills to build and implement these. 
– A deep understanding of the consumer products industry is a must. 
– Ideally 2-5+ years experience. 
– Should have strong ability to influence others.”

Future Job Ads
- Marble Security is looking for an experienced innovative data research analyst with expert knowledge in building a highly reliable, redundant and scalable system to deliver rich risk analytics for the enterprise IT Admin to control mobile risk. The risk data set would include employee owned mobile devices, access networks, applications, etc. In addition, responsibilities include interacting with various teams including Product Management, Engineering, and Marketing to enhance the Marble Security solution.

Bigdata and BI
- There are four types of big data BI that really aid business:
– Prescriptive – This type of analysis reveals what actions should be taken. This is the most valuable kind of analysis and usually results in rules and recommendations for next steps.

– Predictive – An analysis of likely scenarios of what might happen. The deliverables are usually a predictive forecast.

Bigdata and BI
- There are four types of big data BI that really aid business:
– Diagnostic – A look at past performance to determine what happened and why. The result of the analysis is often an analytic dashboard.

– Descriptive – What is happening now based on incoming data. To mine the analytics, you typically use a real-time dashboard and/or email reports.

 BI Frame work
 BI Frame work

---

## Big Data deployment?
- Deploying smart meter systems presents an immediate technical challenge: 

- Going from one meter reading a month to smart meter readings every 15 minutes works out to 96 million reads per day for every million meters: a 3,000-fold increase in data collection rates

- provides a better understanding of customer segmentation and behavior
Big Data deployment?
- A single flight from London’s Heathrow Airport to John F. Kennedy in New York would generate about 650TB of data!

- Most of this data is likely never looked at, unless disaster strikes

- Data is “dropped to the floor” and is referred to as data exhaust
What is the impact of big data ?
- Companies like Facebook,  LinkedIn, Yahoo, and Google are generating data not only as their primary product, but are analyzing  it to continuously improve their products. 

- Pharmaceutical and biomedical companies are using big  data to find new cures and analyze genetic information, while marketers leverage the same  technology to generate new customer insights.

---

## What is the impact of Big data?
- Businesses embrace Big Data to know more about their customers

- Hospitals can deliver effective, personalized medicine to patients

- Governments can mine enormous data resources to more effectively serve  constituents 

- Energy companies can bring more renewable energy on-line using a highly instrumented smart  grid, smart meters at the home, and increasingly accurate weather forecasts

---

## What is the impact of Big data?
- Drug researchers use vast genomics databases to discover the next generation of cancer treatments. 
- Big Data is already an important part of the $64 billion database and data analytics market and offers commercial opportunities of a comparable scale to enterprise software in the late 1980s, the Internet boom of the 1990s, and the social media explosion of today.

---

## Session 1 summary & Questions

## Session 2 know your datasets and hidden business
- 11:15 to 12:30 
– Static and Streaming data at high velocity 
– Big Data sources, e.g. web logs, click stream, sensor data, unstructured and semi-structured content
– Need to analyze complex data sources 
– Role of information management
– Challenges for managing and analyzing big data
– Analytical workloads and Types  
– Structured data analysis 
– Multi-structured data analysis 
– Extended Analytical environment
– Supplying consistent data to multiple analytical platforms

---

## Where are the sources of big data ?
- Primary sources of big data
– Meteorology 
– Complex physics simulations
– Biology 
– Business
- Web searching
- Social networking
- Telecommunications 
- Many programs for storage and processing
– Most Popular: HDFS, GFS, Hadoop, and MapReduce
– No standard for processing/storing data
-  No common “off the shelf” software 
- Increases the difficulty in mining data within a field or industry

---

## Where Is This “Big Data” Coming From ?
From transactions to observations
What is the use of big data?
- The value of big data to an organization falls into two categories: 
– Analytical use: analytics can reveal insights hidden previously by data too costly to process, such as peer influence among customers, revealed by analyzing shoppers’ transactions and social and geographical data. 
– Enabling new products: by combining a large number of signals from a user’s actions and those of their friends, Facebook has been able to craft a highly personalized user experience and create a new kind of advertising business


---

## What is big data challenge?
- Organizations today are facing more and more Big Data challenges. 
- They have access to a wealth of information, but they don’t know how to get value out of it because it is sitting in its most raw form or in a semistructured or unstructured format; and as a result, they don’t even know whether it’s worth keeping

---

## What is big data challenge?
- First, data quality remains an issue. 
– The more data you accumulate, the harder it is to keep everything consistent and correct. 
- Second, adequate data characterization (metadata to the geeks) is critical. 
– How you deal with data -- even how you choose to organize its storage -- requires you to know how much data there is going to be and how fast it's likely to grow and change. A query that runs well to find 100 rows in a million-row table may not run well on 100 billion rows. 

---

## What is big data challenge?
- Third, interpretation remains more of an art than a science. 
– Software developers have had to design efficient filters and pattern recognizers that can sift through mountains of data and find (perhaps unanticipated) patterns that are relevant to a dimension of interest.
- Fourth, data visualization -- representing results in an easily consumable form -- is critical. 
– What good is all that data if you can't understand what the interpreters--human or software--concluded from their analysis. 

---

## What is big data challenge?
- Fifth, you're generally going to have to choose 
– between a real-time view of the data (which may mean that you have to continuously recompute everything whenever the data changes) and a complete but retrospective view which will always be somewhat out of date.
- Sixth, how do you know in advance how long the data is relevant or valuable? 
– Data costs money to acquire, store, analyze and back up. A retention policy beyond a typical "keep everything forever" approach is needed, and that policy has to be enforced.

---

## What are the associated difficulties? 
- Storage
– Developing a system in which very large amounts of data can be stored securely and accessed quickly
- Transfer
– Transfer from the storage site to the processing site
– Moving large amounts of data over TCP is costly
- Processing
– How powerful of a system is needed?
– “There is a lot of data but no information”
– Processing the data in an efficient manner and obtaining the correct information

---

## What is big data solution used for?
- Big Data solutions are ideal 
– for analyzing not only raw structured data, but semistructured and unstructured data from a wide variety of sources.
– when all, or most, of the data needs to be analyzed versus a sample of the data; or a sampling of data isn’t nearly as effective as a larger set of data from which to derive analysis.
– for iterative and exploratory analysis when business measures on data are not predetermined.

---

## What is an analytical workload?
- The practice of analytics involves applying science and computing technology to vast amounts of raw data to yield valuable insights, and the “analytics” label covers a wide array of applications, tools, and techniques.
- Predictive analytics, in-database analytics, advanced analytics, web analytics etc are collectively called as analytical workload.
What is an analytical workload?
- Most interested parties can answer this question, more or less correctly, in a general way: “heavy statistical processing,” “lots of complex queries,” and so on
- Analytics processing is characterized by fewer users (business analysts rather than customers and POS operators) submitting fewer requests, but queries can be very complex and resourceintensive. 

---

## What is an analytical workload?
- Analytic workloads tend to share 
– a set of attributes, 
– with strong design and 
– deployment implications 
– for the processing systems assigned to handle these workloads.

---

## What is an analytical workload?
- An analytic workload will exhibit one or more of the following characteristics, each of which elevates a given workload’s degree of difficulty:
– Extreme data volume
– Data model complexity
– Variable and unpredictable traversal paths, patterns, and frequencies
– Set-oriented processing and bulk operations
– Multi-step, multi-touch analysis algorithms
– Complex computation
– Temporary or intermediate staging of data
– Change isolation/data stability implications

---

## What is an analytical workload?
Analytical platforms
Business value of analytic platforms
- Kelley Blue Book – Consolidates millions of auto transactions each week to calculate car valuations
- AT&T Mobility – Tracks purchasing patterns for 80M customers daily to optimize targeted marketing	

---

## Which platform do you choose?
Big data platform comparison

---

## What is the Big data hype cycle?

---
## Session 2 summary & Questions



