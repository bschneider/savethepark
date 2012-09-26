savethepark
===========

Mashup of social media feeds about Patterson Park.

I'm using publically accessible information from Facebook, Twitter, and Instagram.

Facebook:
  Simple query looking for the string "Patterson" and "Park"
  
Twitter:
  Looking for "Patterson Park" OR #dontpavethepark OR geocoded from center of park 39.289095,-76.58025,1km
  
Instagram:
  I picked up the top 10 or so location ids for the park and then iterate over the list searching 1 at a time. 
  After completeing the calls, it then sorts by date to show the most recent photos.
  

Improvements/Help:
  -better querries
  -paging results of Twitter or getting more tweets to start
  -improving the speed
  -design and layout of it