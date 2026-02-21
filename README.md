# m0o0nfox.github.io - Professional Studio Setup — Complete Technical Specification

## 📷 CAMERA: Canon EOS R5

| Parameter | Value |
|---|---|
| **Body** | Canon EOS R5 (45MP Full-Frame CMOS) |
| **Lens** | RF 85mm f/1.2L USM |
| **Aperture** | f/2.0 |
| **Shutter Speed** | 1/160s (at or below X-sync 1/200s) |
| **ISO** | 400 |
| **Format** | RAW (CR3, 14-bit lossless) |
| **White Balance** | Custom / Kelvin 5500K (matched to Profoto D2 daylight-balanced output) |
| **Picture Style** | Neutral (for RAW baseline — no in-camera processing dependency) |
| **Metering** | Manual (full manual exposure, flash-driven) |
| **AF Mode** | One-Shot AF / Eye Detection AF (RF lens IBIS off for studio tripod work) |
| **Drive Mode** | Single Shot |
| **IBIS** | OFF (tripod mounted) |
| **Color Space** | Adobe RGB (RAW capture, expanded gamut for retouching) |
| **Electronic Shutter** | OFF (mechanical shutter to prevent flash sync issues) |

---

## 📐 CAMERA POSITION & ANGLE

| Parameter | Value |
|---|---|
| **Distance from Subject** | 2.8m – 3.0m (9.2 – 9.8 ft) |
| **Shooting Height** | Eye level — lens nodal point at subject's eye line (~155–165cm from floor depending on subject height) |
| **Horizontal Angle** | 0° (dead-center, straight-on axis to subject) |
| **Vertical Angle** | Slight downward tilt ~3°–5° (flattering compression, avoids nostril-forward distortion) |
| **Tripod** | Manfrotto 055 carbon + MVHXPRO3W fluid head |
| **Focal Length Compression** | 85mm on full-frame = natural face compression, zero barrel distortion |
| **Field of View** | Head + shoulders environmental crop (approx. 60cm wide frame at 3m) |
| **Focus Point** | Near eye (camera-left eye — the dominant eye closer to main light) |
| **Depth of Field at f/2.0 / 3m** | ~5.2cm total DoF — sharp on both eyes if subject faces straight, bokeh activates on ears/backdrop |

---

## 💡 LIGHTING SETUP — FULL SPECIFICATION

### LIGHT 1 — KEY LIGHT (Main)

| Parameter | Value |
|---|---|
| **Unit** | Profoto D2 1000 Air Monolight |
| **Modifier** | Profoto XL Octa 150cm (59") Softbox |
| **Power Output** | ~500–600 Ws (approx. f/8–f/9 at 1m incident — dialed to camera f/2.0 target via distance) |
| **Effective Power at Subject** | Metered to incident f/2.0 + 0.3 EV at subject position |
| **Color Temperature** | 5,500K (daylight-balanced) |
| **Position — Horizontal** | 45° camera-left of subject centerline |
| **Position — Vertical** | Eye level (center of octa at subject eye height ~160cm from floor) |
| **Distance from Subject** | 1.4m – 1.6m (4.6–5.2 ft) — large source = ultra-soft, minimal specular harshness |
| **Light Quality** | Broad, enveloping, even illumination — wraps cheekbones, minimizes deep nasolabial fold shadows |
| **Octa Orientation** | Face-on to subject, inner diffusion panel + outer diffusion panel both active |
| **Catch Light Shape** | Octagonal, positioned at 10–11 o'clock in subject's iris |

---

### LIGHT 2 — FILL (Reflector, Passive)

| Parameter | Value |
|---|---|
| **Type** | White V-Flat (foam board folded at 120° angle) |
| **Size** | 120cm × 240cm full V-flat, one panel active |
| **Surface** | Matte white — soft, non-specular fill |
| **Position — Horizontal** | Camera-right, 60–70° from camera axis |
| **Distance from Subject** | 0.6m – 0.8m (2.0–2.6 ft) — close proximity for maximum bounce efficiency |
| **Height** | Floor to ceiling, centered at subject torso-to-head zone |
| **Shadow Ratio** | 1.2:1 (key side : fill side) — near-flat ratio, almost imperceptible shadow transition |
| **Effect** | Lifts under-eye hollows, eliminates deep nasolabial shadows, removes neck shadow |
| **Output (reflected)** | Approx. -0.3 EV below key (1.2:1 ratio = nearly equal) |

> **Ratio Note:** 1.2:1 is extremely flat — almost beauty/commercial lit. Shadow side reads only ~0.2 stops darker than key side. This is intentional for editorial skin clarity.

---

### LIGHT 3 — HAIR / RIM LIGHT

| Parameter | Value |
|---|---|
| **Unit** | Profoto A10 AirTTL (battery strobe, 76 Ws max) |
| **Modifier** | Profoto Zoom Reflector (standard silver reflector, narrow beam) |
| **Power Output** | ~1/8 to 1/4 power (approx. 10–20 Ws) — subtle, not blown-out rim |
| **Color Temperature** | 5,500K |
| **Position — Horizontal** | Behind subject, centered or slight camera-right offset ~15° |
| **Position — Vertical** | Above and behind subject — boom arm at ~210–220cm height, angled down 30°–40° |
| **Distance from Subject** | 1.0m – 1.2m (3.3–4.0 ft) |
| **Aim Point** | Top of head / crown, spilling gently onto hair outline and shoulder edges |
| **Effect** | Silver-white specular rim on hair strands — separates subject from backdrop, creates 3D depth |
| **Spill Control** | Barn doors or snoot grid (10° or 20°) to prevent flare into lens or backdrop contamination |

---

## 🎨 BACKDROP SPECIFICATION

| Parameter | Value |
|---|---|
| **Type** | Seamless paper roll, light neutral gray |
| **Color Value** | #C8C8C8 (RGB: 200, 200, 200) — approximately 18–20% luminance above mid-gray |
| **Texture** | None — flat, even, matte surface |
| **Gradient** | None — uniform exposure across full backdrop width |
| **Backdrop Illumination** | Spill from key + ambient only — NO dedicated backdrop light |
| **Backdrop Exposure** | ~1.5 – 2 stops below subject (renders as neutral mid-gray in camera, not blown white) |
| **Bokeh on Backdrop** | Slight specular softening at f/2.0 / 3m subject distance — backdrop at ~5m = ~2m behind subject, falls outside DoF, rendering as soft neutral plane |
| **Width** | Minimum 2.7m (9 ft) roll — covers full frame width at 3m camera distance |

---

## 🗺️ STUDIO FLOOR PLAN (Top View — Text Diagram)

```
                        [ HAIR LIGHT — Profoto A10 on Boom ]
                                        ↓ (angled 35° down)

        [KEY LIGHT]                  [SUBJECT]              [V-FLAT FILL]
   Profoto D2 1000W Octa        ★ facing camera          White, 0.7m away
   45° camera-left              eyes at 160cm            camera-right
   1.5m distance                                          60° from axis


                                   [CAMERA]
                              Canon EOS R5 + RF85mm
                              3.0m from subject
                              Eye-level, tripod
                              0° horizontal / -4° vertical tilt


                                  [ BACKDROP ]
                           Light Gray Seamless #C8C8C8
                           5.0m behind camera / 2.0m behind subject
```

---

## ⚡ SYNC & TRIGGERING

| Parameter | Value |
|---|---|
| **Trigger System** | Profoto Air Remote TTL-C (Canon mount, hot shoe) |
| **Sync Method** | Radio sync — Profoto Air protocol |
| **Sync Speed** | 1/160s (safe under Canon EOS R5 mechanical X-sync 1/200s) |
| **HSS** | OFF — not needed at 1/160s, avoids power loss penalty |
| **Channels** | D2 on Channel 1 / A10 hair light on Channel 2 (independent power control) |

---

## 🎯 EXPOSURE VALIDATION WORKFLOW

1. **Incident meter** (Sekonic L-858D) at subject position, dome facing camera
2. Dial D2 power until meter reads **f/2.0** (target aperture)
3. Verify fill ratio — meter from fill side → should read **f/1.6 to f/1.7** (1.2:1 = ~0.2 stop difference)
4. Hair light metered separately — target **f/1.4 to f/1.6** at rim (below key, above ambient)
5. Shoot test frame → check histogram (skin tones at 65–75% luminance, no clipping on highlights)
6. Backdrop gray value verified in Lightroom — target ~195–205 out of 255 in RGB readout
