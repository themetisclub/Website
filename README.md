# The Mētis Club website

A static site with no build step. Deploy the repo root as-is (Vercel: Framework preset "Other", no build command, output directory `.`).

SEO: the site URL is set in each page head and in robots.txt/sitemap.xml (currently the vercel.app URL). Swap it to https://themetisclub.com once the domain is connected.

Routes: `/` (home) · `/workshop` · `/pricing` · `/refund` · `/terms` · `/privacy` · `/contact`

To-dos before launch:
- Set `WHATSAPP_URL` in `index.html` and `workshop/index.html` (it's currently `#whatsapp-link-pending`).
- Confirm the FormSubmit activation email at themetisclub@gmail.com.
- Add the VSL embed inside `#vsl` in `workshop/index.html`.
