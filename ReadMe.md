# [Due](http://www.dueapp.com) Tools

## Version 2 Release Notes

* Rewritten with UI scripting
  * Search bar actions are far more reliable
  * Grouped simalar actions into contained compiled scripts
Send calendar events to Due
    * BusyCal
    * OS X Calendars
* Search Panes
  * Reminders
  * Timers
  * Logbook
* Examples of how I slice my Due reminders lists
* [OmniFocus Perspective Icons by Icons & Coffee](http://iconsandcoffee.com/perspective-icons/)

## OmniFocus

**;do**
:   Send Selected OmniFocus tasks to Due.app

## Quick Task Entry (Imitates the the iOS presets)

**;dam**
:   Quick Task – Morning (6 AM)

**;dm**
:   Quick Task – Middle Day (11:30 PM)

**;ded**
:   Quick Task – End of the Day (4 PM)

**;de**
:   Quick Task – Evening (6 PM)


NB: The times can be adjusted in the 'Run Scripts' Actions (middle column) echo statement.

## Defer Reminders

**;dd**
:   Postpone by One Day

**;dh**
:   Postpone by One Hour

**;ds**
:   Postpone by 10 Minutes


NB: These trigger the defined keyboard shortcuts (I can never remember them).

## Pomodoro Timers

**;dpl**
:   Pomodoro Long Break Timer (15 Min)

**;dps**
:   Pomodoro Short Break Timer (5 Min)

**;dpw**
:   Pomodoro Work Timer (25 Min)

### Pomodoro Timers Notes

* These actions work by searching for the names of Specific timers
* You must create timers on the Timer Panel
    * 5 Minutes Timer
    * 15 Minutes Timer
    * 25 Minutes Timer
* If you use different Timer names, adjust the 'Run Scripts' Actions (middle column) echo statement.

**;dq**
:   Create a Sequential Task

## Sequential Tasks Notes

* Formatting: `This is task one 6 am -- This is task two 5 pm`
* NB: The first task NEEDS TO BE COMPLETED ON AN iOS DEVICE.

### Create a Reminder for Calendar Events

**;dce**
:   BusyCal Event to Due (Create a Due reminder from a selected BusyCal event)

**;dcce**
:   OS X Calendar to Due (Create a Due reminder from a selected calendar event)

### Search Reminders, Timers and Logbook

**;dsr**
:   Search Reminders Panel

**;dsm**
:   Search Timers Panel

**;dsb**
:   Search Logbook Panel

**;dsu**
:   Search Reminders for URLs

## Examples of How I Slice My Due Reminders

* I shove a lot of stuff in Due–I use a defined naming convention to list the differnt reminder types
    * Any task that pops up and needs to be completed the same day
    * Deferred Toots
    * Deferred SMS
    * Consumables (Usually Triggered by Bookmarklets)
* I use a unicode Trigram as a delimiter for these types of reminders
    * Thunder - "inciting movement"
* These actions should be deleted / modified to fit your needs
* Any actions which are not triggered by bookmarklets have matching Drafts actions.

**;dt**
:   Create a Today Reminder

**;dj**
:   Create a Journal Reminder

**;dst**
:   List Today Reminders

**;dso**
:   List Deferred Toot Reminders

**;dss**
:   List Deferred SMS Reminders

**;dsr**
: List Items to Read

**;dsc**
: List Items to Check Out (Apps, Websites, Etc.)

**;dsl**
: List Items to Listen to (Random Podcasts)

**;dsw**
: List Items to Watch

**;dsj**
: List Items to Journal

### Adjust Alert Sounds

**;dan**
:   Remove Alert Sound From Reminder

**;dah**
:   Set Alert Sound for Must Do Reminder
:   Sonar (1s)

**;dah**
:   Set Alert Sound for Default
:   Coin (1s)