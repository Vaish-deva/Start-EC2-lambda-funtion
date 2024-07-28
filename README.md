This file has lambda function to start the instance when user requests with the domain URL. Instance is will be always non-active, and when use kits the URL, 
it will send to cloudwatch. The alarm will trigeer the lambda function. The lambda function is for both front end and back end. It will first start the back end and then the front end. 
