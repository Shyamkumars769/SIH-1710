# Smart India Hackathon Workshop
**Date:** 18-09-2026

**Register Number:** 212224040315

**Name:** Shyam Kumar.S

## Problem Title

**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

## Problem Description

Railway stations are large and complex environments containing platforms, ticket counters, restrooms, food courts, waiting areas, lifts and other facilities. Passengers, especially first-time visitors, elderly people and differently-abled passengers, may have difficulty finding these locations.

The proposed system provides an easy-to-use indoor navigation solution that helps passengers find facilities and reach their destinations quickly. It provides interactive maps, shortest-path navigation, AR-based directions, voice guidance and accessibility-friendly routes.

## Problem Creator's Organization

**Ministry of Railways**

## Idea

**SmartRail Nav** is a multi-platform indoor navigation system for railway stations.

1. **Interactive Station Map** – Provides detailed 2D/3D maps showing platforms, ticket counters, restrooms, food courts, waiting halls, lifts, exits and other facilities.
2. **Smart Destination Search** – Passengers can search for any facility or platform and get directions.
3. **Shortest-Path Navigation** – Uses the **A* algorithm** to calculate the shortest and most suitable route.
4. **AR Navigation** – Uses the mobile camera to display arrows and directions for easier navigation.
5. **Voice Guidance** – Provides voice-based instructions for visually impaired passengers.
6. **Accessibility Mode** – Provides wheelchair-friendly routes using ramps and lifts while avoiding stairs.
7. **Digital Kiosk** – Touch-screen kiosks placed inside stations allow passengers to use the navigation system without installing the mobile application.
8. **Real-Time Updates** – Station authorities can update facility locations, blocked routes and changes in the station layout.
9. **Railway Service Integration** – Can be integrated with existing railway services for platform and train-related information.

## Proposed Solution / Architecture Diagram

The system consists of a passenger-facing mobile application and digital kiosks connected to backend services. The backend manages station maps, facility locations and navigation data. A pathfinding engine calculates the shortest route, while AR, voice guidance and accessibility modules provide different navigation options.

**Architecture Flow:**

**Passenger → Mobile App / Digital Kiosk → API Layer → Map & Navigation Engine → A* Pathfinding → Navigation Output**

The system also connects to a database for station information and an admin panel for updating facility locations and station changes.

**Architecture Diagram:**

[Download / View Architecture Diagram](sandbox:/mnt/data/a_clean_infographic_diagram_on_a_white_background.png)

## Use Cases

1. **Facility Search** – Find ticket counters, restrooms, food courts, waiting halls, lifts, exits, etc.
2. **Platform Navigation** – Guide passengers from their current location to the required platform.
3. **Shortest Route** – Calculate the shortest route between two locations.
4. **AR Navigation** – Display directional arrows using the phone camera.
5. **Voice Navigation** – Provide spoken directions for visually impaired users.
6. **Accessible Route** – Find routes suitable for wheelchair users and elderly passengers.
7. **Digital Kiosk Navigation** – Provide navigation through touch-screen kiosks.
8. **Real-Time Route Update** – Recalculate routes when a path or facility becomes unavailable.
9. **Admin Management** – Allow railway authorities to update maps, facilities and routes.
10. **Multi-Facility Navigation** – Help passengers navigate through multiple destinations within the station.

## Technology Stack

| Category            | Technology                               |
| ------------------- | ---------------------------------------- |
| Mobile Application  | React Native / Android                   |
| Frontend            | React.js / React Native                  |
| AR Navigation       | ARCore                                   |
| 3D/Interactive Maps | Unity / 3D Map Engine                    |
| Backend             | Node.js / Django                         |
| Database            | Firebase Firestore / PostgreSQL          |
| Pathfinding         | A* Algorithm                             |
| Location Detection  | GPS + Mobile Sensors + QR/AR Checkpoints |
| Sensors             | Accelerometer, Gyroscope, Compass        |
| Authentication      | Firebase Authentication                  |
| APIs                | REST APIs                                |
| API Testing         | Postman                                  |
| Version Control     | Git / GitHub                             |

## Dependencies

1. **Station Map Data** – Accurate maps and layouts of railway stations.
2. **Facility Data** – Locations of platforms, ticket counters, restrooms, lifts, food courts, etc.
3. **Mapping Service** – Required for creating and displaying station maps.
4. **Backend Server** – Required for storing and processing navigation data.
5. **Database** – Stores station maps, facility locations and route information.
6. **ARCore-Compatible Device** – Required for AR-based navigation.
7. **Mobile Sensors** – Accelerometer, gyroscope and compass help with indoor positioning.
8. **Internet Connection** – Required for synchronizing real-time updates.
9. **Railway API Integration** – Required for live train/platform information if provided by railway services.
10. **Admin Access** – Required for updating station layouts and facility information.
11. **Development Tools** – Android Studio / VS Code / Unity / Git.
12. **Deployment Infrastructure** – Cloud/server infrastructure for hosting the backend and database.

## Expected Outcome

<img width="1536" height="1024" alt="b8855146-eebb-4925-978a-c6cbf9e9c30d" src="https://github.com/user-attachments/assets/bb9c8094-8298-4cd4-bb3b-717df6779509" />

The proposed system will help passengers **find railway station facilities quickly, follow the shortest route, receive real-time directions and navigate independently**. It will also improve accessibility for elderly, visually impaired and differently-abled passengers.
