<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="vite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

<h3 align="center">Modern UI/UX SaaS Website</h3>


## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets (Code to Copy)](#snippets)


If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects
like these step-by-step in a beginner-friendly manner!

## <a name="introduction">🤖 Introduction</a>

Xora is a Modern UI/UX SaaS website developed using React.js and Tailwind CSS that exemplifies modern UI/UX principles.
Its sleek design, seamless animations, and overall user experience set a high standard, serving as a reference or
inspiration for future modern applications or websites in general.

If you're getting started and need assistance or face any bugs, join our active Discord community with over **34k+**
members. It's a place where people help each other out.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Vite
- React.js
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Stunning Sections**: Includes hero, features, pricing (monthly/yearly), FAQ, testimonials, and download software
sections.

👉 **Smooth Animations**: Complex CSS for fluid animations and eye-catching effects.

👉 **Cool CSS Gradients**: Beautiful gradient effects using CSS `before` and `after` pseudo-elements.

👉 **Seamless Navigation**: Offers a smooth user experience with intuitive navigation and scrolling.

👉 **Optimized Performance**: Built for fast loading and an optimized experience.

👉 **Pixel Perfect Design**: Ensures flawless responsiveness across all devices and screen sizes.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>tailwind.config.js</code></summary>

```jsx
/** @type {import('tailwindcss').Config} */
export default {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: {
    extend: {
      colors: {
        p1: '#2EF2FF',
        p2: '#3C52D9',
        p3: '#C8EA80',
        p4: '#EAEDFF',
        p5: '#C4CBF5',
        s1: '#080D27',
        s2: '#0C1838',
        s3: '#334679',
        s4: '#1959AD',
        s5: '#263466',
        black: {
          DEFAULT: '#000000',
          100: '#05091D',
        },
      },
      boxShadow: {
        100: '0px 4px 4px rgba(0, 0, 0, 0.25), 0px 16px 24px rgba(0, 0, 0, 0.25), inset 0px 3px 6px #1959AD',
        200: '0px 4px 4px rgba(0, 0, 0, 0.25), 0px 16px 24px rgba(0, 0, 0, 0.25), inset 0px 4px 10px #3391FF',
        300: '0px 4px 4px rgba(0, 0, 0, 0.25), 0px 16px 24px rgba(0, 0, 0, 0.25), inset 0px 3px 6px #1959AD',
        400: 'inset 0px 2px 4px 0 rgba(255, 255, 255, 0.05)',
        500: '0px 16px 24px rgba(0, 0, 0, 0.25), 0px -14px 48px rgba(40, 51, 111, 0.7)',
      },
      fontFamily: {
        inter: ['Inter', 'sans-serif'],
        poppins: ['Poppins', 'sans-serif'],
      },
      transitionProperty: {
        borderColor: 'border-color',
      },
      spacing: {
        '1/5': '20%',
        '2/5': '40%',
        '3/5': '60%',
        '4/5': '80%',
        '3/20': '15%',
        '7/20': '35%',
        '9/20': '45%',
        '11/20': '55%',
        '13/20': '65%',
        '15/20': '75%',
        '17/20': '85%',
        '19/20': '95%',
        22: '88px',
        100: '100px',
        512: '512px',
        330: '330px',
        388: '388px',
        400: '400px',
        440: '440px',
        640: '640px',
        960: '960px',
        1230: '1230px',
      },
      zIndex: {
        1: '1',
        2: '2',
        4: '4',
      },
      lineHeight: {
        12: '48px',
      },
      borderRadius: {
        14: '14px',
        20: '20px',
        40: '40px',
        half: '50%',
        '7xl': '40px',
      },
      flex: {
        50: '0 0 50%',
        320: '1px 0 320px',
        300: '0 0 300px',
        540: '0 0 540px',
        280: '0 0 280px',
        256: '0 0 256px',
        100: '0 0 100%',
      },
    },
  },
  plugins: [],
};
```

</details>

<details>
<summary><code>index.css</code></summary>

```css
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

@tailwind base;
@tailwind components;
@tailwind utilities;

@layer base {
  html {
    @apply bg-s1;
  }

  body {
    @apply font-poppins text-[16px] tracking-[-0.03em] text-p5;
  }

  a {
    @apply no-underline;
  }

  img {
    @apply block max-w-full;
  }

  button {
    @apply bg-none tracking-[-0.03em];
  }

  input {
    @apply tracking-[-0.03em];
  }
}

@layer utilities {
  /* START of Typography */
  .h-num {
    @apply font-inter text-[72px] font-bold leading-[84px];
  }

  .h1 {
    @apply text-[84px] font-black leading-[84px] tracking-[-0.03em];
  }

  .h2 {
    @apply text-[64px] font-black leading-[64px];
  }

  .h3 {
    @apply text-[48px] font-semibold leading-[56px] tracking-[-0.02em];
  }

  .h4 {
    @apply text-[40px] font-semibold leading-[52px];
  }

  .h5 {
    @apply text-[32px] font-semibold leading-[40px];
  }

  .h6 {
    @apply text-[24px] font-medium leading-[36px];
  }

  .body-1 {
    @apply text-[22px] leading-[36px];
  }

  .body-2 {
    @apply text-[18px] font-semibold leading-[32px];
  }

  .body-3 {
    @apply text-[16px] leading-[28px] tracking-[0.02em];
  }

  .base {
    @apply text-[16px] font-medium leading-[24px] tracking-[0.03em];
  }

  .base-bold {
    @apply text-[16px] font-bold leading-[24px];
  }

  .base-small {
    @apply text-[14px] font-semibold leading-[18px] tracking-[0.03em];
  }

  .small-1 {
    @apply text-[14px] font-semibold leading-[18px] tracking-[0.03em];
  }

  .small-2 {
    @apply text-[12px] font-bold leading-[16px] tracking-[0.3em];
  }

  .small-compact {
    @apply text-[12px] font-semibold leading-[18px] tracking-[0.03em];
  }

  /* END of Typography */
  /* START of Gradients */
  .g1 {
    background: linear-gradient(rgba(196, 203, 245, 0.5), transparent);
  }

  .g2 {
    background: linear-gradient(#3062a3, #19549f);
  }

  .g3 {
    background: linear-gradient(#3c52d9, #0c1838);
  }

  .g4 {
    background: linear-gradient(#253575, #162561);
  }

  .g5 {
    background: linear-gradient(#334679, #162561);
  }

  .g6 {
    background: linear-gradient(#334679, #0c1838);
  }

  .g7 {
    background: linear-gradient(#1b275a, #0e1434);
  }

  .g8 {
    background: linear-gradient(to right, transparent, #2ef2ff, transparent);
  }

  .g9 {
    background: linear-gradient(#080d27, transparent);
  }

  /* END of Gradients */
  /* START of Common */
  .container {
    @apply mx-auto max-w-[1252px] px-16 max-xl:px-10 max-lg:px-6 max-sm:px-4;
  }

  .caption {
    @apply small-2 mb-5 uppercase text-p3;
  }

  .scroll-hide::-webkit-scrollbar {
    display: none;
  }

  .scroll-hide {
    -ms-overflow-style: none; /* IE and Edge */
    scrollbar-width: none; /* Firefox */
  }

  /* END of Common */
  /* START of Header */
  .nav-active {
    @apply text-p3;
  }

  .nav-li {
    @apply relative flex flex-1 items-center justify-between max-lg:flex-col max-lg:items-start;
  }

  .nav-logo {
    @apply relative flex flex-1 items-center justify-center;
  }

  .dot {
    @apply size-1.5 rounded-full bg-p2 max-lg:hidden;
  }

  .sidebar-before {
    @apply max-lg:before:absolute max-lg:before:-right-64 max-lg:before:top-2/5 max-lg:before:h-[440px] max-lg:before:w-[252px] max-lg:before:bg-s4 max-lg:before:blur-[200px] max-lg:before:content-[''];
  }

  /* END of Header */
  /* START of Hero */
  .hero-img_res {
    @apply max-lg:-top-40 max-lg:left-[calc(50%-280px)] max-lg:w-[1160px] max-md:bottom-[-590px] max-md:left-[calc(50%-390px)] max-md:top-auto;
  }

  /* END of Hero */
  /*START of Custom Button*/
  .inner-before {
    @apply before:g7 before:absolute before:inset-0 before:opacity-0 before:transition-opacity before:duration-500 before:content-[''];
  }

  .glow-before {
    @apply before:g8 before:absolute before:left-2/5 before:top-0 before:z-4 before:h-0.5 before:w-3/5 before:opacity-0 before:transition-all before:duration-500 before:content-[''] group-hover:before:left-4 group-hover:before:opacity-40;
  }

  .glow-after {
    @apply after:g8 after:absolute after:bottom-0 after:left-4 after:z-4 after:h-0.5 after:w-7/20 after:opacity-0 after:transition-all after:duration-500 after:content-[''] group-hover:after:left-3/5 group-hover:after:opacity-40;
  }

  /*END of Custom Button*/
  /* START of Feature */
  .feature-after {
    @apply after:g1 after:absolute after:right-0 after:top-0 after:h-full after:w-1/2 after:mix-blend-soft-light after:content-[''] max-md:after:hidden;
  }

  /* END of Feature */
  /* START of Pricing */
  .pricing-head_before {
    @apply before:absolute before:-bottom-44 before:left-1/5 before:h-96 before:w-13/20 before:bg-s4/50 before:blur-[200px] before:content-[''];
  }

  .pricing-head_btn {
    @apply base-bold relative z-2 h-16 flex-1 uppercase text-p5 transition-colors duration-500 hover:text-p4;
  }

  .pricing-head_btn_before {
    @apply before:absolute before:-top-16 before:left-9 before:right-9 before:bg-s4 before:blur-xl before:content-[""];
  }

  .pricing-bg {
    @apply pointer-events-none absolute -bottom-16 left-[calc(50%-480px)] z-2 mx-auto w-960;
  }

  .pricing-plan_first {
    @apply first:rounded-bl-3xl first:rounded-tl-3xl lg:first:border-r-0;
  }

  .pricing-plan_last {
    @apply last:rounded-br-3xl last:rounded-tr-3xl lg:last:border-l-0;
  }

  .pricing-plan_odd {
    @apply odd:border-s3 odd:bg-s1 lg:odd:mt-12;
  }

  .pricing-plan_even {
    @apply even:g7 even:rounded-bl-3xl even:rounded-br-3xl even:rounded-tl-3xl even:rounded-tr-3xl even:border-s4;
  }

  /* END of Pricing */
  /* START of FAQ */
  .faq-line_after {
    @apply after:absolute after:-top-1.5 after:left-[calc(50%-5px)] after:z-4 after:size-2.5 after:rounded-half after:border-2 after:border-s2 after:bg-s1 after:content-[''];
  }

  .faq-glow_before {
    @apply before:absolute before:left-[calc(50%-160px)] before:top-[-160px] before:size-[320px] before:bg-s4/25 before:mix-blend-soft-light before:blur-[200px] before:content-[''];
  }

  .faq-icon {
    @apply before:absolute before:h-0.5 before:w-3 before:bg-p3 before:content-[''] after:absolute after:h-0.5 after:w-3 after:rotate-90 after:bg-p3 after:transition-all after:duration-500 after:content-[''];
  }

  /* END of FAQ */
  /* START of Testimonials */
  .testimonials_head-res {
    @apply max-2xl:mr-6 max-xl:mr-3 max-lg:mx-auto max-lg:mb-36 max-lg:max-w-330 max-lg:text-center max-md:mb-24 max-md:max-w-52;
  }

  .testimonials_inner-before {
    @apply before:pointer-events-none before:absolute before:-top-28 before:left-[calc(50%-1px)] before:h-[calc(100%+218px)] before:w-0.5 before:bg-s2 before:content-[''] before:max-lg:top-0 before:max-lg:h-full before:max-md:hidden;
  }

  .testimonials_inner-after {
    @apply after:pointer-events-none after:absolute after:-bottom-52 after:left-[calc(50%-1px)] after:h-24 after:w-0.5 after:bg-s5 after:content-[''] after:max-lg:-bottom-24 after:max-md:hidden;
  }

  .testimonials_group-after {
    @apply after:pointer-events-none after:absolute after:-bottom-[212px] after:left-[calc(50%-5px)] after:z-2 after:size-2.5 after:rounded-half after:border-2 after:border-s5 after:bg-s1 after:content-[''] max-lg:after:-bottom-[102px] max-md:after:hidden;
  }

  /* END of Testimonials */
  /*  START of Download*/
  .download_tech-link_last-before {
    @apply last:relative last:before:pointer-events-none last:before:absolute last:before:left-full last:before:top-[calc(50%-1px)] last:before:mr-6 last:before:h-0.5 last:before:w-[140px] last:before:bg-s5 last:before:content-[''] last:before:max-xl:w-[105px] last:before:max-lg:w-[80px] last:before:max-md:hidden;
  }

  .download_tech-link_last-after {
    @apply last:after:pointer-events-none last:after:absolute last:after:left-[223px] last:after:top-[calc(50%-5px)] last:after:z-2 last:after:size-2.5 last:after:rounded-half last:after:border-2 last:after:border-s5 last:after:bg-s1 last:after:content-[''] last:after:max-xl:left-[187px] last:after:max-lg:left-[163px] last:after:max-md:hidden;
  }

  .download_tech-icon {
    @apply relative z-2 flex size-full items-center justify-center transition-all duration-500;
  }

  .download_tech-icon_before {
    @apply before:absolute before:inset-1.5 before:rounded-half before:bg-s2 before:content-[''] hover:border-s4;
  }

  .download_tech-link:hover .download_tech-icon svg path {
    @apply fill-p1;
  }

  .download_preview-before {
    @apply before:g8 before:absolute before:-top-0.5 before:right-6 before:h-0.5 before:w-[63.2%] before:opacity-40 before:content-[''];
  }

  .download_preview-after {
    @apply after:g8 after:absolute after:-bottom-0.5 after:left-6 after:h-0.5 after:w-[42.2%] after:opacity-40 after:content-[''];
  }

  .download_preview-dot {
    @apply absolute top-6 size-2.5 rounded-half;
  }

  /*  END of Download*/
  /*  START of Footer */
  .legal-after {
    @apply after:absolute after:-right-5 after:top-[calc(50%-1px)] after:h-0.5 after:w-0.5 after:rounded-half after:bg-p2 after:content-[''];
  }

  .social-icon {
    @apply flex size-10 items-center justify-center rounded-full border-2 border-s4/25 bg-s1/5 transition-all duration-500 hover:border-s4;
  }

  /*  END of Footer*/
}
```

</details>

