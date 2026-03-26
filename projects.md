---
layout: default
title: Projects
---

<div class="page-header">
  <h1>Projects &amp; Areas of Expertise</h1>
  <p>Themes that define my engineering journey</p>
</div>

<div style="display:flex;flex-direction:column;gap:1.5rem;">

  <!-- Storage -->
  <div class="card project-card">
    <div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
      <span style="font-size:1.4rem;">🗄️</span>
      <h3 style="margin:0;">Enterprise Storage Ecosystem — NAS &amp; SAN Expertise</h3>
    </div>
    <p style="margin-bottom:1rem;">
      Worked deeply across the enterprise storage landscape — not just integrating APIs, but genuinely understanding what makes each vendor's offering unique and how to leverage those strengths to deliver better data protection. Every storage vendor has a distinct architecture and a key USP; the work has always been about mapping those capabilities onto our product in a way that makes the integration feel native, not bolted on.
    </p>
    <p style="margin-bottom:1rem;">
      <strong>Pure Storage FlashArray</strong> — leveraged Managed Directories for granular, VM-level snapshotting; integrated REST 2.x APIs and File Services for NFS/SMB multi-protocol share deployment.<br><br>
      <strong>NetApp</strong> — deep integration across ZAPI, REST, and NMSDK/OCUM APIs; designed vendor-agnostic replication workflows; built snapshot-diff infrastructure using NetApp's V3 diff API bridged into Python via ctypes.<br><br>
      <strong>Dell EMC Isilon / PowerScale</strong> — resolved complex SmartConnect (DNS delegation, load balancing, failover) and SMB Multichannel configurations; built changelist-based incremental backup framework; root-caused and fixed a critical SDK defect affecting files &gt;4 GB.<br><br>
      <strong>Qumulo</strong> — migrated plugin through V1→V2→V3 API lifecycle; designed Tenant-ID-to-VLAN mapping logic for multi-tenant NFS/SMB environments while preserving backward compatibility with single-tenant deployments.<br><br>
      <strong>PowerMax &amp; EMC Unity</strong> — extended snapshot and backup workflows to SAN multi-volume environments, standardising consistency group snapshots across vendors.
    </p>
    <div class="skill-tags">
      <span class="tag">NetApp (ZAPI, REST, NMSDK)</span>
      <span class="tag">Dell EMC Isilon / PowerScale</span>
      <span class="tag">Pure Storage FlashArray</span>
      <span class="tag">Qumulo V1–V3</span>
      <span class="tag">PowerMax / EMC Unity</span>
      <span class="tag">NAS (NFS / SMB)</span>
      <span class="tag">SAN</span>
      <span class="tag">Snapshot Orchestration</span>
      <span class="tag">Incremental Backup</span>
      <span class="tag">Python</span>
      <span class="tag">C / ctypes</span>
    </div>
  </div>

  <!-- Cloud -->
  <div class="card project-card">
    <div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
      <span style="font-size:1.4rem;">☁️</span>
      <h3 style="margin:0;">Cloud Data Protection — Azure &amp; AWS</h3>
    </div>
    <p style="margin-bottom:1rem;">
      Extended data protection capabilities into the cloud by understanding each platform's architecture and working with its native constructs rather than against them. On AWS, this meant implementing IAM role-based configuration with cross-account trust, designing a versioned schema that handled both instance roles and access keys, and managing seamless upgrades without disrupting existing deployments. On Azure, the work spanned both deep technical exploration and end-to-end product delivery.
    </p>
    <p style="margin-bottom:1rem;">
      <strong>Azure NetApp Files (ANF)</strong> — analysed the dedicated ANF infrastructure (distinct from Azure Blob/File), including NetApp Accounts, Capacity Pools, Volumes, and Snapshots; consolidated findings into reusable guidelines for future snapshot and backup workflow support.<br><br>
      <strong>Azure Marketplace Publishing</strong> — delivered end-to-end product publishing: compliance research, customised deployment packaging, thorough validation, post-launch support, and ongoing monitoring to ensure smooth customer adoption.
    </p>
    <div class="skill-tags">
      <span class="tag">Azure (ANF, Marketplace)</span>
      <span class="tag">AWS (IAM, EC2)</span>
      <span class="tag">Cross-Account Trust</span>
      <span class="tag">Cloud-Native Architecture</span>
      <span class="tag">IAM Role-Based Config</span>
      <span class="tag">Python</span>
    </div>
  </div>

  <!-- Mentorship -->
  <div class="card project-card">
    <div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
      <span style="font-size:1.4rem;">🧭</span>
      <h3 style="margin:0;">Guide, Mentor &amp; Always a Learner</h3>
    </div>
    <p style="margin-bottom:1rem;">
      Engineering is as much about growing people and sharing knowledge as it is about writing code. Across my work I've consistently taken ownership of onboarding teammates onto complex integrations — running TOI sessions, leading POC walkthroughs, documenting reusable guidelines, and aligning teams on vendor-specific nuances before they hit a wall.
    </p>
    <p style="margin-bottom:1rem;">
      Led cross-vendor NAS enablement efforts, mentored on SAN replication infrastructure, guided the team through snapshot architecture comparisons (Pure vs. NetApp), and helped build internal knowledge assets that outlasted individual features. At the same time, every new vendor, every new API version, every customer escalation has been an opportunity to learn something non-obvious about how storage systems actually work under the hood.
    </p>
    <div class="skill-tags">
      <span class="tag">Technical Mentorship</span>
      <span class="tag">TOI Sessions</span>
      <span class="tag">POC Delivery</span>
      <span class="tag">Architecture Reviews</span>
      <span class="tag">Documentation</span>
      <span class="tag">Customer Escalations</span>
      <span class="tag">Cross-Functional Collaboration</span>
    </div>
  </div>

</div>
