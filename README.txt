aulad.me — static responsive candidate website

HOW TO DEPLOY
1. Unzip the package.
2. On Apache/cPanel, upload index.html, .htaccess and the assets folder to public_html (or the document root for aulad.me).
3. Point DNS A/AAAA records to your hosting and issue a valid SSL/TLS certificate for aulad.me and www.aulad.me.
4. Apache mod_rewrite must be enabled and AllowOverride must permit .htaccess. All HTTP and www requests redirect to https://aulad.me/ (301 permanent).
5. On Nginx, use nginx-example.conf as a reference in your server configuration; it is not used in public_html. Replace root and certificate paths.
6. On Cloudflare, select SSL/TLS Full (strict) after the origin SSL is configured and optionally enable Always Use HTTPS. Avoid Flexible mode redirect loops.

OPENING POSTER + BANGLA ELECTION MESSAGE
On every page load the opening section displays the full brochure on the left and the complete Bengali election statement on the right (stacked on mobile). The brochure remains sticky beside the message while scrolling through the statement on wider screens. There is no automatic seven-second dismissal.
Use the Home navigation link or the floating “↑ পোস্টার ও বার্তা” button to return to this opening section. “Visit Website” jumps to the candidate profile below. The manifesto has eleven priority points and remains visible and readable in full on the page.

BRANDING
Browser title includes candidate name, membership and ballot number; the logo and favicon use his portrait.

NOTES
This package creates the website files; it does not register the domain, upload them to hosting, or activate SSL.
