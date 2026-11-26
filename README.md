# Jean-Jacques' Skyhawk School — Flight Simulator

Browser-based Cessna 182Q Skylane (N4975F, 320 hp) flight simulator at KMYF Montgomery-Gibbs, San Diego. v1.53.0.

## Run it

Open `index.html` in a browser, or serve it (e.g. `python3 -m http.server`) and open http://localhost:8000/

No build step, no install. Single self-contained HTML file.

## What is in it

- Blade-element-theory flight physics at 1/120 s: nine aerodynamic surfaces with individual polars, asymmetric stall/spin, ground effect, P-factor, torque, slipstream
- 320 hp conversion + speed kit: ~170 KTAS top, ~155 cruise, Vy 92, Vno/Vne 165/195
- Real Esri satellite imagery draped over San Diego terrain, with painted-terrain fallback offline; runways georeferenced to real airports
- Full instrument panel + military HUD: pitch ladder, IAS/ALT tapes, compass, throttle/flap/gear/AoA, flashing STALL, flight-path vector, slip ball, V-speed bugs, adjustable QNH, ILS diamonds for 28L
- Engine start sequence (battery/avionics/pump/starter) + instant start, fuel burn shifting CG, manifold pressure and ISA readouts
- Retractable gear on spring-damper suspension with Pacejka-style tires, Dryden turbulence, wind shear and thermals
- Lessons, checklists, V-speeds, engine and avionics tabs, Jean-Jacques' log
- Graded checkrides: 7-maneuver mock checkride and ACS Area IV takeoff & landing ride
- Moving cars on freeways, boats and ships with wakes in Mission Bay, San Diego Bay and along the coast
- Camera shake / headshake (FULL/LOW/OFF), keyboard / mouse / on-screen yoke, gamepad support, trim, telemetry drawer, GPWS callouts
- Keyboard / mouse / on-screen yoke controls, sound, pause

Built with Muse.
