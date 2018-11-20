## Last Week's Accomplishments

I finished refactoring the user controller file. This involved mainly converting callbacks to async/await uses, but also some housekeeping. This housekeeping included tidying syntax/whitespace, simplifying some instances of logic flow, and updating deprecated built-in functions (e.g. res.json(status, obj) --> res.status(status).json(obj); expiresInMinutes --> expiresIn). I tested my changes with npm test. I opened the issue corresponding to this big refactoring and made the corresponding PRs. My changes were merged in.

My mind was mildly blown (okay, very) when I learned from Charlie that I was not in fact working with VueJS and that the async/await syntax is a feature of ECMAScript8, a specification for JS. We on the backend are working on a NodeJS application, not a frontend VueJS application. This mistake was seen in my previous status updates, as well as in my recent applications.

## This Week's Plan

Get a new issue to tackle from Charlie or Alex.

## Anything Blocking?

Other than preparing for tests, we're full steam ahead. And this week is Thanksgiving break.

## Notes

No notes.
