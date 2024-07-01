# PCBs for RoboCup 2024 Internationals
## Possible Improvements
- Establish proper design rules before starting the PCB design
    - Helps to avoid overlooking critical DRC errors (e.g. shorts) due to an abundance of minor errors (see TEMT8/GPIO14 in [bottom-rounded.kicad_pcb](https://github.com/PorridgePi/soccer-pcbs/blob/506bb3b5a68c0d0ed1313e4a490990bbbff14e21/internationals/pcbs/bottom/bottom-rounded.kicad_pcb) which shorted to ground thanks to a via intended to reduce EMI)
- Increase the general clearance (rather than the default 0.2mm)
