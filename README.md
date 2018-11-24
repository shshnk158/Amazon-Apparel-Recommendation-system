# Amazon-Apparel-Recommendation-system
Recommend similar apparel items/products in ecommerce.

#### Business objective 
> Recommending similar apparel items to user.
Its estimated that amazon's 35% revenue is generated using product recommendations.

#### Approach

We have two approaches here, 

1. Content based recommendation:
As its name suggests, we do content based recommendation, means its based on tittle text,Description text, images.

2. Collobarative filtering based recommendation:
This recommendations are done based on the behaviour of the user.A small example can be seen,
```
if    U1 ===> I1,I2 ,I3   (Purchases or Searches)   # U-User , I-Item
and   U2 ===> I1,I3,I4
then  U3 ===> I1,(I3)      # recommend user 3 item I3 as he purchased I1.

```
U3's recommendations came from behaviour of similar users as he purchased I1. This is Collobarative filtering.
But, Amazon doesnt provide users data, so we are not going to do collobarative filtering. Instead we use content based.

#### Plan of Attack

These are the steps we follow during this project.
1. Data aquisition
2. Data Cleaning
3. Text Processing (NLP)
We solve this problem with both Text based and Image based.
4. Text based product recommendation
  - Bag of Words
  - Term frequency-Inverse document frequency (TF-IDF)
  - Word2Vec
    - Avg W2V
    - TF-IDF weighted W2V
  
5. Image based product recommendation
  - Using CNN deep learning techniques
6. A/B testing.

####


