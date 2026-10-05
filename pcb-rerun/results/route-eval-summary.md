# Route eval 20261004-230037

Board: `/home/dan/sandbox/punkfab/flexisette/pcb-rerun/index.circuit.kicad_pcb`  
Versions: {'circuit_skills': '284eb4e', 'capacity_autorouter': '0.0.958'}

| # | backend | shorts | open | DFM | floating | size | clearance | vias | track mm | plane-net mm | route s |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | freerouting ✓ | 0 | 0 | 0 | 0 | 0 | 0 | 47 | 1000.3 | 44.1 | 5.5 |
| 2 | srj:all | 0 | 0 | 0 | 0 | 0 | 14 | 66 | 1168.4 | 269.6 | 5.3 |

Ranked by shorts+crossings, open nets, DFM actionable, floating pads, size violations, clearance, vias, track length. ✓ = no blocking or fab issue at all.

## Hand-finish or re-place?

**order-ready candidate: freerouting passes every gate; review it and run check_board before ordering**

Placement: congestion peak 0.64, hot cells 342 (>= 0.129), ratsnest 991.1 mm with 87 crossings.
- hotspot (peak 0.64, 19 cells) at [123.88, 106.12, 132.88, 109.12]: J_SPK, U2
- hotspot (peak 0.59, 14 cells) at [75.88, 75.12, 85.88, 79.12]: R_CC1, R_CC2, USBC
- hotspot (peak 0.38, 5 cells) at [93.88, 82.12, 95.88, 85.12]: R_PROG, U_CHG
- hotspot (peak 0.26, 6 cells) at [58.88, 95.12, 60.88, 98.12]: U1
- hotspot (peak 0.39, 3 cells) at [56.88, 106.12, 58.88, 108.12]: U1
