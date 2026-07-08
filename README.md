# New Sites 13:00

10 standalone local business websites for Horwich, Bolton (BL6). Each site is a completely self-contained, single-page HTML website ready for independent Vercel deployment.

## Sites

| Folder | Business | Description | Domain |
|--------|----------|-------------|--------|
| `site-1/` | JDE Plumbing & Heating | Plumber / Gas Engineer — boiler installation, servicing, repairs, bathroom fitting | |
| `site-2/` | Whitehead Electrical | Electrician — domestic & commercial rewiring, repairs, installations, testing | |
| `site-3/` | BL Joiners | Carpenter / Joiner — bespoke kitchens, wardrobes, doors, flooring, 20+ years | |
| `site-4/` | SM Garden Maintenance | Gardener / Landscaper — veteran-owned, lawn care, fencing, pressure washing | |
| `site-5/` | MV Nails Horwich | Nail Salon — acrylics, BIAB, shellac, nail art, 4.9 stars (119 reviews) | |
| `site-6/` | The Hair Shop | Hairdresser — balayage, extensions, braiding, all hair types, 5 stars | |
| `site-7/` | Nina Nails & Beauty | Nail & Beauty Salon — est. 2019, gel nails, manicures, 4.6 stars (94 reviews) | |
| `site-8/` | Horwich Barber | Barber Shop — men's cuts, fades, beard trims, 4.7 stars (107 reviews) | |
| `site-9/` | Pretty Little Pooch | Dog Groomer — full grooms, puppy grooming, run by Megan, 5 stars | |
| `site-10/` | Vanity Fur Dog Daycare & Spa | Dog Daycare & Grooming — award-winning, daycare, spa, boarding, 4.8 stars | |

## Structure

```
sites/
  site-1/          # JDE Plumbing & Heating
    index.html
    robots.txt
  site-2/          # Whitehead Electrical
    index.html
    robots.txt
  ...
  site-10/         # Vanity Fur Dog Daycare & Spa
    index.html
    robots.txt
```

Each site folder is completely independent. No shared files, imports, or links between folders. All CSS and JS are inline within `index.html`.

## Deployment

Each site is ready for Vercel deployment. To deploy a site:

1. Connect the repo to Vercel
2. Set the **Root Directory** to the site's folder (e.g. `sites/site-1`)
3. Set the domain in Vercel
4. Replace `https://REPLACE-ME.com` in the site's `index.html` and `robots.txt` with the actual domain

## SEO

Each site includes:
- Unique `<title>` and meta description
- Open Graph tags (replace `REPLACE-ME.com` with actual domain)
- Twitter Card tags
- Geo meta tags for Horwich, Bolton
- Canonical URL
- SVG favicon and Apple touch icon
- `robots.txt`

## Contact Forms

Contact forms use Web3Forms. Replace `YOUR_ACCESS_KEY_HERE` in each site's HTML with a valid [Web3Forms](https://web3forms.com/) access key.

## License

Proprietary — created for local business outreach in Horwich, Bolton.
