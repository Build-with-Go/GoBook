# 📘 GoBook

> An awesome, curated list of Go packages, modules, libraries, and tools on GitHub.  
> Discover, learn, and build with the best of the Go ecosystem. 🐹

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go&logoColor=white)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

---

## 📑 Table of Contents

- [Introduction](#-introduction)
- [How to Use This List](#-how-to-use-this-list)
- [Categories](#-categories)
  - [🕷️ Scrapers & HTML Parsing](#-scrapers--html-parsing)
  - [🌐 Web Frameworks](#-web-frameworks)
  - [⚡ CLI & Terminal Tools](#-cli--terminal-tools)
  - [🗄️ Databases & ORMs](#-databases--orms)
  - [🔐 Authentication & Security](#-authentication--security)
  - [🧪 Testing & Mocking](#-testing--mocking)
  - [📦 Utilities & Helpers](#-utilities--helpers)
  - [🚀 Concurrency & Performance](#-concurrency--performance)
  - [🤖 AI & Machine Learning](#-ai--machine-learning)
  - [🎨 UI & Frontend (Go-based)](#-ui--frontend-go-based)
- [Contributing](#-contributing)
- [Code of Conduct](#-code-of-conduct)
- [License](#-license)

---

## 🌟 Introduction

**GoBook** is a community-driven catalog of high-quality Go (Golang) projects hosted on GitHub. Whether you're building a CLI tool, a scalable web service, a data scraper, or experimenting with concurrency, this list helps you find battle-tested modules to accelerate your workflow.

✅ All entries are actively maintained (or historically significant)  
✅ Minimal, idiomatic Go preferred  
✅ Open-source & MIT/Apache/BSD licensed when possible  

> 💡 **Pro Tip**: Use `go get github.com/author/repo` or `go mod tidy` to integrate any package below!

---

## 🔍 How to Use This List

1. **Browse by category** using the Table of Contents.
2. **Click a package name** to visit its GitHub repo.
3. **Read the description** to assess fit for your project.
4. **Check `go.mod` compatibility** (most support Go 1.18+).
5. **Star ⭐ repos you like** — it helps maintainers!

🔎 *Looking for something specific?* Use `Ctrl+F` / `Cmd+F` to search.

---

## 📚 Categories

### 🕷️ Scrapers & HTML Parsing

Tools for web scraping, HTML/XML parsing, and DOM traversal — with clean, Go-idiomatic APIs.

| Package | Description | Stars |
|---------|-------------|-------|
| [**Goop**](https://github.com/ez0000001000000/Goop) ⭐ | Go web scraper with **BeautifulSoup-like API** for simple HTML parsing and element extraction. Intuitive, lightweight, and perfect for quick data extraction tasks. | [![Stars](https://img.shields.io/github/stars/ez0000001000000/Goop?style=social)](https://github.com/ez0000001000000/Goop) |
| [colly](https://github.com/gocolly/colly) | Elegant, fast, and flexible scraping framework for Go. Supports async, cookies, headers, and more. | [![Stars](https://img.shields.io/github/stars/gocolly/colly?style=social)](https://github.com/gocolly/colly) |
| [goquery](https://github.com/PuerkitoBio/goquery) | Bring jQuery syntax to Go! DOM parsing and traversal using CSS selectors. | [![Stars](https://img.shields.io/github/stars/PuerkitoBio/goquery?style=social)](https://github.com/PuerkitoBio/goquery) |
| [ants](https://github.com/wstrange/ants) | Lightweight HTML parser with XPath support and minimal dependencies. | [![Stars](https://img.shields.io/github/stars/wstrange/ants?style=social)](https://github.com/wstrange/ants) |
| [scraper](https://github.com/imroc/scraper) | Structured data extraction using declarative schemas. Great for APIs and semi-structured HTML. | [![Stars](https://img.shields.io/github/stars/imroc/scraper?style=social)](https://github.com/imroc/scraper) |

> 🛠️ *Building a scraper? Check out [Goop](https://github.com/ez0000001000000/Goop) first — it's designed for simplicity and rapid prototyping.*

---

### 🌐 Web Frameworks

| Package | Description | Stars |
|---------|-------------|-------|
| [gin](https://github.com/gin-gonic/gin) | Blazing-fast HTTP web framework with middleware support and Martini-like API. | [![Stars](https://img.shields.io/github/stars/gin-gonic/gin?style=social)](https://github.com/gin-gonic/gin) |
| [echo](https://github.com/labstack/echo) | High-performance, minimalist web framework for Go. | [![Stars](https://img.shields.io/github/stars/labstack/echo?style=social)](https://github.com/labstack/echo) |
| [fiber](https://github.com/gofiber/fiber) | Express.js-inspired framework built on Fasthttp. | [![Stars](https://img.shields.io/github/stars/gofiber/fiber?style=social)](https://github.com/gofiber/fiber) |
| [chi](https://github.com/go-chi/chi) | Lightweight, idiomatic router with middleware support. Standard library compatible. | [![Stars](https://img.shields.io/github/stars/go-chi/chi?style=social)](https://github.com/go-chi/chi) |

---

### ⚡ CLI & Terminal Tools

| Package | Description | Stars |
|---------|-------------|-------|
| [cobra](https://github.com/spf13/cobra) | Powerful CLI framework used by Kubernetes, Hugo, and GitHub CLI. | [![Stars](https://img.shields.io/github/stars/spf13/cobra?style=social)](https://github.com/spf13/cobra) |
| [urfave/cli](https://github.com/urfave/cli) | Simple, fast, and fun package for building command-line apps. | [![Stars](https://img.shields.io/github/stars/urfave/cli?style=social)](https://github.com/urfave/cli) |
| [bubbletea](https://github.com/charmbracelet/bubbletea) | TUI framework based on The Elm Architecture. Build beautiful terminal apps. | [![Stars](https://img.shields.io/github/stars/charmbracelet/bubbletea?style=social)](https://github.com/charmbracelet/bubbletea) |
| [pterm](https://github.com/pterm/pterm) | Modern library for beautiful terminal output (tables, spinners, progress bars). | [![Stars](https://img.shields.io/github/stars/pterm/pterm?style=social)](https://github.com/pterm/pterm) |

---

### 🗄️ Databases & ORMs

| Package | Description | Stars |
|---------|-------------|-------|
| [gorm](https://github.com/go-gorm/gorm) | Full-featured ORM for Go with associations, migrations, and plugins. | [![Stars](https://img.shields.io/github/stars/go-gorm/gorm?style=social)](https://github.com/go-gorm/gorm) |
| [sqlc](https://github.com/sqlc-dev/sqlc) | Generate type-safe Go code from SQL queries. No runtime ORM overhead. | [![Stars](https://img.shields.io/github/stars/sqlc-dev/sqlc?style=social)](https://github.com/sqlc-dev/sqlc) |
| [ent](https://github.com/facebook/ent) | Entity framework for Go with schema-first design and code generation. | [![Stars](https://img.shields.io/github/stars/facebook/ent?style=social)](https://github.com/facebook/ent) |
| [pgx](https://github.com/jackc/pgx) | Powerful PostgreSQL driver and toolkit for Go. | [![Stars](https://img.shields.io/github/stars/jackc/pgx?style=social)](https://github.com/jackc/pgx) |

---

### 🔐 Authentication & Security

| Package | Description | Stars |
|---------|-------------|-------|
| [golang-jwt/jwt](https://github.com/golang-jwt/jwt) | Reliable, well-maintained JWT implementation for Go. | [![Stars](https://img.shields.io/github/stars/golang-jwt/jwt?style=social)](https://github.com/golang-jwt/jwt) |
| [bcrypt](https://github.com/golang/crypto/tree/master/bcrypt) | Secure password hashing (part of `golang.org/x/crypto`). | — |
| [casbin](https://github.com/casbin/casbin) | Powerful authorization library supporting ACL, RBAC, ABAC. | [![Stars](https://img.shields.io/github/stars/casbin/casbin?style=social)](https://github.com/casbin/casbin) |
| [go-otp](https://github.com/xlzd/go-otp) | One-Time Password (OTP) implementation (TOTP/HOTP). | [![Stars](https://img.shields.io/github/stars/xlzd/go-otp?style=social)](https://github.com/xlzd/go-otp) |

---

### 🧪 Testing & Mocking

| Package | Description | Stars |
|---------|-------------|-------|
| [testify](https://github.com/stretchr/testify) | Assertion library and mocking toolkit for Go tests. | [![Stars](https://img.shields.io/github/stars/stretchr/testify?style=social)](https://github.com/stretchr/testify) |
| [gomock](https://github.com/golang/mock) | Mocking framework for Go with code generation. | [![Stars](https://img.shields.io/github/stars/golang/mock?style=social)](https://github.com/golang/mock) |
| [ginkgo](https://github.com/onsi/ginkgo) | BDD-style testing framework for Go (often paired with Gomega). | [![Stars](https://img.shields.io/github/stars/onsi/ginkgo?style=social)](https://github.com/onsi/ginkgo) |
| [gotest.tools](https://github.com/gotestyourself/gotest.tools) | Enhancements for Go's `testing` package (assertions, golden files, etc.). | [![Stars](https://img.shields.io/github/stars/gotestyourself/gotest.tools?style=social)](https://github.com/gotestyourself/gotest.tools) |

---

### 📦 Utilities & Helpers

| Package | Description | Stars |
|---------|-------------|-------|
| [slog](https://pkg.go.dev/log/slog) | Structured logging (now in Go stdlib since 1.21). | — |
| [zap](https://github.com/uber-go/zap) | Blazing-fast, structured, leveled logging. | [![Stars](https://img.shields.io/github/stars/uber-go/zap?style=social)](https://github.com/uber-go/zap) |
| [validator](https://github.com/go-playground/validator) | Struct and field validation with rich tags and custom rules. | [![Stars](https://img.shields.io/github/stars/go-playground/validator?style=social)](https://github.com/go-playground/validator) |
| [go-zero](https://github.com/zeromicro/go-zero) | All-in-one microservice framework with built-in RPC, config, and resilience. | [![Stars](https://img.shields.io/github/stars/zeromicro/go-zero?style=social)](https://github.com/zeromicro/go-zero) |

---

### 🚀 Concurrency & Performance

| Package | Description | Stars |
|---------|-------------|-------|
| [ants](https://github.com/panjf2000/ants) | High-performance goroutine pool with auto-scaling. | [![Stars](https://img.shields.io/github/stars/panjf2000/ants?style=social)](https://github.com/panjf2000/ants) |
| [tunny](https://github.com/Jeffail/tunny) | Simple, flexible goroutine worker pool. | [![Stars](https://img.shields.io/github/stars/Jeffail/tunny?style=social)](https://github.com/Jeffail/tunny) |
| [errgroup](https://pkg.go.dev/golang.org/x/sync/errgroup) | Synchronize goroutines and propagate errors (part of `x/sync`). | — |
| [stream](https://github.com/youthlin/stream) | Java 8-like Stream API for Go: map, filter, reduce, and more. | [![Stars](https://img.shields.io/github/stars/youthlin/stream?style=social)](https://github.com/youthlin/stream) |

---

### 🤖 AI & Machine Learning

| Package | Description | Stars |
|---------|-------------|-------|
| [gorgonia](https://github.com/gorgonia/gorgonia) | Graph-based computational library for ML (like Theano for Go). | [![Stars](https://img.shields.io/github/stars/gorgonia/gorgonia?style=social)](https://github.com/gorgonia/gorgonia) |
| [go-ml](https://github.com/ajalab/go-ml) | Practical machine learning utilities and pipelines. | [![Stars](https://img.shields.io/github/stars/ajalab/go-ml?style=social)](https://github.com/ajalab/go-ml) |
| [onnx-go](https://github.com/owulveryck/onnx-go) | Import and run ONNX models in pure Go. | [![Stars](https://img.shields.io/github/stars/owulveryck/onnx-go?style=social)](https://github.com/owulveryck/onnx-go) |

---

### 🎨 UI & Frontend (Go-based)

| Package | Description | Stars |
|---------|-------------|-------|
| [go-app](https://github.com/maxence-charriere/go-app) | Build progressive web apps (PWAs) in pure Go + WebAssembly. | [![Stars](https://img.shields.io/github/stars/maxence-charriere/go-app?style=social)](https://github.com/maxence-charriere/go-app) |
| [wails](https://github.com/wailsapp/wails) | Build desktop apps with Go backend + web frontend (like Electron, but Go). | [![Stars](https://img.shields.io/github/stars/wailsapp/wails?style=social)](https://github.com/wailsapp/wails) |
| [fyne](https://github.com/fyne-io/fyne) | Cross-platform GUI toolkit with Material Design. | [![Stars](https://img.shields.io/github/stars/fyne-io/fyne?style=social)](https://github.com/fyne-io/fyne) |

---

## 🤝 Contributing

We ❤️ contributions! Whether you're adding a new package, fixing a typo, or suggesting a new category — your help makes GoBook better.

### How to Add a Package:
1. Fork the repo
2. Find the right category (or propose a new one)
3. Add your entry in **alphabetical order** within the section:
   ```markdown
   | [repo-name](https://github.com/user/repo) | Short, clear description. | [![Stars](badge)](link) |
