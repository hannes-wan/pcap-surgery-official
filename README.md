# PCAP Surgery

**Clean, redact, and hand off packet captures without breaking the evidence.**

Turn customer PCAP files into smaller, safer, checksum-correct handoff captures for support tickets, test fixtures, and reproducible network cases.

[Website](https://hannes-software.com/pcap-surgery/) · [Download](https://hannes-software.com/pcap-surgery/download/) · [Help](https://hannes-software.com/pcap-surgery/help/) · [Latest release](https://github.com/hannes-wan/pcap-surgery-official/releases/tag/v0.1.6)

## The problem it solves

**Support captures should be useful without leaking everything.**

Built for engineers who need repeatable packet-capture evidence review before they rewrite, trim, sanitize, repair checksums, or send a capture to someone else.

## Why you should try it

- You need to send a packet capture to a vendor or teammate without exposing unrelated traffic.
- You need to trim, redact, annotate, repair, and export while still seeing what the capture means.
- You want a repeatable support handoff instead of “open this giant PCAP and scroll around”.

## What makes it strong

### Inspect before you change anything

- Classic PCAP and basic Ethernet PCAPNG import feed a dense packet table with protocol, endpoint, direction, packet number, time range, and text filters.
- Ethernet, IP, TCP, UDP, DNS, ICMP, ARP, offsets, and payload bytes stay tied to the selected packet so edits are grounded in visible evidence.
- The workflow is built for packet-capture evidence review, not a generic capture viewer with edit commands bolted on.

### Edits are explicit and exportable

- Professional unlocks edited PCAP export, subset PCAP export, rewrite and anonymize rule workflows, and checksum repair.
- Supported PCAP edit paths cover practical rewrite work such as fixed-length field changes, anonymization, trim/keep decisions, and focused handoff captures.
- Checksum status is part of the workflow, so repaired IPv4/TCP/UDP output is not hidden behind a silent save button.

### Repair without losing the story

- Large capture windows stay focused through filters, case navigation, decoded detail, byte evidence, and export scope rather than forcing every task into CLI notes.
- Subset export helps remove unrelated packets while preserving the sequence and timing evidence needed for DNS, TCP, UDP, ICMP, ARP, and application investigations.
- Classic PCAP export is the paid path today, with a focused workflow for trimming, anonymizing, rewriting, and sharing packet evidence.

### $19 lifetime for the work that matters

- Use Community for local inspection and validation; buy Professional when you need rewrite, repair, checksum, anonymization, and export workflows.
- No subscription and no cloud upload are required for customer traces, lab captures, or incident evidence.
- The value is speed and confidence: open the PCAP, prove what is inside, change only what you intend, then export a cleaner file.

## What you can do with it

- **PCAP and basic PCAPNG import** — Open capture files, index packet metadata, decode link and network-layer evidence, and keep large windows responsive.
- **Packet timeline and filters** — Filter by protocol, endpoint, direction, packet number, time range, and text while preserving a dense packet table.
- **Decoded packet detail** — Inspect Ethernet, IP, TCP, UDP, DNS, ICMP, ARP, payload bytes, offsets, and copyable evidence for the selected packet.

## Screenshots

### Packet detail evidence

![Packet detail evidence](https://hannes-software.com/assets/pcap-surgery/screenshots/packet-detail-44b36293ad.webp)

Decoded layers, packet metadata, raw bytes, and selected-packet context.

### Time workshop

![Time workshop](https://hannes-software.com/assets/pcap-surgery/screenshots/time-workshop-521b0a28e7.webp)

Preview timestamp edits and duration changes before writing a capture.

### Export plan

![Export plan](https://hannes-software.com/assets/pcap-surgery/screenshots/export-plan-f875e21c65.webp)

Review edited capture export readiness and warnings before handoff.

## Download packages

Latest GitHub release: **v0.1.6**

- [pcap-surgery-0.1.6-windows-x64-setup.exe](https://github.com/hannes-wan/pcap-surgery-official/releases/download/v0.1.6/pcap-surgery-0.1.6-windows-x64-setup.exe)
- [pcap-surgery-0.1.6-linux-x64.AppImage](https://github.com/hannes-wan/pcap-surgery-official/releases/download/v0.1.6/pcap-surgery-0.1.6-linux-x64.AppImage)
- [pcap-surgery-0.1.6-linux-x64.deb](https://github.com/hannes-wan/pcap-surgery-official/releases/download/v0.1.6/pcap-surgery-0.1.6-linux-x64.deb)
- [pcap-surgery-0.1.6-linux-x64.rpm](https://github.com/hannes-wan/pcap-surgery-official/releases/download/v0.1.6/pcap-surgery-0.1.6-linux-x64.rpm)

Prefer the product page if you want the full download notes, licensing details, and help articles:

- https://hannes-software.com/pcap-surgery/download/

## Editions

- **Community** — Free: Local capture inspection and validation workflows for small PCAP surgery tasks. Key features: Capture metadata review, Packet evidence inspection, Filter and detail workflows, Website direct downloads.
- **Professional** — $19 lifetime: One-time lifetime license for paid export and rewrite workflows when the product gate requires it. Key features: Export edited PCAP files, Export subset PCAP files, Rewrite and anonymize rule workflows, Checksum repair, Website checkout activation.
- **Team** — $49 team / 3 seats: Three-seat team bundle for one product. Key features: Three machine-bound seats, All Professional features, One billing email, Website checkout activation.

## Good fit / not a good fit

Good fit: Turn customer PCAP files into smaller, safer, checksum-correct handoff captures for support tickets, test fixtures, and reproducible network cases.

Boundary: Not a live packet sniffer, IDS, VPN, or traffic generator. It works on existing captures so handoffs are smaller, safer, and reproducible.

## Search terms this product is built around

PCAP editor, PCAP viewer, PCAPNG viewer, packet analyzer, Wireshark alternative, anonymize PCAP, checksum repair, network analyzer, packet sniffer, wireless network analyzer app

## About Hannes Software

Hannes Software builds focused local-first desktop tools: protocol diagnostics, music practice/transcription utilities, and small-clinic operations software. The pattern is simple: solve a narrow workflow well, keep data on the user’s machine, and sell with one-time pricing instead of a subscription treadmill.

Website: https://hannes-software.com/
Contact: support@hannes-software.com

## Repository note

This is the official public repository for PCAP Surgery downloads, screenshots, release links, and product information. The commercial desktop application source code is not published in this repository.
