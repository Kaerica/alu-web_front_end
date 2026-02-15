# Developer Tools - ALX Front-End Project

This folder contains deliverables for the **Developer tools** project (Advanced Front-End Development).

## Overview

Tasks are based on the website: **https://dev-tools.alx-tools.com/**

Use **Google Chrome** (78.0.3904.70 or later). Screenshots can be taken with the OS; they are used to show how and where you used DevTools.

## Tasks summary

| # | Task | Deliverable |
|---|------|-------------|
| 0 | Responsive device (iPhone X) | `0-responsive_device.png` |
| 1 | Change background color to #4233bd | `1-change_bg_color.png` |
| 2 | Force hover on "cake" block | `2-pathways_menu.png` |
| 3 | Copy all CSS of "Download me!" button | `3-button_styles` |
| 4 | New button colors (primary #0080ee, outline #0020aa) | `4-new_buttons.png` |
| 5 | Remove "cake" box | `5-deleted_elements.png` |
| 6 | File for h2 ABOUT margin-bottom | `6-declaration_file` |
| 7 | Number of click event references in JS | `7-number_of_listeners` |
| 8 | HSL of primary "Send" button background | `8-hsl` |
| 9 | max-width of first .container in About (1250–1440px, 100% zoom) | `9-max_width` |
| 10 | Switch About and Portfolio sections | `10-moved_around.png` |
| 11 | Bytes covered by freelancer.css | `11-coverage` |
| 12 | Print version of homepage | `12-print_version.png` |
| 13 | $0 when Avatar is selected | `13-logo_dollar0` |
| 14 | Result of console.log(document.title) | `14-doc_title` |
| 15 | Front-end framework (A/B/C/D) | `15-hbtn_framework` |
| 16 | Total page weight | `16-weight.png` |
| 17 | Number of requests | `17-requests.png` |
| 18 | Number of CSS resources | `18-css_loaded` |
| 19 | Number of image resources | `19-images_loaded` |
| 20 | Favicon type value | `20-favicon_type` |
| 21 | Font library for icons | `21-hbtn_font_lib` |
| 22 | Resource that generates 1 XHR call | `22-xhr_calls` |
| 23 | Performance audit (Lighthouse, desktop) | `23-performance_audit.png` |
| 24 | Static assets needing better cache | `24-static_assets_audit.png` |
| 25 | Accessibility contrast issue (A/B/C) | `25-contrast_issue` |
| 26 | Classes on images with no alt | `26-no_alt` |
| 27 | Missing attribute on target _blank (A/B/C/D) | `27-missing_attr` |
| 28 | Links without enough text (SEO) | `28-unclear_desc.png` |
| 29 | Snippet allcolors.js result | `29-how_many_colors.png` |
| 30 | Block CSS requests | `30-no_css.png` |
| 31 | Session storage key | `31-session_storage_key` |
| 32 | Service workers (Yes/No) | `32-service_workers` |
| 33 | SSL certificate issuer | `33-ssl_cert` |
| 34 | SSL expiration date | `34-ssl_expiration.png` |

## How to complete screenshot tasks

1. Open https://dev-tools.alx-tools.com/ in Chrome.
2. Open DevTools (F12 or Ctrl+Shift+I).
3. Follow each task description (e.g. device toolbar for task 0, override body background for task 1).
4. Save screenshots in this folder with the exact filenames above.

## How to complete text-answer tasks

- **Task 3:** In Elements, select the "Download me!" button → Styles panel → copy every applied CSS declaration, one per line, into `3-button_styles`.
- **Task 6:** Elements → select h2 "ABOUT" → Computed → find `margin-bottom` → note the file in the right panel → put that filename in `6-declaration_file`.
- **Task 7:** Sources → search in JS files for "click" (or Event Listeners in Elements) → count references → put the number in `7-number_of_listeners`.
- **Task 8:** Select "Send" button → Styles → find background-color hex → convert to HSL (e.g. via DevTools color picker) → write in format `hsl(...);` in `8-hsl`.
- **Task 9:** Resize window to 1250–1440px, zoom 100% → select first .container in About → Computed → max-width → put `max-width: <VALUE>;` in `9-max_width`.
- **Tasks 11, 18, 19, 22:** Use Coverage tab / Network tab (filter by CSS, Img, XHR) and write the requested numbers or names in the corresponding files.
- **Tasks 13–15, 20–21, 25–27, 31–33:** Use Console, Application (Storage), Security, or Audits as described in the task; write the exact answer in the corresponding file.

## Verify on the live site

These answers are based on typical Bootstrap/freelancer setups. **Check on https://dev-tools.alx-tools.com/ and update if your site differs:**

- **6-declaration_file:** In Computed for h2 "ABOUT", click the margin-bottom value to see the source file.
- **7-number_of_listeners:** Sources → search "click" in JS files, or use Event Listeners panel.
- **9-max_width:** Window width 1250–1440px, zoom 100%, then inspect first .container in About.
- **11-coverage:** Coverage tab → reload → find freelancer.css → use "Bytes" value (number only, e.g. 6144).
- **18-css_loaded / 19-images_loaded:** Network tab → filter by CSS or Img, count resources.
- **22-xhr_calls:** Network → filter XHR → identify the one that triggers 1 XHR.
- **26-no_alt:** Accessibility audit or Elements → find images without alt → note their class names (format: .class1.class2).
- **31-session_storage_key:** Application → Session Storage → key name.
- **33-ssl_cert:** Security tab → view certificate → Issuer.
