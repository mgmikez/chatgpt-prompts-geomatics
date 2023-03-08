<p align="center"><h1>🧠 ChatGPT Prompts applied to Geomatics</h1></p>

Welcome to the ChatGPT Prompts applied to Geomatics" repository! This is a collection of prompt examples to be used with the ChatGPT model for geomatics applications.

The [ChatGPT](https://chat.openai.com/chat) model is a large language model trained by [OpenAI](https://openai.com) that is capable of generating human-like text. By providing it with a prompt, it can generate responses.

In this repository, you will find a variety of prompts that can be used with ChatGPT for various geomatics applications. We encourage you to [add your own prompts](https://github.com/f/chatgpt-prompts-geomatics/edit/main/README.md) to the list, and to use ChatGPT to generate new prompts as well.

To get started, simply clone this repository and use the prompts in the README.md file as input for ChatGPT. You can also use the prompts in this file as inspiration for creating your own.

We hope you find these prompts useful and have fun using ChatGPT!

---

# Prompts

## Extract geographic information from a text and generate geographic coordinates
Contributed by: [@mgmikez](https://github.com/mgmikez)
**Example**: with the novel "Les Misérables" by Victor Hugo

### Step 1
>What are the main geographical locations in Paris in the novel "Les Miserables"?

### Step 2
>Can you generate a CSV file with this information by adding a column for latitude and longitude?

###  Result displayed with QGIS with an OSM base map
![alt text](https://github.com/mgmikez/chatgpt-prompts-geomatics/blob/main/images/miserables.jpg?raw=true)

## Create a dynamic web map with points in CSV format
Contributed by: [@mgmikez](https://github.com/mgmikez)
**Example**: with the Google Maps API

>Generate the HTML and javascript files with the Google Maps API for a CSV file

###  Result displayed on a web browser
![alt text](https://github.com/mgmikez/chatgpt-prompts-geomatics/blob/main/images/googlemaps.jpg?raw=true)
Link: [Map Example](http://igeomedia.com/~mickael/dga)

## Create a relational database with a spatial relationship 
Contributed by: [@mgmikez](https://github.com/mgmikez)
**Example**: spatial relationship with PostgreSQL/PostGIS -  municipality belongs to a county, and a county belongs to a region

### Step 1
>Create a relational database with spatial reference with the following concepts: a municipality belongs to a county, and a county belongs to a region

### Step 2
>Generate the SQL schema for postgis

### Step 3
>Give me an example of an SQL query to display all the municipalities in a region

## Generate javascript code for Google Earth Engine to display image collection
Contributed by: [@mgmikez](https://github.com/mgmikez)
**Example**: Sentinel-2 on Montreal, Canada

>Generate javascript code for Google Earth Engine to show SENTINEL-2 images on Montreal for July 2022

###  Result displayed on the Google Earth Engine Editor
![alt text](https://github.com/mgmikez/chatgpt-prompts-geomatics/blob/main/images/gee1.jpg?raw=true)

## Generate javascript code for Google Earth Engine to display DEM and Slope map
Contributed by: [@mgmikez](https://github.com/mgmikez)
**Example**: on Montreal, Canada

>Generate the javascript code of Google Earth Engine to show the digital terrain model of Montreal and the slope

###  Result displayed on the Google Earth Engine Editor
![alt text](https://github.com/mgmikez/chatgpt-prompts-geomatics/blob/main/images/gee2.jpg?raw=true)
