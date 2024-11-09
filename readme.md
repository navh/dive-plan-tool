
# Dive Plan Tool

"Strava" but for Diving.

Goal is something agency and computer brand agnostic where people can track, share, and plan their dives.

Initially a web app. Maybe create an apple watch dive computer to try to get mapping info?

For now this document is going to contain just a bunch of notes and ideas, most of which are pipe dreams.

## Dive Club

First issue I see, there's currently no good solution (that I've found) that allows for the sort of "keep track of membership, who has paid, who has signed waivers, who has signed out equipment, who has returned equipment" sort of thing. Managing all of those individually feels like more work than doing it all in one place, there's a lot of quadruple checking things or asking students/members to fill out forms as if we've never met them before every time we try to run a dive. That said, I think part of the problem is that we're also not willing to pay for it.

In my head other clubs, for example, curling clubs, may have the same issues. Even perhaps all recreational leagues? Unsure.

## Real-Time Data Integration

Current decompression planners are pretty limited and oddly specific. I don't think technical divers want less, but I don't think recreational divers want so much. There feels like there's a canyon between "I don't bother planning at all and just keep an eye on my computer" and "I printed off a spreadsheet with a half dozen different accelerated decompression strategies".

- no apps offer real-time weather/conditions updates
- Limited integration with tide tables and current predictions
- No dynamic replanning based on conditions

- Poor underwater navigation support
- Limited 3D visualization of dive sites
- No crowd-sourced mapping of popular routes or sites (sites are so secret)
- Lack of offline functionality for remote locations

- Limited buddy tracking capabilities (sonar array maybe at least at surface? divers could wear a beacon that just screams at ultrasound, array on surface could have GPS in air and array in water and trianguate diver position to create maps? No need to tow?)
- No real-time air consumption analysis (although, GUE friends hate air integration)
- Poor integration with emergency services

## Social and Community

- Fragmented community features
- Limited ability to share routes and experiences
- No verification of dive site information
- Poor integration with training/certification systems
- No "route numbers" like rock climbing.
- Predictive (reactive?) maintenance for equipment, my garmin app allows this but it's tedious and just always wrong.
- Create virtual dive site tours for planning (sonar on ceiling could triangulate diver, combine with GPS, then broadcast location back to diver in real time, then watch could report where you are? Arrows could point to points of interest, boat? shore? enable drift-dive with dissimilar entry and exit)
- Crowd-sourced mapping of sites as many divers cover same site over and over, similar to strava heat map, get an idea of where neat things may be.

## Technical Diving

- Any gas mixtures
- rebreather-specific features
