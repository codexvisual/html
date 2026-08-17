<div align="center">

# 🌐 Ultimate HTML Commands Key Guide

**Tags · Attributes · Structure · Semantics**  
_Everything you need to write clean HTML_

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![W3C Valid](https://img.shields.io/badge/W3C-Validated-brightgreen?style=for-the-badge)](https://validator.w3.org/)

</div>

---

## 📄 1. Basic Structure (বেসিক স্ট্রাকচার)

<div align="center">

| 🧱 Tag / Code | 📖 Description |
|:--------------|:---------------|
| `<!DOCTYPE html>` | HTML5 ডকুমেন্ট ডিক্লেয়ার |
| `<html lang="en">` | পুরো পেজের রুট এলিমেন্ট |
| `<head> ... </head>` | মেটাডাটা, টাইটেল, লিংক |
| `<title>Page Title</title>` | ব্রাউজার ট্যাবের টাইটেল |
| `<body> ... </body>` | ভিজিবল কন্টেন্ট |
| `<!-- This is a comment -->` | HTML কমেন্ট (ব্রাউজারে দেখা যায় না) |

</div>

---

## 🔤 2. Text & Headings (টেক্সট ও হেডিং)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<h1> to <h6>` | হেডিং (বড় থেকে ছোট) |
| `<p> ... </p>` | প্যারাগ্রাফ |
| `<br>` | লাইন ব্রেক |
| `<hr>` | হরাইজন্টাল রুল (থিম্যাটিক ব্রেক) |
| `<b>` / `<strong>` | বোল্ড টেক্সট (`<strong>` সিমান্টিক) |
| `<i>` / `<em>` | ইটালিক টেক্সট (`<em>` সিমান্টিক) |
| `<u>` | আন্ডারলাইন |
| `<small>` | ছোট টেক্সট |
| `<mark>` | হাইলাইটেড টেক্সট |
| `<del>` | ডিলিটেড (স্ট্রাইকথ্রু) টেক্সট |
| `<sup>` / `<sub>` | সুপারস্ক্রিপ্ট / সাবস্ক্রিপ্ট |

</div>

---

## 📋 3. Lists (তালিকা)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<ul> ... </ul>` | আনঅর্ডার্ড লিস্ট (বুলেট) |
| `<ol> ... </ol>` | অর্ডার্ড লিস্ট (নাম্বার) |
| `<li> ... </li>` | লিস্ট আইটেম |
| `<dl>` / `<dt>` / `<dd>` | ডেসক্রিপশন লিস্ট |

</div>

---

## 🔗 4. Links & Images (লিংক ও ছবি)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<a href="url">Link</a>` | হাইপারলিংক |
| `<a href="url" target="_blank">` | নতুন ট্যাবে লিংক ওপেন |
| `<a href="#section">` | পেজের ভেতরে নেভিগেশন (anchor) |
| `<img src="image.jpg" alt="text">` | ছবি দেখানো |
| `<img src="..." width="300" height="200">` | ছবির সাইজ নির্ধারণ |

</div>

---

## 📊 5. Tables (টেবিল)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<table>` | টেবিল শুরু |
| `<tr>` | টেবিল রো |
| `<th>` | টেবিল হেডার সেল (বোল্ড, সেন্টার) |
| `<td>` | টেবিল ডাটা সেল |
| `<caption>` | টেবিল ক্যাপশন |
| `<thead>` | টেবিল হেডার গ্রুপ |
| `<tbody>` | টেবিল বডি গ্রুপ |
| `<tfoot>` | টেবিল ফুটার গ্রুপ |
| `colspan="2"` / `rowspan="2"` | সেল মার্জ করা |

</div>

---

## 📝 6. Forms (ফর্ম)

<div align="center">

| Tag / Attribute | Description |
|:----------------|:------------|
| `<form action="/submit" method="POST">` | ফর্ম শুরু |
| `<input type="text" placeholder="Name">` | টেক্সট ইনপুট |
| `<input type="email">` | ইমেইল ইনপুট |
| `<input type="password">` | পাসওয়ার্ড ইনপুট |
| `<input type="number">` | নাম্বার ইনপুট |
| `<input type="checkbox">` | চেকবক্স |
| `<input type="radio" name="group">` | রেডিও বাটন |
| `<input type="file">` | ফাইল আপলোড |
| `<input type="submit" value="Send">` | সাবমিট বাটন |
| `<button type="submit">Submit</button>` | বাটন (সাবমিট) |
| `<textarea rows="4" cols="50"></textarea>` | মাল্টি-লাইন টেক্সট |
| `<select><option>...</option></select>` | ড্রপডাউন মেনু |
| `<label for="id">Label</label>` | লেবেল (অ্যাকসেসিবিলিটি) |
| `required`, `placeholder`, `maxlength` | কমন অ্যাট্রিবিউট |

</div>

---

## 🧱 7. Semantic HTML (সিমান্টিক এলিমেন্ট)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<header>` | পেজ বা সেকশনের হেডার |
| `<nav>` | নেভিগেশন লিংক |
| `<main>` | মূল কন্টেন্ট |
| `<section>` | থিম্যাটিক সেকশন |
| `<article>` | স্বাধীন কন্টেন্ট (ব্লগ পোস্ট) |
| `<aside>` | সাইডবার / পরিপূরক কন্টেন্ট |
| `<footer>` | ফুটার |
| `<figure>` / `<figcaption>` | ছবি/ডায়াগ্রাম + ক্যাপশন |
| `<details>` + `<summary>` | কলাপসিবল কন্টেন্ট |

</div>

---

## 🎬 8. Media (মিডিয়া)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<audio controls><source src="song.mp3"></audio>` | অডিও প্লেয়ার |
| `<video controls width="400"><source src="movie.mp4"></video>` | ভিডিও প্লেয়ার |
| `<iframe src="url" width="560" height="315"></iframe>` | অন্য পেজ এম্বেড (YouTube) |

</div>

---

## 💡 9. Meta & SEO (মেটা ট্যাগ)

<div align="center">

| Tag | Description |
|:----|:------------|
| `<meta charset="UTF-8">` | ক্যারেক্টার এনকোডিং |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | রেসপনসিভ ডিজাইন |
| `<meta name="description" content="...">` | পেজ ডেসক্রিপশন (SEO) |
| `<meta name="keywords" content="...">` | কীওয়ার্ড (পুরনো) |
| `<link rel="icon" href="favicon.ico">` | ফেভিকন |

</div>

---

<div align="center">

### 🚀 Bookmark this for instant reference  
**Happy Coding with HTML!**

[![Profile Views](https://komarev.com/ghpvc/?username=your-username&color=E34F26&style=flat-square)](https://github.com/your-username)

</div> html

---

## Installation

### Prerequisites
- A modern web browser
- (Optional) [Visual Studio Code](https://code.visualstudio.com/) with the Live Server extension

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/codexvisual/html.git
   cd html
   ```
2. Open the project folder.
3. Open `index.html` directly in your browser, or use **Live Server** in VS Code:
   ```bash
   npx live-server
   ```
