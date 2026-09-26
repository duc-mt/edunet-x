# Edunet-X Project Budget and Costing

This document outlines the baseline budget for the Edunet-X project as well as the separate costing for the "School of the Future" transportables bid.

## Baseline Budget: Core Network
**Total Allotted Budget:** $860,000

| Category | Estimated Cost | Notes |
|----------|----------------|-------|
| Core Networking Equipment (Routers, Core/Dist Switches, APs) | $450,000 | For G, C, B, and J buildings. Includes CS1, CS2, Firewalls. |
| Cabling & Physical Infrastructure | $150,000 | Racks, patch panels, Cat6a runs, Fiber links between core buildings. |
| End-User Devices (Computers, Phones, Cameras, Alarms) | $180,000 | Standard IT endpoints across the campus. |
| Labor & Consultation | $50,000 | External consultant, network engineers, cabling technicians. |
| Maintenance & Support | $30,000 | First-year support contracts, software licenses, spares. |
| **Total Baseline Estimate** | **$860,000** | **On Budget** |

---

## Additional Costing: "School of the Future" Bid (Transportables T1, T2, T3)
*Per client requirements, these costs are itemized separately for the bid. These items are required to integrate the new computer pools (T1, T2) and the Advanced Video Capture Studio (T3).*

### 1. Network Cabling & Infrastructure
*Note: Due to the ~200m distance from the G building to the transportables (near oval/J building), standard copper is insufficient. Fiber optic uplinks are required.*

| Item | Qty | Unit Cost (Est) | Total Cost (Est) |
|------|-----|-----------------|------------------|
| OS2 Single-Mode Fiber Cable (6-core, armoured, 250m) | 1 | $1,200 | $1,200 |
| Fiber Patch Panels & Cassettes (24-port) | 2 | $300 | $600 |
| 10GBASE-LR SFP+ Transceivers | 4 | $150 | $600 |
| Cat6a Copper Cabling (Internal drops) | 100 | $150 | $15,000 |
| Small Rack Enclosure (12U-18U) & UPS | 1 | $1,400 | $1,400 |
| **Subtotal** | | | **$18,800** |

### 2. Networking Equipment
| Item | Qty | Unit Cost (Est) | Total Cost (Est) |
|------|-----|-----------------|------------------|
| Distribution Switches (24-port, 10G uplink) | 2 | $4,500 | $9,000 |
| Access Switches (48-port PoE+) | 3 | $2,800 | $8,400 |
| Wireless Access Points | 3 | $700 | $2,100 |
| **Subtotal** | | | **$19,500** |

### 3. End-User Equipment (Computers & AV)
| Item | Qty | Unit Cost (Est) | Total Cost (Est) |
|------|-----|-----------------|------------------|
| Standard Desktop Computers (T1 & T2) | 60 | $1,200 | $72,000 |
| High-Performance Video Computers (T3) | 10 | $2,500 | $25,000 |
| 1080p Web Cameras (T1 & T2) | 60 | $100 | $6,000 |
| 4K Studio Cameras & Capture Cards (T3) | 2 | $3,000 | $6,000 |
| **Subtotal** | | | **$109,000** |

### 4. Labor & Configuration
| Item | Qty | Unit Cost (Est) | Total Cost (Est) |
|------|-----|-----------------|------------------|
| Network Engineer (Config, VLANs, QoS for 4K video) | 40 hrs | $150/hr | $6,000 |
| Cable Installation Technician | 60 hrs | $100/hr | $6,000 |
| **Subtotal** | | | **$12,000** |

### **Total Additional Bid Cost:** $159,300

---
## Technical Requirements Noted for Implementation
- **Fiber Optic Uplink:** Required for the 200m distance to Transportables.
- **QoS Policies:** Must be configured to prioritize 4K outbound video streams from T3 over standard computer pool traffic from T1 & T2.
