# Part 2: Downloading and using your own Geospatial Dataset
  1. Finding your own dataset
  2. Cleaning your dataset
  3. Uploading your dataset to mapbox as a tileset
  4. Displaying your tileset on a map
 ---
 ### 1. Finding your own dataset
 For this part you are free to download any .csv file that contains geographic data (Longitude and Latitude).
 You can find them on https://www.data.gouv.fr/fr/pages/donnees-geographiques/ or any other source. 
 Open it manually to check if there are the Longitude or latitude columns (could be called long and lat).
 Warning: - Some .csv have different column separators ("," or ";"), you can open your .csv file in your text editor to check.
 
 ### 2. Cleaning your dataset
 Most datasets aren't "clean": Some data could be missing or unreadable.
 You can use Python and the Pandas library to clean your dataset:
 1. Download Python.
 2. Learn what Pandas is (https://pandas.pydata.org/) and what a pandas dataframe is.
 3. Create a Python binary file (.py).
 4. Download Pandas with `pip install pandas` in your terminal or at the begining of your python binary.
 5. In your .py binary:
    1. Import the pandas library into your runnable Python file with `import pandas as pd`.
    2. Read your .csv dataset and save it in a pandas dataframe.
    3. Verify that the coordinates decimals are separated by "." and not by ",".
    4. Use pandas to create a dataframe that only has the data you want to display on the map.
    5. Export your dataframe to a .csv
 
 ### 3. Uploading your dataset to mapbox as a tileset
 1. Create an account on Mapbox
 2. Upload your dataset as a Tileset on Mapbox studio (https://studio.mapbox.com/tilesets/)
 
 ### 4. Displaying your tileset on a map
 1. Use the part 1 of this workshop
 2. Change the token we gave you in part 1 to your mapbox token, you can find it on your account page.
 3. Change the tileset called in Part 1 to yours
 4. Display your dataset.
