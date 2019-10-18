# 100 Days Of Code - Log

### Day 79 : Oct 17, 2019
Added more random stuff in my browser game. Seeing how to make it app with condova.

### Day 76-78 : Oct 14-16, 2019
Fixing bugs and add more security from csrf attacks.

### Day 73-75 : Oct 9-11, 2019
Prepering my javascript game with the final details to publish it.

### Day 73 : Oct 8, 2019
Tried to to use phpmail with sendgrid but with no result.

### Day 72 : Oct 7, 2019
Published the new update of my broswer game.

### Day 71 : Oct 4, 2019
Started a new css grid design for a new website. Light backgound, nice google fonts.

### Day 70 : Oct 3, 2019
Deployed some automated tests on circleci

### Day 69 : Oct 2, 2019
My open source project Gila CMS got its first code contribution!!

### Day 68 : Oct 1, 2019
Added new feature on my javascript game.

### Day 67 : Sep 30, 2019
My reggression tests passed so easy today. Three merges on master is not a small thing!

### Day 66 : Sep 29, 2019
Pubished a new version of gila cms and uploaded youtube videos.

### Day 65 : Sep 28, 2019
Published a new website. With impressive refections on hotfixes :p

### Day 62-64 : Sep 24-26, 2019
Made more fixes to my browser game. And update it daily by git. Continuous delivery at its best :)

### Day 61 : Sep 23, 2019
Detected some small bugs in javascript, used vuejs to create main menu for game.

### Day 60 : Sep 20, 2019
Started logging the requests on onw of my websites.

### Day 59 : Sep 19, 2019
Fixed a broken breadcrumb with css. Found that $_COOKIE saves more reliably data from $_SESSION

### Day 58: Sep 19, 2019
Created new github repository of my small game to better keep track of development.

### Day 57: Sep 18, 2019
Made redirects in php with header('Location: ..').

### Day 56: Sep 17, 2019
Finished some more regression tests.

### Day 55: Sep 16, 2019
Made automated tests with jmeter by recording them from blazemeter.

### Day 54: Sep 15, 2019
Published a turotial of how to create multisite.

### Day 50-53: Sep 10-13, 2019
Added more crsf protection for my framework.

### Day 49: Sep 9, 2019
Checked the basic steps to turn a website to pwa. New project is on the way.

### Day 46-48: Sep 4-6, 2019
Working on new ideas of the roguelike game. Trying unsuccessfully read downloaded files from the selenium webdriver.

### Day 44-45: Sep 2-3, 2019
Did not update for 2 weeks. So I'll take from here. Many improvements made with my idie game on mobile. It's getting more comfortable to work with vanilla javasript.

### Day 43: Aug 13, 2019
Searching info for docker containers. Updated some functions on dungeon generator.

### Day 42: Aug 12, 2019
Created a new blog theme for [Gila CMS](https://github.com/gilacms/gila).

### Day 39-41: Aug 7-9, 2019
Other than making a regression test, I finished a dungeon generator for my roguelike game.

### Day 38: Aug 6, 2019
Designed a multiquery api and found this nice e-book (link: http://pcgbook.com) pcgbook.com

### Day 37: Aug 5, 2019
Avoid duplicating code, you may end up with big pieces of junk. There is always a simple way to avoid that.

### Day 32-36: Jul 29 - Aug 2, 2019

Finished the third version of my coffe break roguelike [Grey Oakwoods](https://vzuburlis.itch.io/grey-oakwoods).

### Day 27-31: Jul 22-26, 2019

No luck with the falling test. Refactured an edit page for entities.

### Day 24-26: Jul 17-19, 2019

Working on a test that keep falling on python with selenium :/

### Day 23: Jul 16, 2019

Refreshed the vuejs properties and how to use them.

### Day 22: Jul 15, 2019

I had to make the frontend refresh its data only once by a response that comes every second. So I checked the state of a specific value, when it changes it will update the data
```
if (response.value1==1 && local.value1) {
  for(i in response) local[i] = response[i];
}
```

### Day 21: Jul 12, 2019

Found that CONCAT() in MySql gives null when the value from the parameters is missing. Used case to skip it.
```
CONCAT('Payment made',
case when userName is NULL then '' else CONCAT(' from ', userName) end
)
```

### Day 22: Jul 11, 2019

Refreshed some CSS. This grid will give 4 columns max in big screens:
```
grid-template-columns: repeat(auto-fit, minmax(25%, 240px));
```

### Day 21: Jul 10, 2019

Removed a bug from Gila CMS and released a new version.

### Day 20: Jul 9, 2019

Lost a lot of time trying to find why my automated test dont work.

### Day 19: Jul 8, 2019

Started a new class that will reflect a table row from the database.

### Day 18: Jul 7, 2019

Fixed a bug at Gila CMS, where a widget could not save a text with the html tags.

### Day 17: Jul 6, 2019

Visited a friend and showed me some good stuff made with 3d printer. Little coding.

### Day 16: Jul 5, 2019

Edit a list of emails from the administration and save them in json format.

### Day 15: Jul 4, 2019

**Today's Progress**: Refacture an old tool with angular and doctrine.

### Day 14: Jul 4, 2019

**Today's Progress**: Made the draft state for the block editor of Gila CMS. Data are stored in a json file until user saves them in the database or discards them.

### Day 13: Jul 2, 2019

**Today's Progress**: Published the latest update of Gila CMS 1.10.9. 

**Thoughts**: With no exceptions, must avoid all warnings cause from the code.

### Day 12: Jul 1, 2019

**Today's Progress**: Used regex for a php unit test.

### Day 11: Jun 30, 2019

**Today's Progress**: Selebrated Asteroid's day by visiting a museum. Finished a new template fo Gila CMS.

### Day 10: Jun 29, 2019

**Today's Progress**: Added the template field for pages. A feature I wanted to add for a long time, so you can choose the pages layout.

### Day 9: Jun 28, 2019

**Today's Progress**: Worked with css grid with less googling.

### Day 8: Jun 27, 2019

**Today's Progress**: Attended on a php meetup and see the views of junir and experiensed devs aboout web apis.

### Day 7: Jun 26, 2019

**Today's Progress**: Learned how a complicated html generator worked and made an update.

**Thoughts**: Never try to invent new stuff for solving problems only once, there are tools for anything!

### Day 6: Jun 25, 2019

**Today's Progress**: Updated my docker image, added new tags.

### Day 5: Jun 24, 2019

**Today's Progress**: Mostly bugfixes on my previous code.

### Day 4: Jun 23, 2019

**Today's Progress**: Check for json format and dont modify the data when is posted.

**Thoughts**: Always use hmlentities() for html print. Escape quotes for tag props (href, src, ...)

### Day 3: Jun 22, 2019

**Today's Progress**: Avoid some XSS injections in the database.

**Thoughts**: Cannot trust any data, either they come from the client or your db.

### Day 2: Jun 21, 2019

**Today's Progress**: Reduced an sql query by removing unused columns from sub SELECT.

**Thoughts**: Table views and functions don't give any speed advantage. Only useful to keep the big queries in the db.

### Day 1: Jun 20, 2019

**Today's Progress**: Use spaceship operator for first time.
```
$direction = $end<=>$start;
for($i=0; $i=$end; $i+=$direction) {
  ...
}
```
**Thoughts**: Should take advantage all the cool stuff php 7.x has to offer
