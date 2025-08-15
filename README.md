# 🚂 Railway Cloud Kitchen – Online Ordering Website

A mobile-friendly, easy-to-edit restaurant ordering website designed for railway food delivery services.  
Supports **Veg/Non-Veg categories, Add-to-Cart, Checkout, UPI & COD payments, WhatsApp orders**, and is optimized for stations between **Solapur – Pune** (Solapur, Wadi, Tandur, Nalwar).

---

## 📌 Features
- **Homepage** with:
  - Brand logo & name
  - Special offers (e.g., first-day discount)
  - Highlights of menu categories
  - **Popular Picks** quick add-to-cart section
- **Menu Page** with:
  - Categories (Veg Thali, Non-Veg Thali, Snacks, Tea/Coffee, etc.)
  - Editable dish images & descriptions
  - Veg/Non-Veg icon support
- **Cart System**
  - Mobile-friendly fixed cart
  - Add/remove items, update quantity
- **Order Form**
  - Fields: Train No., Coach/Seat, Station (Solapur, Wadi, Tandur, Nalwar)
  - Contact info (name, WhatsApp)
- **Payment Options**
  - UPI QR code & payment link
  - Cash on Delivery
  - Razorpay demo button (placeholder with instructions)
- **Quick WhatsApp Order**
  - Prefills order details and opens WhatsApp with one click
- **Responsive Design**
  - Works on mobile, tablet, and desktop
  - Easy-to-edit colors & menu

---

## 🖼 Editing Images
Dish images are defined in the `ITEMS` array in `script.js`:
```javascript
{
  id: "veg-thali",
  title: "Veg Thali",
  price: 129,
  cat: "veg",
  img: "images/veg-thali.png",
  desc: "Fresh homestyle veg thali with dal, sabzi & rice."
}
