# howardyoung.github.io — Project & Agent Rules

## Overview
This repository contains the source code and deployment configuration for **`howardyoung.github.io`**, an official GitHub Pages web property contributing to the **Knowledge Graph Machine ID (KGMID)** for **Howard O Young**.

---

## Role in KGMID Ecosystem
- **Constituent Web Property**: This site is one of several distributed web endpoints managed under the primary aggregation notes project at `/Users/howard/notes/Projects/Howard O Young KGMID/`.
- **Identity Consistency**: Content, biographical information, social links, and structured metadata on this site must stay strictly synchronized with the master KGMID entity definitions anchored to `https://howardyoung.co/#person`.

---

## Technical Stack & Build Requirements
- **Hosting**: GitHub Pages
- **Deployment**: Deploys static HTML/CSS directly from branch `main`.

---

## Structured Data & SEO Standards
- **JSON-LD Schema Markup**: Include and maintain Schema.org structured data (`Person`, `ProfilePage`, `WebSite`) within `<script type="application/ld+json">`.
- **Entity Signals**: Canonical anchor `https://howardyoung.co/#person`, exact name `Howard O Young`, and `sameAs` array matching the master KGMID registry.
- **Semantic HTML**: Maintain clean, accessible, semantic markup with Open Graph and Twitter Cards.

---

## Agent Guidelines
1. **KGMID Alignment**: When updating personal profiles, contact info, or entity descriptions, verify consistency with the primary KGMID notes project.
2. **Clean Code & Commits**: Write clean, modular markup and provide descriptive commit messages when preparing changes.
