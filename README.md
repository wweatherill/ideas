# Password best practice service :lock:
Idea inspired by article in New Scientist 2 July 2022 - [Top websites allow bad passwords](https://www.newscientist.com/article/2325880-75-per-cent-of-the-worlds-top-websites-allow-bad-passwords/)

Functional Requirements
- Measures password quality and feeds back to user
- Checks passwords against sources of breached passwords
- Allows clients to tailor strictness of the quality checker (?)

Non-Functional Requirements
- Service should be easy to integrate with
- Could use it to build a reusable web component (React maybe) that people can take and embed
- What about if the service is down, could the web component still perform some level of checking?
