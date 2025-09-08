# LendMi-Storage
## IPFS Ecology Revenue Protocol
It has a variety of products including VFIL lending mining funds.LendMi opens up mining and coin circles through DEFI to generate higher coin-based returns for investors.

LendMi collects FIL in the form of central lending, lends FIL to large nodes (large mining pools) for mining, and rewards for output are then distributed to investors. Because output is stable, investors can be guaranteed fixed income. On the other hand, in order to ensure the validity of the node pledge assets, the community elects large nodes (high value) and requires the node pledge node private key to ensure control of the node (control can be verified by the miner’s signature).

LendMi now supports HECO and BSC Main Chain Ecology, with deposit exceeded 900,000 coins and TVL once exceeded $150 million.

## LendMi Security Commitment
LendMi code does not go open source to reduce the likelihood of a cyber attack while protecting the intellectual property of the project team.
LendMi promises to conduct cross-audits with a number of well-known auditors for each version upgrade to ensure the security of user assets
LendMi's auditors：Fairyproof

## Filecoin Plus Allocator Information

### Allocator Type
Public Open Allocator Pathway

### On-chain Addresses
- **DC Allocated Address**: `f410fci3jb6xm7qhtvtsnozgde4lvyvjsvw227nkzgyi`
- **Organization Chain Address**: `f17gyewdt3aviprhmhcl52xq2rtv3ihrakiv6bukq`

### Allocation Requirements

#### Allocation Tranche Schedule
- First allocation: max no more than 100TiB
- Second allocation: max no more than 256TiB
- Third allocation: max no more than 512TiB
- Fourth allocation: max no more than 1PiB
- Fifth and thereafter: max no more than 2PiB

#### Storage Requirements
- **Replicas Required**: 5 (verified by CID checker)
- **Number of Storage Providers Required**: 5
- **DataCap Allocation Limits**: 20%

### Verification & Compliance

#### License & Provenance Verification
- **Automated License Scanner**: Crawl dataset landing pages for license metadata (e.g., SPDX tags)
- **Provenance Audit**: Cross-reference manifest CIDs against original source via Lotus CLI's `lotus client list-all-deals`

#### Cryptographic Manifest & Sampling
- **Manifest Submission**: Clients upload a CAR manifest list of CIDs for the dataset
- **Random Sampling**: Perform a 5-10% CAR-based retrieval audit using a Retrieval Tester Utility to confirm integrity and content match

#### Auditing & Reporting
- **Monthly Compliance Report**:
  - License compliance status
  - Manifest match rate (>95%)
  - Retrieval audit RSR and latency distributions
- **Public Dashboard**: Integrate with a metrics portal (e.g., DataCap Stats) to visualize uptime, RSR, and onboarding velocity

### Qualification & Verification Process

#### Public License Check
Clients must submit the source URL and license identifier (such as CC0, CC-BY). We verify this through the Creative Commons registry API.

#### Proof of Origin
Client provides a list of original data source set buckets (e.g., Data.gov API endpoints). We verify checksum alignment.

#### Sybil Mitigation & Rate Limiting
- **Email Domain Allowlist**: Only recognized public data administrators (e.g., government.gov/.edu, major open data non-governmental organizations) are accepted
- **Allocation Caps**: New clients begin with a 500 TiB total cap and 100 TiB/week throttle until they demonstrate sustained retrieval success and compliance

#### Audit Trail & Governance Proof
- All due-diligence artifacts (license scans, API logs, correspondence) are published in the GitHub issue for each allocation, per Fil+ best practices
- Automated pathway leverages GitHub OAuth for identity verification and posts a signed JSON record of checks

### Success Metrics (6-Month Goals)

#### 1. Dataset Onboarding Speed
- **Measures**: Number of unique public datasets approved and joined each month
- **Goals**:
  - Monthly: ≥12 datasets/month
  - Cumulative 6-month: ≥70 datasets

#### 2. Search Success Rate
- **Measures**: Ratio of successful retrievals to total retrieval attempts for all storage providers of a public dataset
- **Goal**: Overall RSR ≥90% of search requests are successful

#### 3. Data Availability Uptime
- **Measures**: Percentage of scheduled retrieval tests that return data within the SLA (e.g., within 60 seconds)
- **Goal**: Uptime of all public datasets ≥99.9%

#### 4. Geographically Redundant Index
- **Measures**: Average number of different geographic regions (data centers) that store each dataset
- **Goal**: Replication factor ≥3 regions per dataset

#### 5. Community Engagement
- **Measures**: Number of external projects or users actively consuming or referencing a dataset (e.g., GitHub forks, API calls)
- **Goal**: Active integration ≥5 different projects

Email: contact@lendmi.xyz

Slack: LendMi

Twitter: [LendMi_Official](https://twitter.com/LendMi_Official) 
