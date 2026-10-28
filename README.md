<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14532D,16A34A,4ADE80&height=220&section=header&text=Card%20Game%20Architecture%20%28Java%20OOP%29&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Card%20%26%20Dealer%20Distribution%20System%20with%20UML%20Object%20Modeling&descSize=16&descAlignY=62&descAlign=50" width="100%" alt="Card Game Architecture (Java OOP) Header Banner"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/> <img src="https://img.shields.io/badge/Architecture-Object--Oriented%20Design-blue?style=for-the-badge" alt="OOP"/> <img src="https://img.shields.io/badge/UML-Object%20Diagram-green?style=for-the-badge" alt="UML"/>
</p>


## 📌 Table of Contents
- [📖 Executive Summary](#-executive-summary)
- [✨ Key Features & Capabilities](#-key-features--capabilities)
- [🏗️ System Architecture & Workflow](#️-system-architecture--workflow)
- [🛠️ Tech Stack Breakdown](#️-tech-stack-breakdown)
- [⚙️ Reproducible Quickstart & Setup](#️-reproducible-quickstart--setup)
- [📂 Project Directory Layout](#-project-directory-layout)
- [👩‍💻 Author & Contributions](#-author--contributions)

---

## 📖 Executive Summary
### Problem Statement
Simulating multi-player card games requires clean separation of concerns between deck manipulation, card state encapsulation, and dealer shuffle/deal mechanics.

### Motivation & Solution Overview
An Object-Oriented Java simulation modeling card decks, dealers, and game distribution rules alongside verified UML structural object diagrams.

---

## ✨ Key Features & Capabilities
- **Modular Card State:** Models suits, ranks, and numerical values with encapsulation.
- **Dealer Engine:** Manages card shuffling, randomized dealing, and hand distribution.
- **Architectural Diagram:** Object-level visual specification included in repository.

---

## 🏗️ System Architecture & Workflow
```mermaid
classDiagram
    class Card {
        -String suit
        -int rank
        +getSuit()
        +getRank()
    }
    class Dealer {
        -List~Card~ deck
        +shuffle()
        +dealCard()
    }
    class Main {
        +main(args)
    }
    Dealer "1" *-- "52" Card
    Main ..> Dealer
```

---

## 🛠️ Tech Stack Breakdown
| Category | Technologies |
|---|---|
| **Language** | Java (JDK 8+) |
| **Paradigm** | Object-Oriented Programming (OOP) |
| **Documentation** | UML Object Diagram (`object level diagram-card.jpg`) |

---

## ⚙️ Reproducible Quickstart & Setup
### Compilation and Execution
```bash
git clone https://github.com/Bhumikaravi/cardgame-repo.git
cd cardgame-repo
javac *.java
java Main
```

---

## 📂 Project Directory Layout
```text
cardgame-repo/
├── Card.java
├── Dealer.java
├── Main.java
├── object level diagram-card.jpg
└── README.md
```

---

## 👩‍💻 Author & Contributions
Developed by **Bhumika Ravi** ([@Bhumikaravi](https://github.com/Bhumikaravi)), Bachelor of Computer Applications (BCA) at **Alliance University, Bengaluru**.

- 💻 **GitHub Profile:** [github.com/Bhumikaravi](https://github.com/Bhumikaravi)
- 🔗 **LinkedIn:** [linkedin.com/in/bhumika-ravi-b5a01b326](https://www.linkedin.com/in/bhumika-ravi-b5a01b326/)
- 📬 **Email Contact:** [bhumikaravi2006@gmail.com](mailto:bhumikaravi2006@gmail.com)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14532D,16A34A,4ADE80&height=100&section=footer" width="100%" alt="Footer Banner"/>
</p>
