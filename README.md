<h1>AI Mental Fitness Tracker</h1>

<h2>Overview</h2>
<p>
    The AI Mental Fitness Tracker is a project that leverages artificial intelligence to analyze and monitor mental well-being over time. This project uses various data sources to evaluate the prevalence and impact of mental disorders and provides insights through visualizations and predictions.
</p>

<h2>Features</h2>
<ul>
    <li><strong>Data Analysis:</strong> Merges and analyzes data on mental health prevalence and disability-adjusted life years (DALYs).</li>
    <li><strong>Visualizations:</strong> Provides various visualizations such as heatmaps, pair plots, and line charts to understand trends and correlations.</li>
    <li><strong>Predictive Modeling:</strong> Implements a linear regression model to predict mental fitness based on historical data.</li>
</ul>

<h2>Data</h2>
<ul>
    <li><strong>Data Sources:</strong> The notebook uses two CSV files for analysis:
        <ul>
            <li><code>prevalence-by-mental-and-substance-use-disorder.csv</code></li>
            <li><code>mental-and-substance-use-as-share-of-disease.csv</code></li>
        </ul>
    </li>
    <li><strong>Data Description:</strong>
        <ul>
            <li><strong>Prevalence Data:</strong> Contains information on the prevalence of various mental disorders across different countries and years.</li>
            <li><strong>DALY Data:</strong> Contains information on disability-adjusted life years for mental disorders.</li>
        </ul>
    </li>
</ul>

<h2>Visualizations</h2>
<ul>
    <li><strong>Heatmap:</strong> Shows correlations between different mental health metrics.</li>
    <li><strong>Pair Plot:</strong> Provides insights into relationships between multiple variables.</li>
    <li><strong>Pie Chart:</strong> Displays the distribution of mental fitness scores across years.</li>
    <li><strong>Line Chart:</strong> Illustrates the year-wise variation in mental fitness across different countries.</li>
</ul>

<h2>Model</h2>
<ul>
    <li><strong>Model Type:</strong> Linear Regression</li>
    <li><strong>Performance Metrics:</strong> Evaluated using mean squared error and R-squared score.</li>
</ul>
