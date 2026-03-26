---
layout: default
title: Resume
---

<div class="resume-header">
  <div>
    <div class="resume-name">Mukesh Gupta</div>
    <div class="resume-title">Member of Technical Staff III (MTS-III) &mdash; Storage, Distributed Systems &amp; Backend Platform</div>
  </div>
  <a href="https://www.linkedin.com/in/mukesh-gupta-847a54105/" target="_blank" rel="noopener" class="btn btn-outline">LinkedIn Profile &rarr;</a>
</div>

<div class="resume-note">
  Contact details are intentionally omitted. Reach out via
  <a href="https://www.linkedin.com/in/mukesh-gupta-847a54105/" target="_blank" rel="noopener">LinkedIn</a>.
</div>

<div class="resume-section">
  <div class="resume-section-title">Summary</div>
  <ul style="padding-left:1.2rem;color:var(--muted);font-size:0.95rem;">
    <li style="margin-bottom:0.6rem;">9+ years of backend and systems engineering, specialising in distributed storage, data protection, and cloud-native platform development across enterprise-scale products.</li>
    <li style="margin-bottom:0.6rem;">Delivered production features spanning microservices (Docker/Kubernetes), event-driven messaging (Kafka, RabbitMQ), cloud platforms (AWS, Azure), and system-level C/C++ and Python development.</li>
    <li>Proven track record owning the full engineering lifecycle: architecture exploration, multi-vendor API integration, customer POC delivery, and hotfix turnaround under aggressive timelines.</li>
  </ul>
</div>

<div class="resume-section">
  <div class="resume-section-title">Experience</div>
  <div class="timeline">

    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">Member of Technical Staff III (MTS-III)</div>
          <div class="timeline-org">Cohesity NetBackup</div>
        </div>
        <div class="timeline-date">Dec 2024 &ndash; Present &bull; Pune</div>
      </div>
      <ul>
        <li><strong>Qumulo Multi-Tenancy:</strong> Migrated plugin from legacy V1/V2 to V3 APIs, designed Tenant-ID-to-VLAN mapping, refactored snapshot/export/deletion flows preserving backward compatibility.</li>
        <li><strong>Pure Storage FlashArray File Services:</strong> Integrated REST 2.x APIs and SDK enabling reliable NFS/SMB multi-protocol share deployment.</li>
        <li><strong>Isilon SDK Bug Fix:</strong> Root-caused snapshot-diff failures to a hardcoded size-validation defect (&gt;4 GB files), patched and delivered tested build to QA within days.</li>
        <li><strong>PowerScale POC:</strong> Simulated full PowerScale environment in-house; validated SmartConnect DNS delegation, load balancing, failover, and SMB Multichannel.</li>
        <li><strong>Azure NetApp Files:</strong> Analysed ANF architecture; consolidated findings into reusable internal guidelines for future backup workflow support.</li>
      </ul>
    </div>

    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">Senior Software Engineer</div>
          <div class="timeline-org">Veritas Technologies</div>
        </div>
        <div class="timeline-date">Mar 2022 &ndash; Nov 2024 &bull; Pune</div>
      </div>
      <ul>
        <li><strong>Cross-Vendor NAS Enablement:</strong> Implemented core APIs to extend NAS (NFS/SMB) support across multiple on-premise storage vendors; mentored team on integration patterns.</li>
        <li><strong>NetApp Replication:</strong> Designed vendor-agnostic replication format; multi-threaded API handling improved discovery performance by <strong>over 80%</strong>.</li>
        <li><strong>Snapshot Diff Infrastructure:</strong> Built reusable snapshot-diff framework bridging C SDK into Python via ctypes, backed by SQLite.</li>
        <li><strong>SAN Consistency Group Snapshots:</strong> Standardised REST API payloads across Pure FlashArray, PowerMax, and EMC Unity for simultaneous point-in-time backups.</li>
      </ul>
    </div>

    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">Software Engineer</div>
          <div class="timeline-org">Veritas Technologies</div>
        </div>
        <div class="timeline-date">Jun 2019 &ndash; Mar 2022 &bull; Pune</div>
      </div>
      <ul>
        <li><strong>AWS IAM Role-Based Config:</strong> Implemented instance roles, access keys, and cross-account trust with versioned vendor-agnostic schema.</li>
        <li><strong>Licensing Module:</strong> Built Docker-based licensing service (VLIC format), metering by disk size, multiple license types with feature toggles.</li>
        <li><strong>Azure Marketplace:</strong> Delivered end-to-end product publishing &mdash; compliance, packaging, validation, post-launch support.</li>
      </ul>
    </div>

    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">Associate Software Engineer</div>
          <div class="timeline-org">Veritas Technologies</div>
        </div>
        <div class="timeline-date">Jan 2016 &ndash; May 2019 &bull; Pune</div>
      </div>
      <ul>
        <li><strong>Pure Storage Integration:</strong> Extended snapshot support for Pure Storage as a new vendor within CloudPoint.</li>
        <li><strong>Volume Manager Escalations:</strong> Resolved critical multipathing bugs across Linux (RHEL/SUSE), Solaris, and AIX.</li>
      </ul>
    </div>

  </div>
</div>

<div class="resume-section">
  <div class="resume-section-title">Education</div>
  <div class="timeline">
    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">PG Diploma in Embedded Systems and Design</div>
          <div class="timeline-org">Sunbeam CDAC ACTS, Pune</div>
        </div>
        <div class="timeline-date">2015</div>
      </div>
    </div>
    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">B.E. in Electronics and Communication</div>
          <div class="timeline-org">Leelavati Awhad Institute of Engineering, Mumbai University</div>
        </div>
        <div class="timeline-date">2014</div>
      </div>
    </div>
    <div class="timeline-entry">
      <div class="timeline-header">
        <div>
          <div class="timeline-title">Diploma in Electronics and Communication</div>
          <div class="timeline-org">S. S. Jondhle Polytechnic, Maharashtra State Board</div>
        </div>
        <div class="timeline-date">2011</div>
      </div>
    </div>
  </div>
</div>

<div class="resume-section">
  <div class="resume-section-title">Skills</div>
  <div class="skill-tags">
    <span class="tag tag-blue">Python</span>
    <span class="tag tag-blue">C / C++</span>
    <span class="tag tag-blue">Shell Scripting</span>
    <span class="tag tag-blue">Go</span>
    <span class="tag tag-purple">Docker</span>
    <span class="tag tag-purple">Kubernetes</span>
    <span class="tag tag-green">Kafka</span>
    <span class="tag tag-green">RabbitMQ</span>
    <span class="tag tag-orange">AWS (IAM, EC2)</span>
    <span class="tag tag-orange">Azure</span>
    <span class="tag tag-orange">GCP</span>
    <span class="tag tag-cyan">NetApp (ZAPI, REST)</span>
    <span class="tag tag-cyan">Dell EMC Isilon / PowerScale</span>
    <span class="tag tag-cyan">Pure Storage FlashArray</span>
    <span class="tag tag-cyan">Qumulo</span>
    <span class="tag tag-cyan">NAS / SAN</span>
    <span class="tag tag-red">Snapshot Orchestration</span>
    <span class="tag tag-red">Incremental Backup</span>
    <span class="tag tag-green">Microservices</span>
    <span class="tag tag-green">REST API Design</span>
    <span class="tag tag-purple">Linux (RHEL/SUSE)</span>
    <span class="tag tag-blue">SQLite</span>
    <span class="tag tag-blue">Git</span>
  </div>
</div>
