# Aditya Rathod Portfolio

Personal portfolio website built with Next.js to showcase Vedant Pawar's profile, skills, projects, certifications, internship experience, and contact information.

## Overview

This project is a responsive portfolio site with:

- Hero, about, skills, projects, certifications, hobbies, experience, and contact sections
- Theme switching support
- Animated UI using AOS and type animation
- Resume download support
- Project cards with GitHub links
- Certificate and internship document previews

## Tech Stack

- Next.js 16.2.4
- React 19
- JavaScript
- CSS
- AOS
- React Type Animation

## Project Structure

```text
components/   Reusable UI sections
pages/        Next.js pages and app entry
public/       Images, resume, certificates, and static assets
styles/       Global and module CSS
```

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

## Available Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
```

## Main Content Files

- `components/Hero.jsx`
- `components/About.jsx`
- `components/Skills.jsx`
- `components/Portfolio.jsx`
- `components/Certifications.jsx`
- `components/Experience.jsx`
- `components/Contact.jsx`
- `components/Footer.jsx`

## Assets

Important files used in the site:

- `public/PortfolioPhoto.jpeg`
- `public/VedantPawar.pdf`
- `public/Human Computer Interaction (In English).pdf`
- `public/Cloud computing.jpg`
- `public/Vedant-Internship-Certificate.pdf`

## Notes

- The project uses the Pages Router.
- Lint may show warnings for regular `<img>` usage because the site currently uses standard image tags instead of `next/image`.

## Build Status

Verified locally with:

```bash
npm run lint
npm run build
```
