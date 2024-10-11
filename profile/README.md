<p align="center">
  <a href="https://cims.carleton.ca/#/home">CIMS lab</a>
  |
  <a href="https://canadasdigitaltwin.ca/">Imagine Canada's Digital Twin</a>
  |
  <a href=https://cdt.vercel.app>CDT Demo</a>
  |
  <a href=https://nicoarellano.github.io/cdt/></a>
</p>

<img src="public/images/icdt.gif">
<h1><img src="public/themes/cdt/cdt-logo.png" width="40">&nbsp;Canada's Digital Twin</h1>

# 🌎 The Platform

Canada's Digital Twin platform is a web-based, non-proprietary system designed for the visualization and interaction of multi-scale geospatial information systems (GIS), open data, open building information modeling (BIM), and various other types of digital media, including text, images, and both animated and static 3D models, IFCs, etc.
The platform employs full-stack web development frameworks, such as React.js for the user interface, state management, and memory optimization, and Next.js for file organization, routing, and server-side rendering (SSR). It seamlessly integrates multiple open-source packages to incorporate maps and 3D models. GIS integration utilizes Maplibre as a web map renderer and OpenStreetMap for layers. For 3D models and BIM, it integrates Three.js, Deck.gl, Ifc.js, and openBIM-components. The database is powered by MongoDB and Minio.
The platform efficiently incorporates multi-scale (federal, provincial, municipal) open data, fetched directly from respective organization APIs without the need for data storage. It operates as a framework or infrastructure for referencing and linking data rather than functioning as a system of records.
Finally, the platform boasts an authentication system enabling users to participate in groups, assume different roles and credentials for accessing data and features, collaborate, and input various types of digital media, whether publicly or privately.

# 🧭 Mission

Imagining Canada’s Digital Twin is an **exploration** of the **idea** of a digital twin for Canada.
Our goal is not to resolve the question of a digital twin for Canada, but to determine its feasibility.

# 🔭 Vision

What we are developing is a national, inclusive, and multidisciplinary research consortium to begin developing the technical, cultural, and ethical framework for building Canada’s digital twin.

# ⚖️ Values

- prioritizing equity and inclusion by supporting the largest group of contributors to the AECOO (architecture, engineering, construction, owner operator), **small to medium enterprises (SMEs)**
- using open (FLOSS) standards and technologies as often as possible

<hr style="background-color:#73CEE2; height=2px">

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
