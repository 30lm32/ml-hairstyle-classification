# Hairstyle Classification
![Image](https://howng.com/wp-content/uploads/2016/10/traditional-hairstyles-e1477039899416.jpg)

If you want to see the further ML projects, you may visit my main repo: https://github.com/erdiolmezogullari/ml-projects

The dataset contains a sample 10000 images mined from Instagram 
and clustered based on the hairstyle they showcase.  
 
The variable `cluster`  represents the hairstyle cluster that the image has been assigned to by 
the visual recognition algorithm. 
 
Each row contains the variable `url` which is the link to the image and  the number of ​ likes 
together with the `comments` per image.  The `user_id`  is the unique id of the Instagram account 
from which the post comes and the variable  `id`  is the unique identifier associated with the post 
itself.

Each post contains the date(`date_unix`)  in unix format when the image was posted on 
Instagram and additionally the date has been converted to different formats (`date_week`->non-iso number of the week, `date_month`  -> the month, `date_formated` ->full date dd/mm/YY) partly 
for use in prior analyses. Feel free to convert that variable in a way that suits your analysis. 
 
Additionally a classifier `influencer_flag` was added to each of the images which have more than 
500 likes, flagging them as influencer posts.  
