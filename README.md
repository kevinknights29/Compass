# Compass: Golden Path Dev Portal

## Topics

1. [Overview](#overview)
2. [Goals](#goals)
3. [Scope and Context](#scope-and-context)
4. [System Design](#system-design)
5. [Alternatives Considered](#alternatives-considered)
6. [Learning Logs](#learning-logs)
7. [Resources](#resources)

## Overview

Compass is a lightweight, easy-to-use developer portal designed to implement and manage golden paths within an organization. Inspired by Spotify's golden path concept, Compass aims to standardize development practices, accelerate onboarding, and enhance productivity across teams.

![image](https://github.com/user-attachments/assets/18ffbcc2-fa65-4043-b334-f8935f46b0bc)

![image](https://github.com/user-attachments/assets/8386353f-ad72-4db9-bd1e-d2e8529703c7)

## Goals

1. Provide a centralized hub for golden path documentation

2. Streamline the process of creating and maintaining golden paths

3. Reduce technical overhead for teams implementing golden paths

4. Foster knowledge sharing and best practices across the organization

5. Accelerate developer onboarding and reduce time-to-productivity

6. Ensure consistency in development practices across different projects and teams

## Scope and Context

Compass is designed for organizations looking to implement golden paths with minimal technical overhead. It serves as a documentation platform and guide for developers, focusing on:

- Step-by-step tutorials for common development tasks

- Best practices and standardized workflows

- Easy customization and extension for organization-specific needs

The primary audience for Compass is golden path champions - engineers, scientists, or leaders responsible for implementing and driving adoption of golden paths within their organizations.

## System Design

Compass leverages MkDocs and MkDocs-Material to create a responsive, easy-to-use documentation site. The system architecture includes:

- MkDocs as the core static site generator

- MkDocs-Material theme for enhanced UI and functionality

- Markdown-based content for easy authoring and version control

- Python-based setup for straightforward installation and customization

This design allows for a low-barrier entry point while providing a scalable foundation for future enhancements.

## Alternatives Considered

1. **Spotify's Backstage**:

   - Pros: More robust, offers extensive features out-of-the-box

   - Cons: Higher technical overhead, requires JavaScript and web framework knowledge

   - Decision: Opted for a simpler solution to lower the barrier to entry

2. **Custom-built solution**:

   - Pros: Fully tailored to specific needs

   - Cons: Time-consuming to develop, potentially harder to maintain

   - Decision: Chose existing tools (MkDocs) to leverage community support and faster setup

## Learning Logs

| Date | Learning |
|------|----------|
| 2024-09-08 | Identified the need for a simpler alternative to complex dev portals |
| 2024-09-08 | Discovered the effectiveness of MkDocs for creating documentation sites |

## Resources

1. [Spotify Engineering Blog: How We Use Golden Paths to Solve Fragmentation in Our Software Ecosystem](https://engineering.atspotify.com/2020/08/how-we-use-golden-paths-to-solve-fragmentation-in-our-software-ecosystem/)

2. [MkDocs Documentation](https://www.mkdocs.org/)

3. [MkDocs-Material Documentation](https://squidfunk.github.io/mkdocs-material/)
