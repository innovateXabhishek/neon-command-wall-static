NEON AI COMMAND WALL - STATIC DEPLOYMENT

This package is a complete static website. It needs no login, database,
Node.js server or environment variables. All logos and photographs are inside
the package.

RENDER (MANUAL GITHUB UPLOAD)
1. Extract the ZIP.
2. Create a new empty GitHub repository.
3. Upload everything inside the extracted folder to the repository root.
   The repository root must contain index.html, assets and _next.
4. In Render, choose New > Static Site and connect that GitHub repository.
5. Set:
     Branch: main
     Root Directory: leave blank
     Build Command: leave blank
     Publish Directory: .
6. Create the site. No authentication or environment variables are needed.

LOCAL TEST
Run this command inside the extracted folder:
  python3 -m http.server 8080

Then open:
  http://localhost:8080/

VPS / APACHE / NGINX
Copy the complete extracted contents to the website document root. Keep the
_next and assets directory names unchanged.

IMPORTANT
- Upload the extracted files, not the ZIP itself.
- File and folder names are case-sensitive.
- Do not move images out of assets.
