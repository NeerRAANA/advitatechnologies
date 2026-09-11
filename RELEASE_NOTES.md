# Advita Technologies Website — Release Notes

Summarized from the project git history (November 2022 – April 2025).

## [2.1.0] — 2025-04-17

Brand refresh: orange-and-black theme, company logos, and image loading fixes.

### Added
- Company logo in the site header (animated GIF, then sharper PNG artwork)
- Dedicated service icons for Custom Software, Cloud Migration, VOIP, VoLTE, IoT, and Blockchain
- Additional logo variants (header, inverted, and service-card artwork)

### Changed
- Color scheme from blue to orange and black (`#EB6F25` / `#252324`)
- Header, navigation, and button hover styles to match the new brand
- Header wordmark styling (cursive display type) and logo sizing
- Service-card image size increased for clearer branding

### Fixed
- PNG service images not loading (path and file-extension mismatches on case-sensitive hosts)
- Header logo source updated to a sharper PNG asset

---

## [2.0.0] — 2024-09-04

Full marketing-site redesign. Replaced the original single-page placeholder with a multi-section company site.

### Added
- Fixed navigation: Home, Services, Careers, Contact
- Hero / showcase section (“Innovative Software Solutions”)
- Services grid covering:
  - Custom Software Development
  - Cloud Migration
  - VOIP Solutions
  - VoLTE Integration
  - IoT Development
  - Blockchain Solutions
- Careers section with job listings (Senior Software Engineer, UX/UI Designer, DevOps Specialist) and an application form
- Contact form
- Smooth scrolling, header-on-scroll styling, and fade-in animations for service and job cards

### Changed
- New layout, Poppins typography, and a blue theme (later replaced in 2.1.0)
- Page title set to **Advita Technologies - Innovative Software Solutions**

### Removed
- Semantic UI / compiled CSS dependency and the earlier background-image-only landing page

---

## [1.1.0] — 2023-07-14

### Added
- Full-page background image (`AdvitaBackground3.jpg`)
- Custom domain **advitatechnologies.com** (GitHub Pages `CNAME`)

### Changed
- Landing-page markup and styles around the background image

---

## [1.0.0] — 2022-11-28

Initial public site.

### Added
- First Advita Technologies landing page (`index.html`)
- Logo assets (`logo.gif`, `logo.png`)
- GitHub Pages custom-domain setup (`CNAME` → advitatechnologies.com)

---

## Version map (from git)

| Version | Date       | Commits |
|---------|------------|---------|
| 2.1.0   | 2025-04-10 – 2025-04-17 | Logo files and orange/black theme; Sharp logo and color scheme; PNG loading bugfix; logo addition and minor bug fix; updated GIF and logos |
| 2.0.0   | 2024-09-04 | Full `index.html` rewrite (360+ lines added) |
| 1.1.0   | 2023-07-09 – 2023-07-14 | CNAME updates; background image and page update |
| 1.0.0   | 2022-11-28 | Initial commit and basic page |
