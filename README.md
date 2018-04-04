# Rating App
Building a simple rating website with AWS serverless technologies

My approach is to upload all the static contents for the website on a S3 bucket.
This would include, html pages, css and javascripts.

Since there is no need for a relational database to store the ratings, I will use a simple dynamodb to store the ratings.

Then I would look at using AWS Lambdas with APIGateway for the app's backend to push the ratings to the dynamodb and pull it from the db for users to view ratings 

## Static contents for the website
All the contents of the static-content folder gets pushed to an AWS S3 bucket that is made publicly accessible with index.html as the default root for the static website.
