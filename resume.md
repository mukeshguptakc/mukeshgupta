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
  <ul style="padding-left:1.1rem;color:var(--text);font-size:0.93rem;display:flex;flex-direction:column;gap:0.45rem;">
    <li>A decade building backend and systems software for enterprise data protection &mdash; distributed storage, snapshots, and cloud-native platforms that ship to real customers at scale.</li>
    <li>Comfortable up and down the stack: system-level C/C++ and Python, microservices on Docker/Kubernetes, event-driven messaging with Kafka and RabbitMQ, and cloud integration across AWS and Azure.</li>
    <li>I take features from first sketch to production &mdash; architecture exploration, multi-vendor API integration, customer POCs, and the occasional hotfix that has to land under a tight deadline.</li>
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
        <li><strong>Qumulo multi-tenancy:</strong> Carried the plugin from legacy V1/V2 to the V3 APIs, designed Tenant-ID-to-VLAN mapping, and reworked the snapshot, export, and deletion flows &mdash; all without breaking existing single-tenant deployments.</li>
        <li><strong>Pure Storage FlashArray File Services:</strong> Integrated the REST 2.x APIs and SDK to make NFS/SMB multi-protocol share deployment dependable.</li>
        <li><strong>Isilon SDK fix:</strong> Traced intermittent snapshot-diff failures to a hardcoded size-validation defect on files over 4&nbsp;GB; patched it and handed QA a tested build within days.</li>
        <li><strong>PowerScale POC:</strong> Stood up a full PowerScale environment in-house and validated SmartConnect (DNS delegation, load balancing, failover) and SMB Multichannel end to end.</li>
        <li><strong>Azure NetApp Files:</strong> Mapped out the ANF architecture and turned the findings into reusable internal guidelines for the team's future backup work.</li>
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
        <li><strong>Cross-vendor NAS enablement:</strong> Built the core APIs that extended NAS (NFS/SMB) support across multiple on-premise storage vendors, and mentored the team on the integration patterns behind them.</li>
        <li><strong>NetApp replication:</strong> Designed a vendor-agnostic replication format; multi-threading the API calls cut discovery time by <strong>over 80%</strong>.</li>
        <li><strong>Snapshot-diff infrastructure:</strong> Built a reusable snapshot-diff framework that bridges a C SDK into Python via ctypes, backed by SQLite.</li>
        <li><strong>SAN consistency-group snapshots:</strong> Standardised the REST payloads across Pure FlashArray, PowerMax, and EMC Unity so multi-volume backups capture a true simultaneous point-in-time.</li>
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
        <li><strong>AWS IAM role-based config:</strong> Implemented instance roles, access keys, and cross-account trust behind a versioned, vendor-agnostic schema so upgrades stayed seamless.</li>
        <li><strong>Licensing module:</strong> Built a Docker-based licensing service (VLIC format) that meters by disk size and supports multiple license types with feature toggles.</li>
        <li><strong>Azure Marketplace:</strong> Took a product through end-to-end publishing &mdash; compliance, packaging, validation, and post-launch support.</li>
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
        <li><strong>Pure Storage integration:</strong> Brought Pure Storage in as a new vendor within CloudPoint, extending snapshot support to its arrays.</li>
        <li><strong>Volume Manager escalations:</strong> Resolved critical multipathing bugs across Linux (RHEL/SUSE), Solaris, and AIX &mdash; the kind that only surface under real customer load.</li>
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
