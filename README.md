# Awesome-Cloud-Cold-Storage-Data-Archiving 🧊 🗄️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Cold Storage Data Archiving Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Cold Storage & Data Archiving Ecosystem

**Curated List of Commercial Archival Platforms & Open-Source Cold Storage Tools**  
*Focused on Long-Term Retention, Retrieval Cost Optimization, Immutable Archives, Tape Integration & Self-Hosted Object Storage* 🧊

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary 🔍

Welcome to the ultimate curated directory of **cloud cold storage platforms**, **open-source archival storage systems**, and **data preservation frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS S3 Glacier*, *Azure Archive Blob Storage*, *Google Cloud Archive*, *Wasabi*, and *Backblaze B2*), or self-hostable open-source alternatives (like *MinIO*, *Ceph*, *rclone*, *restic*, and *BorgBackup*), this list covers category leaders, immutable archive strategies, tape libraries, and privacy-respecting long-term retention tools.

---

## 📑 Table of Contents 📖

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms 🌐

> 💡 **Market Size & Structure**: The global cloud data archiving and cold storage market is estimated at **$7.5 Billion to $10.2 Billion**, growing at a **17.4% CAGR**. The market is **highly concentrated** among hyperscale cloud leaders (*Microsoft*, *Amazon AWS*, *Alphabet/Google*) which hold over 65% market share due to infrastructure lock-in and egress economics, alongside specialized niche storage providers (*Iron Mountain*, *Wasabi*, *Backblaze*).

The cold storage and archiving market spans **hyperscaler archive tiers** (Glacier, Azure Archive, GCP Archive) that charge ultra-low storage rates but impose retrieval fees and minimum retention durations, and **flat-rate providers** (Wasabi, Backblaze B2) that eliminate egress fees and retrieval delays.

| SaaS / Commercial Platform | Company / Owner | Market Cap / Valuation 📈 | Standard Edition Starting Price 💰 | Free Tier / Free Trial Limits 🎁 | Description 📝 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Archive Blob Storage](https://azure.microsoft.com/en-us/products/storage/blobs/)** 🔷 | Microsoft | **~$3.90 Trillion** | **$0.00099/GB-month** ($0.02/GB retrieval) | **5 GB LRS Hot storage free for 12 months** | **Azure-native cold storage** — **Rehydration takes up to 15 hours**. **Minimum retention: 180 days**. Early deletion penalties apply. |
| **[Amazon S3 Glacier](https://aws.amazon.com/s3/storage-classes/glacier/)** ☁️ | Amazon | **~$2.0 Trillion** | **Deep Archive: $0.00099/GB-month** ($0.0025/GB retrieval) | **10 GB Glacier storage free for 12 months** | **AWS-native cold storage** — Three tiers: Instant Retrieval (ms), Flexible Retrieval (min–12 hrs), Deep Archive (12–48 hrs). **Minimum retention: 90–180 days**. |
| **[Google Cloud Archive Storage](https://cloud.google.com/storage/docs/storage-classes)** 🌐 | Google (Alphabet) | **~$2.0 Trillion** | **$0.0012/GB-month** ($0.05/GB retrieval) | **$300 free credits valid for 90 days** for new accounts | **GCP-native cold storage** — Designed for data accessed less than once per year. **Minimum storage duration: 365 days**. |
| **[Iron Mountain Cloud Archive](https://www.ironmountain.com/)** 🏔️ | Iron Mountain | **~$10 Billion** | **$0.004/GB-month** ($0.015/GB retrieval) | **30-day free enterprise proof-of-concept trial** | **Managed enterprise archive** — Physical tape and cloud archive integration. **Compliance-focused** for healthcare and financial sector. |
| **[Quantum ActiveScale](https://www.quantum.com/)** ⚛️ | Quantum | **~$500 Million** | **$0.003/GB-month** (on-prem software sub) | **30-day virtual appliance software trial** | **Object storage & archive** — **Scales to exabytes**. Designed for long-term data preservation with object lock immutability. |
| **[Wasabi Hot Cloud Storage](https://wasabi.com/)** 🟢 | Wasabi Technologies | **$1.1 Billion** (Private) | **$0.0069/GB-month** (no egress / API fees) | **30-day free trial up to 1 TB** | **Flat-rate cloud storage** — **No egress fees, no retrieval fees**. **90-day minimum retention**. **S3-compatible** with immediate access. |
| **[CTERA Cloud Archive](https://www.ctera.com/)** 📁 | CTERA Networks | **$300 Million** (Private) | **$1,000/month** ($12,000/year base platform) | **30-day free trial up to 5 TB** | **Edge-to-cloud file services** — Hybrid cloud file platform with automated tiering to cold cloud storage. |
| **[Scality ARTESCA](https://www.scality.com/artesca/)** 🏗️ | Scality | **$250 Million** (Private) | **$3.80/TB-month** ($0.0037/GB-month) | **Free tier: 5 TB full-feature capacity forever** | **Software-defined object storage** — Light-footprint S3 object storage for cloud-native apps, backup, and cold archiving. |
| **[Backblaze B2 Archive](https://www.backblaze.com/cloud-storage)** 🔵 | Backblaze | **$120 Million** | **$0.006/GB-month** ($0.01/GB egress) | **10 GB storage free forever** (+ 1 GB daily download) | **Simple cloud storage** — **No minimum retention duration**. S3-compatible. **Cloudflare integration eliminates egress fees**. |
| **[Spectra Logic BlackPearl](https://spectralogic.com/)** 🎞️ | Spectra Logic | **$100 Million** (Private) | **$0.0038/GB-month** (5-year TCO scale) | **30-day interactive demo & lab trial** | **On-premises digital archive** — **Ransomware-resilient** with virtual air gaps, immutable snapshots, and offline tape copies. |

---

## 🔓 Open-Source GitHub Projects 🚀

*Sorted by GitHub Stars_Count (Descending)* 🌟

- **[MinIO](https://github.com/minio/minio)** [![Stars](https://img.shields.io/github/stars/minio/minio?style=social&color=white)](https://github.com/minio/minio/stargazers) 🎯  
  **High-performance S3-compatible object storage**, AGPL-3.0 licensed. **Single binary deployment** — runs on bare metal, Kubernetes, or edge nodes. **Erasure coding, bit-rot protection, server-side encryption**, and **S3 Select** for fast data filtering.

- **[rclone](https://github.com/rclone/rclone)** [![Stars](https://img.shields.io/github/stars/rclone/rclone?style=social&color=white)](https://github.com/rclone/rclone/stargazers) 🔗  
  **The Swiss army knife of cloud storage sync**, MIT licensed. **Supports 70+ cloud storage providers** including AWS Glacier, Azure Blob, GCP, B2, and Wasabi. **Sync, copy, move, mount, encryption, and lifecycle automation** between hot and cold tiers.

- **[Nextcloud](https://github.com/nextcloud/server)** [![Stars](https://img.shields.io/github/stars/nextcloud/server?style=social&color=white)](https://github.com/nextcloud/server/stargazers) ☁️  
  **Self-hosted content collaboration platform**, AGPL-3.0 licensed. **File synchronization and sharing** with **external storage support** for S3, SMB, and FTP backends. Features server-side encryption and retention policies.

- **[restic](https://github.com/restic/restic)** [![Stars](https://img.shields.io/github/stars/restic/restic?style=social&color=white)](https://github.com/restic/restic/stargazers) ⚡  
  **Fast, secure, efficient backup program**, BSD-2-Clause licensed. **Single binary tool**, supports S3, GCS, Azure, B2, SFTP, and REST backends. Features **AES-256 encryption, deduplication**, and incremental snapshots ideal for cold archives.

- **[Ceph](https://github.com/ceph/ceph)** [![Stars](https://img.shields.io/github/stars/ceph/ceph?style=social&color=white)](https://github.com/ceph/ceph/stargazers) 🐙  
  **The most widely deployed open-source distributed storage platform**, LGPL-2.1 / GPL-2.0 / BSD licensed. **Unified object, block, and file storage** from commodity hardware clusters. **RADOS Gateway** delivers S3 compatibility with erasure coding for archival storage.

- **[Seafile](https://github.com/haiwen/seafile)** [![Stars](https://img.shields.io/github/stars/haiwen/seafile?style=social&color=white)](https://github.com/haiwen/seafile/stargazers) 🗂️  
  **High-performance file sync and share system**, AGPL-3.0 licensed. **Delta sync** for fast file transfer, library encryption, version control, and support for S3/Ceph object storage backends.

- **[Duplicati](https://github.com/duplicati/duplicati)** [![Stars](https://img.shields.io/github/stars/duplicati/duplicati?style=social&color=white)](https://github.com/duplicati/duplicati/stargazers) 🔐  
  **Encrypted backup client for cloud storage**, LGPL-2.1 licensed. Stores encrypted, incremental, compressed backups on 20+ providers including **S3 Glacier, Azure Archive, Google Cloud, and B2**. Web UI and CLI included.

- **[Kopia](https://github.com/kopia/kopia)** [![Stars](https://img.shields.io/github/stars/kopia/kopia?style=social&color=white)](https://github.com/kopia/kopia/stargazers) 🛡️  
  **Fast and secure open-source backup tool**, Apache-2.0 licensed. Features **end-to-end encryption, deduplication, compression**, and policy-driven snapshot retention over cloud cold storage.

- **[BorgBackup](https://github.com/borgbackup/borg)** [![Stars](https://img.shields.io/github/stars/borgbackup/borg?style=social&color=white)](https://github.com/borgbackup/borg/stargazers) 📦  
  **Deduplicating archiver program**, BSD-3-Clause licensed. **Authenticated encryption, compression (LZ4, ZSTD), chunk-level deduplication**, and efficient remote backup capabilities.

- **[Duplicacy](https://github.com/gilbertchen/duplicacy)** [![Stars](https://img.shields.io/github/stars/gilbertchen/duplicacy?style=social&color=white)](https://github.com/gilbertchen/duplicacy/stargazers) 💾  
  **Lock-free deduplicating cloud backup tool**, source-available / open-source core. Multi-client deduplication across cloud storage services including S3, B2, Azure, and Google Drive.

- **[Bareos](https://github.com/bareos/bareos)** [![Stars](https://img.shields.io/github/stars/bareos/bareos?style=social&color=white)](https://github.com/bareos/bareos/stargazers) 📼  
  **Cross-network open-source data backup & recovery solution**, AGPL-3.0 licensed. Specialized in enterprise archiving across disk, cloud, and physical tape libraries (LTO tape support).

- **[s3ql](https://github.com/s3ql/s3ql)** [![Stars](https://img.shields.io/github/stars/s3ql/s3ql?style=social&color=white)](https://github.com/s3ql/s3ql/stargazers) 🗄️  
  **Full-featured file system for online data storage**, GPL-3.0 licensed. Presents S3, Google Storage, or OpenStack backends as an infinite-capacity hard disk with compression, deduplication, and snapshots.

- **[Ferro](https://github.com/WyattAu/ferro)** [![Stars](https://img.shields.io/github/stars/WyattAu/ferro?style=social&color=white)](https://github.com/WyattAu/ferro/stargazers) 🦀  
  **High-performance self-hosted file storage platform**, open-source. **Rust-based** with WebDAV, S3, OIDC, WASM, full-text search, and snapshot management.

---

## 🛠️ How to Contribute 🤝

Contributions are welcome! Follow these steps to submit new cold storage platforms or open-source archival software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 🤝 Support & Sponsorship 💖

Thank you for exploring and using this curated cloud cold storage & data archiving directory! If you find this project valuable, please consider supporting its continued maintenance and curation:

- ⭐ **Star** this repository to increase visibility and help other engineers find it!
- 🔀 **Fork** and share with fellow storage engineers, compliance officers, and open-source advocates.
- ☕ **Buy Me a Coffee / Sponsor**: Support ongoing open-source curation directly via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer ℹ️

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Retrieval fees dominate cold storage TCO for frequently accessed data**: AWS Glacier Deep Archive charges **$0.0025/GB retrieval** plus **$0.09/GB egress** if restoring outside AWS. A **100TB restore costs ~$11,000** in retrieval and egress fees alone. **Wasabi and Backblaze B2 eliminate these fees** — Wasabi's free egress and B2's Cloudflare integration make them cheaper for DR workloads with periodic restore testing.
- **Minimum retention penalties apply**: AWS Deep Archive requires **180-day minimum retention**; Wasabi requires **90 days**. Deleting data early still incurs charges as if the data remained for the full period.
- **Tape remains the cheapest long-term archive**: Spectra on-premises tape archive costs **$0.0038/GB/month** over 5 years vs **$0.012/GB/month** for cloud storage — a **~3x cost advantage** at 5PB scale. Tape also provides **physical air gap** for ransomware resilience that cloud immutability cannot replicate.
- Open-source solutions (Ceph, MinIO, s3ql, restic, BorgBackup) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, managed infrastructure, and tape library automation remain primarily commercial offerings. **Always model retrieval costs against your actual access patterns** before committing to a cold storage tier. 🧊

---

## Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Cold-Storage-Data-Archiving&type=date&legend=top-left)

---

<p align="center">
  <b>Made with ❤️ for storage engineers, compliance officers, and open-source archival advocates.</b>
</p>
