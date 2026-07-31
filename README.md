<div align="center">

# 📄 CV

**My resume, written in Typst — auto-compiled to PDF on every push.**

[![Build Resume](https://github.com/turki013/cv/actions/workflows/build.yml/badge.svg)](https://github.com/turki013/cv/actions)
[![Latest Release](https://img.shields.io/github/v/release/turki013/cv?label=latest%20release&color=brightgreen)](https://github.com/turki013/cv/releases/latest)
[![Typst](https://img.shields.io/badge/Typst-000000?logo=typst&logoColor=white)](https://typst.app)
[![Last Commit](https://img.shields.io/github/last-commit/turki013/cv)](https://github.com/turki013/cv/commits/main)

</div>

-----

## 📌 About

This repository holds the source of my curriculum vitae, typeset with [Typst](https://typst.app) instead of LaTeX or a design tool — clean source, real version control, and no design software required.

A GitHub Actions workflow compiles `resume.typ` into a PDF on every push and publishes it as a [release](../../releases), so the latest version is always available with one click — no manual exports.

## 🛠 Built With

|Tool                      |Purpose                                       |
|--------------------------|----------------------------------------------|
|[Typst](https://typst.app)|Typesetting the resume                        |
|GitHub Actions            |CI — compiles + releases the PDF automatically|

## 🚀 Usage

### Compile locally

```bash
# 1. Install Typst
# https://github.com/typst/typst#installation

# 2. Clone the repo
git clone https://github.com/turki013/cv.git
cd cv

# 3. Compile
typst compile resume.typ
```

### Automatic builds

Every push to `main`:

1. Triggers the CI workflow (`.github/workflows/`)
1. Compiles `resume.typ` → `resume.pdf`
1. Publishes it to [Releases](../../releases) as the new **Latest**

## 📥 Download

Always get the newest version here → [**Latest Release**](../../releases/latest)

## 📂 Structure

```
.
├── .github/workflows/   # CI: build + release automation
├── resume.typ           # Typst source
└── README.md
```



-----

<div align="center">
<sub>Built with Typst • Automated with GitHub Actions</sub>
</div>
