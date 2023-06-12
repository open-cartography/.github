# Observability Visualization in the Age of OpenTelemetry

# Elevator Pitch:

OpenTelemetry isn't just a step forward; it's a leap into a new era of observability. Born from the complex needs of cloud and Kubernetes environments, it has unlocked a world of possibilities that extend beyond the conventional realm. From system modeling to application cataloging, process mining to testing, it has reshaped our traditional approaches to observability. But one transformation stands out - visualization. With OpenTelemetry, we can now visualize data like never before, illuminating insights that were once hidden. In this talk, we will explore the new dimensions of data visualization that these open-source observability tools have unlocked and embark on a captivating journey into what the future holds for data visualization in observability.

# Description:

Embark with me on a voyage through the world of observability visualization. As we delve into numerous examples and prototypes, both existing and potential, my hope is that they will ignite your own creative sparks. When it comes to understanding our complex systems, remember, visuals truly do matter! 


- `A Brief and Personal History of Visualization in Understanding Complex Systems`    <sup>[1](https://tractatus.one/the-quest-for-the-holy-observability-graph-foreword-27d8c4f7c8b5)</sup>
    - From modeling to real-time architecture in Application Performance Management (APM), transaction visibility to call graphs, and sequence diagrams, we've come a long way in visualizing our complex systems. <sup>[2](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-1-9d3613e28332)</sup>
    - We have a rich vocabulary of buzzwords such as topology, graph, network, flow diagrams, dependency maps, etc. 
    - Complex Nature of data: We've always dealt with dynamic temporal graph networks (TGNs)    <sup>[3](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-2-1b2b0b9b2b0b)</sup>, <sup>[4](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a)</sup>

- `What does does OpenTelemetry unlock?`
    - Unparalleled Tech Stack and Industry Coverage Enabling Unified Data Landscape <sup>[5](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-2-51defa4e97d9)</sup>
    - Open Source Community and innovation
        - Game-changing introduction of OpenTelemetry Collector
        - Emerging New techniques: 
            - The Critical User Interaction (CUI)
            <sup>[6](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572)</sup>
            - Failed Customer Interactions (FCI)
            - Trace based testing and usage as RUM
        - Shifting Left: Build-time observability, briding the gap between ops and dev
        - Serving the truth: Service catalog , process mining, etc.

- `The Future of Visualization`: Opportunities and Possibilities
    We're moving towards a new era of topology visualization and navigation.
    
    - `The Art of Metaphors`: Illuminating the Value of Visualization <sup>[7](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572)</sup>
    - `Visualization Libraries Uncovered`:  D3, Cytoscape, etc. <sup>[8](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572)</sup> , <sup>[9](https://https://tractatus.one/shahmaran-20a9f1678)</sup>
    - `The Open Source Dilemma with AGPL Turns`: Grafana, Jaeger, Kiali , Perses, Coredash, etc. 
    - `A Personal Journey of Visual Prototyping`:
        - Sequence Diagrams from Traces <sup>[10](https://devrimdemiroz.gitlab.io/post/2021-03-09-observeopenam/)</sup>
        - Converting Metrics to Topology and Encountering Boundaries <sup>[11](https://tractatus.one/shahmaran-20a9f1678)</sup>
        - `Innovating Tracing Presentation`: 
            - Adopting the Transit-Map Metaphor <sup>[18](https://tractatus.one/collector-pipelinesvisual-language-26f950c8d22)</sup> , <sup>[19](https://tractatus.one/transit-observability-map-e73c61a9b9e0)</sup>
            - Rediscovering the Power of Path-Centric Representation  <sup>[18](https://tractatus.one/collector-pipelinesvisual-language-26f950c8d22)</sup> , <sup>[20](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-1-9d3613e28332)</sup>
            - Incorporating Time into Visuals (UCM) <sup>[21](https://tractatus.one/shahmaran-20a9f1678)</sup>
        - `Pareidolia Phenomenon`: Revealing Unexpected Forms in Observability Visualization
            - o11y octopus <sup>[12](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a)</sup>
            -  Clowns with Crowns <sup>[13](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a)</sup>
            - Front End Running , One Leg Bleeding <sup>[14](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a)</sup>
            - Microservices Caught Between Slides and Coverslips <sup>[15](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a)</sup>
        - The Need for 3D Visualizations and its Implications
    - `Elevating Relationships to First-Class Citizen Status`:
        - Extracting and Archiving Topologies
        - Viewing Topology as a Signal <sup>[16](https://github.com/devrimdemiroz/opentelemetry-demo-webstore/blob/shahmaran/src/servicetopology/SpanGraphProcessor.md)</sup>
        - Pheromones Analogy <sup>[17](https://tractatus.one/using-pheromones-via-opentelemetry-for-efficient-routing-in-distributed-system-ac163b26382e)</sup>
        - Is there a Role for AI in Enhancing Human-Perceptible Visualizations? Or the other way around, Visualizations as ML for Enhancing AI for observability?


---


# Notes

As a software performance engineer, although I consider myself a newbie in data visualization, I have a clear vision of what I want to see in observability visualization. Instead of waiting for others to take the lead, I have taken it upon myself to prototype possibilities and unlock the full potential of OpenTelemetry. With a passion for sharing knowledge and helping others navigate the complexities of technology, I strive to contribute to a more connected and empowered future, harness collective intelligence, embrace environmental responsibility, and democratize the evolution of the dialect between observation and understanding, where the sense of meaning might exist somewhere within this relationship.

>  #VisualsMatter! 


## 👀 Titles in links cited in `Description`:
| **#** | **Title and Link** | **Notes** |
| --- | --- | --- |
| 1 | [Footprints of a Dinosaur](https://tractatus.one/the-quest-for-the-holy-observability-graph-foreword-27d8c4f7c8b5) | ![](https://miro.medium.com/v2/resize:fill:224:224/g:fp:0.29:0.09/1*cwgB2gERTgYo82PJ7rNjAg.jpeg) |
| 2 | [The Quest for the Holy Observability Graph • Part 1](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-1-9d3613e28332) |![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*dBl4n92jl-q1Vs-cCe7F0A.png)  |
| 3 | [Models versus Real-time Architectures](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572) |  ![](https://miro.medium.com/v2/resize:fit:808/format:webp/1*Fne9xoPThjNLve3D1isr4w.png)|
| 4 | [Dynamic TGN Notes](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a) | ![](https://miro.medium.com/v2/resize:fit:1400/0*JSLDSDFIicPb8SN3) |
| 5 | [The Revolution](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-2-51defa4e97d9) | ![](https://miro.medium.com/v2/resize:fit:1002/format:webp/1*moChPG_vYVgunqnnpHNXxQ.jpeg)  |
| 6 | [Beyond Distributed Tracing](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*qhJqHxT3xgPvgOpgzPYbAw.png)  |
| 7 | [Visual Methapors](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*nSrFQvpC4zlVZcpz.jpeg) |
| 8 | [Visual Library Options](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-3-5a8969cff572) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*QY-MGwiyGTWW4UWhoVKPcA.png) |
| 9 | [Visual Library re-review](https://tractatus.one/shahmaran-20a9f1678) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*iHDpuErH8DUVJendtsJ05w.png) |
| 10 | [Observability Experiment on Forgerock OpenAM](https://devrimdemiroz.gitlab.io/post/2021-03-09-observeopenam/) | ![](https://devrimdemiroz.gitlab.io/oidc-authz.svg) |
| 11 | [Service Topology Map from Prometheus metrics](https://tractatus.one/shahmaran-20a9f1678) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*BXUMKn4u-5tdU6noFGXU8w.png) |
| 12 | [o11y octopus](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*V7p2-EfICdEa4iMdsscDqA.png)  |
| 13| [Clowns with Crowns](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a) | ![](https://miro.medium.com/v2/resize:fit:848/format:webp/1*5uhyy-S-MYjfjRgA76vKgw.png)  |
| 14 | [Front End Running One Leg Bleeding ](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*-Mq81wajV5R5qtev539ddw.png)  |
| 15 | [Microservices Caught Between Slides and Coverslips](https://tractatus.one/pathways-metrics-to-traces-55a7d6c8682a) | ![](https://miro.medium.com/v2/resize:fit:1280/1*FhwJko3X-fOxFp_RE8eKpw.gif)  |
| 16 | [Topology Processor](https://github.com/devrimdemiroz/opentelemetry-demo-webstore/blob/shahmaran/src/servicetopology/SpanGraphProcessor.md) | ![](https://github.com/devrimdemiroz/opentelemetry-demo-webstore/raw/shahmaran/src/servicetopology/img.png)  |
| 17 | [Using Pheromones via OpenTelemetry for Efficient Routing in Distributed System](https://tractatus.one/using-pheromones-via-opentelemetry-for-efficient-routing-in-distributed-system-ac163b26382e) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*rxSMGWCDn68lChd7m88txw.png)  |
| 18 | [Collector Pipelines Visual Language](https://tractatus.one/collector-pipelinesvisual-language-26f950c8d22) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*cObFTtFHt8NBlbsN5hDofA.png)  |
| 19 | [Transit Observability Map](https://tractatus.one/transit-observability-map-e73c61a9b9e0) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*DL5HF9zHFjduFD3Fr8q2FQ.png)  |
| 20 | [UCM — Bridging the Requirements/Design Gap](https://tractatus.one/the-quest-for-the-holy-observability-graph-part-1-9d3613e28332) |  ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*W1a4a69e6Knbj93bevx1yQ.png)|
| 21 | [Trace Routes ( Silk, Spice, …)](https://tractatus.one/shahmaran-20a9f1678) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*sxaXYQAr26oeZVJa-k-vug.png)  |
| 22 | [Opencartogaphy](https://tractatus.one/on-the-road-again-84091e77782a) | ![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pwYayJDW9sm2Exar2KMivw.png)  |


