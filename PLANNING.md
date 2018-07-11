# TechSpeakers Hub

The TechSpeakers hub is an offline-capable progressive webapp to serve as the base of the Mozilla TechSpeakers information-infrastructure. The app is a webapp providing A2HS functionality via a PWA Web Application Manifest, and provides a tiled start-screen of various features, making them easily accessible to Mozilla TechSpeakers.

## Authentication
Initially beta-testers would receive manual credentials linked to their identities (e.g. Twitter, Telegram etc. accounts) to provide them with access to the infrastructure. Later the TechSpeakers Hub would be integrated into the Mozilla IAM infrastructure that would provide always-up-to-date access to all active TechSpeakers.

## Tiles (features):
Arranged in a grid on the homescreen of the application these icons would provide instant access to some oft-used features. The reduced friction would lead to more TechSpeakers using these features and e.g. filing requests, reports etc.

Most features should (at least on the long term) be capable of store-and-submit operation, leveraging the service worker technology provided on all modern browser platforms, including iOS/Safari. This would mean all requests could be submitted on-the-spot, regardless of connectivity, and would be synced later on when connectivity is re-established. This is important for TechSpeakers working on the field, abroad, without constant/4G connectivity or spotty wifi conditions such as conferences.

A list of proposed features

- (Re)Tweet (social amplification)
- Register upcoming CFP deadline
- File activity calendar report
- Announcements (Upcoming events/calls/briefings, CFP highlights etc.)
- Submit request:
  - Travel request,
  - CFP calendar entry*
  - Contact request/inquiry (from event)
  - New short link
  - ...
- Event Scratchpad
- FAQ
- Links

(*) see "[Register upcoming CFP deadline](#register-upcoming-cfp-deadline)" section

Almost all of the proposed features could be built in a "progressively-enhanced" manner, that is, when the base/grid of the application is built, individual features could be provided as they are being implemented, other features being hidden until the underlying code stabilizes. In addition, features themselves could be built with increasing complexibility, reducing UX/friction or administrative burden (or both); see the [Register upcoming CFP deadline](#register-upcoming-cfp-deadline) section for more information on this.


### (Re)Tweet
### Register upcoming CFP deadline
### File activity calendar report
### Announcements

- Upcoming events
- Upcoming monthly calls or meetings
- Scheduled Tech Briefings
- CFP highlights
- Event looking for speaker/volunteers/contributors etc.

### Submit request
- Travel request
- CFP calendar entry*
- Contact request/inquiry (from event)
- New short link
### Event Scratchpad

_Input_ should be links to tweets/toots about events or more epcifically links to images taken during an event/talk relevant to the Tech Speaker activity. _Input_ would only be visible in the speaker/event organizer view, from the authenticated user who submitted the links
_ScratchPad_ Any tweet/toot/image link posted via _inpput_ view will be expanded to show the relevant images of the event. This would be visible for everybody.  tweet/toot/image shoudl follow specific convention with event HashTag and scratchpad can take that to show the iamges eventwise. Everyone apart from poster should be able to see this to boost/or just for later reporting purposes.

** For now I propose this to be expanded only for teh day those images/tweets are posted. And hidden to an archive on future dates and only used later for reporting purposes.
### FAQ
### Links
