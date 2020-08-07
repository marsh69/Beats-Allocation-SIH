# SIH Admin Dashboard 
## Beats Allocation and Tracking
In police terminology, a beat is the territory and time that a police officer patrols
### Live Demo
[See the live demo here](https://ishank-dev.github.io/Beats-Allocation-SIH/fly.html)
### Workflow
1. The police officers are assigned their zones via the admin dashboard.
2. An SMS is sent along with the place details the area is also marked on the map that needs to be patrolled. 
3. If the police officer has internet connectivity, he can get directions about how he has to navigate to a specific place.
4. The police can send live alerts that gets displayed on the same map marked as a pulsing dot to alert other police officers.
5. Zones and police are customisable and can be used by different police stations matching their unique requirements.


### Screenshots
### Interactive map to manage alert
![Maps](/screenshots/1.png?raw=true "Optional Title")
### Settings to allocate new zones and police on map
![Dashboard](/screenshots/2.png?raw=true "Optional Title")
### Beats Overview
![Allot Beats](/screenshots/3.png?raw=true "Optional Title")

## Our priorities while building this application
- Accessible by all states - Our architecture provides a customizable and flexible approach which can adapt to any state’s unique requirements
- Simplified and user-friendly UI/UX
- Resolves the diversity across Indian states - Supports over 100 languages 
- Data driven maps to display details on the map
- Decoupled architecture that can be added as a layer on top of CCTNS
- Easily extensible by NCRB developers for further development
## Authors
- Aman Bhatnagar (Backend + REST APIs)
- Ishank Sharma (Connected Django REST-APIs with MapBox + Firebase) 
- Kritika (Styled the index page components)

## TechStack
- Django Rest Framework
- Mapbox APIs
- HTML, CSS, JavaScript