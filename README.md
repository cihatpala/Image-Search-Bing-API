# Image-Search-Bing-API
## An API where you can quickly create a dataset for training in Deep Learning

![Angelina_Jolie](https://user-images.githubusercontent.com/30652453/85960781-d78cd300-b9ae-11ea-9157-516ee663dec5.png)

# Step 0 (Getting keys from Microsoft)

* First, log in to your microsoft account.
>Note: You should be given a free trial key. - as an experiment - (The current situation is unknown.)

* Go to this link: https://azure.microsoft.com/en-us/try/cognitive-services/my-apis/?api=bing-image-search-api
   >Note: Key1 and Key2 must be values. Note them because they will be pasted into the code.

# Step 1 (Requirements)

* ###  Python 
   Download: https://www.python.org/downloads/
     
* ### Anaconda Powershell Promt
   This is a command screen. 
   You can use another screen where you can run the "pip install" command, there is no need to download it.
   Download: https://www.anaconda.com/products/individual#windows
     

## Required modules

   It is a module that you can download from the command screen (Anaconda Powershell Promt).
     
* ### Requests Module
   Download command : `pip install requests`
     
* ### Argparse Module
   Download command : `pip install argparse`
   
* ###  cv2 (OpenCV) Module
   Download command : `pip install opencv-python`
   
* ###  Os Module
   Download command : `pip install os-win`


# Step 2 (Installation)
   
   ### (Alternative 1) You may need to use Git Bash for this.
   #### Git Bash Download Link: https://git-scm.com/downloads
   * Go to [your working directory] <br>
     Note: You can easily switch between directories with the `cd` command.)
   * `git init`
   * Clone link of this project : https://github.com/cihatpala/Image-Search-Bing-API.git
   * `git remote add [remote_name] https://github.com/cihatpala/Image-Search-Bing-API.git`
   * `git pull [remote_name]`
  
   ### (Alternative 2)
   * Download the `zip file` of this project.
   
# Step 3 (How It Works)

   ## Using the key given to you by Microsoft
   * Type the key given to you in the `API_KEY = "key given to you"` section of the Bing_image_search_api.py script.
   
   ### Start Anaconda Promt
   * Go to the file where you clone the project. <br>
     Note: You can easily switch between directories with the `cd` command.)
   * `mkdir train_set`
   * `mkdir train_set/angelina_jolie`
   * `python Bing_image_search_api.py –query "Angelina Jolie" --output train_set/angelina_jolie`
   
   >Note: Whatever number you give to the `GROUP_SIZE` variable in the Bing_image_search_api.py script, it will be so visual.
     
   * >As a result, you get *Angelina Jolie's* photos as many as `GROUP_SIZE`.
