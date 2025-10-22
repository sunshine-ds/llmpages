# GitHub Pages Files — Ready to Publish

A single-file web application that generates a small project suitable for publishing on GitHub Pages. The app produces the following files and helps you download them individually or as a ZIP ready to commit and publish:

- ashravan.txt — a short (300–400 word) original story inspired by Brandon Sanderson (disclaimer included)
- dilemma.json — ethical decision cases for an autonomous vehicle
- about.md — three-word description
- pelican.svg — an SVG illustration of a pelican riding a bicycle
- restaurant.json — a recommended restaurant in Bangalore with coordinates
- prediction.json — a prediction for the Fed Funds rate by December 2025
- index.html — this homepage (included in the ZIP)
- LICENSE — MIT license text
- uid.txt — optionally include your own uid.txt unchanged (upload in the UI)

Features

- Responsive, modern UI built with Tailwind CSS (CDN)
- All JavaScript is inline; no external JS libraries required
- Preview, copy, and download each file individually
- "Download All (ZIP)" packages all generated files into a ZIP (store/no compression) for easy repository creation
- Helpful instructions for publishing the generated files on GitHub Pages

Usage

1. Open index.html in a modern browser (Chrome, Firefox, Edge, Safari).
2. Inspect files using the Preview panel. Click a filename on the left to preview it.
3. If you have a uid.txt file to include unchanged, click "Upload" and choose your uid.txt.
4. Download files individually with the "Download" buttons or use "Download All (ZIP)" to get a single archive ready to add to a GitHub repo.
5. Create a new public GitHub repository, add the files, commit and push.
6. In the repository settings -> Pages, enable publishing from the main branch (root). After a minute or two your site will be available at: `https://<username>.github.io/<repo>/`.

Notes

- The short story file includes a brief disclaimer as required when producing an original work capturing high-level characteristics of a living author's style.
- The app includes a minimal-built ZIP writer (store-only) to avoid external dependencies. Files are not compressed to keep the implementation compact and robust.
- The ethical cases and financial prediction are illustrative and should not be used as professional advice.

License

This project is released under the MIT License — see the included LICENSE file.
