# Rating App
Building a simple rating website with AWS sreverless technologies

My approach is to upload all the static contents for the website on a S3 bucket.
This would include, html pages, css and javascripts.

Since there is no need for a relational database to store the ratings, I will use a simple dynamodb to store the ratings.

Then I would look at using AWS Lambdas with APIGateway for the app's backend to push the ratings to the dynamodb and pull it from the db for users to view ratings 