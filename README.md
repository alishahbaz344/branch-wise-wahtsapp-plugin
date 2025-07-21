# 📌 Branch WhatsApp Sticky Button – WordPress Plugin

**Branch WhatsApp Sticky Button** is a lightweight and powerful WordPress plugin that displays a **WhatsApp sticky chat button** on specific branch-based pages. Each page can be assigned a **unique WhatsApp number**, perfect for multi-branch businesses or location-specific customer support.

---

## ✨ Features

* 🔄 Display a **custom WhatsApp number per page slug**
* 📱 Responsive sticky button on the **bottom-left** corner
* 🧠 Easy-to-use admin panel to manage branches and numbers
* 🛡️ Secure input handling and admin form submission
* 🎨 Customizable UI with hover animation and responsive design

---

## 🛠️ How It Works

1. Go to **Settings > Branch WhatsApp Button** in your WordPress dashboard
2. Add page slugs (e.g., `lahore-branch`) and their corresponding WhatsApp numbers
3. The plugin automatically detects the current page slug and displays the matching WhatsApp button

---

## 📦 Installation

1. Upload the plugin to your `/wp-content/plugins/` directory
2. Activate it through the **Plugins** menu in WordPress
3. Go to **Settings > Branch WhatsApp Button** to configure branch numbers

---

## 🧩 Example

```php
[
  ['slug' => 'karachi-branch', 'number' => '923001234567'],
  ['slug' => 'lahore-branch', 'number' => '923451234567'],
]
```

---

## 🔐 Security

* CSRF protection with `check_admin_referer()`
* Sanitization via `sanitize_text_field()` and `sanitize_title()`
* Output escaping with `esc_attr()`

---

## 🧑‍💻 Author

**Ali Shahbaz**
🔗 [atechno.pk](https://atechno.pk)
📧 [info@atechno.pk](mailto:info@atechno.pk)

---

## 📃 License

Licensed under the [GPLv2](https://www.gnu.org/licenses/gpl-2.0.html).
