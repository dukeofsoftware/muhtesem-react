# muhtesem-react

En çok kullandığım, yararlı bulduğum ve sevdiğim React ve Next.js kaynaklarının bir listesi

---

## Başlıklar
- [React ve Next.js](#react)

  - [React Paketleri](#react-paketleri)
    - [Formlar](#formlar-için)
    - [Veri Çekmek](#veri-çekerken)
    - [State Yönetimi](#state-yönetimi)
    - [Testing](#testing)
    - [İşe Yarar Paketler](#i̇şe-yarar-paketler)
  - [Next.js Paketleri](#nextjs-paketleri)
  - [React UI Kitleri ve Geliştirme Araçları](#react-ui-kitleri-ve-geliştirme-araçları)
  - [TailwindCSS](#tailwindcss-paketleri)
  - [React Şablonları](#react-şablonları)
  - [React Youtube Kanalları](#react-youtube-kanalları)
  - [React Udemy Kursları](#react-udemy-kursları)
  - [Paket Menajeri](#paket-menajeri)

- [Projeye Başlarken](#projeye-başlarken)
  - [Projenin kurulumu](#projenin-kurulumu-eslint-prettier-tailwindcss-ve-dosya-yapısı-içerir)
  - [Production Action Workflow](#production-build-için-action-workflow)
  - [Preview Action Workflow](#preview-build-için-action-workflow)

---

### React Paketleri

- #### Formlar için

  - [React Hook Form](https://react-hook-form.com/) => Önerdiğim
  - [Formik](https://formik.org/)
  - [Yup](https://github.com/jquense/yup) => Form doğrulamaları için react-hook-form ve formik ile beraber kullanılmasını önerdiğim

- #### Veri Çekerken

  - [React Query](https://tanstack.com/query/v3/) => önerdiğim
  - [SWR](https://swr.vercel.app/)
  - [axios]() => HTTP isteklerini yapmak için SWR ve react-query için önerdiğim

- #### State Yönetimi

  - [Zustand](https://github.com/pmndrs/zustand) => Başlangıç için önerdiğim
  - [Redux Toolkit](https://redux-toolkit.js.org/)

- #### Testing

  - [cypress](https://docs.cypress.io/guides/overview/why-cypress)
  - [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro/)
  - [jest](https://jestjs.io/)

- #### İşe Yarar Paketler
  - [react-icons](https://react-icons.github.io/react-icons/) => Popüler ikon kütüphanelerinden ikonları React uygulamasına eklemek için
  - [react-toastify](https://www.npmjs.com/package/react-toastify) => Bildirimler için
  - [react-hot-toast](https://react-hot-toast.com/) => Bildirimler için
  - [sonner](https://github.com/emilkowalski/sonner) => Bildirimler için
  - [react-helmet](https://www.npmjs.com/package/react-helmet) => SEO ayarı için
  - [react-modal](https://www.npmjs.com/package/react-modal) => Modal penceresi oluşturmak için
  - [react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) => Sürükle ve bırak özellikleri eklemek için
  - [react-infinite-scroller](https://www.npmjs.com/package/react-infinite-scroller) => Sonsuz kaydırma için
  - [react-leaflet](https://react-leaflet.js.org/) => Harita kullanımı için
  - [framer-motion](https://www.framer.com/motion/) => Animasyonlar için
  - [react-chartjs-2](https://react-chartjs-2.js.org/) => Grafikler için
  - [react-joyride](https://react-joyride.com/) => Site turu için
  - [lodash.debounce](https://www.npmjs.com/package/lodash.debounce) => Optimizasyon için
  - [storybook](https://storybook.js.org/docs/react/writing-docs/docs-page) => UI bileşenlerin geliştirilip test edilmesi için
  - [react-loading-skeleton](https://www.npmjs.com/package/react-loading-skeleton) => Yükleme göstergesi için
  - [react-table](https://react-table-v7.tanstack.com/) => Tablo oluşturmak ve yönetmek için
  - [firebase](https://firebase.google.com/docs/web/setup?hl=tr)
  - [supabase](https://supabase.com/docs)

### Next.js Paketleri

- [next-offline](https://www.npmjs.com/package/next-offline) => Next.js uygulamasını offline kullanabilmek için
- [next-auth](https://next-auth.js.org/) => Doğrulama işlemleri için
- [next-translate](https://github.com/aralroca/next-translate) => Çoklu dil desteği için
- [next-i18next](https://github.com/i18next/next-i18next) => Çoklu dil desteği için
- [next-sitemap](https://www.npmjs.com/package/next-sitemap) => sitemap oluşturmak için
- [nextjs-progressbar](https://www.npmjs.com/package/nextjs-progressbar) => progress bar için
- [@next/mdx](https://nextjs.org/docs/advanced-features/using-mdx) => mdx dosyaları için
- [next-mdx-remote](https://github.com/hashicorp/next-mdx-remote#react-server-components-rsc--nextjs-app-directory-support) => Serverdan mdx dosyası çekmek için
- [@next/bundle-analyzer](https://www.npmjs.com/package/@next/bundle-analyzer) => Uygulamanızdaki paketlerin boyutunu analiz etmenize yardım eder
- [next-pwa](https://www.npmjs.com/package/next-pwa)
- [next-compose-plugins](https://www.npmjs.com/package/next-compose-plugins) => Birden fazla paketi bir arada kullanmak için
- [next-themes](next-themes) => Next.js uygulamasında tema kulanmak için
- [pusher-js](https://pusher.com/) => Realtime işlemler için
- [database-js](https://www.npmjs.com/package/database-js) => Database
- [prisma](https://www.prisma.io/) => Database
- [stripe](https://www.npmjs.com/package/stripe) => Ödeme işlemleri

### Paket Menajeri

- [npm](https://www.npmjs.com/)
- [yarn](https://yarnpkg.com/)
- [pnpm](https://pnpm.io/) => Önerdiğim

### React UI Kitleri ve Geliştirme Araçları

- [TailwindCSS](https://tailwindcss.com/) => Önerdiğim
- [Material UI](https://mui.com/) => Önerdiğim
- [Material Tailwind](https://www.material-tailwind.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Mantine](https://mantine.dev/)

### TailwindCSS paketleri

- [class-variance-authority](https://cva.style/docs)
- [tailwind-merge](https://www.npmjs.com/package/tailwind-merge)
- [@tailwindcss/forms](https://github.com/tailwindlabs/tailwindcss-forms)
- [@tailwindcss/typography](https://tailwindcss.com/docs/typography-plugin)
- [@tailwindcss/line-clamp](https://www.npmjs.com/package/@tailwindcss/line-clamp)
- [tailwindcss-debug-screens](https://www.npmjs.com/package/tailwindcss-debug-screens)
- [prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)

### React Şablonları

- [Next.js v13.2 tailwindcss template with prettier and eslint](https://github.com/dukeofsoftware/next-project-starter) => önerdiğim

### React Youtube Kanalları

- #### Türkçe
  - [Prototürk | React ile Proje Geliştirme Serisi](https://www.youtube.com/watch?v=slVS7QNsSk8&list=PLfAfrKyDRWrGXWpnJdyC4yXIW6v-PcFu-) => React için önerdiğim kaynak
  - [Yunus Eş](https://www.youtube.com/@YunusEs) => React başlangıç için önerdiğim Kaynak
  - [Mehmet Pekcan | Sıfırdan İleri Seviye Next.js v13](https://www.youtube.com/watch?v=QLFahNliOW0&list=PLf3cxVeAm439RsaHrGACExl3o060pM7W2) => Next.js için önerdiğim kaynak
- #### İngilizce
  - [frontendfyi](https://www.youtube.com/@frontendfyi)
  - [Josh tried coding](https://www.youtube.com/@joshtriedcoding)
  - [JavaScript Mastery](https://www.youtube.com/@javascriptmastery)
  - [Jack Herrington](https://www.youtube.com/@jherr)
  - [React & Next js Projects with Sahand](https://www.youtube.com/@reactproject)
  - [RoadsideCoder](https://www.youtube.com/@RoadsideCoder/videos)
  - [Sakura Dev](https://www.youtube.com/@SakuraDev)
  - [Shadee Merhi](https://www.youtube.com/@shadmerhi)
  - [Smoljames](https://www.youtube.com/@Smoljames)
  - [Sonny Sangha](https://www.youtube.com/@SonnySangha)

### React Udemy Kursları

- [Mehmet Pekcan | Sıfırdan, İleri Seviye Next.js 13 ile Web App Geliştirme
  ](https://www.udemy.com/course/sifirdan-ileri-seviye-nextjs-13-ile-web-app-gelistirme/) => Next.js için önerdiğim

---

### Projeye Başlarken

#### Projenin kurulumu. Eslint prettier tailwindcss ve dosya yapısı içerir.

```
pnpx  create-next-app -e https://github.com/dukeofsoftware/next-project-starter
```

#### Projenin otomatik olarak her committe yayınlanması için ayarlar (CI/CD)

[Full döküman](https://voracious.dev/blog/how-to-deploy-to-vercel-with-github-actions)

```
pnpm add -D vercel
```

```
pnpx vercel login
```

```
pnpx vercel link
```

### VERCEL_ORG_ID, VERCEL_PROJECT_ID, VERCEL_TOKEN repository secrets olarak girilmelidir.

#### production build için action workflow

```
name: deploy
on:
  push:
    branches:
      - main
  workflow_dispatch:
env:
  VERCEL_ORG_ID: ${{ secrets.VERCEL_ORG_ID }}
  VERCEL_PROJECT_ID: ${{ secrets.VERCEL_PROJECT_ID }}
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: pnpm/action-setup@v2
        with:
          node-version: 16
          cache: pnpm
      - run: pnpm install --immutable --frozen-lockfile
      - run: pnpx vercel pull --yes --environment=production --token=${{ secrets.VERCEL_TOKEN }}
      - run: pnpx vercel build --prod --token=${{ secrets.VERCEL_TOKEN }}
      - run: pnpx vercel deploy --prod --prebuilt --token=${{ secrets.VERCEL_TOKEN }}
      - id: deploy
        run: echo "::set-output name=url::$(pnpx vercel deploy --prebuilt --token=${{ secrets.VERCEL_TOKEN }})"
```

#### Preview build için action workflow

```
name: preview
on:
  pull_request:
  workflow_dispatch:
env:
  VERCEL_ORG_ID: ${{ secrets.VERCEL_ORG_ID }}
  VERCEL_PROJECT_ID: ${{ secrets.VERCEL_PROJECT_ID }}
jobs:
  preview:
    runs-on: ubuntu-latest
    environment:
      name: preview
      url: ${{ steps.deploy.outputs.url }}
    steps:
      - uses: actions/checkout@v3
      - uses: pnpm/action-setup@v2
        with:
          node-version: 16
          check-latest: true
          cache: pnpm
      - run: pnpm install --immutable
      - run: pnpx vercel pull --yes --environment=preview --token=${{ secrets.VERCEL_TOKEN }}
      - run: pnpx vercel build --token=${{ secrets.VERCEL_TOKEN }}
      - id: deploy
        run: echo "::set-output name=url::$(pnpx vercel deploy --prebuilt --token=${{ secrets.VERCEL_TOKEN }})"
```
