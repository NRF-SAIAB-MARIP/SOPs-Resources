<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-HRZ20D7BNQ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  const urlParams = new URLSearchParams(window.location.search);
  const isDebug = urlParams.get('debug') === 'true';

  gtag('config', 'G-HRZ20D7BNQ', {
    ...(isDebug && { debug_mode: true })
  });
</script>

<a name="readme-top"></a>

![Mar-RIP](/assets/img/MARIP_Logo-2.png)

<div align="center">
<a href="https://nrf-saiab-marip.github.io/">Home</a> - 
<a href="https://saiab.ac.za/platforms/marine-remote-imagery-platform-mar-ip/" target="_blank">About</a> -
<a href="https://nrf-saiab-marip.github.io/SOPs-Resources/">SOPs & Resources</a> - 
<a href="https://nrf-saiab-marip.github.io/SOPs-Resources/#quick-reference--downloads">Downloads</a> -
<a href="https://github.com/NRF-SAIAB-MARIP/NRF-SAIAB-MARIP.github.io">GitHub</a> -
<a href="mailto:atf.bernard@saiab.nrf.ac.za?cc=e.heyns-veale@saiab.nrf.ac.za,a.vanwyk@saiab.nrf.ac.za&subject=MARIP%20Website%20Inquiry">Contact</a>
</div>

<br>

# Getting Started with MaRIP Shared Resources

If this is your first time working on a MaRIP project, follow Parts 1 to 3 below in order, completing each step as you go.

If you are already familiar with the setup and just need to find something, skip to the [_Quick Reference & Downloads_](#quick-reference--downloads) section at the bottom of the page.


## Part 1 — Download and Read SOP1a

Before doing anything else, download and read <a href="https://drive.google.com/file/d/1wcK9LaCjf0wBrzzcJuivJ1hlzMvInafJ/preview" target="_blank">SOP1a: Project Setup and Data Management</a>. This is the foundation document for all MaRIP projects and everything in Parts 2 and 3 refers back to it.

<iframe src="https://drive.google.com/file/d/1wcK9LaCjf0wBrzzcJuivJ1hlzMvInafJ/preview" width="100%" height="500px"></iframe>

<br>

The <a href="https://drive.google.com/drive/folders/1-TXOWxBSvXX0618xqpZMe30GI4fDvpJj?usp=sharing" target="_blank">Shared Resources</a> folder is a Google Drive folder containing all MaRIP SOPs, templates, field sheets, and reference materials. 

<a href="https://drive.google.com/file/d/1wcK9LaCjf0wBrzzcJuivJ1hlzMvInafJ/preview" target="_blank">SOP1a</a> is located at: `1_project_setup > 1.1_data_management > SOP1a - Project setup and Data management`

SOP1a covers the following, all of which you will need to refer to as you work through Parts 2 and 3:

- <a href="assets/img/MARIP_ProjectWorkflow.png" target="_blank">Complete project workflow (Figure 1)</a> — an overview of the full MaRIP project lifecycle from setup to data publication
- <a href="assets/img/MARIP_ProjectSetupTree.png" target="_blank">Project setup decision tree (Figure 2)</a> — use this to confirm which setup option applies to you before starting Part 2
- <a href="assets/img/MARIP_SopFramework.png" target="_blank">SOP framework overview (Figure 3)</a> — shows how the SOPs are organised across project setup, sampling, and data extraction
- Data management systems, including:
  - Role-based workflow — who is responsible for what at each stage
  - <a href="https://drive.google.com/drive/folders/1klWTo05PjByNcBYqMNGgvySqE7anpMxm?usp=share_link" target="_blank">Template Folder System (TFS)</a> — the standardised folder structure used across all MaRIP projects
  - Unique identifier codes — how samples, fieldtrips, and projects are named and tracked
  - Storage guidance — hard drive requirements and long-term archiving
- <a href="assets/img/MARIP_SharedResources.png" target="_blank">Shared Resources layout (Figure 6)</a> — a visual map of the Shared Resources folder and where to find everything
- <a href="https://drive.google.com/file/d/13nf0uaZjpP-QokfQUO__gxV727XF38hu/preview" target="_blank">SOP Decision Tree (Figure 7)</a> — use this in Part 2 Step 2 to identify which SOPs you need to download



## Part 2 — Set Up Your Workspace

### Step 1: Choose Your Setup

Before downloading anything, use the <a href="assets/img/MARIP_ProjectSetupTree.png" target="_blank">project setup decision tree (Figure 2)</a> in <a href="https://drive.google.com/file/d/1wcK9LaCjf0wBrzzcJuivJ1hlzMvInafJ/preview" target="_blank">SOP1a</a> to confirm which of the three options below applies to you. Each option requires a different set of folders and resources.

<iframe src="https://drive.google.com/file/d/13nf0uaZjpP-QokfQUO__gxV727XF38hu/preview" width="100%" height="500px"></iframe>

<br>

**Option 1 — New Project** *(you need permits, ethics approval, and a full project setup)*

1. Prepare your hard drive for field sampling
2. Download the full <a href="https://drive.google.com/drive/folders/1uwe-C10x_U8FtBPy6i_PFgSEBUsP96qg?usp=share_link" target="_blank">Project Folder</a> from the <a href="https://drive.google.com/drive/folders/1klWTo05PjByNcBYqMNGgvySqE7anpMxm?usp=share_link" target="_blank">Template Folder System</a> in Shared Resources: `1_project_setup > 1.1_data_management > template_folder_system`
3. Rename the downloaded folder using your project unique identifier code (see <a href="https://drive.google.com/file/d/1wcK9LaCjf0wBrzzcJuivJ1hlzMvInafJ/preview" target="_blank">SOP1a</a>  Section 1.2.4 for the naming convention)



**Option 2 — Existing Project** *(the project is already set up and you are going into the field)*

1. Prepare your hard drive for field sampling
2. Download only the <a href="https://drive.google.com/drive/folders/1kxoaZLK3YDrvIXf9P_Bwp9jUbYGhdVAp?usp=share_link" target="_blank">Fieldtrip Folder</a> from the Template Folder System in Shared Resources
3. Rename the folder using the fieldtrip unique identifier code



**Option 3 — Video Analyst** *(you are analysing existing footage and are not going into the field)*

1. Prepare your workspace:
   - **At SAIAB:** Access videos directly from the Network Attached Storage (NAS). Arrange NAS access with SAIAB's IT department, then create a working folder in the student workspace.
   - **Remote workers:** Obtain the populated fieldtrip folder on a hard drive from the Platform Scientist, then create a working folder on your local drive.
2. Download only the <a href="https://drive.google.com/drive/folders/1X3S_NhucjL3Vp2_r4H774H5xdL9fFBA3?usp=share_link" target="_blank">Data Extraction Folder</a> from the Template Folder System to your workspace
3. For shared resources, either:
   - Download shared resources once to a central location outside your project folders, or
   - Follow standard TFS structure and populate `1_resources` in each fieldtrip folder *(note: this causes duplication but matches the TFS structure)*



### Step 2: Populate Your Resources Folder

Once your folder is in place, you need to fill it with the SOPs and supporting materials relevant to your role. All of these come from the <a href="https://drive.google.com/drive/folders/1-TXOWxBSvXX0618xqpZMe30GI4fDvpJj?usp=sharing" target="_blank">Shared Resources</a> folder.

Use the <a href="assets/img/MARIP_SharedResources.png" target="_blank">Shared Resources layout (Figure 6)</a> to understand where everything is kept, and the <a href="https://drive.google.com/file/d/13nf0uaZjpP-QokfQUO__gxV727XF38hu/preview" target="_blank">SOP Decision Tree (Figure 7)</a> to identify which SOPs apply to your role and methods. The full list of SOPs is available in the [Quick Reference & Downloads](#quick-reference--downloads) section below.

Save your resources to: `template_folder_system > project_name > 2_data_collection > fieldtrip > method > 1_resources`

Remember to print all field sheets before leaving for the field.

## Part 3 — Read the Relevant SOPs for Your Role

Once your folder is set up and populated, read through the SOPs you downloaded. Each SOP contains detailed step-by-step procedures for your specific role and method. If you are unsure which SOPs apply to you, refer back to the <a href="https://drive.google.com/file/d/13nf0uaZjpP-QokfQUO__gxV727XF38hu/preview" target="_blank">SOP Decision Tree (Figure 7)</a> or <a href="mailto:atf.bernard@saiab.nrf.ac.za?cc=e.heyns-veale@saiab.nrf.ac.za,a.vanwyk@saiab.nrf.ac.za&subject=MARIP%20Website%20Inquiry">get in touch</a> and we will point you in the right direction.


## Quick Reference & Downloads

Already familiar with the setup and just need to find something? Use the tables below to jump straight to the resource you need.

### Folder Templates

| Folder | Link |
|--------|:----:|
| Shared Resources Folder | <a href="https://drive.google.com/drive/folders/1-TXOWxBSvXX0618xqpZMe30GI4fDvpJj?usp=share_link" target="_blank">Open ↗</a> |
| Template Folder System | <a href="https://drive.google.com/drive/folders/1klWTo05PjByNcBYqMNGgvySqE7anpMxm?usp=share_link" target="_blank">Open ↗</a> |
| Project Folder | <a href="https://drive.google.com/drive/folders/1uwe-C10x_U8FtBPy6i_PFgSEBUsP96qg?usp=share_link" target="_blank">Open ↗</a> |
| Fieldtrip Folder | <a href="https://drive.google.com/drive/folders/1kxoaZLK3YDrvIXf9P_Bwp9jUbYGhdVAp?usp=share_link" target="_blank">Open ↗</a> |
| Data Extraction Folder | <a href="https://drive.google.com/drive/folders/1X3S_NhucjL3Vp2_r4H774H5xdL9fFBA3?usp=share_link" target="_blank">Open ↗</a> |

### Standard Operating Procedures & Resources

| SOP | Description | Link |
|-----|-------------|:----:|
| SOP1a | Project Setup and Data Management | <a href="https://drive.google.com/drive/folders/1lSXq9-cIj7gET9h9USO84CIsnQnHahHd" target="_blank">Open ↗</a> |
| SOP1b | Quality Control | <a href="https://drive.google.com/drive/folders/1lSXq9-cIj7gET9h9USO84CIsnQnHahHd" target="_blank">Open ↗</a> |
| SOP1c | Calibration | <a href="https://drive.google.com/drive/folders/10qKTiBBTQqX2ZB2cpK67g1nnbTm-6Go9" target="_blank">Open ↗</a> |
| SOP2a | BRUVs sampling | <a href="https://drive.google.com/drive/folders/1zO3SdiR9outDXPhAs7IGDVrQjtjySOay" target="_blank">Open ↗</a> |
| SOP2b | Landers sampling | <a href="https://drive.google.com/drive/folders/1zO3SdiR9outDXPhAs7IGDVrQjtjySOay" target="_blank">Open ↗</a> |
| SOP2c | ROVs sampling | <a href="https://drive.google.com/drive/folders/1DHdGFUJ0vWLh121OseOZjME5FPagKrdH" target="_blank">Open ↗</a> |
| SOP2d | DOVs sampling | <a href="https://drive.google.com/drive/folders/1DHdGFUJ0vWLh121OseOZjME5FPagKrdH" target="_blank">Open ↗</a> |
| SOP2e | DropCam sampling | <a href="https://drive.google.com/drive/folders/1RKrnwzT8RMyotGzyHn2CC2xKnUc6TTkX" target="_blank">Open ↗</a> |
| SOP2f | CTD sampling | <a href="https://drive.google.com/drive/folders/1qhyBOrI8ACPmwrG6VGShYYnt3Pq-Tftg" target="_blank">Open ↗</a> |
| SOP3a | Stationary video analysis (BRUVs \| Landers) | <a href="https://drive.google.com/drive/folders/1h5S2q0t569MU-AYpKwgq3RX0HdxCR320" target="_blank">Open ↗</a> |
| SOP3b | Video transect analysis (ROVs \| DOVs) | <a href="https://drive.google.com/drive/folders/1h5S2q0t569MU-AYpKwgq3RX0HdxCR320" target="_blank">Open ↗</a> |
| SOP3c | Still image analysis (DropCam \| ROVs \| Landers) | <a href="https://drive.google.com/drive/folders/1DI8TXl8YBzC_9G87NtHstkYEg08JkXAp" target="_blank">Open ↗</a> |

# Developers

**Author & maintainer:** Angus van Wyk,  **Author:** Elodie Heyns-Veale,  **Author:** Anthony Bernard

<p align="center">
  <img src="assets/img/Footer.png" width="50%">
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>