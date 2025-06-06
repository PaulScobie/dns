DNS Lookup Tool
A modern, single-page web application for performing DNS lookups on domain names. Enter any domain (e.g., example.com) and instantly view its DNS records in a clean, responsive interface.

Features
Modern UI: Built with Bootstrap 5 for a clean, mobile-friendly look.
Instant DNS Results: Fetches and displays A, AAAA, MX, NS, TXT, SOA, CNAME, and other DNS records.
No Backend Required: 100% static—just HTML, CSS, and JavaScript.
Free Public API: Uses the NetworkCalc DNS Tools API (no API key needed).
Error Handling: Clear messages for invalid domains or lookup failures.

Demo
Open index.html in your browser, or deploy to any static web host (GitHub Pages, Netlify, Replit, etc.).

Getting Started
Clone the repository:

bash
git clone https://github.com/yourusername/dns-lookup-tool.git
cd dns-lookup-tool
Open the app:

Double-click index.html or open it in your browser.

Usage
Enter a domain name (e.g., openai.com) in the search box.

Click Lookup.

View all available DNS records, grouped by type, in responsive tables.

Deployment
You can deploy this site to any static web host, such as:
GitHub Pages
Netlify
Vercel
Replit
base44.com ([memory])

No server or build process is required.

Customization
API Endpoint:
The app uses the free NetworkCalc DNS API by default. You can swap out the endpoint in the JavaScript for another DNS API if needed.
Styling:
Modify the Bootstrap classes or add your own CSS in the <style> section.
Limitations
The free API is suitable for personal or small project use. For commercial or high-volume needs, consider a dedicated DNS API provider.

License
MIT

Acknowledgments
NetworkCalc DNS Tools API for DNS data

Bootstrap for UI framework

Created by Paul Scobie

For questions or suggestions, open an issue or pull request.
