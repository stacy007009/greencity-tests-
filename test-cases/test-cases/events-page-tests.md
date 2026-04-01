 Test Case 1: Page loading

Preconditions:
Internet is available

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| Open browser | - | Browser opened |
| Go to page | https://www.greencity.cx.ua/#/greenCity/events | Page opened |
| Check content | - | Events list is visible |



Test Case 2: Open event details

Preconditions:
Events page is opened

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| Click on event | - | Event is clickable |
| Check result | - | Event details opened |


 Test Case 3: Filtering events

Preconditions:
Events page is opened

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| Find filter | - | Filter exists |
| Apply filter | any value | List changes |
| Check results | - | Filtered events shown |

---



 Verify page behavior without internet

Preconditions:
Internet is turned off

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| Open browser | - | Browser opened |
| Go to page | https://www.greencity.cx.ua/#/greenCity/events | Page does not load |
| Check screen | - | Error message or no connection message displayed |


 Negative Test: No results

Preconditions:
Filter is applied

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| Apply rare filter | - | No events |
| Check page | - | Message "No events" shown |
