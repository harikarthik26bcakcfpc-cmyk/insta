# Instagram Clone (UI Concept)

A UI mockup set recreating the core Instagram experience — splash, stories, feed, DMs, media picker, and profile — across 9 screens.

## Screens

| # | Screen | Purpose |
|---|---|---|
| 1 | **Splash** | Instagram logo on a white background, shown on app launch. |
| 2 | **Story View** | Full-screen story playback with progress bar, poster's avatar/username, timestamp, and reply/share controls at the bottom. |
| 3 | **Story View (alt)** | Second story example — same layout, different content, showing the story viewer handles multiple posts. |
| 4 | **Feed** | Home feed with stories tray at top, scrollable posts (photo, like/comment/share/save icons, caption), and bottom tab bar. |
| 5 | **DM Inbox** | List of message threads with avatars, latest message preview, and unread indicators; search bar at top. |
| 6 | **Chat Thread** | One-on-one conversation view with message bubbles, a shared photo, and a text input bar. |
| 7 | **Chat Thread (alt)** | Another conversation example, showing a different contact and message content. |
| 8 | **Media Picker / Gallery** | Grid of camera-roll photos for selecting content to post, with a search bar above the grid. |
| 9 | **Profile Setup** | New/empty profile screen prompting the user to "Create your first post" and "Complete your profile," with bottom nav visible. |

## Flow Covered

Splash → Feed (with Stories) → tap a story → view Story → open DMs → open a Chat Thread → tap add-post → pick from Gallery → land on Profile.

## Design Notes

- Closely follows Instagram's native visual system: white/light backgrounds, black-and-white iconography, circular avatars, and the standard 5-icon bottom tab bar (Home, Search, Add, Reels/Activity, Profile).
- Stories use the familiar full-bleed vertical format with a segmented progress bar.
- Chat and inbox screens mirror Instagram Direct's bubble and thread-list styling.

## Status

Static visual mockups only — no interactivity, navigation, or backend/API integration yet.

## Suggested Next Steps

- Define navigation flow between all 9 screens (e.g. in Figma prototype or React Navigation)
- Decide on real vs. placeholder content/data source for feed, stories, and DMs
- Build out remaining core screens (search/explore, notifications/activity, settings, edit profile)
- Establish a component library (avatar, post card, message bubble, tab bar) for reuse across screens
