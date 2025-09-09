# Ubuntu-Inspired Image Fetcher

> *"I am because we are"* – Ubuntu Philosophy  

This project is a **Python script** inspired by the spirit of Ubuntu, emphasizing **community, sharing, and respect**.  
It allows users to fetch images from the internet, organize them neatly, and handle errors gracefully.  

---

## Features

-  **Download images** from user-provided URLs  
-  **Saves images** into a directory called `Fetched_Images`  
- **Duplicate protection**: skips downloading if the image already exists  
-  **Content check**: ensures only valid images are saved  
-  **Multiple URLs support**: fetch several images in one go  
-  **Error handling**: gracefully manages timeouts, HTTP errors, and bad URLs  

---

##  Requirements

- Python 3.7+  
- Install dependencies with:

```bash
pip install requests
