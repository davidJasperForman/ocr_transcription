# ocr_transcription
A Jupyter Notebook for some document transcription work

The goal is to take an image (a jpg, a png, or even another type) and extract the text. 
This code uses the Google Cloud Vision OCR pipeline to get a high-quality transcription.

1. Download Anaconda https://www.anaconda.com/products/individual
    (or somehow get Jupyter Notebook to work)
2. Download this JupyterNotebook
3. Obtain a Google Cloud account and (for this low-security way) insert the security code into the code. (Ctrl-F for 'key' or 'INSERT_SECURITY_KEY_HERE'.)
4. Run the code for either
       a) a single filepath of an image (for that, replace INSERT_IMAGE_FILEPATH_HERE with the relevant image filepath).
       b) all the jpg or png files within a given folder (for that, replace INSERT_IMAGE_FOLDER_PATH_HERE with the relevant folder path)
       
      This works for certain file types, not others. For example, you can't simply replace instances of "jpg" within the code with "pdf" and have it work. For pdfs, a hacker's shortcut is to take screenshots of the pdfs and save them as .pngs in a directory, and then run this code for that directory.
      
      
