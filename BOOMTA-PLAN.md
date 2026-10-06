# BOOMTA: Project Summary and Setup Plan

## Context
- **BOOMKAST** (boomkast.com) is the main project and gets most of the investment. It runs on WordPress with Elementor.
- **BOOMTA** is the new project, with a different design and concept. It starts as a simple site, and a full store comes later.

## Decisions so far
- **Platform now:** WordPress with Elementor, the same setup as BOOMKAST, possibly on the same hosting.
- **Store later:** Shopify, once products are ready. No WooCommerce.
- **No Shopify plan yet:** the full plan is about $39 a month, not worth paying before there's anything to sell.
- **Low-cost option if needed:** Shopify Starter at $5 a month, plus about 5% per sale. It adds Buy Buttons to the WordPress site.
- **Long term:** a full Shopify store, with WordPress content moved over or linked.

## Phase 1: Starter site
| Page | Content |
|---|---|
| Home | Branding, short intro, latest articles |
| About | Bio |
| Articles | Three to five starter blog posts |
| Shop | "Coming soon" teaser with a waitlist email signup |
| Contact | Contact form and business email |

**Waitlist:** an Elementor Pro form linked to Mailchimp or Kit. The list can be imported into Shopify at launch.

**Deliverables Claude will write:**
- Bio in short, medium and long versions
- Three to five starter articles
- Brand guide: mission, tagline options, voice and tone, colors, fonts, logo direction

## Setup checklist
1. Domain for BOOMTA
2. WordPress hosting, with Elementor and Elementor Pro installed
3. Business email on the domain, for example Google Workspace, with MX, SPF, DKIM and DMARC records set in DNS
4. Waitlist form connected to an email tool
5. Claude Code connected through **Elementor MCP**:
   - In WP Admin, go to Elementor → Elementor MCP and choose Claude Code
   - Paste the prompt it generates into **Claude Code on your own computer**, not a cloud session
   - Restart Claude Code. Pages are created as drafts for you to review.
6. Optionally, a GitHub repo to store content, brand files and templates

## Phase 2: Store launch (later)
- Open a Shopify store, on the Basic plan or higher
- Choose either:
  - a full Shopify site, with blog posts moved from WordPress, or
  - Shopify at `shop.yourdomain.com`, styled to match the site
- Connect the Shopify theme to GitHub so Claude Code can make design updates for you to preview before publishing
- Optional: the Shopify AI Toolkit for Claude Code, for theme, product and store management
- Email the waitlist at launch

## Security rules
- Never paste passwords, application passwords or API keys into a chat.
- Use dedicated, limited-permission WordPress users for AI tools where possible.
- Revoke any password that was shared in a chat.

## Open questions before writing content
1. What is BOOMTA, and what will it sell?
2. Whose bio is it, the founder's or the brand's?
3. Which article topics?
4. Is there an existing logo, colors or a style you like?
5. Should it look connected to BOOMKAST, or stand on its own?
