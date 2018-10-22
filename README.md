# six-nights-of-protest
data analysis of the #BlackLivesMatter conversation in Baltimore, April 2015

# SARC 5400 Data Visualization Final
# narrative 

This is one of the most challenging projects I’ve ever worked on. I chose to deal with a lot of
data and, although I don’t regret it, it really challenged me technically.

A PSA: currently, not all of my D3 is working. I had to make a pseudo-axis (you can see the div) because I kept getting an “undefined” value in my days array and it threw the whole thing off. The clicking function stopped working when I loaded the html from a node server, I can't figure out why. 

Because I couldn't get the page to load with more than 1,000 rows of data, I used a random sample of each day's csv and concatenated them. This could potentially be interesting if I could loop through a series of random samples as part of my interactive viz--something to do in the future. 

I had to make a lot of concessions to my original vision of online/offline comparisons, but I ended up asking a more complex question at the end, which is about conversations: what conversations were people having? and who was having those conversations? Instead of just looking at a comparison, by creating a series of filters and buttons I could ask questions about who and what that aren't possible in my static visualization.

The static vis actually presented a lot of challenges for that reason— I found myself having to change the narrative I wanted in order to continue to make an effective vis within my abilities. However, I figured out how to scale tweets and protest numbers, which are not in any way proportionate (and hopefully that would be obvious) based on the percentage of the whole. I did not expect to see so many differences, so that was quite interesting.

To find protest numbers I had to dig through many, many different news sources and try to put together a “best guess” from their often vague and sometimes exaggerated numbers. I think it’s okay that they’re not exact, though, because the important thing here is percentages.

 Writing the timeline/events narrative was also a challenge. I went through a <strong>to</strong> of news sources looking for accurate and not sensationalized information. I wanted to look specifically at Baltimore-local happenings, because I think it’s interesting to see the wide range of twitter activity that’s sparked by events that happen in a single neighborhood.
 
Overall, I didn’t get my axis quite right, and I wish I had been able to select my sampled data for continuity. Because there is less continuity than I expected, I would’ve liked to have refined my question: who tweets consistently, and what conversations are they having? 

---
<h6>All event updates sourced from The Baltimore Sun; their timelines can be found <a href="http://www.baltimoresun.com/news/maryland/baltimore-city/west-baltimore/bal-freddie-gray-protests-social-photos-20150422-htmlstory.html">here</a> and <a href="http://data.baltimoresun.com/news/freddie-gray/">here.</a> All Twitter data publicly released from the 2016 Center for Media and Social Impact Report, <i>Beyond the hashtags: #Ferguson, #Blacklivesmatter, and the online struggle for offline justice.</i> Authored by Dan Freelon, Charlton D. McIlwain, and Meredith D. Clark. The <a href="http://dfreelon.org/2017/01/03/beyond-the-hashtags-twitter-data/">data</a> and <a href="http://cmsimpact.org/resource/beyond-hashtags-ferguson-blacklivesmatter-online-struggle-offline-justice/">report</a> are available freely online.</h6>

