For https://www.papercall.io/talks/250397

## 0.1 Rocky Trail

### 0.1.1 Me
I'm Devrim Demiroz. Today I would like to share a vision in other words my dreams regarding a visualisation is off complex systems. My journey began with c64 and we are here today.   charting new ideas in observability visualization with OpenTelemetry.  still i am learning. still i am growing. my passion drives me to contribute to a more meaningful relationship between technology and understanding. In a way, I'm a modern Cartographer, Young in Heart, and always eager to discover what's next.

### 0.1.2 this talk

this talk  is about how to make better decisions under uncertainty. I strongly believe   visualisaing complex software structures ( systems) is a form of art that will change our understanding. 

### 0.1.3 Disclaimers
- I am currently employed at Swisscom. However, this talk is presented as my individual perspective and does not reflect the views or positions of the company.

- I started using chatgpt 4 to enhance this speech and used it in heavily with copilot in prototyping. 

- in this talk, I will not deep dive many  referenced concepts, products, et cetera. Rather, I will leave them as clues for curious minds.

## 1.1 Why Software Modelling became hype in 2000s?
My take is that it was a reaction to the complexity of software systems. Internets second wave was demanding more and more integration led to more and more complexity.

## 1.2 But what is modelling?
Models are built to scale. Human brain is not good at scaling. Models can help by abstracting away the complexity.

Internet second wave needed scaling...

## 1.3 The hype 
Unified Modeling Language (UML) was the hype. It introduced many useful models as well brought its own complexity.

Here are some of the models:

### 1.3.1 Use Case Diagram
### 1.3.2 Class Diagram
### 1.3.3 Sequence Diagram , my favorite

This Sequence Diagram is from Forgerock documnemtaiion representing the OpenID Connect flow.


### 1.3.4 Activity Diagram


# 2 annotation 1
Around 2008/2009, in my point of view, three major things happened in computer industry:
1. linux: We witnessed  The rise of linux and open source software. 
2. devops: The movement started with one spark: Enter jira task id in commit message!
3. iphone: Changed the way we interact with computers. Changed telecommuniction industry. Changed the way we live.


# Scene 3 slide APM

## 3.1 2003 Mercury Performant and LoadRunner
## 3.2 APM ERA
### 3.2.1 Gartner APM Conceptual Framework
Though End User Experience and Analytics are significant, they are outside the scope of this talk. Instead, I'll focus on three groundbreaking visualizations introduced by the framework:

#### 3.2.1. Runtime Application Architecture 
This involves the discovery, modeling, and display of application components and their interconnections. One example from my early APM implementations beautifully encapsulates a complex system in a single, insightful picture.

#### 3.2.2. Business Transactions
This refers to the visual depiction of specific call flows traversing multiple components.

#### 3.2.3. Component Deep Dive
Mostly flamegraphs, represented in Jaeger tracing as most of the industry is familiar Jaeger trace Gantt charts. The core techniques remain consistent across both realms, intersecting at the essence of their function.

#### 3.2.4. Trace as Data
Runtime Application Architecture, Business Transactions are built on top of call graph or in other words , a trace. Nothing but refined data visualization techniques.

Most of the visuals you would see are about this Trace as data and their topological and temporal relationships. All talk is around variations of these three visualizations.

# 4 Context among Buzzwords

## 4.1 Navigating through the buzzwords

Architecture as Code, software catalogs, flow diagrams, sequence diagrams ... there are aliases fron software modeling world describing the similar diagrams.

System topology, Application topology, Service topology, Service map, Service dependency, Application dependency, Application map are example aliases of Runtime Application Architecture visualizations mentioned in APM conceptual framework. Almost all products in the market have somewhat different naming for these visials. 

## 4.2 Higher level of abstraction

Stepping outside IT operations, similar visualizations are used in other domains like social networks, neural networks, protein networks, chemical networks. In fact, these visualizations are based on graph theory, which is a branch of mathematics. A new branch called network science emerged in 2000s to study these networks. Network science is a multidisciplinary field that uses graph theory to study complex systems. Network visualization is a subfield of network science. Data visualization is a subfield of network visualization.

This Brain network visualization is from the Connectome, 2019 from barabasi lab. Where it lands in fields of ART and defined as data sculpture.

No worries, I will not jump into what is art from here 😊 

## 4.3 Models versus Real-time Architectures

Fundamentally, models exist even you switch off the system. Where real-time architecture views exist in a timeframe where telemetry data is available. Real-time architectures depend on spatiotemporal data. Where spatial refers to space and temporal refers to time. Waze(acquired by Google) crowd-sourced traffic data from its users to construct traffic and map data like new roads appearing. The dialect between software modelling and telemetry-derived data is very similar in that sense.

Models are the map , telemetry data is the traffic as an analogy.
My closest guess Dynamic Temporal Graph Networks (TGNs) are a type of model designed to handle temporal graph-structured data. Which is the nature of complex observability data.

1. Nodes: Entities in the graph (e.g., users, items, etc.).
2. Edges: Relationships between the entities.
3. Timestamps: Time of the interaction or relationship.

“stream” of timed events is the challange in visualization.Presenting time in visualizations is still a challenge. 

# 5 Annotation 2

The second annotation on this timeline according to me happened around 2018.
The rush to cloud and kubernetes happened. Again, scaling systems was the main driver.

And covid-19 pandemic changed the way we work. 

In ashes of k8s, system complexity exponentially increased. Current monitoring, apm and logging tools individually were not enough. Logging companies started acquiring apm companies. APM companies started to merge with monitoring tools. And so forth... Opentracing and OpenCensus merged to form OpenTelemetry. But it was more than that. It quickly became the standard for any observability data collection.

# 6 Opentelemetry

As of 18 Oct’22

2nd most active project in CNCF after Kubernetes
2,5 years old
4 Signals as Traces, Metrics, Logs, Baggage
4,607 developers
58 repositories
699 companies like Amazon, Dynatrace, Google, Honeycomb, Lightstep, Microsoft, Splunk, Uber, …
11 languages like Rust, Swift, Go, Javascript, C++
77 receivers, 46 exporters, 24 processors, 19 extensions, and 6+ deployment patterns for Collector
407 libraries, plugins, integrations, and other useful tools for extension available in Registry
23 Vendor natively support OpenTelemetry in their commercial products like AWS, Grafana, Datadog, Splunk, New Relic
and many products with out-of-box support or compatibility like selenium, nginx, k6…

Opentelemetry in just a two years time grown to a huge ecosystem. For me, it was like a dream coming true. Both sw. modelling and APM worlds were coming together. And opportunities and possibilities were endless.

## 6.1 Opentelemetry and Sequence Diagrams

The sequence diagram is from a blog I posted early 2021. I was able formally ensure compliance of OIDC/SAML flows with the help of OpenTelemetry. Moreover, with PlantUML, I was able to generate the sequence diagram from the trace data. 
So, I was able to compare 102 possible MFA complex flows visually and formally with the help of OpenTelemetry, Puppeteer and PlantUML.  You can find the details of this implementation on the link provided.

## 6.2 

Coverage opetelemetry offers is huge. And this means now we can validate our models with more data and make stronger predictions leading to better decisions. 

It is in a way how our brain works. Keeping a model of the world and validating it with the data we observe , form shared reality.
