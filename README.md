# SC-Schedules

Class schedule data for an independent class schedule finder. This project is
not affiliated with or endorsed by Sierra College.

The data is copied from Sierra College's public class search once an hour by a
scheduled job. It holds the sections, meeting times, rooms and seat counts the
public search shows. Instructor email addresses and ids are left out.

- `term-cache.json`: the current term. It changes only when a section or a seat
  count does.
- `latest.json`: when the seats were last checked, and the sha256 of
  `term-cache.json` they were checked against.

Seat counts move all the time. Banner, Sierra College's registration system,
is the only word on whether a seat is open.
