<h1>🎬 Movie Recommender System</h1>

<p>This project allows you to input the name of a movie and returns the <strong>top 5 most similar movies</strong> based on the content of that movie.</p>

<h2># What does it do?</h2>
<ul>
  <li>You enter a movie name (like "Inception")</li>
  <li>The system checks for similar movies using machine learning</li>
  <li>It recommends 5 movies that are most similar in terms of genres, cast, keywords, and overview</li>
</ul>

<h2># How does it work?</h2>
<ol>
  <li>It uses <strong>text vectorization</strong> (CountVectorizer) to convert movie descriptions into numbers</li>
  <li>Measures similarity using <strong>cosine similarity</strong></li>
  <li>Returns the top 5 movies with highest similarity scores</li>
</ol>

<h2># Features</h2>
<ul>
  <li>Content-based filtering (using tags made from genres, keywords, overview, etc.)</li>
  <li>Clean and beginner-friendly code</li>
  <li>Simple print output of similar movie titles</li>
</ul>

<h2># How to Use</h2>
<ol>
  <li>Clone this repo</li>
  <li>Open the Jupyter Notebook file</li>
  <li>Run all the cells</li>
  <li>Call <code>recommend("Your Movie Title")</code> at the end to get suggestions</li>
</ol>

<h2># Requirements</h2>
<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>Scikit-learn</li>
  <li>NLTK</li>
</ul>

<h2># Example</h2>
<pre>
recommend("Batman Begins")
→ You may also like:
   - The Dark Knight
   - Batman v Superman: Dawn of Justice
   - Man of Steel
   - The Dark Knight Rises
   - Superman Returns
</pre>

<h2># Author</h2>
<p>Made by <strong>Bishal Dutta</strong><br>
GitHub: <a href="https://github.com/i-m-invincible" target="_blank">i-m-invincible</a></p>
