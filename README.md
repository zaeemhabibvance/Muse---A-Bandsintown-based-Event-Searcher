# Muse---A-Bandsintown-based-Event-Searcher
Muse is an AngularJS based single page webapp, that finds artists' events, using data obtained from the Bandsintown API. Please note that you have to get your own API code from Bandistown.
# Pre-requisites
This webapp utilizes CDN based angularJS, as well as JQuery. You would need a browser capable enough of running these, along with HTML5
# Design Decisions
AngularJS is perfect for creating simple single page applications like this one, which utilises minimum resources in the least amount of time, as well as gives us a lot of flexibility with it's directives. In addition to that, JQuery was used for some cosmetic bug removals. Testcases.docx describes various test cases run on the site, all of which passed. I used a minimalistic approach, without a background as to maximize the load times. The only visible load time arise due to the API's response. 
In addition to this, the whole application was made keeping in mind to minimize the use of raw JS.
# Deployment Strategy
We can deploy this app, if needed, with the AWS. For that, we will need to have access to an AWS account with S3 hosting. More details can be found here:
https://medium.com/serverlessguru/deploying-angular-to-aws-in-seconds-or-10-minutes-941faa8c0aab
# Built With
1. AngularJS 1.3.14
2. JQuery 3.4.1
3. Bandsintown API 3.0
4. HTML with CSS
# Acknowledgements
Free to use HTML/CSS objects along with the whole of stackoverflow to find answers along the way.
