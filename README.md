Names: Eric Nguyen

1. When fitting my automated tests in my Recipie Project development pipeline I would chooose to run my tests within a github action that runs whenever code is being pushed and this is because when I push my code it would auotmatically check if the browser would run and output something because when I was working on my code, I sometimes pushed a test which would result in the page being blank which is bad in a real life scenario. It is also good using automated tests as the test could potentially catch a bug before the code is even reviewed which can allow for the developer to make the necessary changes before the code is reviewed by another person.

2. No

3. The difference between navigation and and snapshot mode is that for navigation, Lighthouse determines the if the loading metric of when the user boots up the webpage and how long it takes for the page to load. Navigation basically tracks the runtime and performance of the load of the page on the user. For snapshot mode, the use for this is not for performmance and timing but rather a snapshot of what the page is and determines the page's structure and content. 

4. Based off of the lighthouse report, 3 things that we could do to improve the CSE 110 shop site is to Preload Largest Contentful Paint image, as this could save us 100 ms according to the report. We should preload the image instead of dynamically adding the image. Another thing we can do to improve is to address the issue of Properly size images Potential savings of 914 KiB. This can be done by reducing the amount of white space for images that are unnecessary in order to better the user experience and load. Another issue is Reduce unused JavaScript Potential savings of 1,081 KiB. We can reduce the amount unused JS which can help faster load the user page so that network activity is more efficient.



