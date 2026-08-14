# 🏨 Online Hotel Management System

A fully responsive, multi-section hotel booking website built with pure **HTML, CSS, and JavaScript**. This project simulates a real-world hotel website complete with room availability checking, reservation forms, an image gallery, guest reviews, a contact section with FAQ, and a fully structured footer — all in a single-page layout.

---

## 🌐 Live Preview

> Clone the repo and open `index.html` in any browser — no server or installation required!

---

## 📸 Website Sections

The website is a complete single-page application with the following sections:

### 1. 🔝 Header & Navigation
- Sticky top navigation bar with the brand name **"ONLINE HOTEL MANAGEMENT SYSTEM"**
- Quick-access **"Check Availability"** button in the header
- Smooth scroll navigation links: **Home, About, Reservation, Gallery, Contact, Reviews**
- Hamburger menu icon for mobile devices

### 2. 🏠 Home / Hero Slider
- Full-screen **auto-sliding image carousel** powered by Swiper.js
- Three slides showcasing:
  - **Luxurious Rooms** → links to Check Availability
  - **Foods and Drinks** → links to Make a Reservation
  - **Luxurious Halls** → links to Contact Us
- Previous / Next navigation arrows on the slider

### 3. 📅 Availability Checker
- Booking form with the following fields:
  - **Check-in Date** (date picker)
  - **Check-out Date** (date picker)
  - **Number of Adults** (1–6)
  - **Number of Children** (0–6)
  - **Number of Rooms** (1–6)
- All fields are marked as required for form validation
- Submit button: **"Booked Successfully"**

### 4. ℹ️ About Section
- Three alternating image-and-text rows highlighting hotel highlights:
  - **Best Staff** — dedicated and professional team
  - **Best Foods** — high-quality dining experience
  - **Swimming Pool** — crystal-clear pool facilities
- Each row has a CTA button (Make a Reservation / Contact Us / Check Availability)

### 5. 🛎️ Services Section
- Six service cards displayed in a responsive grid:
  - 🍽️ **Food & Drinks**
  - 🌿 **Outdoor Dining**
  - 🌊 **Beach View**
  - 🎨 **Decorations**
  - 🏊 **Swimming Pool**
  - 🏖️ **Resort Beach**
- Each card has a custom icon image and description

### 6. 📋 Reservation Form
- Dedicated reservation section with the same booking fields as the availability checker:
  - Check-in & Check-out dates
  - Adults, Children, Rooms selection
- Submit button: **"Check Availability"**
- Form validation with required fields

### 7. 🖼️ Gallery Slider
- Swiper.js-powered **image gallery** with 6 hotel photos
- Pagination dots for easy navigation
- Smooth sliding transitions between images

### 8. 📞 Contact Section
Two-column layout:

**Left — Contact Form:**
- Name, Email, Phone Number, Message fields
- All fields have input validation and max-length limits
- Submit button: **"Send Message"**

**Right — FAQ Accordion:**
- 5 frequently asked questions with expandable answers:
  - How to cancel a booking?
  - Is there any vacancy?
  - What are the payment methods?
  - How to claim coupon codes?
  - What are the age requirements?
- First FAQ is open by default (active state)

### 9. ⭐ Reviews / Testimonials Slider
- Swiper.js carousel featuring **6 guest reviews**
- Each review card shows:
  - Guest profile picture
  - Guest name
  - Review text
- Pagination dots for navigation

### 10. 🔻 Footer
- Three-column layout:
  - **Column 1 — Contact Info:** Phone numbers, email, and address (Mumbai, India)
  - **Column 2 — Quick Links:** Home, About, Reservation, Gallery, Contact, Reviews
  - **Column 3 — Social Media:** Facebook, Twitter, Instagram, LinkedIn
- Copyright notice at the bottom

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout, animations, responsiveness |
| **JavaScript (Vanilla)** | Interactivity — FAQ accordion, mobile menu, slider config |
| **Swiper.js v8** | Image sliders (home, gallery, reviews) |
| **Font Awesome 6** | Icons throughout the website |

---

## 📁 Project Structure

```
HOTEL-BOOKING-WEBSITE/
│
├── index.html              # Main single-page HTML file (all sections)
├── style.css               # All CSS styles and responsive media queries
├── script.js               # JavaScript for sliders, accordion FAQ, mobile menu
│
├── home-img-1.jpg          # Hero slider — Luxurious Rooms
├── home-img-2.jpg          # Hero slider — Foods and Drinks
├── home-img-3.jpg          # Hero slider — Luxurious Halls
│
├── about-img-1.jpg         # About section — Best Staff
├── about-img-2.jpg         # About section — Best Foods
├── about-img-3.jpg         # About section — Swimming Pool
│
├── icon-1.png              # Service icon — Food & Drinks
├── icon-2.png              # Service icon — Outdoor Dining
├── icon-3.png              # Service icon — Beach View
├── icon-4.png              # Service icon — Decorations
├── icon-5.png              # Service icon — Swimming Pool
├── icon-6.png              # Service icon — Resort Beach
│
├── gallery-img-1.jpg       # Gallery slider images
├── gallery-img-2.webp
├── gallery-img-3.webp
├── gallery-img-4.webp
├── gallery-img-5.webp
├── gallery-img-6.webp
│
├── pic-1.png               # Review guest profile images
├── pic-2.png
│
└── README.md               # Project documentation
```

---

## 🚀 How to Run

### Option 1 — Open Directly
1. Download or clone the repository
2. Open `index.html` in any modern browser

```bash
git clone https://github.com/Preetham9638/HOTEL-BOOKING-WEBSITE.git
cd HOTEL-BOOKING-WEBSITE
open index.html   # macOS
# OR
start index.html  # Windows
```

### Option 2 — Use VS Code Live Server
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **"Open with Live Server"**
3. The site opens at `http://127.0.0.1:5500`

> ✅ No npm, no build tools, no backend needed — it's 100% frontend!

---

## 📱 Responsive Design

The website is fully responsive and adapts to all screen sizes:

| Device | Behavior |
|--------|---------|
| 🖥️ Desktop | Full layout with all columns and sliders |
| 📱 Mobile | Hamburger menu, stacked sections, touch-friendly sliders |
| 📟 Tablet | Adaptive grid — 2-column service cards, readable forms |

---

## ✨ Key Features

- ✅ Fully responsive single-page website
- ✅ Smooth scrolling between sections
- ✅ Auto-playing hero image carousel with navigation arrows
- ✅ Booking form with check-in/check-out date pickers and guest selection
- ✅ Separate reservation section for table/room booking
- ✅ Image gallery with Swiper pagination
- ✅ Expandable FAQ accordion in the contact section
- ✅ Customer reviews carousel
- ✅ Contact form with validation
- ✅ Footer with contact info, quick links, and social media
- ✅ Mobile hamburger menu

---

## 🔗 External Libraries Used

| Library | Version | CDN |
|---------|---------|-----|
| Swiper.js | v8 | `cdn.jsdelivr.net/npm/swiper@8` |
| Font Awesome | 6.2.0 | `cdnjs.cloudflare.com` |

---

## 📬 Contact Info (from the website)

- 📞 +123-456-7890 / +111-222-3333
- 📧 HotelHBT@gmail.com
- 📍 Mumbai, India — 400104

---

## 🙋‍♂️ Author

Built by **Preetham** as a frontend web development project.
Feel free to ⭐ star the repo if you found it useful!

---

## 📜 License

This project is open-source. Feel free to use, modify, and distribute it.
