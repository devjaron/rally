# Rally ⛳ 

**Rally** is a social mobile app designed to eliminate the hassle of finding playing partners. It connects golfers by allowing them to post open tee times and instantly find matches based on **skill level**, **play style**, and **location**.

> *"Don't wait for your foursome. Rally up."*

## 🚀 Core Features (MVP)

- **Map View:** Visualize nearby golf courses using Apple Maps (iOS)
- **Geo Search:** Find courses by GPS location or zip-code. 
**Radius Filtering:** Filter courses within 10, 25, or 50 miles of your current location.


### For Hosts
- **Post Tee Times:** Quickly share course, date, time, and open spots.
- **Set Preferences:** Define the vibe of your round:
  - 😎 **Casual:** Just for fun, no pressure.
  - 🤝 **Social:** Meet new people, relaxed pace.
  - 🏆 **Competitive:** Match play or stroke play, serious golf.
- **Profile Management:** Update your handicap, home courses, and stats.

### For Players
- **Smart Feed:** Browse upcoming tee times near you, filtered by distance and availability.
- **One-Tap Requests:** Send a join request to a host with a single tap.
- **Handicap Matching:** Ensure you’re playing with golfers at a similar skill level.
- **Real-Time Updates:** See slot availability update in real-time as others join.

## Tech Stack

- **Frontend:** React Native (Expo)
- **Backend:** Supabase (PostgreSQL, Auth, Realtime)
- **Database:** PostgreSQL with PostGIS (for geospatial queries)
- **Mapping:** MapKit (iOS) / React Native Maps / Zipcode (OpenStreetMap Nominatim API) / Expo Location (Device GPS)
- **State Management:** React Query / Supabase Client

## Current Status: MVP
- **Work in Progress:** Rally is current in its Minimum Viable Product phase.
- **✅ Live:** Core mapping, location services, tee time posting, and real-time sync.
- **🚧 In Progress:** Payment processing, advanced handicap stats, user verification, and profile editing.
- **📅 Roadmap:** To be determined. 