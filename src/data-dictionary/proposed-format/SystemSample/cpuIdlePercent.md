---
name: cpuIdlePercent
type: attribute
units: percentage (%)
---

The portion of the current CPU utilization capacity that is idle.

This is calculated as:

(100.00 - cpuUserPercent - cpuSystemPercent - cpuIOWaitPercent) / elapsed\_time