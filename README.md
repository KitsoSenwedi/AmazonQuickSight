Free AWS Project: Analyse Netflix Data with Amazon QuickSight

Step 1
- Download the Dataset

Step 2
- Open S3 Console
- Create bucket
- Name bucket(kitsosenwedi-quicksight-project)
- Region(CapeTown)
- Create Bucket
- Upload the CSV file and manifest.json file into the bucket
- copy netflix.titles.csv file S3 URL
- Open manifest.json file
- Replace URL in manifest file with S3 URL of your dataset
- Re-upload the edited manifest.file
- 
  ![manifest edit](https://github.com/user-attachments/assets/89b4104d-5a0b-43e3-900f-d367ca03adac)

  Step 3
  - Search Amazon QuickSight
  - Sign up for QuickSight
  - Make sure you uncheck this offer to upgrade.
  - Enter details for QuickSight account
  - Select Amazon S3
  - Select S3 bucket
  - Tick S3 bucket you created
    ![s3 account quicksight](https://github.com/user-attachments/assets/ade8c8c7-eda0-480e-bc48-ec862c2eaead)

  - Create
    ![Account created](https://github.com/user-attachments/assets/b6e276c7-4688-48cf-8837-52688778ba58)
  - Select Go To Amazon QuickSight
 
  Step 4: Connect your S3 bucket to Amazon QuickSight
  - From the left hand navigation bar, select Datasets, then New dataset.
  - Select S3
  - For the first field (source name), enter kaggle-netflix-data
  - Open a new tab to open your AWS Management Console again. Head back to your S3 bucket
  - Select the checkbox next to manifest.json, then select Copy S3 URL.
  - Enter the S3 URL to your manifest.json file
  - 
    ![data source](https://github.com/user-attachments/assets/a183a5a0-8311-4574-85eb-b481638b2472)
    
  - Select Connect
  - 
    ![dataset creation](https://github.com/user-attachments/assets/7bcf87fe-1cff-4af4-b9f5-f003013e7992)
    
  - Select Visualize
  - Select Create
  - Select Interactive sheet to start creating visualisations

  Step 5: Create Your First QuickSight Visualisation
  - Drag fields into the graph to create visualisations. Let's run through one example together
  - Drag release_year into the Y-Axis heading. Woo! Now you can see a breakdown on the year that these Netflix-featured TV shows and movies were released
  - Did you know you can create different types of charts too? See what happens when you change your chart to a donut chart!
  - Let's save this in a dashboard. Click on the frame surrounding your lovely donut chart, and click on the white boxes at the edges to resize it.
  - 
    ![chart6](https://github.com/user-attachments/assets/85697e4e-2cc9-4e28-9446-429a6d302876)

  - Now let's create a new visual, select + ADD under the Visuals heading on your middle navigation bar, and you'll see another blank frame pop out.
  - Hmmmm... what would you do to see a breakdown of TV shows vs movies for every year?
  - Drag the release_year label into the Y Axis heading.
  - Next, drag the type label into the Group/Color heading.
  - 
    ![chart2](https://github.com/user-attachments/assets/d3f8f827-fd61-4308-9d43-fcdfd75401c4)


  Step 6: Your QuickSight treasure hunt
  - "I quite like the breakdown of TV shows/movies for each release year. Would it be possible to stack movies and TV shows in the same row, so you can visualise the % of each?"
  - 
    ![chart3](https://github.com/user-attachments/assets/b094bc17-661a-43af-b20f-2722d6048059)

  - "Now can you show me the same thing in a table? i.e. please show me the number of movies vs TV shows per release year in a table."
  - 
    ![chart5](https://github.com/user-attachments/assets/b49d2d8d-49b7-416c-9094-af195d650b8f)

  - "On what day did Netflix add the largest number of movies/TV shows to their catalogue?"
  - 
    ![chart4](https://github.com/user-attachments/assets/57caca0f-04a3-4ad9-be51-0208a0fb4d27)

  - "Of the TV shows and movies featured, how many were listed as 'Action & Adventure', 'TV Comedies', or 'Thrillers'? For simplicity, ignore the TV shows and movies that have multiple listings/categories."
  - 
    ![chart7](https://github.com/user-attachments/assets/879601b0-9018-47e4-9401-93d9c92632a6)

  - "Of the TV shows and movies with the listing 'Action & Adventure', 'TV Comedies', or 'Thrillers', how many were released on 2015 or after?"
  - 
    ![chart1](https://github.com/user-attachments/assets/b43f6d3d-851b-4b45-aeb2-c148b8ecbd48)

  Step 7: Finishing touches
  - To round it all off, edit the titles in your charts so that anyone can understand them at a glance.
  - Double click on the titles of all the charts you see in front of you.
  - Enter your chart title
  - ![ChartScreenshot](https://github.com/user-attachments/assets/177c1451-00c1-4831-9176-ec5c93ce4f1d)
  - On the top right hand corner, select Publish. This will make your dashboard public so you can share it with your data team lead.
  - Give your dashboard a name (e.g. Netflix titles analysis) and click on that Publish dashboard button
  - Before we close your account and finish this project, let's make sure you have a copy of your dashboard. On the top right hand corner, select the Export icon.
  - Select Generate PDFs.
  - Wait for the PDF to be ready, then select Download when you see that green banner pop up!
    
