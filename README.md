# Website designs

New REPS client websites, made by the Scaling OS dashboard when a client submits the intake form.

Each client gets:

- **Client Name - Website Page.html**, made from the intake form (branding, story, photos) in the look they picked.
- **Client Name - Pre-registration Page.html**, added when the REPS team builds the launch (offer, pricing, launch date). The Website Page is updated with the pricing at the same time.

Every file is a complete page that opens in a browser on its own: styles, fonts, animation and the sign-up forms are all inside it.

## How these are used

1. This repo is added to the **CRM - Website Designs** Claude Project, so new designs appear there after a sync.
2. Review and finish the design in the Project.
3. Commit the final page to the client's own repo, `repshealth/<client-slug>-site`, as `index.html` (and the pre-registration page as `pre-register.html`).
4. The page then appears in that client's Website section on the dashboard, for the REPS team only until it's sent to the client.

Files here are written by the dashboard. Editing them here is fine, but building the client's launch or changing their website look in the dashboard writes a fresh copy over the top.
