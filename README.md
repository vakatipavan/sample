# 🌟 Singara Chennai - Tourism Demo Website

A modern, responsive, and interactive website created for demonstrating **Chennai Tourism (Singara Chennai)**.

---

## 🚀 How to Run & Preview

### Option 1: Direct Browser Launch
Simply double-click `index.html` or right-click and choose **Open with Google Chrome / Microsoft Edge / Firefox**.

### Option 2: Local Web Server (Recommended)
You can serve it with Python or Node in this folder:

```bash
# Using Python
python -m http.server 3000

# Or using npx serve
npx serve .
```
Then visit: [http://localhost:3000](http://localhost:3000)

---

## ✨ Features Included

1. **Hero Section with Coastal Aesthetics**:
   - Live weather indicator, 385+ years heritage milestone badges, and quick stats (13km Marina beach, Margazhi festival stats).
2. **Interactive Attraction Explorer & Filters**:
   - Filter landmarks by: *All*, *Temples & Faith*, *Beaches & Coast*, *Colonial & Arts*, *Food & Bazaars*.
   - Live search bar by keyword (e.g., "Marina", "Mylapore", "Coffee").
   - Detailed modal popup with timings, entry fees, nearest Metro stations, and key highlights.
3. **Taste of Chennai (Madras Gastronomy)**:
   - Iconic South Indian Filter Kaapi (Degree Coffee).
   - Ghee Roast Dosa with 3 chutneys & drumstick sambar.
   - Marina Beach spicy sundal & fried fish.
   - Historic 1927 Kalathi Rose Milk & Bhajjis.
4. **Curated Interactive Itineraries**:
   - **⚡ 1-Day Express Tour**: Sunrise at Marina to sunset at Besant Nagar.
   - **🌊 3-Day Coastal & Heritage Odyssey**: Fort St. George, Mylapore, and coastal ECR to Mahabalipuram.
   - **🎭 Art & Music Special**: Carnatic sabhas, temple architecture, and gastronomy.
5. **Local Lingo & Audio Phrasebook**:
   - Click-to-listen pronunciation using Web Speech API for Tamil phrases (*Vanakkam*, *Nandri*, *Idhu evvalavu?*, *Romba nalla irukku*).
6. **Ambient "Sounds of Marina" Audio Player**:
   - Built with Web Audio API synthesis (gentle binaural ocean surf waves + periodic temple bell chimes) — zero broken links, works completely offline!
7. **Demo Tour Booking Modal**:
   - Interactive booking form with date picker, package selector, and simulated instant confirmation.

8. **Admin Portal & Live Content Management**:
   - **Sample Admin Email:** `admin@chennaitourism.gov.in`
   - **Sample Password:** `admin123`
   - **1-Click Auto Fill** button inside the login modal.
   - Edit, delete, or create new attractions directly with full form controls (timings, fees, metro stops, tags).
   - Inquiries Manager to review and confirm incoming tour bookings.
   - Local browser persistence (`localStorage`) preserves all changes across reloads.
