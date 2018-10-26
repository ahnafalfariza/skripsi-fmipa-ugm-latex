# Template Skripsi FMIPA UGM versi Latex
[![PR's Welcome](https://img.shields.io/badge/prs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Template Latex Skripsi FMIPA UGM. Lanjutan modifikasi template official tanpa harus pakai Sharelatex.

## Table Of Contents
 - [Brief description](#what-are-in-this-repository)
 - [MANIFESTO](#latex-manifesto-in-this-repo)
 - [How to Install Latex (Linux)](#installation-on-linux)
   - [Full Install](#full-package-install)
   - [Basic Install](#basic-package-install)
 - [How to Install Latex (OSX)](#osx)
 - [How to Install Latex (Windows)](#windows)
 - [How to Compile into pdf](#how-to-compile-into-pdf)

## What are in this repository?
 - Class file modifikasi dari skripsi dan proposal skripsi
 - Script untuk mempermudah compile latex menjadi pdf

## LATEX MANIFESTO in This Repo
 * Tidak perlu repot-repot mengatur layouting, pagination, numbering, dan semua kelemahan yang ada pada document editor.
 * Pakai [BibTex](http://www.bibtex.org/) untuk mempermudah sitasi hanya dengan bantuan [Mendeley](https://www.mendeley.com/downloads) jika paper pdf yang kamu miliki sudah tersedia offline (di harddisk).
 * *BibTex* juga bisa didapat dengan **cite** langsung dari [Google Scholar](https://scholar.google.co.id/) atau journal online lain yang ada pilihan sitasi menggunakan *BibTex*
 * Bisa menulis skripsi dengan *Text Editor* favorit anda dengan menambahkan plugin latex. Atom/Sublime/Vim ada pluginnya semua. Atau gunakan TeXmaker.

## How to Install Latex (Linux)

 Disini terdapat dua opsi untuk install compiler latex. [Full](#install-package-latex-secara-keseluruhan) dan seperlunya.

### Full Package Install
* Buka terminal dan ketik
  ```bash
sudo apt-get install texlive-full
  ```

### Basic Package Install
- Buka terminal dan ketik
  ```bash
sudo apt-get install texlive texlive-base texlive-lang-english texlive-lang-other
  ```

## How to compile into pdf?

- Buat build script menjadi executable
  ```bash
chmod +x build.sh
  ```

- Eksekusi file
  ```bash
./build.sh
  ```

## OSX?

Menyusul

## Windows?

Pakai MikTex saja kalau tidak mau ribet! GUI enak!
 1. Download dan Install [MikTex](https://miktex.org/download).
 2. Download dan Install editor yang cocok: [TeXmaker](http://www.xm1math.net/texmaker/) (cross-platform latex editor).

## Ada Internet?

Bisa pakai [Overleaf](https://www.overleaf.com/).

# Selamat Mengerjakan Skripsi!!!

## TODO:
- [ ] Tambah tutorial mendetail cara install dan konfigurasi latex
- [ ] Tambah tutorial BibTex
- [ ] Script untuk OSX dan Windows
- [ ] Tambah contoh file .tex
