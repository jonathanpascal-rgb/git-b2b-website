# EHL B2B — Filename and link reference

Filename convention validated on 2 November 2026. Minimal template and its nine declinations approved on 3 November 2026.

## Active convention

All **13 site HTML files belong in one folder**. Every internal page link uses the exact sibling filename, including `.html` and its case, with no leading slash, subfolder, domain or version suffix.

Examples:

```html
<a href="EHL_B2B_Homepage.html">Home</a>
<a href="EHL_B2B_Services-Consulting.html#service-design">Service Design</a>
```

- The logo on all pages points to `EHL_B2B_Homepage.html`.
- Validated section anchors are retained after the page filename. Same-page links also include their own filename.
- The four homepage matrix blocks keep their approved popins and links to service sections. Their contextual contact action remains unchanged.
- All nine previously missing pages are now provided as minimal templates with a header, breadcrumb, page title, white space and footer. The four existing full pages remain unchanged.
- The new pages contain no service descriptions, images, case studies or forms beyond the shared header and footer logo artwork. Their substantive content remains to be developed.
- Industry subsectors link to the parent filename until content sections and their IDs are developed and approved.
- Insights, client stories, publications and sources keep their external EHL URLs.
- Group controls without a dedicated page open the existing mega menus.
- The contact CTAs on the nine new pages link to the homepage contact form.
- Preserve each filename when completing the page content; existing menu links will continue to work.

This convention replaces the earlier root-relative URLs, `index.html`, and subfolder delivery instructions. The original clean sitemap paths are retained only as reference metadata in EHL_B2B_Routes.json.

## Pages

| Page | Exact filename / href | Content status |
| --- | --- | --- |
| Homepage | `EHL_B2B_Homepage.html` | Existing full page |
| Consulting Services | `EHL_B2B_Services-Consulting.html` | Existing full page |
| Education Services | `EHL_B2B_Services-Education.html` | Existing full page |
| Hospitality Industry | `EHL_B2B_Industry-Hospitality.html` | Existing full page |
| Education Industry | `EHL_B2B_Industry-Education.html` | Minimal template page |
| Service Industries | `EHL_B2B_Industry-Service.html` | Minimal template page |
| Public Sector, Governments & NGOs | `EHL_B2B_Industry-Public.html` | Minimal template page |
| Hospitality & Service DNA | `EHL_B2B_Teams-Hospitality-Service-DNA.html` | Minimal template page |
| Custom Executive Education | `EHL_B2B_Teams-Custom-Executive-Education.html` | Minimal template page |
| Workshops & Seminars | `EHL_B2B_Teams-Workshop-Seminars.html` | Minimal template page |
| Study Tours | `EHL_B2B_Teams-Study-Tours.html` | Minimal template page |
| Our Values | `EHL_B2B_About-Values.html` | Minimal template page |
| Our Methodology | `EHL_B2B_About-Methodology.html` | Minimal template page |

## Opening and hosting

Unzip the complete archive, keep all HTML files together and open `EHL_B2B_Homepage.html`. Upload the folder contents together when hosting the prototype.

The optional Netlify `_redirects` file serves the named homepage at `/`. A small head script preserves sibling filename resolution if a host normalizes a page URL to a directory form.

The standalone `EHL_B2B_Template.html` remains the approved source template. It is not a site page and is excluded from the 13-page deployment archive.

Existing forms remain demonstrations without sending, storage or bookings. Existing team videos remain placeholders. No hosting was published by this delivery.
