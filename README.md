# Maintenance App

For the tasks that are never done.

[In Praise of Maintenance](http://freakonomics.com/podcast/in-praise-of-maintenance/)

## Quick Start

- Ruby
- Rails
- SQLite3

## Vision

**Offload the mental burden of tracking the things you care about doing infrequently.**

_Not one-off tasks. Not for good intentions or habits you wish you had._

## Roadmap

_Unordered_

- Accessible everywhere
    - Web-accessible
    - Mobile-accessible
    - Offline-accessible
    - User-hosted
- Complex date logic
    - ~Calendar days~
    - ~Business days~
    - Holidays
    - Weekday
    - Monthly
    - Business day offset (e.g. last business day of the month)
    - Unusual work-weeks (not M-F)
    - Multiple criteria (two days before the last non-holiday Friday of the month)
- Activity logging
- Undo changes (bi-temporal database)
- Adaptive schedule (log 5,000 mile oil changes and set the due date based on history)
- Notes integration (so that instructions or lessons-learned can be associated with the chore)
- Calendar integration (see due dates on your calendar)
- Task checklists for a chore
- Shared and team chores

**Hypothesis:** This should be a one-page JavaScript app that stores data in Dropbox.
