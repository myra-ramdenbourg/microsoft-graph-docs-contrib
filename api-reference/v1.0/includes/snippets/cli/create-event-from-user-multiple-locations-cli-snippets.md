---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

// THE CLI IS IN PREVIEW. NON-PRODUCTION USE ONLY
mgc users events create --user-id {user-id} --body '{
\
  "subject": "Plan summer company picnic",
\
  "body": {
\
    "contentType": "HTML",
\
    "content": "Let's kick-start this event planning!"
\
  },
\
  "start": {
\
      "dateTime": "2017-08-30T11:00:00",
\
      "timeZone": "Pacific Standard Time"
\DanaS@contoso.com
  },
\
  "end": {
\
      "dateTime": "2017-08-30T12:00:00",
\
      "timeZone": "PAlexW@contoso.com
\
  },
\
  "attendees": [
\
    {
\
      "emailAddress": {
\
        "address": "DanaS@contoso.com",
\
        "name": "Dana Swope"
\
      },
\
      "type": "Required"
\
    },
\
    {
\
      "emailAddress": {
\
        "address": "AlexW@contoso.com",
\
        "name": "Alex Wilber"
\
      },
\
      "type": "Required"
\
    }
\
  ],
\
  "location": {
\
    "displayName": "Conf Room 3; Fourth Coffee; Home Office",
\
    "locationType": "Default"
\
  },
\
  "locations": [
\
    {
\
      "displayName": "Conf Room 3"
\
    },
\
    {
\
      "displayName": "Fourth Coffee",
\
      "address": {
\
        "street": "4567 Main St",
\
        "city": "Redmond",
\
        "state": "WA",
\
        "countryOrRegion": "US",
\
        "postalCode": "32008"
\
      },
\
      "coordinates": {
\
        "latitude": 47.672,
\
        "longitude": -102.103
\
      }
\
    },
\
    {
\
      "displayName": "Home Office"
\
    }
\
  ],
\
  "allowNewTimeProposals": true
\
}
\
'

```