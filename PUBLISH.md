# Publish MDW 2026 Personal Companion

This is a static website. Publish the whole `site/` folder.

Recommended free options:

1. Cloudflare Pages
   - Good default for this project
   - Free static hosting, custom domains, SSL and unlimited static requests/bandwidth
   - Best flow: put the `site/` folder in a GitHub repo, connect it to Cloudflare Pages

2. GitHub Pages
   - Create a GitHub repository
   - Upload the contents of `site/`
   - Enable Pages from the repository settings

3. Vercel
   - Create a new project
   - Use `site/` as the project root
   - No build command is needed

Important note:

Check-ins, reflections and uploaded photos are stored in each browser's local storage. After publishing, everyone can view the same itinerary and program list, but each person's notes stay on their own device unless you add a cloud sync layer later.

To move records between devices:

1. Use "导出记录" on the old device.
2. Send the exported JSON file to the new device.
3. Open the website on the new device and use "导入记录".

For true shared notes/photos between you and your partner, add a cloud layer later, such as Supabase, Firebase, Airtable or a private Google Sheet/Drive workflow.
