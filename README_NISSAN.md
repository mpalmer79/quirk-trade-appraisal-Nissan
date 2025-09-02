
# Quirk Nissan Trade Appraisal (Clone of Quirk Ford)

This is a direct clone of the Quirk Ford trade tool, with branding and links adjusted to **Quirk Nissan**.

## What was changed
- Textual branding: "Quirk Ford" → "Quirk Nissan"
- Common uppercase and camel-case variants updated
- Links updated:
  - quirkfordtrade.netlify.app → quirknissantrade.netlify.app (configure this in Netlify)
  - www.quirkford.com → www.quirknissan.com
- Kept the exact structure so you can push to a **new GitHub repo** and deploy to Netlify.

## What you still need to do
1. **Logos/Images**: Replace Ford-branded assets with Nissan-branded ones.
   - Files that referenced possible Ford assets (check & swap):
   - No obvious Ford logo references found in text files.

2. **Environment variables** (if used): copy any `.env` from Ford and update as needed (VIN, email endpoints, etc.).
3. **Netlify**: Create a new site (e.g. `quirknissantrade.netlify.app`) and set the build settings identical to the Ford project.
4. **Dealer links**: Confirm any "Back to dealer" buttons go to `https://www.quirknissan.com` (already rewritten).
5. **Form names**: If you're using Netlify Forms, consider renaming form identifiers to avoid cross-site collisions.

## Quick start
```bash
# Optional: serve locally (if it's static)
npx serve

# Or if a build step exists (check package.json)
npm i
npm run dev
# or
npm run build && npm run preview
```
