# BITNINE QUESTION 4: AGE VIEWER

For this question, first, I had to use `nvm` to get the right node version.  
Then after installing everything and running the app, I couldn't use it(as in the page was there, but nothing was clickable), so, we can say it wasn't user-friendly.

So, I tried to find the places that might have been causing the issue and fixed them.
One of those places where I made a change, was in the useEffect in DefaultTemplate.jsx, where I switched the isChanged from false to true.
