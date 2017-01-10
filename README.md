# hacker-news-feed.js
hacker-news-feed.js lightweight javascript-based.

Method:
  -	hnfeed(menu, page); 
			
Parameters:
  - {String} menu.
      list ("top", "news", "comments", "show", "ask", "jobs")
  - {Integer} page.
      default (1)
      
Result:
  - {Object}
  
<h3>Sample:</h3>
<pre>var result = hnfeed('news');
console.log(JSON.stringify(result, null, 2));</pre>
