<img src="./.github/asset/illustration/wave_header.svg" width="100%" />

<h1 id="top" align="center">
  <img src="./.github/asset/icon/sass.svg" width="28px" align="center" />
  Sasslys
</h1>

<br />

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<pre align="center">
  <a href="#installation">📦 SETUP</a> • <a href="#configuration">⚙️ CONFIGURATION</a> • <a href="#features">🛰️ FEATURES</a>
</pre>

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<img src="./.github/asset/illustration/sass_cover.svg" width="100%" />

<br />

<div align="center">
  <img src="./.github/asset/illustration/eslint_badge.svg" height="34px" />&nbsp;&nbsp;&nbsp;
  <img src="./.github/asset/illustration/bun_badge.svg" height="34px" />&nbsp;&nbsp;&nbsp;
  <img src="./.github/asset/illustration/github_badge.svg" height="34px" />&nbsp;&nbsp;&nbsp;
  <img src="./.github/asset/illustration/sass_badge.svg" height="34px" />&nbsp;&nbsp;&nbsp;
</div>

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<h2 id="about">
  <img src="./.github/asset/icon/information.svg" width="24px" align="center"/>
  About
</h2>

<table border="0">
<tr>
<td>
A lightweight, modular Sass framework based on design tokens, utility helpers, and fluid typography for rapid layout development.
</td>
</tr>
</table>

<br />

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<h2 id="table-of-content">
  <img src="./.github/asset/icon/book.svg" width="24px" align="center"/>
  Table of content
</h2>

- [<img src="./.github/asset/icon/information.svg" width="20px" align="center" /> About](#about)
- [<img src="./.github/asset/icon/satellite.svg" width="20px" align="center" /> Features](#features)
- [<img src="./.github/asset/icon/thunder.svg" width="20px" align="center" /> Requirements](#requirements)
- [<img src="./.github/asset/icon/package.svg" width="20px" align="center" /> Installation](#installation)
- [<img src="./.github/asset/icon/rocket.svg" width="20px" align="center" /> Usage](#usage)
- [<img src="./.github/asset/icon/gear.svg" width="20px" align="center" /> Configuration](#configuration)

<br />

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<h2 id="features">
  <img src="./.github/asset/icon/satellite.svg" width="24px" align="center" />
  Features
</h2>

- Modular design based on design tokens
- Utility helpers for rapid layout development
- Fluid typography for responsive design
- Lightweight and easy to integrate

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" />

<h2 id="requirements">
  <img src="./.github/asset/icon/thunder.svg" width="24px" align="center" />
  Requirements
</h2>

- <img src="./.github/asset/icon/node.svg" width="20px" align="center" /> node >= **22.17.0**
- <img src="./.github/asset/icon/sass.svg" width="20px" align="center" /> sass >= **1.99.0**
- <img src="./.github/asset/icon/bun.svg" width="20px" align="center" /> bun >= **1.1.0**

<br />

<img src="./.github/asset/illustration/divider.svg" alt="divider" width="100%" align="center" />

<h2 id="installation">
  <img src="./.github/asset/icon/package.svg" width="24px" align="center" />
  Installation
</h2>

<h3><img src="./.github/asset/icon/bun.svg" width="24px" align="center" /> Bun</h3>

```bash
bun i -D sasslys
```

<h3><img src="./.github/asset/icon/npm.svg" width="24px" align="center" /> Npm</h3>

```bash
npm i -D sasslys
```

<h3><img src="./.github/asset/icon/pnpm.svg" width="24px" align="center" /> Pnpm</h3>

```bash
pnpm i -D sasslys
```

<h3><img src="./.github/asset/icon/yarn.svg" width="24px" align="center" /> Yarn</h3>

```bash
yarn i -D sasslys
```

<br />

<img 
  src="./.github/asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<h2 id="usage">
  <img src="./.github/asset/icon/rocket.svg" width="24px" align="center" />
  Usage
</h2>

To use Sasslys in your project, simply import the main Sass file into your stylesheet:

```scss
@use 'sasslys';
@use 'sasslys/config';
```

Sasslys is the default styles, while `sasslys/config` contains the configuration variables that you can customize to fit your project's needs.

<br />

<img 
  src="./.github/asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<h2 id="configuration">
  <img src="./.github/asset/icon/gear.svg" width="24px" align="center" />
  Configuration
</h2>

To customize the configuration of Sasslys, you can modify the variables in the `sasslys/config` file. This allows you to tailor the framework to your project's specific needs.

```scss
@use 'sasslys/config' with (
  $spacing-2: 0.5rem,
  $primary-color: #ff5733;
});
```

Or you can create a new file and import it before importing the main Sasslys file:

```scss
@use 'sasslys/config' as *;
@use 'sasslys';

$spacing-2: 0.5rem;
$primary-color: #ff5733;
```

<br />

<img 
  src="./.github/asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<pre align="center">
  <a href="#top">BACK TO TOP</a>
</pre>

<img 
  src="./.github/asset/illustration/divider.svg" 
  alt="divider" 
  width="100%" 
/>

<pre align="center">
  Copyright © All rights reserved,
  developed by LuisdaByte and
</pre>
<div align="center">
  <img src="./.github/asset/illustration/astralys_logo.svg" width="120px" align="center" />
</div>

<img src="./.github/asset/illustration/wave_footer.svg" width="100%" />