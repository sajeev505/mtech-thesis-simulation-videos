# Bi-disperse Gas-Solid Fluidized Bed: Simulation Videos

This repository contains the CFD simulation videos (Eulerian-Eulerian Multifluid KTGF) of pulsed air injection in a bi-disperse gas-solid bed.

<details open>
<summary><b>0. Combined Summary Videos (16:9)</b></summary>
<br>

These combined videos show side-by-side comparisons of the different cases, formatted for 16:9 presentation slides.

**Mono-disperse Summary**<br>
<video width="100%" src="LINK_PLACEHOLDER_SINGLE_PHASE" controls></video>

**Bi-disperse Density-Ratio Family**<br>
<video width="100%" src="LINK_PLACEHOLDER_DENSITY_FAMILY" controls></video>

**Bi-disperse Diameter-Ratio Family**<br>
<video width="100%" src="LINK_PLACEHOLDER_DIAMETER_FAMILY" controls></video>

</details>

<details>
<summary><b>1. Single-Phase Baselines (Mono-disperse)</b></summary>
<br>

These cases simulate the injection of air into a bed consisting of a single solid phase to establish baseline behavior.

| | | |
| :---: | :---: | :---: |
| **Base Case**<br>($30$ m/s, $d=0.00226$ m, $\rho=2600$ kg/m³)<br><video width="100%" src="https://github.com/user-attachments/assets/18f31403-0d7e-40a9-8303-1092d5736eee" controls></video> | **Low Velocity**<br>($20$ m/s pulse)<br><video width="100%" src="https://github.com/user-attachments/assets/b450c52d-70fc-4f2a-aca2-5b80175b36b1" controls></video> | **High Velocity**<br>($40$ m/s pulse)<br><video width="100%" src="https://github.com/user-attachments/assets/2f434bc9-36c0-4c85-9a25-ff51f63ad517" controls></video> |
| **Double Diameter**<br>($d=0.00452$ m)<br><video width="100%" src="https://github.com/user-attachments/assets/a2b06138-919a-4979-b117-c3fcbe7f23a2" controls></video> | **Double Density**<br>($\rho=5200$ kg/m³)<br><video width="100%" src="https://github.com/user-attachments/assets/39128a8d-2d4c-491d-95be-289f7321f7d6" controls></video> | |

</details>

<details>
<summary><b>2. Grid Independence Study</b></summary>
<br>

Verification cases running the base case configuration on coarser and finer meshes.

| | | |
| :---: | :---: | :---: |
| **Coarse Grid**<br>($20 \times 58 \times 2$)<br><video width="100%" src="https://github.com/user-attachments/assets/be387a75-c8aa-4092-8fad-f5fd89c2963d" controls></video> | **Production Grid**<br>($40 \times 117 \times 4$)<br><video width="100%" src="https://github.com/user-attachments/assets/18f31403-0d7e-40a9-8303-1092d5736eee" controls></video> | **Refined Grid**<br>($80 \times 234 \times 8$)<br><video width="100%" src="https://github.com/user-attachments/assets/1d3226fa-3eae-4737-8578-3ec73b9f5a8b" controls></video> |

</details>

<details>
<summary><b>3. Bi-disperse Density-Ratio Family</b></summary>
<br>

Both solid phases share a common particle diameter ($d=0.00226$ m), but differ in density: the lighter phase has $\rho_1 = 2600$ kg/m³ and the heavier phase has $\rho_2 = 5200$ kg/m³. Split ratio denotes **Lighter : Heavier**.

| | | |
| :---: | :---: | :---: |
| **0 : 100** (Pure Heavier)<br><video width="100%" src="https://github.com/user-attachments/assets/5ba526a9-c427-4bf7-9e80-33ae48d544ae" controls></video> | **30 : 70**<br><video width="100%" src="https://github.com/user-attachments/assets/9bb0eb69-9d6a-4920-954c-087c5750ffa0" controls></video> | **50 : 50**<br><video width="100%" src="https://github.com/user-attachments/assets/c92b5f95-d639-4b8c-92e3-d630f2774364" controls></video> |
| **70 : 30**<br><video width="100%" src="https://github.com/user-attachments/assets/a6a40e3c-32c5-4359-a209-0623e69c55de" controls></video> | **100 : 0** (Pure Lighter)<br><video width="100%" src="https://github.com/user-attachments/assets/4d9d6928-31dc-48b1-9344-ca3f06373419" controls></video> | |

</details>

<details>
<summary><b>4. Bi-disperse Diameter-Ratio Family</b></summary>
<br>

Both solid phases share a common density ($\rho=2600$ kg/m³), but differ in diameter: the finer phase has $d_1 = 0.00226$ m and the coarser phase has $d_2 = 0.00452$ m. Split ratio denotes **Finer : Coarser**.

| | | |
| :---: | :---: | :---: |
| **0 : 100** (Pure Coarser)<br><video width="100%" src="https://github.com/user-attachments/assets/88b53917-a106-4ed6-a1b1-06a9d672b0a2" controls></video> | **30 : 70**<br><video width="100%" src="https://github.com/user-attachments/assets/3144f277-0acd-4933-ae1d-5a7590cf22c1" controls></video> | **50 : 50**<br><video width="100%" src="https://github.com/user-attachments/assets/280a613e-41f6-4de4-9a3e-c77ced6fb231" controls></video> |
| **70 : 30**<br><video width="100%" src="https://github.com/user-attachments/assets/db09a1b6-2d0b-4cbc-9b65-fd53a72c7b67" controls></video> | **100 : 0** (Pure Finer)<br><video width="100%" src="https://github.com/user-attachments/assets/0ae1ec00-1473-424b-abca-5d776d24ceee" controls></video> | |

</details>
