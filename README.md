# SOMM DIGI × CMS Europe — Proposal Site

## Deploy to Vercel

1. Push this folder to GitHub
2. Import repo on vercel.com
3. No build settings needed — pure static HTML
4. Add custom domain: cms.sommdigi.wine
5. Point DNS to Vercel

## Logo
If CMS logo doesn't load from their server:
- Download logo from courtofmastersommeliers.org
- Save as `logo.png` in this folder
- In index.html replace both instances of:
  `src="https://courtofmastersommeliers.org/wp-content/uploads/2025/03/logo.png"`
  with:
  `src="./logo.png"`

## Next Steps
- Add login portal after client approval
- Build progress tracker dashboard
- Convert to React + Supabase for full client portal
