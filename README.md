# 📝 Blogging Platform — Software Requirements Specification (SRS)

![Standard](https://img.shields.io/badge/Standard-IEEE%20830--1998-blue.svg)
![Status](https://img.shields.io/badge/Status-Academic%20Project-brightgreen.svg)
![Type](https://img.shields.io/badge/Type-Documentation%20Only-orange.svg)

A complete **Software Requirements Specification (SRS)** document for a web-based **Blogging Platform**, written in accordance with **IEEE Std 830-1998** (Recommended Practice for Software Requirements Specifications). Developed as a **Software Engineering** course project focused on formal requirements analysis and documentation rather than implementation.

---

## 📋 About This Project

This repository contains a documentation-only deliverable — there is no accompanying source code. The goal of the project was to practice writing a professional, standards-compliant SRS: translating a product idea into precise functional, non-functional, and interface requirements that a real development team could build from.

**Product analyzed:** Blogging Platform — a web-based CMS and social platform allowing users to create, manage, and share blog content, with reader interaction (comments, likes, sharing) and creator analytics.

## 📖 Document Structure

The SRS follows the standard IEEE 830 structure:

| Section | Contents |
|---|---|
| **1. Introduction** | Purpose, scope, intended audience, definitions/acronyms, references |
| **2. Overall Description** | Product perspective, system/user/hardware/software interfaces, product functions, user characteristics, general constraints, assumptions |
| **3. Specific Requirements** | Detailed functional and non-functional requirements, external interface requirements |
| **4. Appendices** | Supplementary references and supporting material |

## ✨ Key Requirements Covered

- **User Account Management** — registration, authentication (incl. MFA), profile management
- **Content Management** — rich-text post creation, editing, multimedia embedding, auto-save drafts, scheduling
- **Content Discovery** — search, tagging/categories, AI-driven recommendations
- **Reader Interaction** — commenting, likes/reactions, social sharing
- **Content Moderation** — admin review panel, user reporting
- **Analytics & Insights** — engagement metrics, demographic analysis, performance trends
- **Notifications** — real-time alerts, subscription updates
- **Accessibility** — responsive design, multi-language support, text-to-speech/high-contrast options
- **Security** — role-based access control, SSL/TLS encryption, regular backups
- **Monetization (optional/premium)** — payment gateway integration, sponsored content, custom domains

## 👥 User Roles Defined

- **Content Creators** — writers/bloggers who create and manage posts
- **Readers** — consume content and engage via comments/likes
- **Administrators** — moderate content and maintain platform health
- **Advertisers** *(optional)* — promote products via sponsored content

## 🛠️ Constraints & Considerations

The document also specifies technical constraints (browser/device compatibility, technology stack flexibility, internet speed dependency), hardware/software interface requirements, memory/scalability estimates, and disaster-recovery expectations.

## 📚 What I Learned

- Structuring formal technical documentation to an established industry standard (IEEE 830)
- Translating a product concept into precise, testable functional and non-functional requirements
- Thinking through a system from multiple user perspectives (creators, readers, admins, advertisers)
- Considering non-functional concerns early — security, scalability, accessibility — rather than as an afterthought

## 📄 File

- [`Blogging_Platform_SRS.pdf`](./Blogging_Platform_SRS.pdf) — full SRS document

## 🎓 Course

Software Engineering — BS Computer Science

## 👩‍💻 Author

**Fatima Nadeem**
BS Computer Science

## 📎 Notes

- This is a documentation-only academic deliverable; no implementation is included
- Written following IEEE Std 830-1998 and referencing IEEE Std 1002-1987
