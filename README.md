# VTaimages

This project is done as an experiment with Amazon Web Services and a reference. VTaimages web application lets user to view, comment and upload images. Developed by Valtteri Taimela in 2015. Application is accessible on `xxx`.

* Operation

Site shows all images that are uploaded to service and comments related to them. With '+' button on the upper right corner user can upload new image. Service resizes the image and adds it to database for viewing and commenting.

* Technical solutions

Application is running on AWS Elastic Beanstalk and written with node.js. Resized images are stored in Amazon Simple Storage bucket whose objects are granted accessible by anyone. The appliction itself gathers image urls on storage and metadata from database and presents them to user.