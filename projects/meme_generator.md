---
layout: project
type: project
image: img/meme_generator/display_page.png
title: "Meme Generator"
date: 2021
published: true
labels:
  - Python
  - PyQt5
  - Request
summary: "This program gets images links from a subchannel called r/Meme in a social media site called Reddit then display them in the display page. "
---

This program was created to help myself better understand about API and the python library called "Requests", as well as a practical programming experience. This project also helped me understand about dynamic and static pagination and the solution to them.  


<div class="text-center flex p-4">
  <img width="300px" src="../img/meme_generator/display_page.png" >
  <img width="300px" src="../img/meme_generator/setting_page.png" >
</div>

# Imports
* random
* requests
* json
* urllib
* PyQt5
* time

  ## Sort By:
  * has 4 elements in the dropbox: top, hot, new, and rising.

  ## Within:
  * has 4 elements in the dropbox: hour, week, year, and all.

  ## Repeat:
  * True: viewed image link won't be deleted(a chance to have the same image coming up again)
  * False: viewed image link will be deleted(no repetition)

<hr>

Source: <a href="https://github.com/jianleliu/MemeGenerator/tree/main"><i class="large-github icon "></i>jianleliu/meme_generator</a>
