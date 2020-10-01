# Humans 

Each human consists of a folder in the format of lastname_firstname. Each human has details data in json format , a biographical summary in markdown, and a profile image.

```
/olson_erik
    bio.md
    details.json
    profile.png
```

Profile images should be between 300x300 and 600x600 pixels.

The following properties in the details should be used.

```
{
  "title": "CEO",
  "slug": "erik-olson",
  "role": ["Organizer","Volunteer"],
  "twitter": "erikpmp",
  "facebook": "erikpmp",
  "linkedin": "erikpmp",
  "personalWebsite": "",
  "companyWebsite": "https:\/\/thisisarray.com",
  "companyName": "Array Digital",
  "firstName": "Erik",
  "lastName": "Olson",
  "interview": "youtubeVideoId"
}
```

A human must have at least one of the following requirement for the human to appear on the site:

- Board Member
- Keynote Speaker
- Organizer
- Panelist
- Speaker
- Volunteer
