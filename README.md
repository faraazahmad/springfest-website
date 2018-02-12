# Spring Fest Jamia
The website for Spring Fest Jamia (2018). This is intended to be a single page site
with all the contents and features neatly arranged so as to generate interest.

## How to contribute
Take a look at the checklist below to know what needs to be done. To make a contribution,
only focus at one item in the checklist at a time. Create a seperate pull request for every
feature item checked off the list. In your commits and pull requests, briefly explain the changes
made so that reviewing gets easier. __*While completing each task, make sure you check that the site
looks good on various screen sizes. Make it mobile first.*__ After completing a task, make sure to fill
the checkbox correspondong to that task by adding a `x` inside the square brackets in this file.

## Tasks to complete
- [ ] Add events cards with background images
- [ ] Add previos sponsors
- [ ] Add an event timeline for each day of the fest
- [ ] Make a seperate page for contacts, team and map
- [x] Add teaser video.
- [x] Add footer with proper content and design
- [x] Replace *We're back* with a proper subtitle and add a small description below
- [x] Add a slideshow with images of the previous year's SFJ.
- [x] Add a navbar-menu to show when clicked on the hamburger menu on mobile
- [x] Add social media buttons for SFJ accounts
- suggest more by opeining an issue

## Testing the site locally on your machine
The best way is to use the npm package browser-sync. When connected to the same wifi network,
any device can open and test the webpage, so you can easily test it on your phone and laptop/pc
simultaneously.
### To use browser-sync
make sure you have nodejs installed. Then installed the `browser-sync` package globally by using
the command
```
$ npm install -g browser-sync
```

### To test your site
`cd` into the directory and run the following command
```
$ browser-sync start --server --files "*/*"
```
You can then open the site on another device using the link given in the output of the above command.
It will be something like this: `External: http://192.168.0.103:3000`
