# Fynder website

Static HTML/CSS/JS; compatible with GitHub Pages, no build or package install needed.

## Publish
Upload the contents of this folder to a public website repository. index.html must be at its root. Settings → Pages → Deploy from a branch → main → / (root). Save and wait for deployment. All local links work with a repository subpath.

## Downloads
No installer is included or advertised as ready. Put the actual installer in downloads/FynderSetup.exe and set available to true in release.json. For large installers, upload to GitHub Releases instead and use the real github.com release asset URL in release.json. Never add a fake executable.

## Contact delivery — activation required
The form posts to FormSubmit, a third-party email relay, addressed to traverseposting@gmail.com. After publication, submit a test message yourself and confirm the activation email sent to that inbox. Until activated, delivery is not ready. FormSubmit handles its CAPTCHA and response page. Live delivery has not been tested and no email was sent during development. Direct mailto contact is also included. Review FormSubmit terms/privacy before launch. This is a static site and contains no SMTP credentials.

## Styling
The only chromatic accent is #276653, plus white and translucent versions of the same green. Google Fonts serves DM Sans and Playfair Display italic; local Arial/Georgia fallbacks work offline. The supplied logo is in assets/fynder-logo.png. The homepage document example is illustrative, not a live search.

## Preview
Run python -m http.server 8080 from this folder, then open http://localhost:8080. Opening files directly works for content, but the release manifest requires HTTP hosting.
