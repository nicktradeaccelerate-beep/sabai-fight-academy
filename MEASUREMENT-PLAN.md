# Sabai Retreat Measurement Plan

## Dashboard stack
- Google Search Console: organic queries, landing pages, CTR, position, indexing.
- Google Analytics 4: sessions, engaged sessions and key events.
- Google Tag Manager: deploys event tags without repeated site edits.
- GSC Wizard: blended Search Console + GA4 reporting inside ChatGPT once Google access is connected.

## Events already emitted to window.dataLayer
- measurement_ready
- contact_click
  - contact_method: whatsapp | line | phone | email | maps | instagram
  - link_url
  - link_text
- booking_intent
  - link_url
  - link_text

## GA4 key events to configure
- contact_click where contact_method = whatsapp
- contact_click where contact_method = phone
- contact_click where contact_method = line
- booking_intent

## Revenue truth
A CTA click is NOT a booking. Primary commercial reporting must ultimately join:
landing page / source -> enquiry -> confirmed booking -> package -> revenue -> repeat booking -> review.
