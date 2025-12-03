# EnrichFlow

**EnrichFlow** is a comprehensive automation and full-stack project designed to streamline the process of fetching and enriching contact data.

## Project Overview

The core objective of this project is to build a premium **Next.js Dashboard** where users can input an Apollo Search URL. The system then automates the backend processes using **n8n** to:
1.  Fetch contacts from Apollo.
2.  Enrich these contacts using a "Waterfall" method via multiple services: **LeadMagic**, **IcyPeas**, **FindyMail**, and **FullEnrich**.
3.  Store and display the enriched data in the dashboard for export.

The project leverages **Supabase** for authentication and database management, ensuring a secure and scalable foundation.

## Repository Structure & Documentation

This repository contains the strategic roadmap and technical requirements for building EnrichFlow.

### 1. [Project Plan](./project_plan.md)
This file serves as the master schedule and budget tracker for the development.
*   **Timeline**: A detailed 15-day breakdown of tasks.
*   **Milestones**: Divided into 4 key phases (Frontend, Auth/DB, Automation, Handover).
*   **Budget**: Allocation of the $800 budget across milestones.

### 2. [Tools & Requirements](./tools_requirements.md)
This file outlines the technical prerequisites and infrastructure needed to execute the project.
*   **Tech Stack**: Details on Next.js, Tailwind CSS, Shadcn/UI, and Supabase.
*   **Hosting**: Options for deploying the frontend (Vercel) and the n8n automation engine (Render/Railway/Cloud).
*   **API Keys**: A list of the user-provided APIs required for the waterfall enrichment logic.

## Getting Started

To begin development, please review the **[Tools & Requirements](./tools_requirements.md)** to ensure all necessary accounts and environments are set up. Then, follow the daily schedule outlined in the **[Project Plan](./project_plan.md)**.
