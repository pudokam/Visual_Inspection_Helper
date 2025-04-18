# Visual_Inspection_Helper
Go through a directory of images and add flags/notes/redshifts to a periodically savable csv file

# From base anaconda environment:
### Should Already Have TKinter
### Requires: 

Python - conda install python

PIL - conda install pillow

pandas - conda install pandas

pdf2image - conda install -c conda-forge pdf2image (only if using \_pdf.py) 

tkinter - automatically installed with python in Anaconda

# To Run:
`python vis_inspect_pdf.py`

This will create a window from which you can enter a file path or you can click `Browse Data Folders` to select a directory that *only* has pdf files in it. Additionally, select a location with `Browse Result Folders` where your visual inspection results will be saved as a csv file with the name you insert. Once selected, click `Set File Path`.  

Next, a window titled [OIII] Visual Inspection will pop up. In this window, you can add Flags, Notes, and a nominal Redshift in each of the entry boxes on the left.  On the right is the pdf image.  When satisfied, click `Next` to go to the next file. 

Your input will automatically save to the csv file when you click `Next` or `Back`.  You can go back to a previous source by clicking `Back`.
> **Note: If you have entered information and then go back to a previous source,the information previously added will repopulate in the GUI based on the saved csv file.**

Once you are at the end of the file list, the `Next` tab will turn to `Last Image` and will become obsolete.  You need to click it one more time (or the `Back` button) to save the information you've input for the last source. 

**The `Save` button is now obsolete as it is now automatic and we are working to remove it.**

Once saved, you can click `Exit` which will force you to save it again and will close the window.  You will be left with the first window again and you can choose another directory to inspect.  When finished, simply use the `X` to close the window and end the program. 
