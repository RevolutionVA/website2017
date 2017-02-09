# Sponsors 

Each sponsor consists of a folder in the format of company_name. Each sponsor has details data in json format, company information description in markdown, and a company logo.

```
/strickland_propane
    company_summary.md
    details.json
    logo.png
```

Logo images should be between 300x300 and 600x600 pixels.

The following properties in the details will be used.

```
{
  "title": "Strickland Propane",
  "slug": "strickland-propane",
  "url": "https://www.stricklandpropane.com/",
  "level": "Premier"
}
```

Level must be one of the following for the sponsor to appear on the site:

- Premier
- Platinum
- Gold
- Bronze
- Friends of RevConf
