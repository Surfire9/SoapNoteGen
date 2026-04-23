# SoapNoteGen
### Medspa Medical Massage by Amanda — Roanoke, VA

An interactive body pain location mapper and SOAP note builder. Designed for use during massage therapy intake and documentation. Installable as an offline app on iPhone and Android.

---

## What It Does

- Tap any region on a clickable human body diagram (front and back views)
- Instantly generates relevant **ICD-10 codes** for that region
- Loads a full **SOAP note template** with interactive fields:
  - Tap colored **pills** to select from clinical options
  - Toggle **Y/N** and **+/−** findings
  - Type into measurement fields (ROM degrees, grip strength, pain scale)
- **Copy completed note** to clipboard — ready to paste into any records system
- Select multiple regions at once; all ICD-10 codes pool together

---

## How to Install on iPhone

1. Open the link in **Safari**: `https://[username].github.io/pain-mapper`
2. Tap the **Share** button (box with arrow at bottom of screen)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

The app icon appears on your home screen. It works **completely offline** after the first load.

## How to Install on Android

1. Open the link in **Chrome**
2. Tap the **three-dot menu** (top right)
3. Tap **"Add to Home Screen"** or **"Install app"**

---

## Regions Covered (27 total)

| Front View | Back View |
|---|---|
| Head / Cranium | Head / Cranium |
| Neck / Cervical | Neck / Cervical |
| L / R Shoulder | L / R Shoulder |
| Chest / Pectoral | Upper Back / Thoracic |
| Abdomen | Lower Back / Lumbar |
| L / R Hip | Sacrum / Gluteal |
| L / R Upper Arm | L / R Upper Arm |
| L / R Elbow | L / R Elbow |
| L / R Forearm | L / R Forearm |
| L / R Wrist / Hand | L / R Wrist / Hand |
| L / R Thigh | L / R Thigh |
| L / R Knee | L / R Knee |
| L / R Calf | L / R Calf |
| L / R Ankle / Foot | L / R Ankle / Foot |

---

## Technical Notes

- Single self-contained `index.html` file — no frameworks, no dependencies, no internet required after first load
- Service worker built inline for offline PWA caching
- iOS PWA meta tags included for full-screen home screen behavior
- All SOAP data and ICD-10 codes are embedded directly in the file

---

## Updating the App

To make changes (add regions, update SOAP templates, fix a code):
1. Edit `index.html` locally
2. Go to the GitHub repository
3. Click `index.html` → click the **pencil icon** to edit, or upload a new file
4. Commit the change — the live app updates within ~60 seconds

---

*Built for internal clinical use. Not a substitute for professional clinical judgment.*
