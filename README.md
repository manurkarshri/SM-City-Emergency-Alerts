# CITY EMERGENCY ALERTS

Updated V2 build.

## Updates
- App name changed to CITY EMERGENCY ALERTS
- Tabs changed to Alerts, Controls, Sources, Map, Dial
- Larger tab/header text
- Reduced Region and Locality field height
- Emergency/Warning/Watch/Advisory dashboard remains in one line
- Larger alert viewing area
- Refresh frequency changed to 3 minutes
- Manual alerts support active duration:
  - expiresAt
  - validUntil
  - startsAt
  - durationHours

## Manual alert example
{
  "zone": "pune",
  "locality": "Kothrud",
  "title": "Heavy rain warning active for Kothrud",
  "source": "Manual Emergency Update",
  "link": "#",
  "pubDate": "2026-07-06T19:00:00+05:30",
  "priority": "high",
  "expiresAt": "2026-07-07T07:00:00+05:30"
}
