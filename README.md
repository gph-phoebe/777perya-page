# 777 Perya WordPress Site

This repository is an on-going project that approaches a **777 Perya** themed website created with **WordPress** and **Astra Pro**. It is written as a practical project README for developers, content managers, and site owners who need to understand how the site is structured, how the theme was assembled, and how branded pages are handled inside a WordPress-first workflow.

The goal of this build is simple: keep the site lightweight, mobile-friendly, easy to update, and flexible enough to support landing pages, login-focused content, support pages, and branded navigation flows without rebuilding templates from scratch every time.

---

## 777 Perya Link

Perya 777 login page: ![https://777perya-login.ph/](https://777perya-login.ph/)

---

## Project Overview

This site uses WordPress as the CMS and Astra Pro as the front-end theme framework.

The build is designed around these priorities:

- fast page rendering on mobile
- easy template reuse across branded pages
- minimal plugin dependence
- simple content editing for non-developers
- flexible hero, CTA, and content-block layouts
- clear page hierarchy for users looking for the **777 Perya link** or **Perya 777 login** flow

Instead of treating Astra Pro as just a styling layer, this setup uses it as the main layout system for headers, blog/article pages, page-width controls, spacing, and reusable theme logic.

---

## Stack

### Core
- WordPress
- Astra Pro
- Gutenberg editor

### Optional supporting plugins
These depend on the final deployment, but the build works best with a lean plugin stack:

- SEO plugin for metadata and schema
- caching plugin
- image optimization plugin
- security plugin
- forms plugin
- redirection plugin

The site should avoid plugin overload. Astra Pro already covers a lot of what builders try to solve with extra page design plugins.

---

## Why Astra Pro

Astra Pro makes sense for this project because it is fast, modular, and easy to control without turning the site into a fragile page-builder dependency.

For a branded WordPress setup like **777 Perya**, Astra Pro helps with:

- custom headers and sticky navigation
- page-specific layouts
- spacing and typography controls
- transparent header support for landing pages
- mobile header behavior
- blog/archive styling
- WooCommerce compatibility if needed later
- clean full-width templates for login or promo pages

For this site, Astra Pro is mainly useful because not every page has the same job. A homepage, an info article, and a **777 Perya login** page should not feel identical. Astra Pro makes those differences easier to manage cleanly.
