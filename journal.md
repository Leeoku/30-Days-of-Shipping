#30 Days of Shipping

**Start date**: June 1 2020

**End date**: June 30 2020

## Goals

* Complete Dota Discord Bot Goals
* Contribute to Summer of Shipping Open Source Project(s)
* Learn about databases and implement into project(s)
* Create a personal site

## Day 1

* ### Project you are working on: 
     1.   A [Dota Discord Bot](https://github.com/Leeoku/DotaBot) with the goal of returning wiki links using !hero. Also create a mini profile where users can create a small profile using !myprofile
* ### Progress today: 
     1.   Minimized scope in my project by reducing the number of functions to just !hero and the components for !myprofile. 
     2.   !addhero was added today 
* ### Challenges you faced: 
     1.   I had trouble deciding on whether I wanted to keep my stored data in the JSON file or work to upload it directly to MongoDB. Even though I had some help from a different mentor, it was a pain to set up. Decided to stick with Mongo as the cloud storage database would be useful for future.
* Tasks for tomorrow
     1.   Work on !deregister and !delhero
     2.   Learn more MongoDB

## Day 2

* ### Project you are working on: 
     1.   [Dota Discord Bot](https://github.com/Leeoku/DotaBot)
     2.   [Summer of Shipping (SoS): Product Engineer for Mentor Matchmaking](https://github.com/phil-ociraptor/sos-landing)
* ### Progress today: 
     1.   Fixed bugs on !addhero
     2.   !delhero was added today (partial)
* ### Challenges you faced: 
     1.   While working on !deregister, realized I never tested specific cases for !addhero. So fixed them as I went along
     2.   Learned about string manipulation and how it was important to keep things consistent (lowercase vs titled etc). I decided to lowercase everything
          for comparisons of my data while titling all the results for profile information
     3.   In Summer of Shipping, my mentor Phil taught us about adding `remote upstream`. This was a new concept combined with `git rebase`. I had some troubles
          with this but realized after numerous tries the errors occurred because I didn't fork it initially. Now I know.
* ### Tasks for tomorrow
     1.   Work on !deregister and !delhero
     2.   Learn more MongoDB
     3.   Want to start highlighting some ideas from Phil's orientation document

## Day 3

* ### Project you are working on: 
     1.   [Dota Discord Bot](https://github.com/Leeoku/DotaBot)
     2.   [Summer of Shipping (SoS): Product Engineer for Mentor Matchmaking](https://github.com/phil-ociraptor/sos-landing)
* ### Progress today: 
     1.   Dota Discord Bot: Fixed bugs on !addhero; Completed !delhero and !deregister
     2.   SoS: Initial attempt at defininig and understanding the problem answering initial questions from mentor.
* ### Challenges you faced: 
     1.   MongoDB was more confusing than expected. The documentation is not what I'm used to and the number of resources seemed less. However some simple vids helped me through it. Need to learn to read the docs better!
     2.   Testing my DotaBot seemed to go smoothly until I asked some friends to demo it. They found way more bugs than the case scenarios I expected. Need to think more outside the box and expand testing.
     3.   Defining the problem statement for Mentorship Matchmaking was difficult. It is a complex, multi-layered problem at glance. I'll try to break down the problem more, ask mentor for more insight and definitely ask the users.
* ### Tasks for tomorrow
     1.   Polish up DotaBot for showcase tomorrow.
     2.   Learn more MongoDB
     3.   Work on the problem statement again for SoS