# UOCIS322 - Project 1 #

A "getting started" project for CIS 322, introduction to software engineering,
at the University of Oregon.

### What is this repository for? ###

The objectives of this mini-project are:

  * Extend a tiny web server in Python, to check understanding of
  basic web architecture
  * Use automated tests to check progress (plus manual tests for good measure)

### instructions ###
(a) If URL ends with `name.html` or `name.css`
(i.e., if `path/to/name.html` is in document path (from DOCROOT)),
send content of `name.html` or `name.css` with proper http response.
(b) If `name.html` is not in current directory Respond with 404 (not found).
(c) If a page starts with or includes one of the symbols(~ // ..), and that includes the initial forward slash that all requests have,
respond with 403 forbidden error. For example, `url=hostname:5000/..name.html`
or `/~name.html` would give 403 forbidden error.

### identifying information###
Author: Haoran Zhang, hzhang9@uoregon.edu
