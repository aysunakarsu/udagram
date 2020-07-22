### Udacity Cloud Developer Nanodegree Project 2 
# Udagram Image Filtering Application 


## Local deployment
1. npm i
2. npm run dev
3. eb init 
4. add deploy: artifact: ./www/Archive.zip to .elasticbeanstalk/config.yml
5. npm run build
6. eb create 
7. eb deploy

## Elastic Beanstalk endpoint
http://image-filter-starter-code-dev222222.us-east-1.elasticbeanstalk.com/ 

## Example
http://image-filter-starter-code-dev222222.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg
