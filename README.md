# Fast Hero
Frankenstein project using KMM + Rust

# Goals
- I got a warning from Google saying that they will shut down my account in the next 60 days if I don't submit an app.
- I want to try KMM _just_ for reusing the UI between Android, iOS, and Web.
- I want to use Rust _just_ for reusing business logic between Android and iOS. I mean, things like API calls saving stuff in the DB, etc.

# Milestones

:one: Setup the project so I can reuse a Composable view between Android, iOS, and Web.

:two: Implement a Rust shared library so I can query an API in both Andorid and iOS.

:three: Get the Rust shared library to persist something through a SQLite DB.


# Questions

- Image loading in Composables? How do we handle it across Android/iOS.
