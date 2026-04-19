# Power Systems Interconnection Study

## Curated Python projects for power-systems interconnection analysis

This is a curated list of high-impact Python-focused repositories for grid interconnection studies (load flow, OPF, contingency analysis, dynamics, and planning).

### Core transmission and interconnection analysis
- **pandapower** — https://github.com/e2nIEE/pandapower  
  Widely used Python toolkit for AC/DC power flow, short-circuit, OPF, state estimation, and network modeling.
- **PyPSA** — https://github.com/PyPSA/PyPSA  
  Strong for transmission planning, interconnection studies, and optimization-heavy workflows.
- **PYPOWER** — https://github.com/rwl/PYPOWER  
  Classic MATPOWER port in Python; still important for research baselines and teaching.
- **ANDES** — https://github.com/CURENT/andes  
  Python-native dynamic simulation package for transient and small-signal stability studies.
- **VeraGrid (formerly GridCal)** — https://github.com/SanPen/GridCal  
  Python-based GUI + engine for power flow, contingency, optimization, and planning studies.
- **pypowsybl** — https://github.com/powsybl/pypowsybl  
  Python interface to the PowSyBl ecosystem for load flow, security analysis, and network data exchange.

### Distribution and DER interconnection-focused tooling
- **OpenDSSDirect.py** — https://github.com/dss-extensions/OpenDSSDirect.py  
  Python interface to OpenDSS for feeder and DER interconnection analysis.
- **PyDSS** — https://github.com/NREL/PyDSS  
  NREL tool for distribution-system simulation and DER/time-series studies.
- **power-grid-model** — https://github.com/PowerGridModel/power-grid-model  
  High-performance Python/C++ package for distribution power flow and state estimation.

### Planning and scenario-model projects used in interconnection studies
- **Switch** — https://github.com/switch-model/switch  
  Python optimization platform for generation/transmission expansion and policy-driven grid scenarios.
- **PyPSA-Eur** — https://github.com/PyPSA/pypsa-eur  
  Large-scale, open European grid model built on PyPSA; valuable reference workflow for interconnection and expansion studies.

## Quick recommendation path
If you are starting now:
1. Start with **pandapower** for practical network studies.
2. Add **PyPSA** for optimization/planning and high-RE integration work.
3. Use **OpenDSSDirect.py / PyDSS** for distribution and DER interconnection use cases.
4. Use **ANDES** when dynamic stability analysis is required.
