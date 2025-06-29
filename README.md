# 🌐 nextjs-multizone-boilerplate

A modern, scalable, SEO-optimized **Next.js boilerplate** for building **multi-zone**, **microfrontend** applications with **SSR**, **i18n**, **TailwindCSS**, **shadcn/ui**, and more.

> Created & maintained by **Sunil D**  
> 📁 [Sample Repo](https://github.com/sunild7/nextjs-multizone-boilerplate)

## Demo

https://github.com/user-attachments/assets/ac0d647b-9984-4e48-90ee-a27ff7d7326a

https://github.com/user-attachments/assets/1f0fb236-d36d-4a26-a945-8cac10095f68

https://github.com/user-attachments/assets/defd9c31-da7d-4e4c-bab1-5d51572d283b




## 🚀 Quick Start

1. **Clone the Repository**
```bash
git clone https://github.com/sunild7/nextjs-multizone-boilerplate.git
cd nextjs-multizone-boilerplate
```

2. **Install Dependencies**
```bash
pnpm install
```

3. **Run All Apps in Dev Mode**
```bash
pnpm dev
```
This starts all apps/* (admin, web, etc.) using Turborepo with configured rewrites.

4. **Run Tests**
```bash
# Unit Tests
pnpm test

# E2E Tests
pnpm e2e

# Docker Build & Run
docker-compose up --build
```

## 📚 Features

### 🌍 i18n & SSR
- SSR enabled by default for all apps
- Locale routing via next-intl: `/en`, `/mr`, `/hi`
- SEO-ready with dynamic meta tags, localized routes
- Language switcher included

### 🎨 TailwindCSS + shadcn
- Pre-configured TailwindCSS with shared design tokens
- shadcn/ui components from shared ui package
- Easily themeable and extensible

### 🧠 Key Benefits
- ✅ Multi-zone Next.js structure
- ✅ Microfrontend-friendly architecture
- ✅ TailwindCSS + shadcn/ui design system
- ✅ SSR + SEO out of the box
- ✅ Multi-language support
- ✅ Docker-ready
- ✅ Optimized workspace with pnpm + turborepo
- ✅ Clean separation of concerns

## 📜 Common Commands

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start all apps in dev mode |
| `pnpm build` | Build all apps and packages |
| `pnpm lint` | Run linter |
| `pnpm test` | Run Vitest unit tests |
| `pnpm e2e` | Run Playwright E2E tests |
| `docker-compose up` | Run all apps in containers |

## 📌 Roadmap

- [ ] Add user authentication (NextAuth/Clerk)
- [ ] Add Storybook for UI components
- [ ] Enable CI/CD pipelines
- [ ] Integrate analytics + error tracking


## 📄 License

MIT License © 2025 Sunil Dandwate

## 👥 Contributing

PRs are welcome! Please:
- Follow existing code patterns
- Use the shared eslint-config
- Follow commit hooks (if configured)
