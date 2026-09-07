---
EMAIL ROUTING SETUP:
1. Cloudflare Dashboard > AllOn4DentalImplantsMiami.com > Email > Email Routing > Enable
2. Add Route: Custom Address = hello, Destination = hello@materare.com, Save
3. Cloudflare auto-adds MX records: mx1.cloud... etc
4. Test: Send from personal email to hello@AllOn4DentalImplantsMiami.com - should arrive in hello@materare.com inbox in 60 seconds
5. Gmail Send As: Gmail > Settings > Accounts and Import > Send mail as > Add hello@AllOn4DentalImplantsMiami.com > Verify via code that arrives in materare inbox via forward.
6. For Reply-As: Instruct in README to set Gmail Send As: hello@AllOn4... verified via forward to materare.
7. Forms use FORM_ACTION="https://formsubmit.co/hello@materare.com" which sends to central inbox while displaying hello@AllOn4DentalImplantsMiami.com to user.
8. Footer HTML comment: <!-- Email Routing: Set Cloudflare Email Routing: hello@AllOn4DentalImplantsMiami.com -> hello@materare.com -->

LEAD GEN MODEL: One All-on-4 patient = $20k-$45k to dentist, charge $75-$150 per lead.
DESIGN: Blue #0D47A1, teal #00ACC1, Inter, premium.
---
