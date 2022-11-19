# ENGS 108 Fall 2022 Assignment {NUMBER} Template Repository
Included in this repository is the Assignment {NUMBER} notebook. It provides a skeleton for your coding assignment so that hopefully concepts are enforced over debugging. Although these assignments have been curated throughout the years, this delivery format is experimental, so if anything doesn't work as it should please let the TAs know as soon as possible. 

# Getting Setup

This semester we will be using Github Classroom to host datasets and assignment template notebooks and Google Colab to run all of our code. The process for getting setup is pretty straightforward and you will be aided considerably if you install the following tools:
1. You have already accepted the assignment invite so now you are in your own private repository.
1. You will see a file called *Assignment_{NUMBER}_Fall2022_template.ipynb*, click on it!
1. Then click on the button to "Open in Google Colab."
1. **Important:** Then click Save a copy in Drive and rename it something different like: *submission_assignment_{NUMBER}.ipynb* (This will make it easier for us to find later). 
1. This will open up a new notebook and save a copy to MyDrive/Colab Notebooks. You can check the location by going to File > Locate in Drive.
1. Now you have a copy of the skeleton in your Colab Notebook folder, seperated from your Git Repo.
1. **This is important in case I have to update a skeleton for some reason it won't accidently overwrite work that you have already done.**
1. (Optional) If you haven't already done so install Google Drive Backup and Sync.

## Allow Google Colab to Access Private Repos and Orgs (DO THIS ONCE! MAYBE RIGHT NOW!)
1. Navigate to [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
1. If you're new, maybe look at the intro notebook to get yourself familiar.
1. If you're not signed in, make sure to sign into your appropriate Google Account.
1. Now click Tools > Settings, and navigate to the Github option.
1. Check the "Access private repositories and organizations" option, and click through any authorization pop-ups that come up and click "Save."
1. All done with this!

## Installing Google Drive Backup and Sync
Navigate to [Google's website](https://www.google.com/drive/download/) and download and install the Google Drive Backup and Sync Application. You should also be using your Dartmouth Account for this as it has unlimited storage in case we play around with some larger datasets.

# Accessing Everything From Google Colab
Now that we have everything loaded up in Google Drive accessing Colab is a breeze. **Make sure you've saved a notebook copy as stated above.**
1. Navigate to [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
1. If you're new, maybe look at the intro notebook to get yourself familiar.
1. If you're not signed in, make sure to sign into your appropriate Google Account.
1. Now click File > Open Notebook. 
1. Click on the Google Drive Tab, and you should see your Notebooks appear. 
1. Load your respective notebook and get started on the assignment.

## Mounting your Google Drive in Colab
When we work with datasets, you will need to have access to files in the repository we cloned with all the datasets. This procedure is called mounting. 
1. After opening your desired notebook, click on the little folder icon on the lefthand side.
1. Three icons will now appear on the top of this Files Panel.
1. Click on the rightmost icon (When you hover it should say Mount Drive).
1. That's it. You should be able to see all your Drive contents in the '/content/Drive/MyDrive' directory. 
*Note: If there is any data loading code make sure to change your base file path to what it should be on your particular system.*

# Submitting Homework
Please do not deviate far from the assignment code skeleton. If you find a significant error or have concerns please reach out to the TAs.
The homework development process should be as follows:
1. Run all the setup that is described here.
1. Answer all assignment code inside your Colab notebook via code or Markdown. If you are unsure about writing in Markdown view this [guide](https://colab.research.google.com/notebooks/markdown_guide.ipynb#scrollTo=tPqPXAKKkzaM). It's actually quite easy.
1. We are going to use Github classroom (experimental) to submit assignments because its way easier than Canvas.
1. Upon completion of your assignment in Google Colab, go to File > Save a copy in Github. 
1. A new window will pop up, go to the Repository drop down and select your personal assignment repository (probably labeled something like "Thayer-ENGS108/assignment_{NUMBER}_Fall2022-{your-name}").
1. To make multiple submissions, just keep saving a copy to Github like previously described and just overwrite your old copy.
1. **Important:** Always make sure to check your work to make sure your saved copy on Github matches your work in your notebook, remember you are saving the colab notebook constantlty in Google Drive and saving copies (snapshots) to Github, so Github will only make changes when you explicitly do the File > Save a copy in Github command!
1. Make sure you get your final submission in by the deadline!

# Updating Homework and Datasets
Sometimes there may be incidences when we need to make revisions to a problem set and you will need to update your assignment notebook or datasets. We will try to minimize these disruptions but just in case.

## Updating Assignment Notebook
1.	Go to your assignment Github repository. 
2.	Below your assignment repo name, you should see a “generated from” hyperlink. Click on it.

![Screenshot](assets/readme-image-1.png?raw=true "Screenshot 1")

3.	This base template repo is the place that we will update any assignment corrections. Click on the updated assignment repo and open in Google Colab.
4.	Save this repo to your Google Drive as something new like: assignment-XX-updated.ipynb. 
5.	Then you can manually update this notebook with any old notebook code/markdown that you’ve already completed. In other words, copy and paste your any of your completed work to this new notebook. 
a.	We are sorry for the manual process, but we think it’s the easiest/safest way.
6.	**IMPORTANT:** Once you’ve copied over all your work to the new notebook, save that work to your github repo like you normally do.

## Updating Datasets
1.	Go to your assignment Github repository. 
2.	Below your assignment repo name, you should see a “generated from” hyperlink (See above figure). Click on it.
3.	Click on Code > Download ZIP, to download the entire template repo.

![Screenshot](assets/readme-image-2.png?raw=true "Screenshot 2")

4.	Extract the ZIP file and navigate to datasets.
5.	Now go back to your assignment repo on Github and also navigate to datasets.
6.	Click on Add File > Upload files.

![Screenshot](assets/readme-image-3.png?raw=true "Screenshot 3")

7.	Re-upload all the new data files to your local Github and Click Commit.
8.	You’re now all set.  
