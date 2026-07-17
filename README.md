<div align="center">

# PrexCoder

### Software engineer and founder of Compiur Tech

[![Compiur Tech](https://img.shields.io/badge/compiur.com-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://compiur.com)
![Profile Views](https://komarev.com/ghpvc/?username=your-github-prexcoder&label=Profile%20Views&color=7C3AED&style=for-the-badge)
</div>

---

<h2>
  <img
    src="https://cdn.simpleicons.org/aboutdotme/7C3AED"
    width="24"
    height="24"
    alt=""
    align="center"
  >
  About
</h2>

🛠️ I build full-stack applications and regularly rediscover that every
"simple feature" comes with at least one unexpected edge case 🐛.

🧠 I enjoy learning new things, experimenting with unfamiliar tools,
and finding out that the rabbit hole has several undocumented sublevels.

💻 I mostly work with **C#/.NET, TypeScript, React, Node.js, SQL, Redis,
AWS, and GCP**, plus whatever else the problem calls for.

🏗️ Outside of that work, I run **[Compiur Tech](https://compiur.com)**,
where I build software products and Unreal Engine tooling.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">
  <img
    src="https://cdn.simpleicons.org/unrealengine/7C3AED"
    width="22"
    height="22"
    alt=""
    align="center"
  >
  MultiForge
</h3>

<p align="center">
  <a href="https://multiforge.compiur.com">
    <img
      src="https://compiur.com/assets/MultiForgeLogo-360.webp?v=20260702e"
      alt="MultiForge"
      width="360"
    >
  </a>
</p>

<p>
An Unreal Engine 5.7 multiplayer project built with C++, Blueprints,
UMG, custom plugins, and automated multiplayer testing.
</p>

<p align="center">
  <a href="https://multiforge.compiur.com">
    <img
      src="https://img.shields.io/badge/Official_Site-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white"
      alt="MultiForge official site"
    >
  </a>
  <a href="https://github.com/PrexCoder/Multiforge">
    <img
      src="https://img.shields.io/badge/GitHub_Repository-181717?style=for-the-badge&logo=github&logoColor=white"
      alt="MultiForge GitHub repository"
    >
  </a>
</p>

</td>
<td width="50%" valign="top">

<h3 align="center">
  <img
    src="https://cdn.simpleicons.org/svg/22D3EE"
    width="22"
    height="22"
    alt=""
    align="center"
  >
  Cut Shape Studio
</h3>

<p align="center">
  <a href="https://cut.compiur.com">
    <img
      src="https://img.shields.io/badge/Current_version-1.8.3-22D3EE?style=flat-square"
      alt="Cut Shape Studio version 1.8.3"
    >
  </a>
</p>

<p align="center">
  <a href="https://cut.compiur.com">
    <img
      src="https://compiur.com/assets/cut-shape-studio-preview-380.webp?v=20260708"
      alt="Cut Shape Studio"
      width="380"
    >
  </a>
</p>

<p>
A visual editor for creating custom-shaped images with visual point
editing, instant previews, and SVG, CSS, and React export.
</p>

<p align="center">
  <a href="https://cut.compiur.com">
    <img
      src="https://img.shields.io/badge/Official_Site-0891B2?style=for-the-badge&logo=googlechrome&logoColor=white"
      alt="Cut Shape Studio official site"
    >
  </a>
</p>

</td>
</tr>
</table>

---

<h2>
  <img
    src="https://cdn.simpleicons.org/unrealengine/7C3AED"
    width="24"
    height="24"
    alt=""
    align="center"
  >
  Inside MultiForge
</h2>

MultiForge is where I work on multiplayer gameplay, reusable Unreal
Engine systems, automated testing, and build infrastructure.

### Project stack

<p>
  <img
    src="https://img.shields.io/badge/Unreal_Engine-5.7-0E1128?style=flat-square&logo=unrealengine&logoColor=white"
    alt="Unreal Engine 5.7"
  >
  <img
    src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"
    alt="C++"
  >
  <img
    src="https://img.shields.io/badge/Blueprints-137CBD?style=flat-square&logo=unrealengine&logoColor=white"
    alt="Blueprints"
  >
  <img
    src="https://img.shields.io/badge/UMG-7C3AED?style=flat-square&logo=unrealengine&logoColor=white"
    alt="UMG"
  >
</p>

<p>
  <img
    src="https://img.shields.io/badge/OnlineSubsystemNull-Local_sessions-334155?style=flat-square&logo=unrealengine&logoColor=white"
    alt="OnlineSubsystemNull"
  >
  <img
    src="https://img.shields.io/badge/Gauntlet-Test_automation-B91C1C?style=flat-square&logo=unrealengine&logoColor=white"
    alt="Gauntlet"
  >
  <img
    src="https://img.shields.io/badge/Docusaurus-Documentation-3ECC5F?style=flat-square&logo=docusaurus&logoColor=white"
    alt="Docusaurus"
  >
  <img
    src="https://img.shields.io/badge/GitHub_Actions-CI-2088FF?style=flat-square&logo=githubactions&logoColor=white"
    alt="GitHub Actions"
  >
</p>

Local multiplayer sessions are tested with **OnlineSubsystemNull**.
Multiplayer and runtime tests are automated with **Gauntlet**.
Documentation is built with **Docusaurus and React**, while builds run
through **GitHub Actions on self-hosted runners**.

### In-house Unreal Engine plugins

The systems behind MultiForge are split into reusable plugins developed
in-house at **Compiur Tech**.

- **Reuso:** A world-independent gameplay foundation containing the shared focus trace, highlighting components, and networking and ownership helpers used by the other plugins.

- **ReplicatedGrab:** Server-authoritative physics interaction with replicated pickup, carrying, throwing, free-physics and socketed carry modes, custom carry poses, and unit-tested carry calculations.

- **Inventory:** A replicated, server-authoritative grid and hotbar inventory with item definitions, stacking, weight, containers, transfers, drag-and-drop UI, and persistence.

- **Multiplayer:** Platform-independent sessions and parties built on Unreal's Online Subsystem and beacons, with support for Null, Steam, and EOS through configuration. Party, reconnect, session data, and lobby-code logic is unit-tested.

- **LiveOpsApi:** A dedicated-server HTTP API implementing the OpenAPI contract, authentication, MFA, and an isolated data-provider interface. It also powers the TypeScript operations dashboard.

- **ReusoFunctionalTests:** Functional and automation testing infrastructure, including a multiplayer test harness for two-client and dedicated-server scenarios with structured JSON output for CI.

- **BlueprintMCP:** An Unreal Engine editor plugin with a C++ HTTP backend and C#/.NET MCP server for AI-assisted authoring and inspection of Blueprints, materials, levels, UMG, DataTables, data assets, foliage, and Niagara systems.

---

<h2>
  <img
    src="https://cdn.simpleicons.org/stackshare/0690FA"
    width="24"
    height="24"
    alt=""
    align="center"
  >
  Tech
</h2>

### Unreal Engine

<p>
  <img
    src="https://skillicons.dev/icons?i=unreal,cpp"
    alt="Unreal Engine and C++"
  >
</p>

### Application Development

<p>
  <img
    src="https://skillicons.dev/icons?i=cs,dotnet,ts,js,react,angular,nodejs"
    alt="C Sharp, .NET, TypeScript, JavaScript, React, Angular, and Node.js"
  >
</p>

### Data

<p>
  <img
    src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis"
    alt="PostgreSQL, MySQL, MongoDB, and Redis"
  >
</p>

### Infrastructure

<p>
  <img
    src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,kubernetes,jenkins,githubactions"
    alt="AWS, Google Cloud, Azure, Docker, Kubernetes, Jenkins, and GitHub Actions"
  >
</p>

### Tools

<p>
  <img
    src="https://skillicons.dev/icons?i=git,github,gitlab,visualstudio,vscode,rider,postman"
    alt="Git, GitHub, GitLab, Visual Studio, Visual Studio Code, Rider, and Postman"
  >
</p>

---

<h2>
  <img
    src="https://cdn.simpleicons.org/github/7C3AED"
    width="24"
    height="24"
    alt=""
    align="center"
  >
  Links
</h2>

<p>
  <a href="https://compiur.com">
    <img
      src="https://img.shields.io/badge/Compiur_Tech-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white"
      alt="Compiur Tech"
    >
  </a>
  <a href="https://multiforge.compiur.com">
    <img
      src="https://img.shields.io/badge/MultiForge-7C3AED?style=for-the-badge&logo=unrealengine&logoColor=white"
      alt="MultiForge"
    >
  </a>
  <a href="https://cut.compiur.com">
    <img
      src="https://img.shields.io/badge/Cut_Shape_Studio-0891B2?style=for-the-badge&logo=svg&logoColor=white"
      alt="Cut Shape Studio"
    >
  </a>
</p>
