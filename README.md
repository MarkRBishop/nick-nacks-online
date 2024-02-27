# nick-nacks-online

![picture of the product's post request](https://github.com/MarkRBishop/nick-nacks-online/blob/main/Assets/nick-nack-product-post.png)

## Description 

This was a fun little project to build api based inventory system that is customizeable and easy to use. Any part of the models can be easily edited to fit a stores needs. It can be more comprehensive or less depending on the users needs. This is a just a simple mock up, with seeds to use as examples.

## Links

 video tutorial on the basic uses of the application
 https://drive.google.com/file/d/1XhlpbTb_-AWlqGsyM6r5Saq_J7xBKOTG/view

## Getting started

After you have cloned the repository, navigate to the root folder of the repository.

1. Install npm 

```
npm i
```

2. Rename the .env.example to .env and edit the user name and password information

3. Run mysql -u (your user name) -p, for example:

```
mysql -u -root -p
```

4. Enter your password when prompted

5. Run the schema.sql

```
source db/schema.sql
```

6. quit mysql by typing quit

7. Run the the seeds

```
npm run seed
```

8. finally start nodemon 
```
npm run watch
```

## Usage

Once you've got everything up and running, open an application like insomnia (the application used in the video, there are other programs available as well). Create a new HTTP Request, and set the navication to localhost:3001/api followed by whatever request you'd like to make ex: ...3001/api/products. Choose your request type, and make sure the body is set to JSON. After that follow the model structure to make your requests. 


![picture of the Categories get request](https://github.com/MarkRBishop/nick-nacks-online/blob/main/Assets/nick-nack-cat-get.png)

![picture of the tag's put request](https://github.com/MarkRBishop/nick-nacks-online/blob/main/Assets/nick-nack-tag-put.png)