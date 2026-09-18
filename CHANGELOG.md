# TradeConnect Changelog

All notable changes made during the development of the TradeConnect
website are recorded in this document.

## [1.0.0] - Initial Development

### Project Structure

- Created the TradeConnect project folder.
- Created the main HTML files.
- Created the images folder.

### Pages Created

- Created the Home page.
- Created the Services page.
- Created the About Us page.
- Created the Our Work page.
- Created the Contact page.

### Website Features

- Added navigation between website pages.
- Added service information.
- Added relevant images.
- Added a contact form.
- Added semantic HTML5 elements.
- Added HTML comments.
- Added contact information.

### Documentation

- Created the README document.
- Created the CHANGELOG document.

---

## [1.1.0] - Homepage Styling

### Added

- Styled the Services section on the Home page as a card grid, using
  the site's `#ff7300` accent colour, with each card linked to its
  matching service image (plumbing, electrical, painting, tiling,
  carpentry, general maintenance).
- Styled the "Why Choose TradeConnect?" section as a checklist layout
  alongside the introductory text.
- Added a "Recent Projects" gallery section to the Home page,
  showcasing completed work using the project images.
- Styled the call-to-action section as a full-width highlighted band.
- Rebuilt the footer from a single copyright line into a structured
  footer with Quick Links, Our Services and Contact Us columns.

### Changed

- Corrected the "Why Choose FixRight?" heading to
  "Why Choose TradeConnect?".
- Replaced the plain, unstyled `<section>` elements on the Home page
  with the styled classes above.

---

## [1.2.0] - Services, About Us and Contact Page Development

### Added

- Created the Services page, with an alternating image/text row for
  each service (Plumbing, Electrical Services, Painting, Tiling,
  Carpentry, General Maintenance) and a closing call-to-action.
- Created the About Us page, covering the company story, mission,
  values and what makes TradeConnect different.
- Created the Contact page, with business contact details, a
  "Request a Quote" enquiry form (including a "Service Needed"
  dropdown), and a placeholder section left empty for a map embed.
- Added a shared `page_banner` section, used at the top of the
  Services, About Us and Contact pages.
- Added a `values_list` chip-style layout for the company values on
  the About Us page.

### Changed

- Applied consistent header, navigation and footer styling across the
  Services, About Us and Contact pages, matching the Home page.

---

## [1.3.0] - Responsive Design

### Added

- Added responsive breakpoints across `style.css` for tablets, mobile
  phones and other smaller devices:
  - 1024px - small laptops / large tablets.
  - 900px - tablets (portrait).
  - 768px - tablets (portrait), including a wrapping navigation bar.
  - 600px - large phones.
  - 480px - phones.
  - 360px - small / older phones.
- Added responsive scaling for the hero slogan, page banner heading
  and body text at each breakpoint.
- Added responsive stacking for the Services grid, Recent Projects
  gallery, "Why Choose Us" layout, Services page rows, and the
  Contact page's info/form layout on smaller screens.
- Added responsive column adjustments for the footer, collapsing from
  a multi-column layout down to a single column on phones.
- Added a rule so an embedded map placed
  inside `.map_placeholder` automatically fills the container at any
  screen size.
