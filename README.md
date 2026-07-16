<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a1a2e,100:16213e&height=200&section=header&text=Software%20Design%20%26%20Architecture&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Object-Oriented%20Modeling%20%7C%20UML%20Blueprints%20%7C%20Low-Level%20Design&descSize=14&descAlignY=62&descColor=8892b0"/>
  <img alt="header" src="https://capsule-render.vercel.app/api?type=waving&color=0:4776e6,100:8e54e9&height=200&section=header&text=Software%20Design%20%26%20Architecture&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Object-Oriented%20Modeling%20%7C%20UML%20Blueprints%20%7C%20Low-Level%20Design&descSize=14&descAlignY=62&descColor=ffffff"/>
</picture>

<a href="https://www.oracle.com/java/"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/></a>
<a href="https://plantuml.com"><img src="https://img.shields.io/badge/PlantUML-555555?style=for-the-badge&logo=diagrams.net&logoColor=F08705"/></a>
<a href="https://en.wikipedia.org/wiki/Unified_Modeling_Language"><img src="https://img.shields.io/badge/UML%202.5-007ACC?style=for-the-badge"/></a>
<a href="https://en.wikipedia.org/wiki/GRASP_(object-oriented_design)"><img src="https://img.shields.io/badge/GRASP%20Patterns-2ea44f?style=for-the-badge"/></a>

<br/><br/>

<a href="https://readme-typing-svg.demolab.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=8892B0&center=true&vCenter=true&width=600&lines=7+production-domain+systems+designed+end-to-end;56+UML+specification+files+across+all+systems;Class+Models+%C2%B7+State+Machines+%C2%B7+Sequence+Traces;GRASP+%3A+Information+Expert+%C2%B7+Creator+%C2%B7+Controller" alt="Typing SVG" /></a>

</div>

<br/>

<div align="center">

| Paradigm | Scope | Modeling | Artifacts |
|:---:|:---:|:---:|:---:|
| Object-Oriented Design | Low-Level Design (LLD) | UML 2.5 + Graphviz DOT | 56 Specification Files |

</div>

<br/>

## 🗂 System Design Portfolio

> Seven production-domain systems, each modeled end-to-end with a complete UML specification set.

| | System | Domain | Architecture Focus |
|:--:|:--|:--|:--|
| ✈ | **Airline Reservation** | Logistics | Booking workflows · seat allotment · check-in flows |
| 🛒 | **Supermarket System** | Retail | Cart checkout · payment gateways · stock replenishment |
| 🏙 | **Smart City System** | IoT & Infrastructure | Sensor networks · emergency dispatch · waste routing |
| 🎓 | **Student Management** | Administration | Course registration · transcripts · timetabling |
| 🚂 | **Railway Reservation** | Public Transit | Route maps · PNR tracking · seat upgrades |
| 💳 | **Point of Sale (POS)** | FinTech | Barcode scanning · cashier sessions · EOD reconciliation |
| 🏧 | **ATM System** | FinTech Hardware | PIN verification · cash dispensing · card retention |

Each system directory ships with:

```
use-case-diagram.md         →  Actor-system boundary interactions
use-case-description.md     →  Main flows + alternative flows
class-diagram.md            →  Class hierarchy, relationships, visibility
sequence-diagram.md         →  Chronological message traces
collaboration-diagram.md    →  Object communication and numbering
activity-diagram.md         →  Swimlane control-flow charts
state-chart-diagram.md      →  Object lifecycle state machines
```

<br/>

## ☕ Lab Implementations

| Lab | Focus | Concepts |
|:--:|:--|:--|
| 1 | Algorithms | Bubble sort · matrix ops · prime sieves |
| 2 | Class Design | Constructors · `this` reference · static members |
| 3 | Inheritance | Superclass/subclass hierarchies · composition |
| 4 | Interfaces & Packages | Abstract classes · custom package routing |
| 5 | Data Structures | Generic stacks · date validation |
| 6 | Concurrency | Producer-Consumer · multithreaded matrix sums |
| 7 | Generics | Bounded type parameters · generic methods |
| 8 | GUI | Swing desktop apps — calculator · login form |

<br/>

## ⚙ Usage

<details>
<summary><b>Render UML Diagrams</b></summary>
<br/>

**VS Code** — Install the [PlantUML extension by Jebbs](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml), open any `.md` file, press `Alt + D`.

**Web** — Paste the PUML block into [plantuml.com/plantuml](https://plantuml.com/plantuml).

> Collaboration diagrams use Graphviz DOT syntax inside `@startdot` / `@enddot` tags.

</details>

<details>
<summary><b>Compile & Run Java Labs</b></summary>
<br/>

```bash
cd labs/lab-part1
javac BubbleSort.java
java BubbleSort
```

Requires JDK 17 or above.

</details>

<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d0d0d&height=100&section=footer"/>
  <img alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:8e54e9,100:4776e6&height=100&section=footer"/>
</picture>
</div>
