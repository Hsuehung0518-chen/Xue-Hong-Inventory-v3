# 📦 Xue-Hong Inventory System v5 (Firebase Edition)

> **Status:** 🚀 Active Development (v5 Upgrade)
> **Author:** Xue-Hong (學宏)
> **Role:** Personal Chief AI Orchestrator

## 🎯 Project Overview
A modern, mobile-friendly personal inventory system. This version (v5) moves from the old Drive-Proxy method to a high-performance **Direct Firebase Storage** architecture.

## 🛠️ Technology Stack
* **Storage:** Firebase Storage (Direct URL Access)
* **Database:** Google Sheets (Multi-Sheet Mode)
* **Backend:** Google Apps Script (RESTful API)
* **Security:** HMAC-SHA256 (5-minute Time-Locked Tokens)
* **Frontend:** GitHub Pages (Tailwind CSS / Dark-Glass UI)

## ✨ Core Features
* ✅ **Mobile First:** Camera-ready upload interface.
* ✅ **Multi-Category:** Smart routing to *Collections*, *Fridge*, *Books*, or *Wardrobe*.
* ✅ **Security:** HMAC token verification prevents unauthorized writes.
* ✅ **Visual UX:** Dark-glass aesthetic with dynamic status monitoring (LIVE indicator).
* 🕒 **Coming Soon:** Automatic expiry-date alerts for Fridge items.

## 📊 Database Schema (Google Sheets)
Each sheet follows a strict 5-column structure to ensure system integrity:
`NAME | SPEC | URL | QTY | UPDATEDAT`

## 📝 TODO (Execution Pipeline)
- [x] Step 1: Apps Script Backend Multi-Sheet Logic.
- [ ] Step 2: `admin.html` API & Token Monitoring Panel.
- [x] Step 3: `index.html` Multi-category UI Switching.
- [x] Step 4: `upload.html` Category Selection & Firebase Linkage.
- [ ] Step 5: Advanced Logic for Fridge expiry-date highlighting (Red/Yellow/Green).

---
*Created with the collaboration of Gemini AI - Exclusive Personal Polymath.*
