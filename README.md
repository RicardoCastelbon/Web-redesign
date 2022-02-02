# Web-redesign

Ricardo Castelbon, Sandra Wallén, Licia Thörn, Elinor Kramming, Amanda Wrede, Nova Boman

## The project

The main purpose of the project is to remake Konstnärsnämndens website using HTML5, CSS & Sass

During the interviews at the start of this project we found that the users main pain points were that the original
page was difficult to navigate and there was too much information being displayed at once.

The design we created was made with the intention of simplifying the navigation, gathering the most important and
interesting links in one place and minimizing the amount of text displayed at once on every page.

## Work process

The project was built in 6 sprints. The first sprint included interviews.

- Sprint 1 - Design

  - Created personas from interviews
  - Created user stories
  - First rough desin sketches

- Sprint 1.2 - Design

  - Finished final design sketches in Figma

- Sprint 2 - HTML

  - Set up project in VS Code and added basic HTML Structure

- Sprint 2.2 - HTML

  - Finished all HTML and added content.
  - During this sprints retro we evaluated the working and meeting processes and decided to elect
    a meeting facilitator for every meeting and gather points to be raised before each meeting.
    We also decided to make review-pairs to simplify the GitHub process.

- Sprint 3 - Dropdown menu

  During this sprint work was devided among team members. Starting the sprint the main goal was to make
  a functiona dropdown menu, but the sprint extended to also include:

  - Adding structure for SASS - we have used the 7-1 architecture with some modifications to fit this project.
  - Created the header including navbar and the footer.
  - Worked with positioning and responsiveness.
  - Gathered assets for the project.
  - Updated paths to links

- Sprint 4 - Styling and testing

  This sprint includes final styling and testing of every page.
  The majority of styling was coded together as a group.
  During this sprint we have corrected minor issues and worked on optimzation.

## Challenges

### HTML & CSS-only nav bar

HTML validator will throw an error because the structure of the dropdown menu required us to put a div inside a label.
This has not affected the page displaying properly during cross-browser testing.

CSS validator is pointing out issues that are related to Webkit.
During cross broswer testing this did not result in any problems.

## Comments

During the project we have partly worked seperately and used Git and GitHub for version handling.
At certain points we have had team coding sessions where we have all worked together using mob programing.
These commits were made direcly in main and merged during the session.

All links that were in the original left side menu have working links to related pages.
Original pages "Om Konstnärsnämnden" and "Regeringsuppdrag" were merged because of similar content.

We integrated the right side menu into main menu and index.html clickable card navigation.

