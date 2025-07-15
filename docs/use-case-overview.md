# GeekRush Use-Case Overview

## 🎯 Purpose
GeekRush is a board gaming coordination platform that streamlines scheduling, attendance tracking, and game matching across multiple gaming groups—making it easier for gamers to gather, play, and organize.

## 👤 User Roles
- **Gamer**: Default role for every user. Can RSVP to events, browse game suggestions, and view group schedules.
- **Game Master (Organizer)**: Any Gamer can create or manage groups and events. This is a dynamic role—not separate from being a Gamer.

## 📱 Mobile-First Convenience
- Available as a Progressive Web App for Android and iPhone.
- Gamers can RSVP to events and view schedules with an app-like experience.
- Push notifications alert users to new events, critical mass updates, or reminders.

## 🔗 BoardGameGeek Integration
- Syncs with BGG accounts to import game libraries and metadata.
- Uses min/max player counts, playtime, and complexity ratings to power smart suggestions.
- Suggests playable games based on RSVP counts and available collections.

## 📆 Event Coordination
- RSVP system aggregates attendance across groups and events.
- Table logic calculates game setups using player counts and game constraints.
- Notifications trigger when enough gamers RSVP to run a session.

## 🎲 Game Matching Engine
- Recommends games from users’ BGG libraries.
- Supports multiple tables per event with optimized layouts.
- Includes filters like preferred themes, duration, and complexity.

## 🛠️ Role Flexibility & Group Ownership
- Any Gamer can create groups or schedule events.
- Group owners can assign co-organizers.
- Role access is permission-based, not hard-coded.

## 🧪 Future Enhancements
- Gamification (e.g., achievements for attendance streaks or hosting sessions).
- Calendar sync (Google Calendar, iCal).
- Voting on game preferences per event.
