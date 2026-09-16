# Campus Connect

## Project Description

Campus Connect is a responsive campus event guide designed to help college
students discover activities and events happening around campus. The website
provides information about upcoming social, career, wellness, entertainment,
and student organization events.

The intended audience is college students who want an easy way to learn about
campus activities and opportunities to get involved.

## Layout Decisions

Flexbox is used for the primary navigation, hero section, related events, and
footer navigation. Flexbox was appropriate for these sections because the
content needed to be aligned horizontally while still being able to wrap or
stack when screen space becomes limited.

CSS Grid is used for the upcoming events section on the home page. The first
event spans two columns to create different card widths and emphasize the
featured event.

Grid is also used on the event details page to create a two-column layout.
The main event information uses the larger column while the event information
sidebar uses the smaller column.

## Responsive Design

The website uses two responsive breakpoints:

- 800px: The hero changes to a vertical layout, the event grid changes to one
  column, and the event details sidebar moves below the main content.
- 500px: The navigation becomes vertical, page spacing is reduced, and related
  event cards stack vertically.

The pages were tested by resizing the browser window and checking the layouts
at desktop, tablet, and mobile widths.

## Semantic HTML

Several semantic HTML elements are used throughout the website:

- `header` contains the site name, tagline, and primary navigation.
- `nav` identifies groups of navigation links.
- `main` contains the primary content of each page.
- `section` separates major areas such as upcoming events and related events.
- `article` represents individual event cards and event content.
- `aside` contains additional featured event information.
- `figure` and `figcaption` provide images with related captions.
- `footer` contains copyright, contact, and secondary navigation information.
- `time` represents event dates and times.

## Sources

All event names, organizations, locations, descriptions, and schedules were
created for this project.

Images used in this project should be credited here with the image creator,
website, and source information when required by the image license.

The website uses the Arial font family and does not use external font
libraries.