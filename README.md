# SDLC

# 📊 SDLC — Waterfall Methodology

> **A linear, sequential approach to software development — each phase must fully complete before the next one begins. No going back!**

![SDLC Waterfall Methodology](./assets/sdlc-waterfall.svg)

---

## 📌 What is Waterfall?

The **Waterfall model** is one of the earliest and most straightforward Software Development Life Cycle (SDLC) methodologies. It follows a strict top-down approach where progress flows in one direction — like a waterfall — through clearly defined phases.

---

## 🔄 Stages Flow: One Step at a Time

### 1. 🗂️ Planning
**What are we building?**
- Define project scope & goals
- Estimate time & budget
- Assign team roles & responsibilities
- Feasibility analysis

---

### 2. 📋 Requirements
**What features are needed?**
- Gather all user & business needs
- Produce a **Software Requirements Specification (SRS)** document
- Identify Functional & Non-functional requirements
- Get formal sign-off from the client

---

### 3. 🏗️ System Design
**How will we build it?**
- High-Level Design (HLD) & Low-Level Design (LLD)
- Database schema & API design
- UI/UX wireframes
- Tech stack decisions

---

### 4. 💻 Implementation (Coding)
**Actually writing the code!**
- Developers write code strictly following design documents
- Unit testing done by developers
- Code reviews & commits
- No scope changes allowed at this stage

---

### 5. 🧪 Testing & QA
**Does it work correctly?**
- QA team tests all features
- Types: Unit → Integration → System → UAT
- Bug fix cycles
- User Acceptance Testing (UAT) with real users

---

### 6. 🚀 Deployment
**Go Live to Production!**
- Release to production server
- User training & documentation
- Rollback plan kept ready
- Handover to operations team

---

### 7. 🔧 Maintenance
**Keep it running smoothly!**
- Bug fixes post-release
- Performance tuning
- Security patches & updates
- Feature enhancement requests

---

## 🏠 Real World Analogy: Building a House

```
Lay blueprint  →  Get permits (requirements)  →  Architect draws design
      →  Builders construct  →  Inspector checks  →  Family moves in  →  Annual maintenance
```

Just like constructing a house — you can't pour the foundation before the blueprint is approved, and you can't move in before the inspector signs off.

---

## ✅ Pros of Waterfall

| Advantage | Details |
|-----------|---------|
| 📐 Clear Structure | Easy to understand and follow for all team members |
| 📄 Well Documented | Every stage produces thorough documentation |
| 🎯 Fixed Scope | Works great when all requirements are known upfront |
| 📅 Easy Milestones | Simple to track progress and deadlines |
| 👥 Client Clarity | Client knows exactly what to expect and when |

---

## ❌ Cons of Waterfall

| Disadvantage | Details |
|--------------|---------|
| 🔒 Inflexible | Difficult to accommodate changing requirements |
| 🐛 Late Testing | Bugs are discovered only near the end |
| 👁️ No Early Demo | Client sees working software only at the finish line |
| ⚠️ High Risk | Misunderstood requirements cause costly rework |
| 🔄 No Iteration | No feedback loops between phases |

---

## 🏆 Best Use Cases

Waterfall works best when you can answer **YES** to all 3 questions:
1. Are requirements **fully known** upfront?
2. Will the scope **NOT change** mid-project?
3. Is **heavy documentation** required?

### Industries where Waterfall shines:

| Industry | Examples |
|----------|---------|
| 🏛️ Government Systems | Tax portals, public records, defence software |
| 🏦 Banking & Finance | Core banking, loan processing, payment gateways |
| 🏥 Healthcare & Medical | Hospital mgmt, patient records, medical devices |
| 🏗️ Construction & Engineering | CAD/CAM tools, infrastructure management |
| ✈️ Aerospace & Defence | Flight controls, satellite software, navigation |

---

## ⚖️ Waterfall vs Agile — Quick Comparison

| Factor | Waterfall | Agile |
|--------|-----------|-------|
| Approach | Linear & Sequential | Iterative & Incremental |
| Flexibility | Low — fixed scope | High — welcomes change |
| Client Involvement | Beginning & end only | Continuous collaboration |
| Delivery | Single final delivery | Frequent small releases |
| Documentation | Heavy & detailed | Light & just-in-time |
| Best For | Stable, well-defined projects | Dynamic, evolving projects |
| Risk | Higher (late feedback) | Lower (early feedback) |

---

## 📁 Project Structure (if using this as a template)

```
project-root/
├── README.md
├── assets/
│   ├── sdlc-waterfall.svg       ← Export from Excalidraw (SVG recommended)
│   └── sdlc-waterfall.png       ← PNG fallback
├── docs/
│   ├── requirements.md
│   ├── design.md
│   └── test-plan.md
└── src/
    └── ...
```

---

## 🖼️ How to Update the Diagram

1. Open the Excalidraw canvas
2. Click **Menu → Export image**
3. Export as **SVG** (preferred) or **PNG**
4. Replace the file in `/assets/` folder
5. Commit and push to GitHub

---

## 📚 Further Reading

- [IEEE Software Development Standards](https://www.ieee.org/)
- [SWEBOK — Software Engineering Body of Knowledge](https://www.computer.org/education/bodies-of-knowledge/software-engineering)
- [Agile Manifesto](https://agilemanifesto.org/) ← For when Waterfall isn't the right fit

---

*Diagram created with [Excalidraw](https://excalidraw.com/) — open source, hand-drawn style diagrams.*
