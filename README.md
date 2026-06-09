# Bi-disperse Gas-Solid Fluidized Bed: Simulation Videos

This repository contains the CFD simulation videos (Eulerian-Eulerian Multifluid KTGF) of pulsed air injection in a bi-disperse gas-solid bed.

<details open>
<summary><b>1. Single-Phase Baselines (Mono-disperse)</b></summary>
<br>

These cases simulate the injection of air into a bed consisting of a single solid phase to establish baseline behavior.

| | | |
| :---: | :---: | :---: |
| **Base Case**<br>($30$ m/s, $d=0.00226$ m, $\rho=2600$ kg/m$^3$)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **Low Velocity**<br>($20$ m/s pulse)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **High Velocity**<br>($40$ m/s pulse)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |
| **Double Diameter**<br>($d=0.00452$ m)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **Double Density**<br>($\rho=5200$ kg/m$^3$)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | |

</details>

<details>
<summary><b>2. Grid Independence Study</b></summary>
<br>

Verification cases running the base case configuration on coarser and finer meshes.

| | | |
| :---: | :---: | :---: |
| **Coarse Grid**<br>($20 \times 58 \times 2$)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **Production Grid**<br>($40 \times 117 \times 4$)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **Refined Grid**<br>($80 \times 234 \times 8$)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |

</details>

<details>
<summary><b>3. Bi-disperse Density-Ratio Family</b></summary>
<br>

Both solid phases share a common particle diameter ($d=0.00226$ m), but differ in density: the lighter phase has $\rho_1 = 2600$ kg/m$^3$ and the heavier phase has $\rho_2 = 5200$ kg/m$^3$. Split ratio denotes **Lighter : Heavier**.

| | | |
| :---: | :---: | :---: |
| **0 : 100** (Pure Heavier)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **10 : 90**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **30 : 70**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |
| **40 : 60**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **50 : 50**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **60 : 40**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |
| **70 : 30**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **90 : 10**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **100 : 0** (Pure Lighter)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |

</details>

<details>
<summary><b>4. Bi-disperse Diameter-Ratio Family</b></summary>
<br>

Both solid phases share a common density ($\rho=2600$ kg/m$^3$), but differ in diameter: the finer phase has $d_1 = 0.00226$ m and the coarser phase has $d_2 = 0.00452$ m. Split ratio denotes **Finer : Coarser**.

| | | |
| :---: | :---: | :---: |
| **0 : 100** (Pure Coarser)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **10 : 90**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **30 : 70**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |
| **40 : 60**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **50 : 50**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **60 : 40**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |
| **70 : 30**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **90 : 10**<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> | **100 : 0** (Pure Finer)<br><video width="100%" src="PLACEHOLDER_LINK" controls></video> |

</details>
