# 📘 GoBook

> An awesome, curated list of Go packages, modules, and libraries on GitHub.  
> Discover, learn, and build with the best of the Go ecosystem. 🐹

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go&logoColor=white)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

---

## 📑 Table of Contents

- [Introduction](#-introduction)
- [How to Use](#-how-to-use)
- [Categories](#-categories)
  - [🕷️ Scrapers & HTML Parsing](#-scrapers--html-parsing)
  - [🌐 Web Frameworks](#-web-frameworks)
  - [⚡ CLI & Terminal Tools](#-cli--terminal-tools)
  - [🗄️ Databases & ORMs](#-databases--orms)
  - [🔐 Auth & Security](#-auth--security)
  - [🧪 Testing](#-testing)
  - [📦 Utilities](#-utilities)
  - [📨 Messaging & Queues](#-messaging--queues)
  - [📁 File Storage](#-file-storage)
  - [⏰ Scheduling](#-scheduling)
  - [🚀 Concurrency](#-concurrency)
  - [🤖 AI/ML](#-aiml)
  - [🎨 UI/Frontend](#-uifrontend)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Introduction

**GoBook** is a community-driven catalog of high-quality Go (Golang) projects on GitHub. Whether you're building a CLI, web service, scraper, or concurrent system — find battle-tested modules to accelerate your work.

✅ Actively maintained or historically significant  
✅ Idiomatic Go, minimal dependencies preferred  
✅ Open-source licenses (MIT/Apache/BSD)  

> 💡 **Tip**: Use `go get github.com/author/repo` or add to `go.mod` to install any package below.

---

## 🔍 How to Use

1. Browse categories via the Table of Contents  
2. Click a package name to visit its GitHub repo  
3. Read the description and check `go.mod` compatibility  
4. ⭐ Star repos you like — it helps maintainers!

> 💡 **Note**: Packages marked with ⭐ are created by [@ez0000001000000](https://github.com/ez0000001000000).

🔎 *Search tip*: Use `Ctrl+F` / `Cmd+F` to find packages fast.

---

## 📚 Categories

### 🕷️ Scrapers & HTML Parsing

| Package | Description | Stars |
|---------|-------------|-------|
| [**Goop**](https://github.com/ez0000001000000/Goop) ⭐ | Go web scraper with **BeautifulSoup-like API** for simple HTML parsing and element extraction. Intuitive, lightweight, perfect for quick data tasks. | [![Stars](https://img.shields.io/github/stars/ez0000001000000/Goop?style=social)](https://github.com/ez0000001000000/Goop) |
| [colly](https://github.com/gocolly/colly) | Elegant, fast scraping framework. Supports async, cookies, headers, robots.txt. | [![Stars](https://img.shields.io/github/stars/gocolly/colly?style=social)](https://github.com/gocolly/colly) |
| [goquery](https://github.com/PuerkitoBio/goquery) | jQuery-like DOM parsing and traversal using CSS selectors. | [![Stars](https://img.shields.io/github/stars/PuerkitoBio/goquery?style=social)](https://github.com/PuerkitoBio/goquery) |
| [htmlquery](https://github.com/antchfx/htmlquery) | XPath query support for HTML/XML documents with streaming. | [![Stars](https://img.shields.io/github/stars/antchfx/htmlquery?style=social)](https://github.com/antchfx/htmlquery) |
| [rod](https://github.com/go-rod/rod) | DevTools driver for browser automation and scraping. High-level API, headless Chrome support. | [![Stars](https://img.shields.io/github/stars/go-rod/rod?style=social)](https://github.com/go-rod/rod) |

> 🛠️ *Building a scraper? Start with [Goop](https://github.com/ez0000001000000/Goop) ⭐ for simple tasks, or [rod](https://github.com/go-rod/rod) for dynamic JS-heavy sites.*

---

### 🌐 Web Frameworks

| Package | Description | Stars |
|---------|-------------|-------|
| [gin](https://github.com/gin-gonic/gin) | Blazing-fast HTTP framework with middleware, validation, and Martini-like API. | [![Stars](https://img.shields.io/github/stars/gin-gonic/gin?style=social)](https://github.com/gin-gonic/gin) |
| [echo](https://github.com/labstack/echo) | High-performance, minimalist framework with extensible middleware. | [![Stars](https://img.shields.io/github/stars/labstack/echo?style=social)](https://github.com/labstack/echo) |
| [fiber](https://github.com/gofiber/fiber) | Express.js-inspired framework built on Fasthttp. Zero allocation router. | [![Stars](https://img.shields.io/github/stars/gofiber/fiber?style=social)](https://github.com/gofiber/fiber) |
| [chi](https://github.com/go-chi/chi) | Lightweight, idiomatic router. Standard library compatible, middleware-friendly. | [![Stars](https://img.shields.io/github/stars/go-chi/chi?style=social)](https://github.com/go-chi/chi) |
| [beego](https://github.com/beego/beego) | Full-featured web framework with ORM, cache, session management, and admin panel. | [![Stars](https://img.shields.io/github/stars/beego/beego?style=social)](https://github.com/beego/beego) |
| [buffalo](https://github.com/gobuffalo/buffalo) | Rapid web development framework with hot-reload, generators, and plugins. | [![Stars](https://img.shields.io/github/stars/gobuffalo/buffalo?style=social)](https://github.com/gobuffalo/buffalo) |

---

### ⚡ CLI & Terminal Tools

| Package | Description | Stars |
|---------|-------------|-------|
| [cobra](https://github.com/spf13/cobra) | Powerful CLI framework used by Kubernetes, Hugo, GitHub CLI. | [![Stars](https://img.shields.io/github/stars/spf13/cobra?style=social)](https://github.com/spf13/cobra) |
| [cli](https://github.com/urfave/cli) | Simple, fast package for building command-line apps. | [![Stars](https://img.shields.io/github/stars/urfave/cli?style=social)](https://github.com/urfave/cli) |
| [bubbletea](https://github.com/charmbracelet/bubbletea) | TUI framework based on The Elm Architecture. Build beautiful terminal apps. | [![Stars](https://img.shields.io/github/stars/charmbracelet/bubbletea?style=social)](https://github.com/charmbracelet/bubbletea) |
| [pterm](https://github.com/pterm/pterm) | Modern library for beautiful terminal output: tables, spinners, progress bars. | [![Stars](https://img.shields.io/github/stars/pterm/pterm?style=social)](https://github.com/pterm/pterm) |

---

### 🗄️ Databases & ORMs

| Package | Description | Stars |
|---------|-------------|-------|
| [gorm](https://github.com/go-gorm/gorm) | Full-featured ORM: associations, migrations, plugins, multiple DBs. | [![Stars](https://img.shields.io/github/stars/go-gorm/gorm?style=social)](https://github.com/go-gorm/gorm) |
| [sqlc](https://github.com/sqlc-dev/sqlc) | Generate type-safe Go code from SQL. No runtime ORM overhead. | [![Stars](https://img.shields.io/github/stars/sqlc-dev/sqlc?style=social)](https://github.com/sqlc-dev/sqlc) |
| [ent](https://github.com/facebook/ent) | Entity framework with schema-first design and code generation. | [![Stars](https://img.shields.io/github/stars/facebook/ent?style=social)](https://github.com/facebook/ent) |
| [pgx](https://github.com/jackc/pgx) | Powerful PostgreSQL driver and toolkit. Pure Go, high performance. | [![Stars](https://img.shields.io/github/stars/jackc/pgx?style=social)](https://github.com/jackc/pgx) |
| [sqlx](https://github.com/jmoiron/sqlx) | Extensions to database/sql for easier queries and struct scanning. | [![Stars](https://img.shields.io/github/stars/jmoiron/sqlx?style=social)](https://github.com/jmoiron/sqlx) |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | Generate type-safe Go code from your database schema. | [![Stars](https://img.shields.io/github/stars/volatiletech/sqlboiler?style=social)](https://github.com/volatiletech/sqlboiler) |
| [go-redis](https://github.com/redis/go-redis) | Redis client with clustering, pub/sub, caching, and Sentinel support. | [![Stars](https://img.shields.io/github/stars/redis/go-redis?style=social)](https://github.com/redis/go-redis) |

---

### 🔐 Auth & Security

| Package | Description | Stars |
|---------|-------------|-------|
| [jwt](https://github.com/golang-jwt/jwt) | Reliable, well-maintained JWT implementation for Go. | [![Stars](https://img.shields.io/github/stars/golang-jwt/jwt?style=social)](https://github.com/golang-jwt/jwt) |
| [bcrypt](https://github.com/golang/crypto/tree/master/bcrypt) | Secure password hashing (part of `golang.org/x/crypto`). | — |
| [casbin](https://github.com/casbin/casbin) | Authorization library supporting ACL, RBAC, ABAC. | [![Stars](https://img.shields.io/github/stars/casbin/casbin?style=social)](https://github.com/casbin/casbin) |
| [otp](https://github.com/pquerna/otp) | Standards-compliant HOTP (RFC 4226) and TOTP (RFC 6238) implementation for 2FA. | [![Stars](https://img.shields.io/github/stars/pquerna/otp?style=social)](https://github.com/pquerna/otp) |

---

### 🧪 Testing

| Package | Description | Stars |
|---------|-------------|-------|
| [testify](https://github.com/stretchr/testify) | Assertion library and mocking toolkit for Go tests. | [![Stars](https://img.shields.io/github/stars/stretchr/testify?style=social)](https://github.com/stretchr/testify) |
| [mock](https://github.com/golang/mock) | Mocking framework with code generation (gomock). | [![Stars](https://img.shields.io/github/stars/golang/mock?style=social)](https://github.com/golang/mock) |
| [ginkgo](https://github.com/onsi/ginkgo) | BDD-style testing framework (often paired with Gomega). | [![Stars](https://img.shields.io/github/stars/onsi/ginkgo?style=social)](https://github.com/onsi/ginkgo) |
| [gotestsum](https://github.com/gotestyourself/gotestsum) | Enhanced `go test` runner with pretty output and JUnit XML. | [![Stars](https://img.shields.io/github/stars/gotestyourself/gotestsum?style=social)](https://github.com/gotestyourself/gotestsum) |
| [mockery](https://github.com/vektra/mockery) | Mock code autogenerator for Go interfaces using testify. | [![Stars](https://img.shields.io/github/stars/vektra/mockery?style=social)](https://github.com/vektra/mockery) |
| [gock](https://github.com/h2non/gock) | HTTP mocking library with regex matching and persistence. | [![Stars](https://img.shields.io/github/stars/h2non/gock?style=social)](https://github.com/h2non/gock) |

---

### 📦 Utilities

| Package | Description | Stars |
|---------|-------------|-------|
| [slog](https://pkg.go.dev/log/slog) | Structured logging (stdlib since Go 1.21). | — |
| [zap](https://github.com/uber-go/zap) | Blazing-fast, structured, leveled logging. | [![Stars](https://img.shields.io/github/stars/uber-go/zap?style=social)](https://github.com/uber-go/zap) |
| [logrus](https://github.com/sirupsen/logrus) | Structured logging optimized for JSON output, API-compatible with stdlib. | [![Stars](https://img.shields.io/github/stars/sirupsen/logrus?style=social)](https://github.com/sirupsen/logrus) |
| [zerolog](https://github.com/rs/zerolog) | Zero-allocation, fast JSON logging library for Go. | [![Stars](https://img.shields.io/github/stars/rs/zerolog?style=social)](https://github.com/rs/zerolog) |
| [validator](https://github.com/go-playground/validator) | Struct/field validation with rich tags and custom rules. | [![Stars](https://img.shields.io/github/stars/go-playground/validator?style=social)](https://github.com/go-playground/validator) |
| [pointer](https://github.com/xorcare/pointer) | Helper functions for working with pointers to primitives. | [![Stars](https://img.shields.io/github/stars/xorcare/pointer?style=social)](https://github.com/xorcare/pointer) |
| [viper](https://github.com/spf13/viper) | Complete configuration solution: JSON, YAML, TOML, env vars, remote configs. | [![Stars](https://img.shields.io/github/stars/spf13/viper?style=social)](https://github.com/spf13/viper) |
| [retryablehttp](https://github.com/hashicorp/go-retryablehttp) | HTTP client with automatic retries and exponential backoff. | [![Stars](https://img.shields.io/github/stars/hashicorp/go-retryablehttp?style=social)](https://github.com/hashicorp/go-retryablehttp) |
| [retry-go](https://github.com/avast/retry-go) | Simple retry mechanism for Go with customizable backoff strategies. | [![Stars](https://img.shields.io/github/stars/avast/retry-go?style=social)](https://github.com/avast/retry-go) |

---

### 📨 Messaging & Queues

| Package | Description | Stars |
|---------|-------------|-------|
| [kafka-go](https://github.com/segmentio/kafka-go) | Kafka library for Go with high-level API and consumer group support. | [![Stars](https://img.shields.io/github/stars/segmentio/kafka-go?style=social)](https://github.com/segmentio/kafka-go) |
| [amqp](https://github.com/rabbitmq/amqp091-go) | Official RabbitMQ AMQP 0.9.1 client for Go. | [![Stars](https://img.shields.io/github/stars/rabbitmq/amqp091-go?style=social)](https://github.com/rabbitmq/amqp091-go) |
| [nsq](https://github.com/nsqio/nsq) | Realtime distributed messaging platform designed for scale and reliability. | [![Stars](https://img.shields.io/github/stars/nsqio/nsq?style=social)](https://github.com/nsqio/nsq) |

---

### 📁 File Storage

| Package | Description | Stars |
|---------|-------------|-------|
| [minio-go](https://github.com/minio/minio-go) | MinIO Client SDK for Go — S3-compatible object storage with full API support. | [![Stars](https://img.shields.io/github/stars/minio/minio-go?style=social)](https://github.com/minio/minio-go) |

---

### ⏰ Scheduling

| Package | Description | Stars |
|---------|-------------|-------|
| [gocron](https://github.com/go-co-op/gocron) | Job scheduling package for Go with cron-like syntax, timezones, and features. | [![Stars](https://img.shields.io/github/stars/go-co-op/gocron?style=social)](https://github.com/go-co-op/gocron) |
| [cron](https://github.com/robfig/cron) | Cron library for Go with Quartz-compatible scheduler and time zone support. | [![Stars](https://img.shields.io/github/stars/robfig/cron?style=social)](https://github.com/robfig/cron) |

---

### 🚀 Concurrency

| Package | Description | Stars |
|---------|-------------|-------|
| [ants](https://github.com/panjf2000/ants) | High-performance goroutine pool with auto-scaling and rate limiting. | [![Stars](https://img.shields.io/github/stars/panjf2000/ants?style=social)](https://github.com/panjf2000/ants) |
| [tunny](https://github.com/Jeffail/tunny) | Simple, flexible goroutine worker pool with context support. | [![Stars](https://img.shields.io/github/stars/Jeffail/tunny?style=social)](https://github.com/Jeffail/tunny) |
| [errgroup](https://pkg.go.dev/golang.org/x/sync/errgroup) | Synchronize goroutines and propagate errors (`x/sync`). | — |
| [stream](https://github.com/youthlin/stream) | Java 8-like Stream API: map, filter, reduce, and more. | [![Stars](https://img.shields.io/github/stars/youthlin/stream?style=social)](https://github.com/youthlin/stream) |
| [conc](https://github.com/sourcegraph/conc) | Better structured concurrency for Go with error handling and panic safety. | [![Stars](https://img.shields.io/github/stars/sourcegraph/conc?style=social)](https://github.com/sourcegraph/conc) |

---

### 🤖 AI/ML

| Package | Description | Stars |
|---------|-------------|-------|
| [gorgonia](https://github.com/gorgonia/gorgonia) | Graph-based computational library for ML (like Theano for Go). | [![Stars](https://img.shields.io/github/stars/gorgonia/gorgonia?style=social)](https://github.com/gorgonia/gorgonia) |
| [goml](https://github.com/cdipaolo/goml) | On-line machine learning library in pure Go with streaming support. | [![Stars](https://img.shields.io/github/stars/cdipaolo/goml?style=social)](https://github.com/cdipaolo/goml) |
| [onnx-go](https://github.com/owulveryck/onnx-go) | Import and run ONNX models in pure Go with backend flexibility. | [![Stars](https://img.shields.io/github/stars/owulveryck/onnx-go?style=social)](https://github.com/owulveryck/onnx-go) |

---

### 🎨 UI/Frontend

| Package | Description | Stars |
|---------|-------------|-------|
| [go-app](https://github.com/maxence-charriere/go-app) | Build progressive web apps (PWAs) in pure Go + WebAssembly. | [![Stars](https://img.shields.io/github/stars/maxence-charriere/go-app?style=social)](https://github.com/maxence-charriere/go-app) |
| [wails](https://github.com/wailsapp/wails) | Build desktop apps with Go backend + web frontend (like Electron, but Go). | [![Stars](https://img.shields.io/github/stars/wailsapp/wails?style=social)](https://github.com/wailsapp/wails) |
| [fyne](https://github.com/fyne-io/fyne) | Cross-platform GUI toolkit with Material Design and native widgets. | [![Stars](https://img.shields.io/github/stars/fyne-io/fyne?style=social)](https://github.com/fyne-io/fyne) |

---

# 📘 GoBook

> An awesome, curated list of Go packages, modules, and libraries on GitHub.  
> Discover, learn, and build with the best of the Go ecosystem. 🐹

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go&logoColor=white)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

---

## 📑 Table of Contents

- [Introduction](#-introduction)
- [How to Use](#-how-to-use)
- [Categories](#-categories)
  - [🕷️ Scrapers & HTML Parsing](#-scrapers--html-parsing)
  - [🌐 Web Frameworks](#-web-frameworks)
  - [⚡ CLI & Terminal Tools](#-cli--terminal-tools)
  - [🗄️ Databases & ORMs](#-databases--orms)
  - [🔐 Auth & Security](#-auth--security)
  - [🧪 Testing](#-testing)
  - [📦 Utilities](#-utilities)
  - [📨 Messaging & Queues](#-messaging--queues)
  - [📁 File Storage](#-file-storage)
  - [⏰ Scheduling](#-scheduling)
  - [🚀 Concurrency](#-concurrency)
  - [🌐 Networking](#-networking)
  - [☁️ Cloud/DevOps](#-clouddevops)
  - [🤖 AI/ML](#-aiml)
  - [🎨 UI/Frontend](#-uifrontend)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Introduction

**GoBook** is a community-driven catalog of high-quality Go (Golang) projects on GitHub. Whether you're building a CLI, web service, scraper, or concurrent system — find battle-tested modules to accelerate your work.

✅ Actively maintained or historically significant  
✅ Idiomatic Go, minimal dependencies preferred  
✅ Open-source licenses (MIT/Apache/BSD)  

> 💡 **Tip**: Use `go get github.com/author/repo` or add to `go.mod` to install any package below.

---

## 🔍 How to Use

1. Browse categories via the Table of Contents  
2. Click a package name to visit its GitHub repo  
3. Read the description and check `go.mod` compatibility  
4. ⭐ Star repos you like — it helps maintainers!

> 💡 **Note**: Packages marked with ⭐ are created by [@ez0000001000000](https://github.com/ez0000001000000).

🔎 *Search tip*: Use `Ctrl+F` / `Cmd+F` to find packages fast.

---

## 📚 Categories

### 🕷️ Scrapers & HTML Parsing

| Package | Description | Stars |
|---------|-------------|-------|
| [**Goop**](https://github.com/ez0000001000000/Goop) ⭐ | Go web scraper with **BeautifulSoup-like API** for simple HTML parsing and element extraction. Intuitive, lightweight, perfect for quick data tasks. | [![Stars](https://img.shields.io/github/stars/ez0000001000000/Goop?style=social)](https://github.com/ez0000001000000/Goop) |
| [colly](https://github.com/gocolly/colly) | Elegant, fast scraping framework. Supports async, cookies, headers, robots.txt. | [![Stars](https://img.shields.io/github/stars/gocolly/colly?style=social)](https://github.com/gocolly/colly) |
| [goquery](https://github.com/PuerkitoBio/goquery) | jQuery-like DOM parsing and traversal using CSS selectors. | [![Stars](https://img.shields.io/github/stars/PuerkitoBio/goquery?style=social)](https://github.com/PuerkitoBio/goquery) |
| [htmlquery](https://github.com/antchfx/htmlquery) | XPath query support for HTML/XML documents with streaming. | [![Stars](https://img.shields.io/github/stars/antchfx/htmlquery?style=social)](https://github.com/antchfx/htmlquery) |
| [rod](https://github.com/go-rod/rod) | DevTools driver for browser automation and scraping. High-level API, headless Chrome support. | [![Stars](https://img.shields.io/github/stars/go-rod/rod?style=social)](https://github.com/go-rod/rod) |

> 🛠️ *Building a scraper? Start with [Goop](https://github.com/ez0000001000000/Goop) ⭐ for simple tasks, or [rod](https://github.com/go-rod/rod) for dynamic JS-heavy sites.*

---

### 🌐 Web Frameworks

| Package | Description | Stars |
|---------|-------------|-------|
| [aah](https://github.com/aahframework/aah) | Scalable, performant, and secure web framework for Go with MVC and plugin support. | [![Stars](https://img.shields.io/github/stars/aahframework/aah?style=social)](https://github.com/aahframework/aah) |
| [beego](https://github.com/beego/beego) | Full-featured web framework with ORM, cache, session management, and admin panel. | [![Stars](https://img.shields.io/github/stars/beego/beego?style=social)](https://github.com/beego/beego) |
| [buffalo](https://github.com/gobuffalo/buffalo) | Rapid web development framework with hot-reload, generators, and plugins. | [![Stars](https://img.shields.io/github/stars/gobuffalo/buffalo?style=social)](https://github.com/gobuffalo/buffalo) |
| [chi](https://github.com/go-chi/chi) | Lightweight, idiomatic router. Standard library compatible, middleware-friendly. | [![Stars](https://img.shields.io/github/stars/go-chi/chi?style=social)](https://github.com/go-chi/chi) |
| [echo](https://github.com/labstack/echo) | High-performance, minimalist framework with extensible middleware. | [![Stars](https://img.shields.io/github/stars/labstack/echo?style=social)](https://github.com/labstack/echo) |
| [fiber](https://github.com/gofiber/fiber) | Express.js-inspired framework built on Fasthttp. Zero allocation router. | [![Stars](https://img.shields.io/github/stars/gofiber/fiber?style=social)](https://github.com/gofiber/fiber) |
| [gin](https://github.com/gin-gonic/gin) | Blazing-fast HTTP framework with middleware, validation, and Martini-like API. | [![Stars](https://img.shields.io/github/stars/gin-gonic/gin?style=social)](https://github.com/gin-gonic/gin) |
| [httprouter](https://github.com/julienschmidt/httprouter) | High-performance HTTP request router with wildcard and named parameter support. | [![Stars](https://img.shields.io/github/stars/julienschmidt/httprouter?style=social)](https://github.com/julienschmidt/httprouter) |
| [iris](https://github.com/kataras/iris) | Full-featured web framework with MVC, Websocket, sessions, and API support. | [![Stars](https://img.shields.io/github/stars/kataras/iris?style=social)](https://github.com/kataras/iris) |
| [kit](https://github.com/go-kit/kit) | Programming toolkit for building microservices with clean boundaries and transport layers. | [![Stars](https://img.shields.io/github/stars/go-kit/kit?style=social)](https://github.com/go-kit/kit) |
| [mux](https://github.com/gorilla/mux) | Powerful URL router and dispatcher for Golang with regex matching and middleware. | [![Stars](https://img.shields.io/github/stars/gorilla/mux?style=social)](https://github.com/gorilla/mux) |

---

### ⚡ CLI & Terminal Tools

| Package | Description | Stars |
|---------|-------------|-------|
| [bubbletea](https://github.com/charmbracelet/bubbletea) | TUI framework based on The Elm Architecture. Build beautiful terminal apps. | [![Stars](https://img.shields.io/github/stars/charmbracelet/bubbletea?style=social)](https://github.com/charmbracelet/bubbletea) |
| [cli](https://github.com/urfave/cli) | Simple, fast package for building command-line apps. | [![Stars](https://img.shields.io/github/stars/urfave/cli?style=social)](https://github.com/urfave/cli) |
| [cobra](https://github.com/spf13/cobra) | Powerful CLI framework used by Kubernetes, Hugo, GitHub CLI. | [![Stars](https://img.shields.io/github/stars/spf13/cobra?style=social)](https://github.com/spf13/cobra) |
| [pterm](https://github.com/pterm/pterm) | Modern library for beautiful terminal output: tables, spinners, progress bars. | [![Stars](https://img.shields.io/github/stars/pterm/pterm?style=social)](https://github.com/pterm/pterm) |

---

### 🗄️ Databases & ORMs

| Package | Description | Stars |
|---------|-------------|-------|
| [bun](https://github.com/uptrace/bun) | SQL client for Go with ORM and query builder, supports PostgreSQL, MySQL, SQLite. | [![Stars](https://img.shields.io/github/stars/uptrace/bun?style=social)](https://github.com/uptrace/bun) |
| [ent](https://github.com/facebook/ent) | Entity framework with schema-first design and code generation. | [![Stars](https://img.shields.io/github/stars/facebook/ent?style=social)](https://github.com/facebook/ent) |
| [go-redis](https://github.com/redis/go-redis) | Redis client with clustering, pub/sub, caching, and Sentinel support. | [![Stars](https://img.shields.io/github/stars/redis/go-redis?style=social)](https://github.com/redis/go-redis) |
| [go-sqlite3](https://github.com/mattn/go-sqlite3) | SQLite3 driver for Go using database/sql with CGo bindings. | [![Stars](https://img.shields.io/github/stars/mattn/go-sqlite3?style=social)](https://github.com/mattn/go-sqlite3) |
| [gorm](https://github.com/go-gorm/gorm) | Full-featured ORM: associations, migrations, plugins, multiple DBs. | [![Stars](https://img.shields.io/github/stars/go-gorm/gorm?style=social)](https://github.com/go-gorm/gorm) |
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | Official MongoDB driver for Go with full CRUD and aggregation support. | [![Stars](https://img.shields.io/github/stars/mongodb/mongo-go-driver?style=social)](https://github.com/mongodb/mongo-go-driver) |
| [pgx](https://github.com/jackc/pgx) | Powerful PostgreSQL driver and toolkit. Pure Go, high performance. | [![Stars](https://img.shields.io/github/stars/jackc/pgx?style=social)](https://github.com/jackc/pgx) |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | Generate type-safe Go code from your database schema. | [![Stars](https://img.shields.io/github/stars/volatiletech/sqlboiler?style=social)](https://github.com/volatiletech/sqlboiler) |
| [sqlc](https://github.com/sqlc-dev/sqlc) | Generate type-safe Go code from SQL. No runtime ORM overhead. | [![Stars](https://img.shields.io/github/stars/sqlc-dev/sqlc?style=social)](https://github.com/sqlc-dev/sqlc) |
| [sqlx](https://github.com/jmoiron/sqlx) | Extensions to database/sql for easier queries and struct scanning. | [![Stars](https://img.shields.io/github/stars/jmoiron/sqlx?style=social)](https://github.com/jmoiron/sqlx) |

---

### 🔐 Auth & Security

| Package | Description | Stars |
|---------|-------------|-------|
| [bcrypt](https://github.com/golang/crypto/tree/master/bcrypt) | Secure password hashing (part of `golang.org/x/crypto`). | — |
| [casbin](https://github.com/casbin/casbin) | Authorization library supporting ACL, RBAC, ABAC. | [![Stars](https://img.shields.io/github/stars/casbin/casbin?style=social)](https://github.com/casbin/casbin) |
| [jwt](https://github.com/golang-jwt/jwt) | Reliable, well-maintained JWT implementation for Go. | [![Stars](https://img.shields.io/github/stars/golang-jwt/jwt?style=social)](https://github.com/golang-jwt/jwt) |
| [otp](https://github.com/pquerna/otp) | Standards-compliant HOTP (RFC 4226) and TOTP (RFC 6238) implementation for 2FA. | [![Stars](https://img.shields.io/github/stars/pquerna/otp?style=social)](https://github.com/pquerna/otp) |

---

### 🧪 Testing

| Package | Description | Stars |
|---------|-------------|-------|
| [ginkgo](https://github.com/onsi/ginkgo) | BDD-style testing framework (often paired with Gomega). | [![Stars](https://img.shields.io/github/stars/onsi/ginkgo?style=social)](https://github.com/onsi/ginkgo) |
| [gock](https://github.com/h2non/gock) | HTTP mocking library with regex matching and persistence. | [![Stars](https://img.shields.io/github/stars/h2non/gock?style=social)](https://github.com/h2non/gock) |
| [gomega](https://github.com/onsi/gomega) | Matcher/assertion library for Go, designed to pair with Ginkgo BDD framework. | [![Stars](https://img.shields.io/github/stars/onsi/gomega?style=social)](https://github.com/onsi/gomega) |
| [gotestsum](https://github.com/gotestyourself/gotestsum) | Enhanced `go test` runner with pretty output and JUnit XML. | [![Stars](https://img.shields.io/github/stars/gotestyourself/gotestsum?style=social)](https://github.com/gotestyourself/gotestsum) |
| [httpmock](https://github.com/jarcoal/httpmock) | HTTP mocking for Golang with easy registration of responders for testing. | [![Stars](https://img.shields.io/github/stars/jarcoal/httpmock?style=social)](https://github.com/jarcoal/httpmock) |
| [mock](https://github.com/golang/mock) | Mocking framework with code generation (gomock). | [![Stars](https://img.shields.io/github/stars/golang/mock?style=social)](https://github.com/golang/mock) |
| [mockery](https://github.com/vektra/mockery) | Mock code autogenerator for Go interfaces using testify. | [![Stars](https://img.shields.io/github/stars/vektra/mockery?style=social)](https://github.com/vektra/mockery) |
| [testify](https://github.com/stretchr/testify) | Assertion library and mocking toolkit for Go tests. | [![Stars](https://img.shields.io/github/stars/stretchr/testify?style=social)](https://github.com/stretchr/testify) |

---

### 📦 Utilities

| Package | Description | Stars |
|---------|-------------|-------|
| [cast](https://github.com/spf13/cast) | Safe, easy type casting and conversion for Go (string, int, bool, time, etc.). | [![Stars](https://img.shields.io/github/stars/spf13/cast?style=social)](https://github.com/spf13/cast) |
| [koanf](https://github.com/knadh/koanf) | Lightweight, extensible configuration management with env, file, and flag support. | [![Stars](https://img.shields.io/github/stars/knadh/koanf?style=social)](https://github.com/knadh/koanf) |
| [logrus](https://github.com/sirupsen/logrus) | Structured logging optimized for JSON output, API-compatible with stdlib. | [![Stars](https://img.shields.io/github/stars/sirupsen/logrus?style=social)](https://github.com/sirupsen/logrus) |
| [pointer](https://github.com/xorcare/pointer) | Helper functions for working with pointers to primitives. | [![Stars](https://img.shields.io/github/stars/xorcare/pointer?style=social)](https://github.com/xorcare/pointer) |
| [quic-go](https://github.com/quic-go/quic-go) | QUIC and HTTP/3 implementation in pure Go with low latency and multiplexing. | [![Stars](https://img.shields.io/github/stars/quic-go/quic-go?style=social)](https://github.com/quic-go/quic-go) |
| [retry-go](https://github.com/avast/retry-go) | Simple retry mechanism for Go with customizable backoff strategies. | [![Stars](https://img.shields.io/github/stars/avast/retry-go?style=social)](https://github.com/avast/retry-go) |
| [retryablehttp](https://github.com/hashicorp/go-retryablehttp) | HTTP client with automatic retries and exponential backoff. | [![Stars](https://img.shields.io/github/stars/hashicorp/go-retryablehttp?style=social)](https://github.com/hashicorp/go-retryablehttp) |
| [slog](https://pkg.go.dev/log/slog) | Structured logging (stdlib since Go 1.21). | — |
| [validator](https://github.com/go-playground/validator) | Struct/field validation with rich tags and custom rules. | [![Stars](https://img.shields.io/github/stars/go-playground/validator?style=social)](https://github.com/go-playground/validator) |
| [viper](https://github.com/spf13/viper) | Complete configuration solution: JSON, YAML, TOML, env vars, remote configs. | [![Stars](https://img.shields.io/github/stars/spf13/viper?style=social)](https://github.com/spf13/viper) |
| [websocket](https://github.com/gorilla/websocket) | Fast, well-tested WebSocket client and server implementation for Go. | [![Stars](https://img.shields.io/github/stars/gorilla/websocket?style=social)](https://github.com/gorilla/websocket) |
| [zap](https://github.com/uber-go/zap) | Blazing-fast, structured, leveled logging. | [![Stars](https://img.shields.io/github/stars/uber-go/zap?style=social)](https://github.com/uber-go/zap) |
| [zerolog](https://github.com/rs/zerolog) | Zero-allocation, fast JSON logging library for Go. | [![Stars](https://img.shields.io/github/stars/rs/zerolog?style=social)](https://github.com/rs/zerolog) |

---

### 📨 Messaging & Queues

| Package | Description | Stars |
|---------|-------------|-------|
| [amqp](https://github.com/rabbitmq/amqp091-go) | Official RabbitMQ AMQP 0.9.1 client for Go. | [![Stars](https://img.shields.io/github/stars/rabbitmq/amqp091-go?style=social)](https://github.com/rabbitmq/amqp091-go) |
| [kafka-go](https://github.com/segmentio/kafka-go) | Kafka library for Go with high-level API and consumer group support. | [![Stars](https://img.shields.io/github/stars/segmentio/kafka-go?style=social)](https://github.com/segmentio/kafka-go) |
| [nsq](https://github.com/nsqio/nsq) | Realtime distributed messaging platform designed for scale and reliability. | [![Stars](https://img.shields.io/github/stars/nsqio/nsq?style=social)](https://github.com/nsqio/nsq) |

---

### 📁 File Storage

| Package | Description | Stars |
|---------|-------------|-------|
| [minio-go](https://github.com/minio/minio-go) | MinIO Client SDK for Go — S3-compatible object storage with full API support. | [![Stars](https://img.shields.io/github/stars/minio/minio-go?style=social)](https://github.com/minio/minio-go) |

---

### ⏰ Scheduling

| Package | Description | Stars |
|---------|-------------|-------|
| [cron](https://github.com/robfig/cron) | Cron library for Go with Quartz-compatible scheduler and time zone support. | [![Stars](https://img.shields.io/github/stars/robfig/cron?style=social)](https://github.com/robfig/cron) |
| [gocron](https://github.com/go-co-op/gocron) | Job scheduling package for Go with cron-like syntax, timezones, and features. | [![Stars](https://img.shields.io/github/stars/go-co-op/gocron?style=social)](https://github.com/go-co-op/gocron) |

---

### 🚀 Concurrency

| Package | Description | Stars |
|---------|-------------|-------|
| [ants](https://github.com/panjf2000/ants) | High-performance goroutine pool with auto-scaling and rate limiting. | [![Stars](https://img.shields.io/github/stars/panjf2000/ants?style=social)](https://github.com/panjf2000/ants) |
| [conc](https://github.com/sourcegraph/conc) | Better structured concurrency for Go with error handling and panic safety. | [![Stars](https://img.shields.io/github/stars/sourcegraph/conc?style=social)](https://github.com/sourcegraph/conc) |
| [errgroup](https://pkg.go.dev/golang.org/x/sync/errgroup) | Synchronize goroutines and propagate errors (`x/sync`). | — |
| [stream](https://github.com/youthlin/stream) | Java 8-like Stream API: map, filter, reduce, and more. | [![Stars](https://img.shields.io/github/stars/youthlin/stream?style=social)](https://github.com/youthlin/stream) |
| [tunny](https://github.com/Jeffail/tunny) | Simple, flexible goroutine worker pool with context support. | [![Stars](https://img.shields.io/github/stars/Jeffail/tunny?style=social)](https://github.com/Jeffail/tunny) |

---

### 🌐 Networking

| Package | Description | Stars |
|---------|-------------|-------|
| [fasthttp](https://github.com/valyala/fasthttp) | Fast HTTP implementation for Go, zero-allocation router, up to 10x faster than net/http. | [![Stars](https://img.shields.io/github/stars/valyala/fasthttp?style=social)](https://github.com/valyala/fasthttp) |
| [grpc-go](https://github.com/grpc/grpc-go) | Official Go implementation of gRPC for high-performance RPC communication. | [![Stars](https://img.shields.io/github/stars/grpc/grpc-go?style=social)](https://github.com/grpc/grpc-go) |
| [yggdrasil](https://github.com/yggdrasil-network/yggdrasil-go) | Encrypted IPv6 network with automatic peer discovery and end-to-end encryption. | [![Stars](https://img.shields.io/github/stars/yggdrasil-network/yggdrasil-go?style=social)](https://github.com/yggdrasil-network/yggdrasil-go) |

---

### ☁️ Cloud/DevOps

| Package | Description | Stars |
|---------|-------------|-------|
| [aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) | Official AWS SDK for Go v2 with modular design and improved performance. | [![Stars](https://img.shields.io/github/stars/aws/aws-sdk-go-v2?style=social)](https://github.com/aws/aws-sdk-go-v2) |
| [consul/api](https://github.com/hashicorp/consul) | HashiCorp Consul API client for service discovery, health checks, and KV storage. | [![Stars](https://img.shields.io/github/stars/hashicorp/consul?style=social)](https://github.com/hashicorp/consul) |
| [terraform-plugin-sdk](https://github.com/hashicorp/terraform-plugin-sdk) | SDK for building Terraform providers and plugins in Go. | [![Stars](https://img.shields.io/github/stars/hashicorp/terraform-plugin-sdk?style=social)](https://github.com/hashicorp/terraform-plugin-sdk) |

---

### 🤖 AI/ML

| Package | Description | Stars |
|---------|-------------|-------|
| [go-openai](https://github.com/sashabaranov/go-openai) | OpenAI API client for Go with support for ChatGPT, completions, embeddings, and more. | [![Stars](https://img.shields.io/github/stars/sashabaranov/go-openai?style=social)](https://github.com/sashabaranov/go-openai) |
| [goml](https://github.com/cdipaolo/goml) | On-line machine learning library in pure Go with streaming support. | [![Stars](https://img.shields.io/github/stars/cdipaolo/goml?style=social)](https://github.com/cdipaolo/goml) |
| [gorgonia](https://github.com/gorgonia/gorgonia) | Graph-based computational library for ML (like Theano for Go). | [![Stars](https://img.shields.io/github/stars/gorgonia/gorgonia?style=social)](https://github.com/gorgonia/gorgonia) |
| [langchaingo](https://github.com/tmc/langchaingo) | LangChain implementation in Go for building LLM-powered applications. | [![Stars](https://img.shields.io/github/stars/tmc/langchaingo?style=social)](https://github.com/tmc/langchaingo) |
| [onnx-go](https://github.com/owulveryck/onnx-go) | Import and run ONNX models in pure Go with backend flexibility. | [![Stars](https://img.shields.io/github/stars/owulveryck/onnx-go?style=social)](https://github.com/owulveryck/onnx-go) |

---

### 🎨 UI/Frontend

| Package | Description | Stars |
|---------|-------------|-------|
| [fyne](https://github.com/fyne-io/fyne) | Cross-platform GUI toolkit with Material Design and native widgets. | [![Stars](https://img.shields.io/github/stars/fyne-io/fyne?style=social)](https://github.com/fyne-io/fyne) |
| [go-app](https://github.com/maxence-charriere/go-app) | Build progressive web apps (PWAs) in pure Go + WebAssembly. | [![Stars](https://img.shields.io/github/stars/maxence-charriere/go-app?style=social)](https://github.com/maxence-charriere/go-app) |
| [wails](https://github.com/wailsapp/wails) | Build desktop apps with Go backend + web frontend (like Electron, but Go). | [![Stars](https://img.shields.io/github/stars/wailsapp/wails?style=social)](https://github.com/wailsapp/wails) |

---

## 🤝 Contributing

We ❤️ contributions! Add a package, fix a typo, or suggest a new category.

### How to Add a Package:
1. Fork the repo
2. Find the right category (or propose a new one)
3. Add your entry **alphabetically** within the section:
   ```markdown
   | [repo-name](https://github.com/user/repo) | Short, clear description. | [![Stars](badge)](link) |
   ```

Ensure the repo:
✅ Is written in Go 🐹
✅ Has a go.mod file (or stdlib-compatible)
✅ Is actively maintained or historically significant
✅ Has an open-source license

Submit a PR with title: `feat(scrapers): add PackageName`

📖 See CONTRIBUTING.md for full guidelines.

## 📜 License
This list is licensed under the MIT License. Individual packages retain their original licenses — always verify before use.

🐹 Made with ❤️ by the Build With Go community
 🏠 [Organization](https://github.com/build-with-go) • 📝 [Suggest a Package](https://github.com/build-with-go/awesome-golang-scrapers/issues/new?assignees=&labels=&template=suggest-a-package.md&title=) 
 **Last updated: April 2026** • Compatible with Go 1.21+
