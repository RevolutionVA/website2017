# Talks 

Each talk consists of a folder in the format of talk slug. Each talk has details data in json format and a description in markdown.

```
/building-a-motion-activated-snapshot-feed
    description.md
    details.json
```

The following properties in the details will be used.

```
{
  "title": "Building Motion Detecting Web Apps with JavaScript",
  "slug": "building-a-motion-activated-snapshot-feed",
  "speaker": "lastName_firstName",
  "summary": "What do my pets do when no one is around? I decided to find out. My session will cover how (and then some).",
  "tags": ["javascript","motion detection"]
}
```
The slug must be all lowercase alphanumeric characters or dashes equal to the folder name.

The speaker must be the folder name of an existing human.

The summary must be a string without html maximum 140 characters.
