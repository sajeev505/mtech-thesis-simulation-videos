# Bi-disperse Gas-Solid Fluidized Bed: Simulation Videos

This repository contains the CFD simulation videos (Eulerian-Eulerian Multifluid KTGF) of pulsed air injection in a bi-disperse gas-solid bed.

<details open>
<summary><b>1. Single-Phase Baselines (Mono-disperse)</b></summary>
<br>

These cases simulate the injection of air into a bed consisting of a single solid phase to establish baseline behavior.

<table width="100%">
  <tr>
    <td width="33%" align="center"><b>Base Case</b><br>(30 m/s, <i>d</i>=0.00226 m, &rho;=2600 kg/mÂ³)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>Low Velocity</b><br>(20 m/s pulse)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>High Velocity</b><br>(40 m/s pulse)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
  <tr>
    <td width="33%" align="center"><b>Double Diameter</b><br>(<i>d</i>=0.00452 m)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>Double Density</b><br>(&rho;=5200 kg/mÂ³)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%"></td>
  </tr>
</table>

</details>

<details>
<summary><b>2. Grid Independence Study</b></summary>
<br>

Verification cases running the base case configuration on coarser and finer meshes.

<table width="100%">
  <tr>
    <td width="33%" align="center"><b>Coarse Grid</b><br>(20 &times; 58 &times; 2)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>Production Grid</b><br>(40 &times; 117 &times; 4)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>Refined Grid</b><br>(80 &times; 234 &times; 8)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
</table>

</details>

<details>
<summary><b>3. Bi-disperse Density-Ratio Family</b></summary>
<br>

Both solid phases share a common particle diameter ($d=0.00226$ m), but differ in density: the lighter phase has $\rho_1 = 2600$ kg/mÂ³ and the heavier phase has $\rho_2 = 5200$ kg/mÂ³. Split ratio denotes **Lighter : Heavier**.

<table width="100%">
  <tr>
    <td width="33%" align="center"><b>0 : 100</b> (Pure Heavier)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>10 : 90</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>30 : 70</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
  <tr>
    <td width="33%" align="center"><b>40 : 60</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>50 : 50</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>60 : 40</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
  <tr>
    <td width="33%" align="center"><b>70 : 30</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>90 : 10</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>100 : 0</b> (Pure Lighter)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
</table>

</details>

<details>
<summary><b>4. Bi-disperse Diameter-Ratio Family</b></summary>
<br>

Both solid phases share a common density ($\rho=2600$ kg/mÂ³), but differ in diameter: the finer phase has $d_1 = 0.00226$ m and the coarser phase has $d_2 = 0.00452$ m. Split ratio denotes **Finer : Coarser**.

<table width="100%">
  <tr>
    <td width="33%" align="center"><b>0 : 100</b> (Pure Coarser)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>10 : 90</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>30 : 70</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
  <tr>
    <td width="33%" align="center"><b>40 : 60</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>50 : 50</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>60 : 40</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
  <tr>
    <td width="33%" align="center"><b>70 : 30</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>90 : 10</b><br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
    <td width="33%" align="center"><b>100 : 0</b> (Pure Finer)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video></td>
  </tr>
</table>

</details>

