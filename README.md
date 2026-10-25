# Suraj Rawat — Engineering Portfolio

A personal portfolio for a student exploring Robotics, Mechatronics, Automation, and Embedded Systems.

## Stack

React 19 and TypeScript with Vinext file-based routes. Shared components and one typed content file keep the portfolio maintainable. No database, contact backend, analytics, or custom authentication was added. Sites controls access to the private preview.

## Start and edit

1. Use Node 22.13 or newer.
2. Run `npm ci` to install the locked dependencies.
3. Run `npm run dev` and open the address printed by the server.
4. Edit `content/portfolio.ts` to update your content.
5. Add approved files under `public/` and use paths beginning with `/`.
6. Run `npm run build` to prepare the site for deployment.

The managed Sites environment uses its supervised preview and build controls; the checked-in scripts also support ordinary local development.

## Pages

- Home: `/`
- About Me: `/about`
- Skills: `/skills`
- Projects: `/projects`
- Qualifications: `/qualifications`
- Contact: `/contact`
- Project details: `/projects/[slug]`
- Unknown addresses: custom 404 page

The five non-Home navigation links open new tabs, with the required security attributes and accessible explanations. Home, logo, and individual project links navigate in the current tab.

## Files

- `content/portfolio.ts` — editable portfolio data, content types, and publication state.
- `app/` — page templates, metadata, and shared styles.
- `components/site-*` and `components/portfolio-ui.tsx` — reusable portfolio interface.
- `components/ui/` — the starter component library; Sheet supplies the accessible mobile menu.
- `public/` — approved images, files, and favicon.
- `docs/EDITING-GUIDE.md` — content replacement and media instructions.
- `docs/CONTENT-CHECKLIST.md` — information still needed.
- `docs/QA.md` — checks actually performed and testing limits.

## Preview content

No portrait, project evidence, public email, social profile, CV, or certificate files were supplied for this build. Those spaces are explicitly labeled or hidden. Proposed project statuses and credential completion are not inferred. The private preview has search indexing disabled.

Keep `previewMode: true` until the content is ready for review. Setting it to false excludes unconfirmed projects, credentials, and skills. Supply real evidence before sharing the finished portfolio with reviewers.
