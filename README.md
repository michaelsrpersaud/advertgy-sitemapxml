# advertgy-sitemapxml
Generates a sitemap from node into the git repo



Initial test route:

app.get('/xmlpage', (req, res) => {
  // Ensure correct Content-Type header for XML
  res.setHeader('Content-Type', 'application/xml');
  res.send(`<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://advertiseguyana.com/listing?id=ngo-test&amp;name=NGO%20TEST%201</loc>
    <lastmod>2025-02-06T22:02:06.156Z</lastmod>
    <changefreq>daily</changefreq>
    <priority>0.5</priority>
  </url>
</urlset>`);
});


Final Route:



