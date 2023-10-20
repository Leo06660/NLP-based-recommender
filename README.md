# NLP-based recommender system for stand-up comedians
<em>This project is also published at [my portfolio website](https://yilichen-leoportfolio-f709a-7d1d9.stackbit.app/blog/NLP-based-Comedian-Recommender-System/) </em>


<div id="header" align="left">
  <ul>
      <li>Recommend a stand-up comedian from given look-alike comedians based on scripts content with Machine Learning</li>
      <li>Keywords: Python, Clustering, Classification, Hypothesis Testing</li>
  </ul>
</div>


### Three main methods to predict which comedians the users may like:
1. Vectorize comedians and users and use machine learning for prediction
2. Practice classic CF
3. Vectorize nodes in graphs and use machine learning for prediction


### Key Findings
The classic CF only has 64% accuracy, meaning that there is room to improve and this approach has been overly accentuated. However, after encompassing other details into our recommender system, the best outcome of our proposed variations is no better than 70% accuracy, indicating that many details that we put into are noise. Therefore, further improvements could be made by studying more on how to extract more meaningful information from text and other resources.
