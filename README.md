# Flight Simulator

Browser-based Cessna 172N Skyhawk (N4975F, 160 hp) flight simulator at KMYF Montgomery-Gibbs, San Diego. v1.56.0.

## Run it

Open `index.html` in a browser, or serve it (e.g. `python3 -m http.server`) and open http://localhost:8000/

No build step, no install. Single self-contained HTML file. Needs internet for Esri satellite imagery — Esri is the only scenery.

## What is in it

- Esri World Imagery only: zoom 14 stitched at 4096px, denser relief mesh, concurrency-limited tile loader; no custom-drawn scenery
- Blade-element-theory flight physics at 1/120 s: nine aerodynamic surfaces with individual polars, asymmetric stall/spin, ground effect, P-factor, torque, slipstream
- Cessna 172N: 160 hp Lycoming O-320, Vs 50, Vfe 85, Vno 128, Vne 160, Vy 76, best glide/final 65 kt, fixed gear
- Full instrument panel: airspeed, Garmin G5 attitude indicator, altimeter, DG, VSI, turn coordinator, GNS 430W, COM 119.20 / NAV 117.80, engine gauges, moving map with GPS Direct-To — no HUD overlay
- Engine start sequence (battery/avionics/pump/starter) + instant start, fuel burn shifting CG, manifold pressure and ISA readouts
- Fixed gear on spring-damper suspension with Pacejka-style tires, Dryden turbulence, wind shear and thermals
- Ground artifacts: 190 moving cars on five freeways + surface streets, 36 trucks/buses, four-car commuter train, 11 boats/ships with wakes
- Camera shake / headshake (FULL/LOW/OFF), keyboard / mouse / on-screen yoke, gamepad support, trim, telemetry drawer, GPWS callouts
- Settings drawer (hidden until SETTINGS): scenarios, wind/time/visibility, engine data, Direct-To, airports, frequencies, controls reference
- Keyboard / mouse / on-screen yoke controls, sound, pause

Built with Muse.
