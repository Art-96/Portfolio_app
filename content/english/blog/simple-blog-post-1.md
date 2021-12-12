---
title: "Information About Schools"
date: 2021-11-10T12:48:00
image_webp: images/blog/  #blog-post-3.webp
image: images/blog/information_about_schools.png  #blog-post-3.jpg
author: Atul Kumar
description : "This is meta description"
---

In this project it was necessary to extract information about schools from the website rajshaladarpan.nic.in and save it in Excel format.

> Project Details

This project was one of the most difficult, because the site is dynamic and used ajax queries. A simple web parser is powerless, so I wrote a Selenium bot that took the input parameter of the URL page, switched to the By School / Office Selection pont. Then took turns choosing a District, a Block, and a School. from the tables that appeared, extracted all the data and saved it in an excel file.