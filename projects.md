---
layout: default
title: Projects
---

<div class="page-header">
  <h1>What I've <span>built</span></h1>
  <p>Three threads that run through my work &mdash; less a feature list, more how I approach the problems.</p>
</div>

<div class="project-card">
  <h3>🗄️&nbsp; Storage, vendor by vendor</h3>
  <p>Enterprise storage isn't one thing &mdash; it's a dozen products that each draw their own boundaries. The craft is learning where a vendor is strong and building to that strength, so the integration feels native instead of bolted on. Over the years I've gone deep on most of the major arrays:</p>
  <p>
    <strong>Pure Storage FlashArray</strong> &mdash; used Managed Directories to snapshot at VM-level granularity, and wired up REST 2.x and File Services for multi-protocol NFS/SMB shares.<br><br>
    <strong>NetApp</strong> &mdash; worked across ZAPI, REST, and NMSDK; designed a vendor-agnostic replication format; and built snapshot-diff infrastructure that pulls NetApp's V3 diff API into Python through a C bridge.<br><br>
    <strong>Dell EMC Isilon / PowerScale</strong> &mdash; got SmartConnect behaving (DNS delegation, load balancing, failover) alongside SMB Multichannel, built a changelist-based incremental backup framework, and chased down a nasty SDK defect that quietly broke files over 4&nbsp;GB.<br><br>
    <strong>Qumulo</strong> &mdash; carried the plugin through three API generations (V1 → V2 → V3) and designed Tenant-ID-to-VLAN mapping for multi-tenant deployments, without breaking the single-tenant customers already in production.<br><br>
    <strong>PowerMax &amp; EMC Unity</strong> &mdash; stretched snapshot and backup workflows onto SAN multi-volume setups and standardised consistency-group snapshots so a point-in-time backup means the same thing across vendors.
  </p>
  <div class="skill-tags">
    <span class="tag">NetApp</span>
    <span class="tag">Dell EMC Isilon / PowerScale</span>
    <span class="tag">Pure Storage</span>
    <span class="tag">Qumulo</span>
    <span class="tag">PowerMax / Unity</span>
    <span class="tag">NAS (NFS / SMB)</span>
    <span class="tag">SAN</span>
    <span class="tag">Python</span>
    <span class="tag">C / ctypes</span>
  </div>
</div>

<div class="project-card">
  <h3>☁️&nbsp; Data protection, into the cloud</h3>
  <p>Moving backup into the cloud goes wrong when you fight the platform. It goes right when you lean on its native building blocks. I've taken that approach on both major clouds:</p>
  <p>
    <strong>AWS</strong> &mdash; built IAM role-based configuration with cross-account trust, and a versioned schema that handles both instance roles and access keys &mdash; so existing customers upgraded cleanly, with nothing breaking underneath them.<br><br>
    <strong>Azure NetApp Files (ANF)</strong> &mdash; mapped out ANF's dedicated infrastructure (Accounts, Capacity Pools, Volumes, Snapshots), which behaves quite differently from ordinary Azure storage, and turned what I learned into reusable guidelines for the team's future backup work.<br><br>
    <strong>Azure Marketplace</strong> &mdash; shepherded a product through end-to-end publishing: compliance, deployment packaging, validation, and the post-launch support that keeps customers happy after day one.
  </p>
  <div class="skill-tags">
    <span class="tag">Azure (ANF, Marketplace)</span>
    <span class="tag">AWS (IAM, EC2)</span>
    <span class="tag">Cross-Account Trust</span>
    <span class="tag">Cloud-Native Architecture</span>
    <span class="tag">Python</span>
  </div>
</div>

<div class="project-card">
  <h3>🧭&nbsp; Sharing what I learn</h3>
  <p>The best code I've written outlived me on a project; the best knowledge I've shared outlived the feature it came from. I've consistently taken on onboarding teammates onto gnarly integrations &mdash; running knowledge-transfer sessions, leading POC walkthroughs, and writing down the vendor-specific gotchas before someone hits them at 2&nbsp;a.m.</p>
  <p>I've led cross-vendor NAS enablement, mentored on SAN replication, and guided the team through snapshot-architecture trade-offs (Pure vs. NetApp is a fun one). And I'm still on the receiving end of that learning every time a new API version or customer escalation shows me something I didn't know.</p>
  <div class="skill-tags">
    <span class="tag">Technical Mentorship</span>
    <span class="tag">Knowledge Transfer</span>
    <span class="tag">POC Delivery</span>
    <span class="tag">Architecture Reviews</span>
    <span class="tag">Documentation</span>
    <span class="tag">Customer Escalations</span>
  </div>
</div>
