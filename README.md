# Awesome-Subcontractor-Management

Edit
Top Subcontractor Management Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Subcontractor Prequalification, Bid Management, Risk Assessment & Construction Procurement
Last updated: August 2026

This repository tracks notable SaaS/hosted platforms and open-source projects for Subcontractor Management. These tools help general contractors, construction managers, owners, and subcontractors manage prequalification, bidding, bid invitations, vendor risk, compliance, contracts, subcontractor performance, and construction procurement workflows.

Examples include COMPASS by Bespoke Metrics, TradeTapp, BuildingConnected, Procore, SubHub, SmartBid, ConstructConnect, Textura, ConWize, and Pantera Global. COMPASS, for example, focuses on subcontractor prequalification, bidding, performance evaluation, risk tracking, and integrations. TradeTapp provides automated financial reviews, safety assessments, benchmarking, questionnaires, risk scoring, and qualification workflows integrated with BuildingConnected.

Open-source emphasis: Dedicated open-source subcontractor-management platforms are considerably rarer than commercial construction-management products. This section therefore includes the strongest open-source construction ERP, estimating, tendering, bid-management, subcontractor-portal, and procurement building blocks that can be combined into a self-hosted subcontractor-management stack.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Additional Strong Open-Source Options

How to Contribute

Disclaimer

SaaS/Hosted Platforms

COMPASS by Bespoke Metrics
Construction-focused subcontractor prequalification, risk management, bidding, and performance-evaluation platform. Its suite includes COMPASS SRP, COMPASS Eval, COMPASS Pulse, Data Control, and COMPASS Connect.

TradeTapp
Subcontractor qualification and risk-management platform from Autodesk, providing financial reviews, safety assessments, benchmarking, questionnaires, risk scoring, approvals, and qualification data that can be connected with BuildingConnected.

BuildingConnected
Autodesk's construction bid-management network for general contractors and subcontractors, supporting bid invitations, proposal tracking, bid coverage, and preconstruction workflows.

Procore
Construction management platform with preconstruction, bid management, subcontractor management, project financials, contracts, documents, and collaboration capabilities.

SubHub
Construction subcontractor management platform focused on organizing subcontractor information, qualification, compliance, and project relationships.

SmartBid
Construction bid-management platform for general contractors that supports subcontractor database management, bid invitations, bid tracking, communications, and bid leveling.

ConstructConnect
Construction project intelligence and bidding ecosystem providing project information, subcontractor discovery, bid management, and preconstruction workflows. SmartBid is part of the ConstructConnect ecosystem.

Textura
Oracle's construction payment-management platform supporting subcontractor payment applications, compliance, approvals, lien waivers, and payment workflows.

ConWize
Cloud-based construction bidding and estimating platform serving general contractors, developers, subcontractors, and construction management organizations.

Pantera Global
Construction bid and preconstruction platform focused on managing trade packages, subcontractor bidding, bid tracking, and procurement workflows.

Additional Notable SaaS / Hosted Platforms

Autodesk Construction Cloud — Construction platform connecting preconstruction, project management, and field workflows.

Autodesk Forma — Construction and preconstruction ecosystem incorporating BuildingConnected and other Autodesk construction products.

STACK — Cloud construction takeoff and estimating platform that can support subcontractor bidding workflows.

PlanHub — Construction bidding marketplace connecting GCs, subcontractors, suppliers, and project opportunities.

iSqFt — Construction project information and bid-management network within the ConstructConnect ecosystem.

Buildertrend — Construction management platform with estimating, project management, procurement, and subcontractor collaboration.

Contractor Foreman — Construction management suite covering estimating, bids, contracts, scheduling, documents, and subcontractor workflows.

Ressio — Construction estimating and bidding platform for contractors and construction teams.

BidBuddy — AI-assisted construction bidding and bid-management workflow.

Bid Board Pro — BuildingConnected product for subcontractors managing bid opportunities and invitations.

Procore Bid Management — Bid solicitation and subcontractor management functionality within Procore's preconstruction suite.

TradeTapp + BuildingConnected — Combined qualification and bid-selection workflow for evaluating subcontractors before inviting them to bid.

Open-Source GitHub Projects

OpenConstructionERP
Open-source construction ERP and project-management platform with modules spanning estimating, BOQ, tendering, contracts, subcontractors, bid management, suppliers, scheduling, quality, field operations, and reporting. Its architecture makes it one of the strongest open-source foundations for building a broader subcontractor-management system.

OpenConstructionERP — Alternative Repository
Open-source construction ERP focused on BOQ, estimating, BIM/CAD takeoff, 4D/5D planning, tendering, and project management. It can serve as a foundation for custom procurement and subcontractor workflows.

IBSConstructionERP
Open-source construction ERP with modules covering contracts, subcontractors, bid management, supplier catalogs, field operations, resources and crews, scheduling, quality, HSE, and reporting.

OpenConstructionERP / Construction
Open-source construction estimation and project-management platform providing BOQ, 4D/5D planning, AI-assisted estimating, CAD/BIM takeoff, tendering, and construction workflows.

BidSheet
Open-source construction estimating and bidding application aimed particularly at underground utility subcontractors. It runs locally and is licensed under GPLv3, making it useful as a self-hosted estimating/bidding component.

Additional Strong Open-Source Options

OpenConstructionERP — Broadest open-source construction ERP foundation for subcontractor, supplier, tendering, and procurement workflows.

IBSConstructionERP — Construction ERP with explicit subcontractor, supplier, bid-management, and contract modules.

BidSheet — Local-first open-source construction estimating and bidding tool.

OpenConstructionERP — Self-hostable construction ERP with estimating, tendering, project management, and cost-control capabilities.

Construction / OpenConstructionERP — Open-source construction estimation and project-management foundation.

Important distinction: Unlike categories such as CRM, ERP, or workflow orchestration, there are relatively few mature open-source projects that are direct one-for-one replacements for TradeTapp, COMPASS, BuildingConnected, or SmartBid. The strongest open-source approach today is therefore to assemble a system from construction ERP + tendering + estimating + supplier/subcontractor + document-management components rather than treating a generic open-source ERP as a complete subcontractor-risk platform.

Framework for building a custom open-source subcontractor-management platform: Combine OpenConstructionERP/IBSConstructionERP for construction-domain data and workflows, BidSheet for estimating/bidding, PostgreSQL for the system of record, MinIO for self-hosted document storage, Keycloak for identity and RBAC, OpenSearch for subcontractor/project search, and Grafana for risk and procurement dashboards.

A more advanced architecture can add OCR/document extraction, OpenSearch, and an LLM/RAG layer to automatically analyze subcontractor financial statements, insurance certificates, safety documents, licenses, bid proposals, and contract documents. This can approximate portions of commercial prequalification and risk-scoring workflows while keeping the underlying data self-hosted.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Prefer actively maintained projects with a public repository.

Clearly distinguish between fully open-source, source-available, and commercial hosted offerings.

For construction software, specify whether a project primarily handles prequalification, bidding, estimating, procurement, compliance, payments, or general project management.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Subcontractor qualification and risk assessments should be independently validated before making material procurement decisions.

Open-source projects may require substantial customization before they can replace enterprise subcontractor-management platforms.

Construction bidding, insurance, safety, financial, licensing, and compliance data may require appropriate verification and access controls.

Some entries are broader construction-management or ERP platforms rather than dedicated subcontractor-management products.

Commercial product capabilities and ownership can change over time; verify current functionality with the vendor.

Made for general contractors, construction managers, subcontractors, estimators, procurement teams, and construction technologists.
Let's make subcontractor management more open, data-driven, interoperable, and self-hostable.
