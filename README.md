# SamaLab

A complete, single-file IPv4/IPv6 networking toolkit built entirely with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no server required — just open `index.html` in any browser.

---

## Features

### Calculators
- **IPv4 Subnet Calculator** — Enter any IP + prefix to get network/broadcast/hosts/mask with a 32-bit visual bitmap, step-by-step solving, and one-click copy
- **Visual Subnet Tree** — Interactive hierarchical view of subnet divisions
- **VLSM Planner** — Variable Length Subnet Masking with automatic allocation, usage bar, and exportable results
- **IPv6 Suite** — Address analyzer, compressor, PTR builder, validator, scope classifier, solicited-node multicast, EUI-64, SLAAC simulator, subnetting, and transition tools (dual-stack, 6to4, NAT64)
- **Overlap Checker** — Detect overlapping CIDR ranges across multiple networks
- **Supernetting** — Aggregate multiple routes into a single summary route

### Learning Modules
- **Binary Basics** — Decimal/binary converter, interactive bit toggle board, AND operation visualizer
- **Subnet Masks** — Slider-driven mask explorer showing prefix, host bits, usable hosts, and wildcard
- **CIDR Deep Dive** — CIDR notation explainer and subnet divider
- **IP Classes** — Classful addressing lookup with private range detection

### Courses
- **CCNA Course** — 16 topic tabs covering OSI/TCP-IP, Ethernet/ARP, Switching/STP, IP Routing, TCP/UDP, DHCP/DNS, OSPF, EtherChannel, EIGRP, IPv6, WAN, and more
- **CCNP Course** — Advanced topics: OSPF areas, BGP deep dive, MPLS, QoS, IPSec VPN, SD-WAN
- **CCIE Course** — Expert-level: EIGRP/DUAL, BGP path selection, multicast, route redistribution, segment routing, EVPN/VXLAN, network automation, IS-IS, advanced BGP, MPLS-TE

### Interactive Tools
- **BGP Path Selector** — Compare BGP attributes across paths with step-by-step best path walkthrough
- **Protocol Simulator** — Step through protocol handshakes (TCP, OSPF, BGP, DHCP, ARP, STP) with timeline and packet viewer
- **Flashcard Engine** — Study networking concepts with spaced repetition
- **Packet Decoder** — Wireshark-style hex dump decoder

### Live Simulators
- **OSPF Topology Canvas** — Drag-and-drop router topology with area configuration and SPF visualization
- **MPLS Label Walker** — Trace label stack operations (push/swap/pop) hop by hop
- **Tunnel Encapsulation Builder** — Visualize GRE, IPSec, VXLAN, and other tunnel headers
- **BGP Hijack Simulator** — See how prefix hijacking works and how RPKI/ROA prevents it
- **STP/RSTP Simulator** — Build switch topologies and watch spanning tree elect root bridges and block ports
- **VLAN 802.1Q Visualizer** — See tagged/untagged frames traverse trunk and access ports
- **TCP State Animator** — Step through TCP connection states (SYN, ESTABLISHED, FIN_WAIT, etc.)
- **Prefix-List & Route-Map Builder** — Generate IOS-style prefix-lists and route-maps interactively

### Analysis Tools
- **Route Table Parser** — Paste `show ip route` output and get structured, searchable results
- **Show Command Interpreter** — Paste any IOS show command output for annotated explanations
- **Convergence Calculator** — Estimate protocol convergence times for OSPF, EIGRP, BGP
- **OSPF LSA Explorer** — Browse and understand LSA types 1–7 with field-level breakdowns

### Troubleshooting Lab
- **Broken Config Challenges** — Find and fix intentional errors in router/switch configurations
- **Network Design Wizard** — Generate full network designs with IP plans, VLAN assignments, and IOS configs

### Practice & Reference
- **Packet Tracer** — Simulated packet walk through network layers
- **Quiz Mode** — Beginner/Intermediate/Expert questions with scoring, streaks, and explanations
- **Cheat Sheet** — Quick reference tables for masks, powers of 2, and common subnets
- **More Tools** — Wildcard calculator, host range lister, number converter, prefix finder

---

## Quality-of-Life Features

| Feature | Description |
|---|---|
| **Autosave** | All inputs auto-saved to localStorage; restored on reload |
| **Page Persistence** | Last visited page restored via URL hash |
| **Copy Buttons** | One-click copy for IPv4, IPv6, VLSM, overlap, and supernet results |
| **Toast Notifications** | Non-intrusive feedback for copy, validation, and random generation |
| **Random Practice** | Generate random IPv4/IPv6 addresses for instant practice |
| **Responsive** | Full mobile support with collapsible sidebar |
| **Offline** | Works entirely offline — no API calls, no CDN dependencies at runtime |
| **Dark Theme** | Purpose-built dark UI optimized for long study sessions |

---

## Getting Started

```bash
# Clone or download the repo
git clone https://github.com/your-username/samalab.git

# Open in any browser
open index.html
```

No build step. No `npm install`. Just a browser.

---

## Tech Stack

- **HTML5** — Semantic markup, SVG bitmaps, Canvas animations
- **CSS3** — Custom properties, grid/flexbox layouts, CSS animations
- **Vanilla JavaScript** — Zero dependencies, ~18,000 lines in a single file

---

## Project Structure

```
.
├── index.html    # The entire application (HTML + CSS + JS)
└── README.md     # This file
```

---

## License

MIT
