---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Quantum Computing for Computer Scientists"
subtitle: ""
summary: ""
authors: []
tags: []
categories: ["cs", "physics"]
date: 2019-11-07T20:36:10+01:00
lastmod: 2019-11-07T20:36:10+01:00
featured: false
draft: false
diagram: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


## What would you do?

```mermaid
graph TD
A(Cbits) -->|Superposition| B(Qbits)
B -->|Computation| B
B -->|Measurement| A
style A fill:#f9f
style B fill:#f9f
```

```mermaid
graph LR
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```

```mermaid
sequenceDiagram
  participant Alice
  participant Bob
  Alice->John: Hello John, how are you?
  loop Healthcheck
      John->John: Fight against hypochondria
  end
  Note right of John: Rational thoughts <br/>prevail...
  John-->Alice: Great!
  John->Bob: How about you?
  Bob-->John: Jolly good!
```




