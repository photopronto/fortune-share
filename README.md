# Fortune Teller share page

The page guests see when they scan the QR code on their fortune:
`https://fortune.photopronto.co.uk/v/<id>`.

GitHub Pages has no routing, so `404.html` is a copy of `index.html`: any
`/v/<id>` address is served by it, and the page reads the id from the address.
Keep the two files identical.

Data comes from the `ft-share` Supabase function. Venue branding (colours,
heading, logo, sign-up gate) is set per account in the dashboard.
