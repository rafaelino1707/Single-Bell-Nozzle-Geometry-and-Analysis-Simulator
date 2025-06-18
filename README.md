# Rocket Nozzle Geometry Simulator

This simulator was made using Python, having an interface in Java. It was developed to simulate the **ideal geometry of a rocket nozzle**. It allows the user to:

- Plot the geometry profile in a 2D graphic and preview the geometry in a 3D plot;
- Calculate the ideal throat radius;
- Plot the ideal expansion ratio to maximize thrust for various chamber pressures;
- Plot performance parameters (Specific Impulse, Thrust, Mach number, etc.) for various O/F ratios;
- Plot exhaust parameters (exhaust temperature and velocity) for different chamber pressures;
- In the 2D plot, the contraction ratio, parabola exit angle, and nozzle length are displayed on the graphic;

> Currently, the simulator has been used to design the nozzle geometry for a **hybrid rocket** using mainly **paraffin wax** as fuel and **N₂O** as oxidizer to compete at EuRock 2025 with Porto Space Team.

---

<table>
  <tr>
    <td align="center" width="50%">

      <h3>2D Geometry Plot</h3>
      <img src="2Dplot.png" width="400"/>

      <h3>AutoDesk Fusion Model</h3>
      <img src="NozzleGeometryFusion0.png" width="400"/>
      <br/>
      <img src="NozzleGeometryFusion1.png" width="195"/>
      <img src="NozzleGeometryFusion2.png" width="195"/>

      <h3>Exhaust Temperature</h3>
      <img src="ExhaustTemperaturePlot.png" width="400"/>

    </td>
    <td align="center" width="50%">

      <h3>3D Geometry Preview</h3>
      <img src="3DPlot.png" width="400"/>

      <h3>Getting Ideal Expansion Ratio</h3>
      <img src="ExpansionRatioPlot.png" width="400"/>

      <h3>Performance Parameters</h3>
      <img src="PerformanceTable.png" width="400"/>

      <h3>Exhaust Velocity</h3>
      <img src="ExhaustVelocityPlot.png" width="400"/>

      <h3>Thrust Analysis</h3>
      <img src="ThrustPlot.png" width="400"/>

    </td>
  </tr>
</table>
