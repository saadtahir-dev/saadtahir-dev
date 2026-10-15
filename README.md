<div align="center">

# Saad Tahir

**Senior Software Engineer** — iOS, macOS & Swift

+92 325 6050085 | [saad.tahir.dev@gmail.com](mailto:saad.tahir.dev@gmail.com) | [linkedin.com/in/saadtahir-dev](https://linkedin.com/in/saadtahir-dev)

</div>

Senior iOS & macOS engineer with 5+ years building production software across security, enterprise, logistics, and digital forensics. Specialized in Swift, SwiftUI, UIKit, macOS system APIs, concurrency, networking, and modular architecture.

## About

Currently engineering RECON LAB, RECON ITR, and RECON IMAGER at PureLogics for [SUMURI](https://sumuri.com), owning macOS forensic workflows across evidence acquisition, filesystem processing, indexing, analysis, and reporting. Background spans Network Extension, Per-App VPN, and MDM work, legacy Objective-C modernisation, and wrapping native C/C++ libraries as Swift Packages on Apple Silicon.

**Education:** Master of IT (Cyber Security), Western Sydney University · BS Computer Science, FAST-NUCES

## Skills

| | |
|---|---|
| **Languages** | Swift, SwiftUI, Objective-C, UIKit |
| **Platforms** | iOS, macOS, Apple Silicon |
| **Concurrency** | Swift Concurrency, async/await, Actors, GCD, Instruments |
| **macOS & Systems** | Network Extension, Per-App VPN, MDM, Disk Arbitration, hdiutil, macFUSE, APFS, Filesystem APIs, Privileged Operations |
| **Architecture** | Clean Architecture, MVVM, Modular SPM, Repository Pattern, Protocol-Oriented Programming |
| **Data** | SQLite, GRDB, Core Data, SwiftData, REST APIs, Database Indexing |
| **Forensics** | E01/EWF, VMDK, VHD/VHDX, AFF4, dtSearch, libewf, libpff, ExifTool |
| **Testing** | XCTest, Unit & Integration Testing, Code Review |
| **AI Tools** | Claude Code, Cursor, Codex |
| **Delivery** | Xcode, Git, CI/CD, Fastlane, App Store Connect, Firebase, Stripe |

## Projects

### Forensics (SUMURI)

**[RECON LAB](https://sumuri.com/product/recon-lab/)** — In Development  
Native macOS forensic analysis suite.
- Evidence-indexing pipeline for forensic images, mounted volumes, logical captures, iTunes/Cellebrite/GrayKey iOS and Android backups, and Google Takeout.
- Streaming SQLite ingestion with Swift actors, bounded batches, and serialized writers to process large datasets without loading full result sets into memory.
- Forensic image mounting for E01/EWF, VMDK, VHD/VHDX, AFF4, DMG, RAW, and split-RAW via hdiutil, macFUSE, and native libraries.
- Email-container parsing, attachment extraction, and dtSearch full-text indexing.
- Project VIC workflows: VICS import, MD5/SHA1 matching, deduplication, and VICS 2.0 export.

**[RECON ITR](https://sumuri.com/software/recon-itr/)** — Released  
macOS forensic imaging, triage, and reporting suite for Apple Silicon and Intel Macs, used in 40+ countries.
- Privileged filesystem access for collection across large directory structures.
- DMG and sparse-image case export with metadata-free evidence copying and optional MD5/SHA1 hashing.
- Unified macOS log collection with privilege elevation, cancellation, and typed failure states.
- File Timeline pipeline turning filesystem metadata into timestamped forensic events.
- Shared reporting architecture for PDF, CSV, and KML output.

**[RECON IMAGER](https://sumuri.com/software/recon-itr/)** — Released  
Forensic imaging utility for Mac acquisition.
- Bootable and live acquisition of APFS volumes.
- Logical images and volatile-data capture.

### Applications

**DeliverMeat Ecosystem** — Released  
Three-app Swift/UIKit commerce ecosystem, built independently.
- Consumer, Driver, and Partner apps covering ordering, fulfillment, and merchant operations.
- Stripe payments, real-time order tracking, and inventory management.
- Owned end to end from requirements through App Store release.

## Experience

### Senior Software Engineer — iOS & macOS · PureLogics <sub>Jun 2025 – Present · Lahore, Pakistan</sub>
- **Led** native iOS and macOS engineering for SUMURI's RECON product line, owning architecture, technical decisions, and code quality for forensic tooling used in 40+ countries.
- **Directed** the native Swift rewrite of RECON ITR v26.0, delivering Apple Silicon/T2 and APFS core modules, structured-concurrency volatile-data pipelines, and Disk Arbitration write-blocking.
- **Architected** a streaming SQLite ingestion layer with Swift actors and bounded batches, letting RECON LAB index large forensic datasets without loading full result sets into memory.
- **Built** FIMountKit to mount 7 forensic image formats (E01/EWF, VMDK, VHD/VHDX, AFF4, DMG, RAW, split-RAW), using chunked split-image merging to bound memory usage.
- **Replaced** an NSXPC privileged helper with a sudo-based filesystem manager, making collection reliable across large directory structures.

### Software Engineer — iOS · Pligence Inc. <sub>Jul 2024 – May 2025 · Lahore, Pakistan</sub>
- **Shipped** a Per-App VPN SDK on iOS Network Extension, enabling policy-based traffic routing for enterprise apps with **sub-5ms** latency overhead.
- **Architected** a multithreaded URL-filtering engine with custom blacklist/whitelist policies, evaluating traffic in real time with no measurable browsing-latency impact.
- **Co-developed** a custom MDM solution covering device enrollment, policy enforcement, and failure handling, backed by automated test coverage.
- **Prototyped** macOS Per-App VPN capabilities, mapping Network Extension and platform requirements for cross-platform rollout.

### Software Engineer — iOS · Joblogic <sub>Dec 2023 – Jun 2024 · Lahore, Pakistan</sub>
- **Modernised** a legacy Objective-C/UIKit codebase to Swift and MVVM, cutting production crashes by **30%**.
- **Introduced** modular, XCTest-covered components with edge-case coverage, reducing mean bug-fix cycle time by **35%**.
- **Implemented** a repository-based data layer across REST APIs and Core Data, lowering data-retrieval latency by **20%**.
- **Eliminated** race conditions in background sync for offline field workflows by adopting Swift Concurrency.

### iOS Developer · Cheetay Logistics <sub>Aug 2022 – Dec 2023 · Lahore, Pakistan</sub>
- **Built** consumer-facing Swift/UIKit features for a logistics platform handling thousands of daily delivery operations.
- **Hardened** REST integrations with retry logic and graceful degradation, keeping the app reliable on variable networks.
- **Delivered** testable, production-ready features within Agile sprints; recognised as **Cheetay of the Quarter (2023)**.

### Junior iOS Developer · Australia Post <sub>Jan 2021 – Dec 2021 · Sydney, Australia</sub>
- **Developed** SwiftUI/UIKit components, animations, and accessibility improvements for a consumer app with millions of users.
- **Delivered** stable features by applying memory management, file I/O, and asynchronous programming best practices.

## Interests

Chess · Badminton · Emerging Technology · AI & Software Innovation · Cybersecurity · Open Source
