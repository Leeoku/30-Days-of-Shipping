#30 Days of Shipping

**Start date**: June 1 2020

**End date**: June 30 2020

## Goals

* Complete Dota Discord Bot Goals
* Contribute to Summer of Shipping Open Source Project(s)
* Learn about databases and implement into project(s)
* Create a personal site

## Day 1

* Project you are working on: https://github.com/Leeoku/DotaBot
     1.   A Dota Discord Bot with the goal of returning wiki links using !hero. Also create a mini profile where users can create a small profile using !myprofile
* Progress today: 
     1.   Minimized scope in my project by reducing the number of functions to just !hero and the components for !myprofile. 
     2.   !addhero was added today 
* Challenges you faced: 
     1.   I had trouble deciding on whether I wanted to keep my stored data in the JSON file or work to upload it directly to MongoDB. Even though I had some help from a different mentor, it was a pain to set up. Decided to stick with Mongo as the cloud storage database would be useful for future.
* Tasks for tomorrow
     1.   Work on !deregister and !delhero
     2.   Learn more MongoDB

## Day 2

* Project you are working on: 
     1.   Continuing on Dota Discord Bot https://github.com/Leeoku/DotaBot
     2.   Getting started with Summer of Shipping Showcase team, I'm Product Engineer for Mentor Matchmaking
* Progress today: 
     1.   Fixed bugs on !addhero
     2.   !delhero was added today (partial)
* Challenges you faced: 
     1.   While working on !deregister, realized I never tested specific cases for !addhero. So fixed them as I went along
     2.   Learned about string manipulation and how it was important to keep things consistent (lowercase vs titled etc). I decided to lowercase everything
          for comparisons of my data while titling all the results for profile information
     3.   In Summer of Shipping, my mentor Phil taught us about adding `remote upstream`. This was a new concept combined with `git rebase`. I had some troubles
          with this but realized after numerous tries the errors occurred because I didn't fork it initially. Now I know.
* Tasks for tomorrow
     1.   Work on !deregister and !delhero
     2.   Learn more MongoDB
     3.   Want to start highlighting some ideas from Phil's orientation document