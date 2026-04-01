 Test Case 1: Page loading

Preconditions:
- Internet is available

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open browser | - | Browser opened |
| 2 | Go to page | https://www.greencity.cx.ua/#/greenCity/events | Page opened |
| 3 | Check content | - | Events list is visible |



Test Case 2: Open event details

Preconditions:
- Events page is opened

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Click on event | - | Event is clickable |
| 2 | Check result | - | Event details opened |


 Test Case 3: Filtering events

Preconditions:
- Events page is opened

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Find filter | - | Filter exists |
| 2 | Apply filter | any value | List changes |
| 3 | Check results | - | Filtered events shown |



 Negative Test: No results

Preconditions:
- Filter is applied

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Apply rare filter | - | No events |
| 2 | Check page | - | Message "No events" shown |
