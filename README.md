# My Personal Business Card

---

## Overview

This repository contains the **LaTeX source files** for my personal business card.  
It demonstrates how to manage a small project with Git, including branching, merging, and version control for assets like logos.

---

## Preview

You can view the final business card PDF here:  
[View My Business Card PDF](https://drive.google.com/file/d/1JlckTrYCkPDTKG9jE_0qUJQdhPF_2_yk/view?usp=sharing)



## The Story

I wanted a business card that reflects my style and can be **easily updated**.  
Using LaTeX allowed me to:

- Keep a **clean source file** (`card.tex`)  
- Add and update a **custom logo** (`logo.pdf`)  
- Compile a professional-looking PDF repeatedly without starting from scratch  

To manage changes safely, I used a separate branch (`new_logo`) for experimenting with new logos before merging them into the main branch (`master`).

---

## Files

- `card.tex` → LaTeX source of the business card  
- `logo.pdf` → My personal logo  
- `.gitignore` → Ignores compiled PDFs and temporary LaTeX files  
- `README.md` → This file  
- `myCard/` → Optional folder with images or resources used in the card  

> **Note:** Compiled PDFs (`card.pdf`) and auxiliary LaTeX files are ignored in Git to keep the repository clean.

---

## Build / Compile Instructions

1. Install **TeX Live** (or MikTeX).  
2. Compile the card using **XeLaTeX**:

```bash
xelatex card.tex
