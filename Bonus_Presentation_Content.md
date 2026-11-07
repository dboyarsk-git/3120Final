# Bonus Slide — THE COST OF CHANGING THE FIELD

Use the existing website's charcoal / off-white / orange theme. Main graphic: `bonus_inductance_breakdown_v2.png`.

**Three clean slide talking points**

- **40.30 mH** estimated series-aiding inductance (assumed winding-pack geometry)
- **95.1 V peak** for a controlled **0→200 A in 100 ms** ramp
- **806 J stored** in the magnetic field at 200 A

**Speaking script (~60 seconds)**

“The magnetic navigation coils cannot change their current instantaneously, because they have inductance. Each coil has its own self-inductance, and the nearby coils also link magnetic flux, producing mutual inductance. For the series-aiding connection, the two add together. Using the official conductor cross-section of 162 square millimeters, plus an assumed winding-pack shape, I estimated a total of 40.3 millihenries.

If we ramp the current from zero to 200 amps in one-tenth of a second, the current changes at 2,000 amps per second. The inductive voltage is about 80.6 volts. The resistive drop increases with current and reaches 14.5 volts, so the total voltage peaks at around 95.1 volts. At full current the magnetic field stores about 806 joules. The important practical point is that we need to design not only for ongoing coil heating, but also for transient voltage and safe energy discharge. The exact figures depend on the actual winding geometry, which wasn't specified in the starter kit.”
