<div align="center">

# Hi, I'm Om Lanke 👋

**Full-Stack Developer · Mobile · ML · Distributed Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-om--lanke-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/om-lanke)
[![LeetCode](https://img.shields.io/badge/LeetCode-omlanke-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://www.leetcode.com/omlanke)
[![Codeforces](https://img.shields.io/badge/Codeforces-omlanke-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/omlanke)
[![CodeChef](https://img.shields.io/badge/CodeChef-oplanke-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://www.codechef.com/users/oplanke)
[![Email](https://img.shields.io/badge/Email-oplanke@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:oplanke@gmail.com)

</div>

---

## About Me

I'm a Computer Science student at **KJSCE** and an active member of the **CSI Student's Chapter**. I build across the full stack — distributed backends, mobile apps (React Native, Flutter, Swift), generative AI pipelines, and interactive computer-vision tools.

- 🔭 Currently exploring **Hono · Svelte · Cloudflare Stack**
- 💬 Ask me about **React · Python · Tailwind · Distributed Systems**
- 📫 Reach me at **oplanke@gmail.com**

---

## 🚀 Projects

### 🔗 [MeshWallet](https://github.com/OmLanke/MeshWallet)
> **Self-custodial Ethereum wallet with offline BLE mesh transactions**

React Native / Expo mobile wallet that routes signed Ethereum transactions over a Bluetooth Low Energy mesh — no internet required. Any device running the app acts as a relay node; once connectivity is restored, buffered transactions flush to the Sepolia RPC automatically. Private keys are stored in the OS secure enclave (`expo-secure-store`), transactions signed with `@noble/curves` secp256k1, and every BLE packet AES-256-GCM encrypted with per-packet nonces.

`TypeScript` `React Native` `Expo` `ethers.js v6` `BLE Mesh` `SQLite` `WalletConnect v2` `NativeWind` `Zustand`

---

### 🎟️ [TicketFlow — fms](https://github.com/OmLanke/fms)
> **Production-grade polyglot microservice ticketing platform**

Distributed event-ticketing system demonstrating polyglot microservice patterns. Java Spring Boot for transactional seat booking, Python FastAPI for the event catalogue, Bun/Elysia for the high-throughput API gateway. The entire booking lifecycle (seat locking → payment → confirmation) runs as a **choreography saga** over Apache Kafka — no central orchestrator. Every service owns its own datastore. Ships with Prometheus + Grafana + Jaeger + Loki and Kubernetes KEDA autoscaling that reacts to Kafka consumer lag.

`Java 21` `Python` `Bun/Elysia` `Apache Kafka` `PostgreSQL` `MongoDB` `Redis` `Docker Compose` `Kubernetes` `KEDA` `React`

---

### 🪑 [Ticketly](https://github.com/OmLanke/ticketly)
> **React Native event booking app with interactive SVG seat maps and QR tickets**

Full React Native / Expo app for event discovery, seat selection, and digital ticket management. Features an interactive SVG venue map where users tap individual seats, a two-layer state design (Redux for global state + CartContext for the ephemeral checkout flow), offline-first QR tickets stored in AsyncStorage, and a local `json-server` mock API. Includes unit tests for the price calculator, QR payload builder, date formatter, and cart reducer.

`JavaScript` `React Native` `Expo` `Redux Toolkit` `React Navigation` `react-native-svg` `AsyncStorage` `Jest`

---

### 🎓 [NextPlacement](https://github.com/OmLanke/nextplacement)
> **TypeScript monorepo placement portal with separate student and admin apps**

Turborepo + pnpm workspaces monorepo with a `student` app and an `admin` app, shared UI packages (shadcn/ui), Docker Compose dev and production configs, and a Dockerfile for containerised deployment. Handles job listings, student applications, status tracking, and admin-side applicant management.

`TypeScript` `Next.js` `Turborepo` `pnpm` `shadcn/ui` `TailwindCSS` `Docker` `ESLint` `Prettier`

---

### 🏫 [RedCard](https://github.com/OmLanke/red_card)
> **Flutter campus event management app for students and council admins**

Full-featured Flutter 3.24 app for Somaiya College — students discover events, register one-tap and receive scannable QR tickets; council admins create events, track registrations, and manage attendance. Role-based access is enforced end-to-end via Firebase Auth + Firestore rules. Built with Riverpod state management, go_router navigation, and Material 3 with Somaiya branding.

`Dart` `Flutter` `Firebase (Auth + Firestore + FCM + Storage)` `Riverpod` `go_router` `Material 3`

---

### 🔭 [Hough Transform Demo](https://github.com/OmLanke/hough-transform-demo)
> **Interactive browser visualizer for the Hough Line Transform**

Zero-dependency React SPA that makes the Hough Line Transform tangible. Click to place edge points and watch sinusoidal curves accumulate in parameter space in real time; peaks pulse when the vote threshold is crossed and detected lines draw themselves back onto the canvas with a glow effect. A road demo mode runs Sobel edge detection + ROI-filtered Hough to extract lane lines from a procedurally rendered scene.

`JavaScript` `React 18` `Vite` `Canvas 2D API` `Sobel Filter` `Computer Vision`

---

### 🐉 [Pookiemon](https://github.com/OmLanke/gen_pookiemon)
> **WGAN-GP that generates novel Pokémon sprites from noise**

Wasserstein GAN with Gradient Penalty trained on ~830 official Pokémon sprites. The pipeline augments sprites 14× to ~11 600 images, trains a 5-layer transposed-convolution generator against a SpectralNorm critic, supports `torch.compile`, TensorBoard logging, and Apple MPS / CUDA / CPU auto-selection. A cleaner PyTorch rewrite with Colab support lives at [wgan_pokemon](https://github.com/OmLanke/wgan_pokemon).

`Python` `PyTorch` `WGAN-GP` `GAN` `Generative AI` `TensorBoard` `uv`

---

### ⚡ [react-express-bun-template](https://github.com/OmLanke/react-express-bun-template) ⭐ 6
> **Minimal React + Vite + Express full-stack starter on Bun**

Production-ready monorepo starter: React (Vite) frontend + Express backend, everything running on Bun for fast installs and dev cycles. Community-used scaffold with 6 stars.

`JavaScript` `React` `Vite` `Express` `Bun` `TailwindCSS`

---

## 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend & Runtime**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorBoard](https://img.shields.io/badge/TensorBoard-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-navy-five-86.vercel.app/api?username=omlanke&show_icons=true&theme=vision-friendly-dark&locale=en&hide_border=true" alt="Om's GitHub stats" height="165"/>
  &nbsp;
  <img src="https://github-readme-stats-navy-five-86.vercel.app/api/top-langs?username=omlanke&show_icons=true&theme=vision-friendly-dark&locale=en&layout=compact&hide_border=true" alt="Top languages" height="165"/>
</p>
