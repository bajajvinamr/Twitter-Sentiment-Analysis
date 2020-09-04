# Twitter-Sentiment-Analysis

This is a  project which I have done under the guidance of Dr. L. Bhera,IIT Kanpur, under a research internship.

<b>Dataset Folder</b> contains the twitter tweets.
<p>
  <b>Train</b> file contain tweet_id, sentiment and tweet_text.
  <ul>
    <li>tweet_id : unique for every tweet.</li>
    <li>sentiment : three types - negative, neutral and positive.</li>
    <li>tweet_text : tweets over which you have to analyse the sentiment.</li>
    </ul>
</p>
<p>
  <b>test_sample</b> data has two columns : tweet_id and tweet_text
  <ul>
    <li>tweet_id: unique for every tweet</li>
    <li>tweet_text: sentiment over which you have to predict whether this text is negative, neutral or positive.</li>
    </ul>
</p>
<p>Three approaches were taken:
<ul>
  <li>Logistic Regression </li>
  <li>LSTM with Glove word embedding</li>
  <li>Bidirectional LSTM with Glove word embedding</li>
</ul>
</p>
<p>Accuracy acheived on Kaggle test_sample:
<ul>
  <li>Logistic Regression - 65% </li> 
  <li>LSTM with Glove word embedding - 67.5% </li>
  <li>Bidirectional LSTM with Glove word embedding - 67%</li>
</ul>
</p>
