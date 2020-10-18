# CECS 450 Project - SoundCloud

DISCLAIMER: This has nothing to do with the website/streaming service SoundCloud. Our name is based on the fact that we create word CLOUDS from songs (SOUND)

## User Guide

### Prequisites
Before we begin, you must have an [account](https://genius.com/signup) and an [API key](https://genius.com/api-clients/new) provided by Genius.

![api_image](https://i.imgur.com/QIhmfNp.png)

When creating a new API client, do not worry about the URL, `example.com` should work just fine. After creating the client, generate the "Client Access Token" and save it for later. You are now able to proceed!

### Instructions
1. Click here [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brandonnhem/450-SoundCloud/main) to be taken to an external site, mybinder.org. Let the page load as it has to download all required packages provided by the `requirements.txt` file.

2. After all packages are downloaded, you should be redirected to a file browser. Please press on the file named `soundCloud.ipynb`.

![file_browser](https://i.imgur.com/R0YFBXS.png)

3. Starting from the top of the notebook, select the first cell, press the play button in the toolbar for each cell.

![notebook_toolbar](https://i.imgur.com/CSLfLN0.png)

4. Enter the API key to proceed when you've reached the `display()` cell. Search any song name and artist in the provided fields and then press "Generate Cloud" button

![gui_elements](https://i.imgur.com/BncWtWD.png)

5. Move onto the next cell and press play, you should be met with your very own word cloud!
