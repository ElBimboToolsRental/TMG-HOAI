# TMGHOAI Website

Final GitHub/AWS-ready static website package.

## Included

- `index.html`
- `style.css` if applicable
- `images/logo.png` using the correct official logo
- Working Google Form links for:
  - Grievance Form
  - Suggestion Form

## Form Links

Grievance Form:
https://docs.google.com/forms/d/e/1FAIpQLSdIbvGL8GOA6NEQMVIFkVygvPj40oVH7I6BjFla2YPtAX1w7g/viewform?usp=share_link&ouid=108804788074927177667

Suggestion Form:
https://docs.google.com/forms/d/e/1FAIpQLSe1yZ9ozDFpRZ_sHzhfBxRdi-vDzbKOEkxxFM-uxgalzSItEg/viewform?usp=share_link&ouid=108804788074927177667

## GitHub Pages Upload

1. Create a new GitHub repository.
2. Upload all files and folders from this ZIP.
3. Go to Settings > Pages.
4. Select Source: Deploy from a branch.
5. Select Branch: main and Folder: /root.
6. Save.

## AWS S3 Upload

1. Create an S3 bucket.
2. Upload all files and folders from this ZIP.
3. Enable Static Website Hosting.
4. Set index document as `index.html`.
5. Configure public access or use CloudFront.
