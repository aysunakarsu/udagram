Udacity Cloud Engineering Nanodegree Project 2: Udagram

## Github Repository
https://github.com/aysunakarsu/udagram

## Local deployment
1. npm i
2. npm run dev
3. eb init 
4. Modify the .elasticbeanstalk/config.yml file to include deploy:
  artifact: ./www/Archive.zip
5. npm run build
6. eb create 
7. eb deploy

## EB endpoint

Dev: http://image-filter-starter-code-dev222222.us-east-1.elasticbeanstalk.com/ 

Example: http://image-filter-starter-code-dev222222.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

## Screenshots

Screenshots of the application can be found in udagram/deployment_screenshots/
