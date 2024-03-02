
<h1 align="center">🏆 Sports Prediction Analysis Project README 🏆</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue.svg" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintained? yes">
  <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg" alt="Made with Python">
  <img src="https://img.shields.io/badge/Contributions-welcome-orange.svg" alt="Contributions welcome">
</p>


<h2>🔬 Scientific Analysis</h2>

<h3>📜 Overview</h3>
<p>This project leverages advanced machine learning to forecast football match outcomes, combining expertise in machine learning, data analysis, and predictive modeling with a focus on robust analytical methods for quick, meaningful insights.</p>

<h3>🔍 Data Collection and Preprocessing</h3>
<p>Extensive feature engineering was executed to integrate team performance metrics and betting odds, enhancing the models' performance by providing a nuanced data representation crucial for accurate predictions.</p>
<table border="1" class="dataframe">
  <caption>Data Downloaded</caption>
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Div</th>
      <th>Date</th>
      <th>HomeTeam</th>
      <th>AwayTeam</th>
      <th>FTHG</th>
      <th>FTAG</th>
      <th>FTR</th>
      <th>HTHG</th>
      <th>HTAG</th>
      <th>HTR</th>
      <th>HC</th>
      <th>AC</th>
      <th>B365H</th>
      <th>B365A</th>
      <th>B365D</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>114770</th>
      <td></td>
      <td>Premier Division</td>
      <td>02/03/2012</td>
      <td>Monaghan</td>
      <td>Dundalk</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>D</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.78</td>
      <td>2.92</td>
      <td>3.10</td>
      <td>2012/2013</td>
    </tr>
    <tr>
      <th>114771</th>
      <td></td>
      <td>Premier Division</td>
      <td>02/03/2012</td>
      <td>Drogheda</td>
      <td>Shamrock Rovers</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>A</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>11.63</td>
      <td>1.34</td>
      <td>5.16</td>
      <td>2012/2013</td>
    </tr>
    <tr>
      <th>114772</th>
      <td></td>
      <td>Premier Division</td>
      <td>02/03/2012</td>
      <td>Shelbourne</td>
      <td>Sligo Rovers</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>D</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>4.01</td>
      <td>2.13</td>
      <td>3.26</td>
      <td>2012/2013</td>
    </tr>
    <tr>
      <th>114773</th>
      <td></td>
      <td>Premier Division</td>
      <td>02/03/2012</td>
      <td>St. Patricks</td>
      <td>Bray</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>H</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.54</td>
      <td>7.34</td>
      <td>4.21</td>
      <td>2012/2013</td>
    </tr>
    <tr>
      <th>114774</th>
      <td></td>
      <td>Premier Division</td>
      <td>02/03/2012</td>
      <td>Derry City</td>
      <td>Bohemians</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>H</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.86</td>
      <td>5.17</td>
      <td>3.39</td>
      <td>2012/2013</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <img src="https://github.com/mhmmdbdrhmd/Football-Match-Predictor/assets/29101930/bcfab8eb-7a5f-4202-b8f5-f03beffb6695" alt="Over/Under 2.5 Goals" width="400">
  <img src="https://github.com/mhmmdbdrhmd/Football-Match-Predictor/assets/29101930/bcfab8eb-7a5f-4202-b8f5-f03beffb6695" alt="Final Results" width="400">
</p>


<h3>🛠 Model Development and Evaluation</h3>
<p>A variety of classifiers were utilized (Logistic Regression, SVM, Decision Trees, MLP, etc.), with initial models built on a limited feature set, serving as a solid baseline for further refinement.</p>

![Models Performance on Test Set](https://github.com/mhmmdbdrhmd/Football-Match-Predictor/assets/29101930/81bbb753-7606-40bf-a27f-c172979bd656)
<p>*Models Performance on Test Set*</p>


<h3>📊 Results</h3>
<p>The recalibrated models demonstrated accuracies of 57% and 77%, reflecting the complexity of sports outcome prediction and the significance of nuanced model development and evaluation strategies.</p>


<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Div</th>
      <th>Date</th>
      <th>HomeTeam</th>
      <th>AwayTeam</th>
      <th>FTR</th>
      <th>FTR probability</th>
      <th>Over/Under</th>
      <th>Over/Under probability</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Belgian First Division A</td>
      <td>B1</td>
      <td>01/03/2024</td>
      <td>Westerlo</td>
      <td>Charleroi</td>
      <td>H</td>
      <td>0.947445</td>
      <td>No</td>
      <td>0.934011</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Belgian First Division A</td>
      <td>B1</td>
      <td>02/03/2024</td>
      <td>Cercle Brugge</td>
      <td>Mechelen</td>
      <td>D</td>
      <td>0.736031</td>
      <td>Yes</td>
      <td>0.736883</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Belgian First Division A</td>
      <td>B1</td>
      <td>02/03/2024</td>
      <td>Oud-Heverlee Leuven</td>
      <td>St. Gilloise</td>
      <td>H</td>
      <td>0.643921</td>
      <td>No</td>
      <td>0.657676</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Belgian First Division A</td>
      <td>B1</td>
      <td>02/03/2024</td>
      <td>Standard</td>
      <td>Gent</td>
      <td>H</td>
      <td>0.993013</td>
      <td>No</td>
      <td>0.991115</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Belgian First Division A</td>
      <td>B1</td>
      <td>03/03/2024</td>
      <td>Genk</td>
      <td>Club Brugge</td>
      <td>D</td>
      <td>0.989625</td>
      <td>Yes</td>
      <td>0.987376</td>
    </tr>
  </tbody>
</table>




<h3>🚀 Future Directions</h3>
<ul>
<li><strong>Data Enrichment</strong>: Augment the dataset via web scraping for more comprehensive model training.</li>
<li><strong>Model Refinement</strong>: Employ advanced preprocessing and validation techniques to improve model performance.</li>
<li><strong>Strategic Betting Simulation</strong>: Develop a simulation environment to test different models' financial efficacy.</li>
<li><strong>Advanced Strategies</strong>: Explore unsupervised learning for confidence assessment and reinforcement learning for optimizing profit goals.</li>
</ul>

<p>These initial models lay the groundwork for future explorations in predictive modeling for sports betting, demonstrating the project's viability and potential for sophisticated analytics applications.</p>


<h3>📈 Output Visualization</h3>
<p>Visualizations include accuracy comparison charts among different models, feature importance graphs, and prediction outcome visualizations.</p>

<h2>📦 Installation & Setup</h2>
<p>Ensure Python 3.8+ is installed. Install dependencies with:
<pre><code>pip install -r requirements.txt</code></pre></p>

<h2>🛠 How It Works</h2>
<p>Run the main script to train models and evaluate their performance:
<pre><code>jupyter notebook Main.ipynb</code></pre></p>

<h2>📚 Usage Guide</h2>
<p>Details on how to use the project for predicting sports outcomes.</p>

<h2>📖 Documentation</h2>
<p>Refer to the included documentation for more in-depth information on the project setup, model development, and evaluation process.</p>

<h2>💬 Community Feedback</h2>
<p>We welcome feedback and suggestions from the community. Your insights are valuable to the continuous improvement of this project.</p>

<h2>🤝 Contributing</h2>
<p>Contributions to the project are welcome. Please refer to the contributing guidelines for more details.</p>

<h2>🔮 Future Development</h2>
<p>We aim to continually improve the models and expand their applicability to various sports and prediction scenarios.</p>

<h2>📄 License</h2>
<p>This project is licensed under the MIT License - see the `LICENSE` file for details.</p>

<h2>📞 Contact</h2>
<p>Mohammad Badri Ahmadi - <a href="mailto:mhmmdbdrhmd@gmail.com">mhmmdbdrhmd@gmail.com</a></p>

<h2>💖 Acknowledgments</h2>
<p>- Credit to data providers and contributors.<br>
- Special thanks to various online resources and communities for their invaluable data and insights.</p>

<p>*This project aims to enhance sports analytics through advanced prediction models, contributing to the fields of betting and fantasy sports.*</p>
