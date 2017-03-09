# Humans 

Each human consists of a folder in the format of lastname_firstname. Each human has details data in json format , a biographical summary in markdown, and a profile image.

```
/olson_erik
    bio.md
    details.json
    profile.png
```

Profile images should be between 300x300 and 600x600 pixels.

The following properties in the details will be used.

```
{
  "title": "CEO",
  "slug": "erik-olson",
  "role": ["Organizer","Speaker"],
  "twitter": "erikpmp",
  "facebook": "erikpmp",
  "linkedin": "erikpmp",
  "personal_website": "",
  "company_website": "http:\/\/8020.co",
  "company_name": "80|20",
  "name": "Erik Olson"
}
```

A human must have at least one of the following for the human to appear on the site:

- Board Member
- Keynote Speaker
- Organizer
- Panelist
- Speaker
- Volunteer
