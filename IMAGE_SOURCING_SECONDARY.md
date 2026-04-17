# Secondary / B-Roll Image Sourcing Report

Companion to `IMAGE_SOURCING.md`. Covers the three secondary/B-roll representative
locations sourced on 2026-04-16 for the Spruce Hollow location scouting site.

All three images were resized to ~800px long edge, JPEG quality 80, progressive,
and validated as legitimate JPEGs (magic bytes `FF D8 FF`, file size > 10KB,
decodes cleanly in PIL).

---

## 1. Rural Gas Station — Route 68

- **Local file:** `/Users/joshualand/Documents/Spruce Hollow Revisions/img/gas-station.jpg`
- **Dimensions:** 800 x 533
- **File size:** 125,942 bytes (~123 KB)
- **Subject:** "Main Street Gas" — a small rural gasoline station in Pocahontas
  County, West Virginia. Weathered signage, isolated Appalachian setting. Exactly
  the Route-68-corridor / National Pike aesthetic we need — works as a stand-in
  for the Flintstone, MD gas station without having to shoot the specific one.
- **Source (LOC):** https://www.loc.gov/item/2015634497/
- **Image URL (IIIF, 12.5% rendition):**
  https://tile.loc.gov/image-services/iiif/service:pnp:highsm:34400:34481/full/pct:12.5/0/default.jpg
- **Also on Wikimedia Commons:**
  https://commons.wikimedia.org/wiki/File:%22Main_Street_Gas%22_in_rural_Pocahontas_County,_West_Virginia,_has_all_the_accountrements_of_an_old_gasoline_station._But_the_closest_Main_Street_of_any_size_is_miles_away_LCCN2015634497.tif
- **License:** Public domain (Carol M. Highsmith's America, Library of Congress
  Prints & Photographs Division — the photographer dedicated her collection to
  the public).
- **Attribution string (use on site):**
  > Photo: Carol M. Highsmith, Library of Congress Prints and Photographs
  > Division (LC-DIG-highsm-34481). Public domain.

---

## 2. I-68 Corridor — Western Maryland (Sideling Hill)

- **Local file:** `/Users/joshualand/Documents/Spruce Hollow Revisions/img/i68-corridor.jpg`
- **Dimensions:** 800 x 533
- **File size:** 100,783 bytes (~98 KB)
- **Subject:** The iconic Sideling Hill road cut on Interstate 68 / U.S. 40
  (National Freeway) in Washington County, Maryland. Dramatic exposed
  sedimentary rock layers framing the highway through the Appalachians — the
  signature I-68 image.
- **Source page:**
  https://commons.wikimedia.org/wiki/File:Sideling_Hill_cut_MD2.jpg
- **Image URL:**
  https://upload.wikimedia.org/wikipedia/commons/c/cf/Sideling_Hill_cut_MD2.jpg
- **License:** CC BY-SA 4.0
  (https://creativecommons.org/licenses/by-sa/4.0/)
- **Attribution string (use on site):**
  > Photo: Acroterion, via Wikimedia Commons. Licensed CC BY-SA 4.0.

---

## 3. Motel 6 / Suburban Studios LaVale (representative)

- **Local file:** `/Users/joshualand/Documents/Spruce Hollow Revisions/img/motel.jpg`
- **Dimensions:** 800 x 518
- **File size:** 64,631 bytes (~63 KB)
- **Subject:** Motel 6 exterior, Claremont, California — the Motel 6 brand's
  current two-tone red/white signage and classic single-story highway motel
  strip. Not the LaVale location, but a faithful brand-accurate representative
  of the same Motel 6 architecture production would shoot.
- **Source page:**
  https://commons.wikimedia.org/wiki/File:Claremont,_California,_Motel_6_exterior.jpg
- **Image URL:**
  https://upload.wikimedia.org/wikipedia/commons/8/81/Claremont%2C_California%2C_Motel_6_exterior.jpg
- **License:** CC BY-SA 4.0
  (https://creativecommons.org/licenses/by-sa/4.0/)
- **Attribution string (use on site):**
  > Photo: Sdkb, via Wikimedia Commons. Licensed CC BY-SA 4.0.

---

## Validation Summary

| File | Size (B) | Magic OK | >10KB | Decodes | Dimensions |
|------|---------:|:--------:|:-----:|:-------:|:-----------|
| gas-station.jpg  | 125,942 | yes | yes | yes | 800 x 533 |
| i68-corridor.jpg | 100,783 | yes | yes | yes | 800 x 533 |
| motel.jpg        |  64,631 | yes | yes | yes | 800 x 518 |

## Notes for Site Integration

- Both CC BY-SA 4.0 images (Sideling Hill, Motel 6) require visible credit AND
  a same-license notice if the containing page is itself published as a
  derivative work. A simple caption line under each image ("Photo: [Artist],
  CC BY-SA 4.0") is sufficient, plus a link back to the source page.
- The gas station photo is public domain (Carol M. Highsmith donation to LOC);
  attribution is courtesy, not legally required, but keep the credit — it
  protects the integrity of the collection.
- Sideling Hill is the single most recognizable image of the I-68 corridor; if
  the site has a hero/header slot for "Western Maryland geography," this is the
  shot.
