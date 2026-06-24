<div align="center">
  <img src="/banner.svg" alt="attar — web developer" width="100%" />
  <br/>
  <sub>jakarta, indonesia</sub>
</div>

<br/>

<img src="divider.svg" width="100%" alt="" />

<br/>

### `// tentang saya`

Saya Attar — web developer dari Jakarta yang tertarik membangun antarmuka yang jelas, mudah dipelajari, dan dapat diakses. Saya menulis kode dengan tujuan dua‑lapis: menyelesaikan masalah pengguna, dan menjadi bahan ajar bagi siapa saja yang ingin belajar arsitektur frontend modern.

Dalam pekerjaan saya, saya menekankan kebersihan komponen, dokumentasi hidup (contoh & stories), dan praktik yang membuat proyek mudah diikuti oleh mahasiswa atau kontributor baru.

<br/>

### `// proyek unggulan` (ringkasan & teknik)

## CitizenCare ID
- Deskripsi: Platform civic‑tech untuk melaporkan masalah komunitas (mis. jalan rusak, kebersihan). Dirancang supaya kode dapat dibaca dan dipelajari — setiap alur utama diberi komentar dan contoh penggunaan.
- Teknologi utama: Next.js, Supabase (Postgres + Auth + Storage), Tailwind CSS
- Fitur penting: autentikasi, unggah foto, pembuatan laporan dengan lokasi, moderasi sederhana, arsitektur fitur yang mudah diikuti.

---

## Wavely
- Deskripsi: Frontend pemutar musik yang terkomponenisasi, fokus pada pengalaman pengguna (micro‑interactions), caching offline ringan, dan performa pemutaran.
- Teknologi utama: React, TypeScript, Supabase (sebagai backend ringan untuk metadata & storage)
- Fitur penting: playlist, pemutar yang dapat di‑embed, kontrol keyboard, responsive layout.
- Demo: https://wavelymusical.netlify.app

<br/>

### `// stack ringkas (project-mapped)`

```js
const stack = {
  core: {
    languages: ["TypeScript", "JavaScript (ES2021)"],
    package_manager: "pnpm / npm",
    monorepo_tooling: null // projects are standalone; replace with turborepo / pnpm-workspace if adopted
  },
  projects: {
    CitizenCareID: {
      role: "civic‑tech app (frontend + Supabase backend)",
      frontend: ["Next.js (React)", "React 18", "Tailwind CSS"],
      backend: ["Supabase (Postgres, Auth, Storage)"],
      infra: ["Vercel (deploy)", "Supabase (managed Postgres)"],
      notes: "code organized for learnability: feature folders, documented flows"
    },
    Wavely: {
      role: "componentized music frontend",
      frontend: ["React 18 + TypeScript"],
      audio: ["Web Audio API / howler.js (implementation varies)"],
      storage: ["Supabase Storage (media)"],
      infra: ["Netlify (deploy)"],
      notes: "focus on UX, player components, keyboard & accessibility"
    }
  },
  components_and_ui: [
    "Radix UI / Headless UI (accessibility primitives)",
    "Design tokens (CSS variables)",
    "Framer Motion (micro-interactions)"
  ],
  dev_and_testing: [
    "Storybook (component catalog)",
    "Vitest / Jest (unit)",
    "Playwright (E2E)",
    "Visual regression (Chromatic or alternative)"
  ],
  ci_cd_and_tooling: ["GitHub Actions", "ESLint", "Prettier", "commitlint", "pnpm / npm" ]
};
```

Stack ini disusun per proyek supaya pembaca bisa langsung melihat teknologi yang relevan untuk tiap produk, plus tooling yang mendukung workflow design‑first dan pengembangan yang mudah diajarkan.

<br/>

### `// kontak`

<p>
  <a href="https://github.com/attarvvv"><img src="https://img.shields.io/badge/GitHub-6366F1?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="mailto:attarr.dev@gmail.com"><img src="https://img.shields.io/badge/Email-6366F1?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/muhammad-attar-67a536263/"><img src="https://img.shields.io/badge/LinkedIn-6366F1?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

<br/>

<div align="center">
  <sub><i>code that teaches — design that scales.</i></sub>
</div>
