# Recommender-Systems: 
Find and recommend items that a user is most likely to be interested in.
# Examples:
<ul>
 <li> Product Recommendations: Amazon </li>
 <li> Movie Recommendations: Netflix </li>
 <li> Music Recommendations: Apple music </li>
  <li> Social Recommendations: Facebook and LinkedIn </li>
</ul>

# Recommender systems types: 
<ol>
<li>
  <font size="5" color="blue"><Strong>Popularity based: </Strong></font>get the most popular items and recommend to users, Not personalized recommendation engine. But good for new users.
</li>
 <li>
   <font size="5" color="blue"><Strong>Content Based Filtering: </Strong></font>Recommend items based on the meta data (item/user attributes).
   <ol>
<li>
  <font size="5" color="blue"><Strong>User based: </Strong></font>Recommend items based on similarity between users (two users have the same attributes such as married, country of birth, etc.), so will be similar users.
</li>
 <li>
   <font size="5" color="blue"><Strong>Item based: </Strong></font>Recommend products based on similarity between items (Two items have the same attributes such as price, category, etc.) , so similar items.
</li>
</ol>
</li>
  <li>
      <font size="5" color="blue"><Strong>Collaborative Filtering: </Strong></font> Recommend items based on user behavior(ratings/reviews).
   <ol>
<li>
  <font size="5" color="blue"><Strong>User based: </Strong></font>Recommend items based on the similarity between users (two users give good rates to the same products), so will be similar.
</li>
 <li>
   <font size="5" color="blue"><Strong>Item based: </Strong></font>Recommend products based on the similarity between items (the same users give item A and item B similar ratings), so the two items are similar.
</li>
</ol>
</li>
<li>
  <font size="5" color="blue"><Strong>Model-based Collaborative Filtering: </Strong></font>Recommend items based on user behavior(ratings/reviews). by factoring out the latent vectors (user attribute) matrix and (item attribute) matrix from the known (ratings/reviews). so make recommendations without back to the complete dataset.
</li>
</ol>

# Used Technologies
Python
Jupyter Notebook
