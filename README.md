# Smart India Hackathon Workshop

**Date:** 26-10-2026

**Register Number:** 212224040154

**Name:** KAVIYA V M

---

## Problem Title
**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

## Problem Description

**Background:** Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections.

**Description:** The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers.

**Expected Solution:** A multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. It should include:
- A mobile application with 3D interactive maps and step-by-step navigation.
- Digital kiosks located throughout the station with touch-screen interfaces.
- Voice-guided navigation for visually impaired passengers.
- Regular updates to reflect changes in station layout and facility locations.
- Integration with existing railway apps and services for a seamless user experience.

## Problem Creator's Organization
Ministry of Railways

---

## Idea

### Functional Requirements Overview

**1. Indoor Map & Navigation**
- Interactive 2D/3D station maps showing platforms, ticket counters, restrooms, food courts, waiting rooms, lifts, escalators, and exits.
- Search for any facility, platform, or train number and get the shortest route from the user's current location.
- Step-by-step directions with estimated walking time.
- Multi-floor routing (stairs, lifts, escalators, foot-over-bridges).

**2. Accessibility Features**
- Voice-guided navigation for visually impaired passengers (text-to-speech, voice commands).
- Wheelchair-friendly routes (ramps and lifts, avoiding stairs).
- High-contrast mode and large fonts.
- Multilingual support (English, Hindi, and regional languages).

**3. Digital Kiosks**
- Touch-screen kiosks placed across the station showing the map with a "You are here" marker.
- QR code on the kiosk to continue the same route on the passenger's phone.

**4. Real-Time Updates**
- Live platform changes, train delays, and facility closures (e.g., a lift under maintenance) reflected on the map.
- Admin dashboard for station staff to update layouts, add or remove facilities, and push alerts.

**5. Railway App Integration**
- Integration with existing railway services (PNR status, live train status) to auto-suggest the platform route for the passenger's train.

### Technical Considerations

**User Experience**
- Responsive design for mobile, tablet, and kiosk screens.
- Simple, intuitive interface usable by all age groups.
- Compliance with accessibility standards (WCAG).

**Positioning**
- Indoor positioning using Wi-Fi / BLE beacons, with GPS for outdoor areas and QR-code checkpoints as a fallback.

**Security & Privacy**
- HTTPS/TLS for data transmission.
- Minimal collection of location data, with user consent and privacy controls.
- Role-based access for the admin panel.

### Phases of Arrangement

**Phase 1: Planning and Requirement Gathering**
- Collect requirements from passengers, station staff, and railway officials.
- Prepare station floor plans and a list of facilities.

**Phase 2: Design and Prototyping**
- Create wireframes for the mobile app, kiosk UI, and admin dashboard.
- Take feedback from sample users, including differently-abled passengers.

**Phase 3: Development**
- Frontend: React.js (web/kiosk) and React Native / Flutter (mobile).
- Backend: Node.js with REST APIs.
- Map and routing engine with indoor positioning.

**Phase 4: Testing**
- Unit and integration testing.
- User acceptance testing at a pilot station.
- Security testing and accuracy testing of routes.

**Phase 5: Deployment and Launch**
- Deploy backend on cloud, publish the mobile app, and install kiosks at the pilot station.
- Monitor performance and usage.

**Phase 6: Post-Launch Support**
- Bug fixes, map updates, and feature improvements based on feedback.

### Challenges and Solutions

| Challenge | Solution |
|-----------|----------|
| Accurate indoor positioning | Combine BLE beacons, Wi-Fi, and QR checkpoints |
| Keeping maps up to date | Admin dashboard with instant map and alert updates |
| Diverse passenger needs | Voice guidance, multilingual UI, accessible routes |
| Poor network inside stations | Offline map caching in the mobile app |

### Outcome and Benefits
- Reduced confusion and time spent finding facilities.
- Less congestion and fewer missed trains.
- Better accessibility for elderly and differently-abled passengers.
- Easy station management through real-time updates.

---

## Proposed Solution / Architecture Diagram

<img width="2550" height="1445" alt="image" src="https://github.com/user-attachments/assets/52b9cd3c-7aef-4ae1-88ab-d6ca034e55ca" />


## Use Cases
1. Passenger searches for a facility (restroom, food court, platform) and gets step-by-step directions.
2. Passenger enters a train number or PNR and is guided to the correct platform.
3. Visually impaired passenger uses voice commands and receives audio directions.
4. Wheelchair user gets a ramp/lift-only route.
5. Passenger scans a kiosk QR code to continue navigation on their phone.
6. Station admin updates the map or posts an alert (platform change, lift closed).

<img width="1288" height="941" alt="image" src="https://github.com/user-attachments/assets/dfc04ad5-1dd5-4667-a13e-5496d5929327" />


## Technology Stack
- React.js (web and kiosk interface)
- React Native / Flutter (mobile app)
- Node.js with Express (backend)
- PostgreSQL (database)
- Google Maps / Mapbox / Indoor map SDK
- Firebase Authentication
- Web Speech API / Text-to-Speech (voice guidance)
- BLE beacons / Wi-Fi positioning
- Git, GitHub, Postman or Insomnia

## Dependencies
- **Information collection:** 1 week
- **Number of days for development and registration:** 10 days
- **Amount arranged for management:** Fifty thousand rupees (₹50,000)
