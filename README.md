# RareCoco.wtf - Static Site

A fully static site with 6 standalone HTML pages. All CSS is inlined, no folder structure needed.

## Files

- `index.html` - Main landing page
- `series1.html` through `series5.html` - Series detail pages
- `rarecoco.jpg` - Logo image
- `favicon.ico` - Site icon
- `robots.txt` - Search engine instructions

## GitHub Pages Setup

1. Create a new repository on GitHub (e.g., `rarecoco-wtf`)
2. Upload all 9 files to the root of the repository
3. Go to Settings → Pages
4. Select the main branch as source
5. Your site will be available at `https://yourusername.github.io/rarecoco-wtf/`

## Arweave Deployment (Later)

The flat structure is perfect for Arweave:

- Upload all 9 files to Arweave
- Each file gets its own transaction ID
- Use Arweave gateways to access: `https://arweave.net/[tx-id]`
- Or use ArDrive/Arweave.app for easier upload

## Notes

- All CSS is inlined in each HTML file
- All paths are relative to root
- No external dependencies except:
  - Typekit fonts (external CDN)
  - Google Fonts (external CDN)
  - Card images (external URLs from Arweave/IPFS)
