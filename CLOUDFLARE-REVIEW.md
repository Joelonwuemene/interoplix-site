# Interoplix Cloudflare review

Review branch: interoplix-cloudflare-review

Use framework None, build command `exit 0`, output directory `dist`, root directory blank, no environment variables. Select this review branch for the temporary Cloudflare deployment. Do not attach the custom domain or change nameservers until approval.

The dist folder contains the revised dark-design homepage, Technical resources page and original dark logo. Existing root files are preserved. Only dist should be served by Cloudflare. The noindex header discourages indexing; it does not make a deployment private. Remove that header only when approved for public launch.

Verified in this preparation: required five content revisions, local links/anchors/assets, JavaScript syntax, desktop rendering, interactive scenario tab and Technical resources return navigation. Mobile was checked during the prior content revision; not rerun during this transfer. Booking/email delivery not tested. No DNS or live branch changes.

Items for owner review before launch: 7+ years/30+ projects/17 countries and certification currency; whether public email should remain joel@interoplix.com or change to contact@interoplix.com; missing privacy notice. Prior review found Calendly /30min displaying 20-minute duration; reconfirm in Calendly. LinkedIn automated destination verification was restricted. No repository changes were made to azure-fhir-pipeline.
