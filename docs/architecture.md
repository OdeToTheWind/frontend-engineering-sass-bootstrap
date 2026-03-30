# Frontend Engineering Architecture

## 🎨 Global Design System
* **Framework:** Bootstrap 5.3.x
* **Pre-processor:** SASS (Dart SASS)
* **Theme Strategy:** Customizing Bootstrap via SCSS variables.

## 📁 SASS Structure
* `_variables.scss`: Global overrides (Colors, Fonts).
* `_mixins.scss`: Custom reusable snippets.
* `main.scss`: Entry point that imports Bootstrap.

## ✅ Demo 01 Implementation
* **Custom Colors:** Defined `$primary: #0d6efd` and `$dark: #212529`.
* **Typography:** Integrated Google Fonts (Inter/Roboto).