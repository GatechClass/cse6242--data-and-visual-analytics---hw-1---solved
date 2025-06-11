# cse6242--data-and-visual-analytics---hw-1---solved
**TO GET THIS SOLUTION VISIT:** [CSE6242 -Data and Visual Analytics – HW 1 – Solved](https://mantutor.com/product/cse6242-data-and-visual-analytics-hw-1-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89179&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE6242 -Data and Visual Analytics - HW 1   - Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<strong>Download the </strong><a href="https://poloclub.github.io/cse6242-2021spring-online/hw1/Y7b5hemF5P_hw1.zip"><strong>HW1 Skeleton</strong></a> <strong>before you begin.</strong>

<h1>Homework Overview</h1>
Vast amounts of digital data are generated each day, but raw data are often not immediately “usable”. Instead, we are interested in the information content of the data: what patterns are captured? This assignment covers a few useful tools for acquiring, cleaning, storing, and visualizing datasets.

In Question 1 (Q1), you will collect data using an API for <em>The Movie Database</em> (TMDb). You will construct a graph representation of this data that will show which actors have acted together in various movies, and use <em>Argo Lite</em> to visualize this graph and highlight patterns that you find. This exercise demonstrates how visualizing and interacting with data can help with discovery.

In Q2, you will construct a TMDb database in SQLite, with tables capturing information such as how well each movie did, which actors acted in each movie, and what the movie was about. You will also partition and combine information in these tables in order to more easily answer questions such as “which actors acted in the highest number of movies?”.

In Q3, you will visualize temporal trends in movie releases, using a JavaScript-based library called D3. This part will show how creating interactive rather than static plots can make data more visually appealing, engaging and easier to parse.

Data analysis and visualization is only as good as the quality of the input data. Real-world data often contain missing values, invalid fields, or entries that are not relevant or of interest. In Q4, you will use OpenRefine to clean data from Mercari, and construct GREL queries to filter the entries in this dataset.

Finally, in Q5, you will build a simple web application that displays a table of TMDb data on a single-page website. To do this, you will use Flask, a Python framework for building web applications that allows you to connect Python data processing on the back end with serving a site that displays these results.

<h1>Q1 [40 points] Collect data from TMDb and visualize co-actor network</h1>
Q1.1 [30 points] Collect data from TMDb and build a graph

&nbsp;

complete the Graph class, the TMDbAPIUtils class, and the two global functions. The Graph class will serve as a re-usable way to represent and write out your collected graph data. The TMDbAPIUtils class will be used to work with the TMDB API for data retrieval.

&nbsp;

<strong>NOTE:</strong> You <strong>must</strong> only use a version of Python ≥ 3.7.0 and &lt; 3.8 for this question. This question has been developed, tested for these versions. You <strong>must not</strong> use any other versions (e.g., Python 3.8). While we want to be able to extend to more Python versions, the specified versions are what we can definitively support at this time.

&nbsp;

&nbsp;

<ol>
<li>[10 pts] Implementation of the Graph class according to the instructions in <strong>py</strong></li>
</ol>
&nbsp;

<ol>
<li>[10 pts] Implementation of the TMDbAPIUtils class according to the instructions in <strong>py. </strong>You will use version 3 of the TMDb API to download data about actors and their co-actors. To use the TMDb API:
<ul>
<li>Create a TMDb account and obtain your client id / client secret which are required to obtain an authentication Token. Refer to <a href="https://poloclub.github.io/cse6242-2021spring-online/hw1/7urMEMxDF8_tmdb_registration_instructions.pdf">this</a> document for detailed instructions (log in using your</li>
</ul>
</li>
</ol>
GT account).

<ul>
<li>Refer to the <a href="https://developers.themoviedb.org/3/getting-started/introduction">TMDB API Documentation</a> as you work on this question. The documentation contains a helpful ‘try-it-out’ feature for interacting with the API calls.</li>
</ul>
&nbsp;

<ol>
<li>[10 pts] Producing correct <strong>csv</strong> and <strong>edges.csv.</strong> You must upload your <strong>nodes.csv</strong> and <strong>edges.csv</strong> files to Argo-Lite as directed in Q1.2.</li>
</ol>
&nbsp;

<strong>NOTE:</strong> Q1.2 builds on the results of Q1.1

Q1.2 [10 points] Visualizing a graph of co-actors using Argo-Lite

Using Argo Lite, visualize a network of actors and their co-actors.

You will produce an Argo Lite graph snapshot your <strong>edges.csv</strong> and <strong>nodes.csv</strong> from Q1.1.c.

&nbsp;

<ol>
<li>To get started, review <a href="https://github.com/poloclub/argo-graph-lite">Argo Lite’s readme on</a> <a href="https://github.com/poloclub/argo-graph-lite">GitHub</a><a href="https://github.com/poloclub/argo-graph-lite">.</a> Argo Lite has been open-sourced.</li>
</ol>
&nbsp;

<ol>
<li>Importing your Graph
<ul>
<li>Launch <a href="https://poloclub.github.io/argo-graph-lite/">Argo Lite</a></li>
<li>From the menu bar, click ‘Graph’ → ‘Import CSV’. In the dialogue that appears:</li>
</ul>
</li>
</ol>
o Select ‘I have both nodes and edges file’

<ul>
<li>Under Nodes, use ‘Choose File’ to select <strong>csv</strong> from your computer o Leave ‘Has Headers’ selected o Verify ‘Column for Node ID’ is ‘id’</li>
<li>Under Edges, use ‘Choose File’ to select <strong>csv</strong> from your computer o Verify ‘Column for Source ID’ is ‘source’ o Select ‘Column for Target ID’ to ‘target’ o Verify ‘Selected Delimiter’ is ‘,’</li>
<li>At the bottom of the dialogue, verify that ‘After import, show’ is set to ‘All Nodes’</li>
<li>The graph will load in the window. Note that the layout is paused by default; you can select to ‘Resume’ or ‘Pause’ layout as needed.</li>
<li>Dragging a node will ‘pin’ it, freezing its position. Selecting a pinned node, right clicking it, then choosing ‘unpin selected’ will unpin that node, so its position will once again be computed by the graph layout algorithm.&nbsp; Experiment with pinning and unpinning nodes.</li>
</ul>
&nbsp;

<strong>NOTE:</strong> If a malformed .csv is uploaded, Argo-Lite could become un-responsive. If you suspect this is the case, open the developer tools for your browser and review any console error messages.

&nbsp;

<ol>
<li>[7 points] Setting graph display options</li>
</ol>
<ul>
<li>On “Graph Options” panel, under ‘Nodes’ → ‘Modifying All Nodes’, expand ‘Color’ menu o Select Color by ‘degree’, with scale: ‘Linear Scale’
<ul>
<li>Select a color gradient of your choice that will assign lighter colors to nodes with higher node degrees, and darker colors to nodes with lower degrees ● Collapse the ‘Color’ options, expand the ‘Size’ options.</li>
<li>Select ‘Scale by’ to ‘degree’, with scale: Linear Scale’ o Select meaningful Size Range values of your choice or use the default range.</li>
</ul>
</li>
<li>Collapse the ‘Size’ options</li>
<li>On the Menu, click ‘Tools’ → ‘Data Sheet’ ● Within the ‘Data Sheet’ dialogue:
<ul>
<li>Click ‘Hide All’</li>
<li>Set ‘10 more nodes with highest degree’ o Click ‘Show’ and then close the ‘Data Sheet’ dialogue</li>
</ul>
</li>
<li>Click and drag a rectangle selection around the visible nodes</li>
<li>With the nodes selected, configure their node visibility by setting the following:
<ul>
<li>Go to ‘Graph Options’ → ‘Labels’ o Click ‘Show Labels of Selected Nodes’</li>
<li>At the bottom of the menu, select ‘Label By’ to ‘name’</li>
<li>Adjust the ‘Label Length’ so that the full text of the actor name is displayed</li>
</ul>
</li>
<li>Show only non-leaf vertices. On the Menu, click ‘Tools’ → Data Sheet→ ‘Show <em>k</em> More Nodes with Highest Degree’. (where <em>k</em> is the input number of nodes such that <strong>only nodes with a degree &gt; 1 are visible</strong>).&nbsp; To make this easier, we suggest writing a utility function in your Graph class to find the count of leaf nodes in order to determine how many nodes should be shown. <em>&nbsp;</em></li>
</ul>
&nbsp;

The result of this workflow yields a graph with the sizing and coloring depend upon the node degree and the nodes with the highest degree are emphasized by showing their labels.&nbsp; Also,

&nbsp;

<ol>
<li>[3 points] Designing a meaningful graph layout</li>
</ol>
Using the following guidelines, create a visually meaningful and appealing layout:

<ul>
<li>Reduce as much edge crossing as possible</li>
<li>Do not allow any nodes to overlap</li>
<li>Keep the graph compact and symmetric as possible</li>
<li>Use the nodes’ spatial positions to convey information (e.g., “clusters” or groups)</li>
<li>Experiment with showing additional node labels. If showing all node labels creates too much visual complexity, show at least 10 “important” node labels. You may decide what “importance” mean to you. For example, you may consider nodes (actors) having higher connectivity as potentially more “important” (based on how the graph is built).</li>
</ul>
&nbsp;

The objective of this task is to familiarize yourself with basic, important graph visualization features. Therefore, this is an <strong>open-ended task</strong> and most designs are acceptable&nbsp; You should experiment with Argo Lite’s features, changing node size and shape, etc. In practice, it is not possible to create “perfect” visualizations for most graph datasets. The above guidelines are ones that generally help.

However, like most design tasks, creating a visualization is about making selective design compromises. Some guidelines could create competing demands and following all guidelines may not guarantee a “perfect” design.

&nbsp;

If you want to save your Argo Lite graph visualization snapshot locally to your device, so you can continue working on it later, we recommend the following workflow.

<ul>
<li>Select ‘Graph’ → ‘Save Snapshot’ o In the ‘Save Snapshot` dialog, click ‘Copy to Clipboard’
<ul>
<li>Open an external text editor program such as TextEdit or Notepad. Paste the clipboard contents of the graph snapshot, and save it to a file with a <strong>.json</strong>&nbsp; You should be able to accomplish this with a default text editor on your computer by overriding the default file extension and manually entering ‘.json’.</li>
<li>You may save your progress by saving the snapshot and loading them into Argo Lite to continue your work.</li>
<li>To load a snapshot, choose ‘Graph’ → ‘Open Snapshot’ ● Select the graph snapshot you created.</li>
</ul>
</li>
</ul>
&nbsp;

&nbsp;

<ol>
<li>Publish and Share your graph snapshot ● Name your graph: On the top navigation bar, click on the label ‘Untitled Graph’. In the</li>
</ol>
‘Rename Snapshot’ dialogue window that appears, enter your GTUsername as the ‘Snapshot Name’ and click ‘Done’

<ul>
<li>Select ‘Graph ‘ → ‘Publish and Share Snapshot’ → ‘Share’</li>
<li>Next, click ‘Copy to Clipboard’ to copy the generated URL</li>
<li>Return the URL in the return_argo_lite_snapshot() function in <strong>py</strong> If you modify your graph after you publish and share a URL, you will need to re-publish and obtain a new URL of your latest graph.</li>
</ul>
&nbsp;

<h1>Q2 [35 points] SQLite</h1>
<a href="http://www.sqlite.org/">SQLite</a> is a lightweight, serverless, embedded database that can easily handle multiple gigabytes of data. It is one of the world’s most popular embedded database systems. It is convenient to share data stored in an SQLite database — just one cross-platform file which does not need to be parsed explicitly (unlike CSV files, which have to be parsed).

&nbsp;

You will modify the given <strong>Q2_SQL.py </strong>file by adding SQL statements to it. We suggest that you consider testing your SQL locally on your computer using interactive tools to speed up testing and debugging, such as DB Browser for SQLite <a href="https://sqlitebrowser.org/">(</a><a href="https://sqlitebrowser.org/">https://sqlitebrowser.org</a><a href="https://sqlitebrowser.org/">)</a>.

&nbsp;

&nbsp;

&nbsp;

<ol>
<li>[9 points] <em>Create tables and import data</em>.
<ol>
<li>[2 points] Create two tables (via two separate methods, part_ai_1 and part_ai_2, respectively in Q2_SQL.py) named movies and movie_cast with columns having the indicated data types:
<ol>
<li>movies
<ol>
<li>id (integer) 2. title (text)</li>
<li>score (real)</li>
</ol>
</li>
<li>movie_cast
<ol>
<li>movie_id (integer)</li>
<li>cast_id (integer)</li>
<li>cast_name (text)</li>
<li>birthday (text)</li>
<li>popularity (real)</li>
</ol>
</li>
</ol>
</li>
</ol>
</li>
</ol>
&nbsp;

.

&nbsp;

<ul>
<li>[5 points]<em> Vertical Database Partitioning. </em>Database partitioning is an important technique that</li>
</ul>
divides large tables into smaller tables, which may help speed up queries. For this question you will create a new table cast_bio from the movie_cast table (i.e., columns in cast_bio will be a subset of those in movie_cast) Do not edit the movie_cast table. Be sure that when you insert into the new cast_bio that the values are unique. Please read <a href="https://www.sqlshack.com/database-table-partitioning-sql-server/">this page</a> for an example of vertical database partitioning.

cast_bio

<ol>
<li>cast_id (integer)</li>
<li>cast_name (text)</li>
<li>birthday (date)</li>
<li>popularity (real)</li>
</ol>
&nbsp;

<ol>
<li>[1 point] <em>Create indexes.</em> Create the following indexes for the tables specified below. This step increases the speed of subsequent operations; though the improvement in speed may be negligible for this small database, it is significant for larger databases.</li>
<li>movie_index for the id column in movies table ii. cast_index for the cast_id column in movie_cast table iii. cast_bio_index for the cast_id column in cast_bio table</li>
</ol>
&nbsp;

<ol>
<li>[3 points] <em>Calculate a proportion</em>. Find the proportion of movies having a score &gt; 50 and that has ‘war’ in the name. Treat each row as a different movie. The proportion should only be based on the total number of rows in the movie table. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a> Do <strong>NOT</strong> use the</li>
</ol>
ROUND() function as it does not work the same on every OS.

&nbsp;

Output format and sample value:

7.70

<strong>&nbsp;</strong>

<ol start="10">
<li>[4 points] <em>Find the most prolific actors</em>. List 5 cast members with the highest number of movie appearances that have a popularity &gt; 10. Sort the results by the number of appearances in descending order, then by cast_name in alphabetical order.</li>
</ol>
&nbsp;

Output format and sample values (cast_name,appearance_count):

Harrison Ford,2

&nbsp;

<ol>
<li>[4 points] <em>Find the highest scoring movies with the smallest cast</em>. List the 5 highest-scoring movies that have the fewest cast members. Sort the results by score in descending order, then by number of cast members in ascending order, then by movie name in alphabetical order. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a></li>
</ol>
&nbsp;

Output format and sample values (movie_title,movie_score,cast_count):

Star Wars: Holiday Special,75.01,12&nbsp; War Games,58.49,33

&nbsp;

&nbsp;

<ol>
<li>[4 points] <em>Get high scoring actors.</em> Find the top ten cast members who have the highest average movie scores. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a>
<ul>
<li>Sort the output by average score in descending order, then by cast_name in alphabetical order.</li>
<li>Do not include movies with score &lt;25 in the average score calculation. <img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Exclude cast members who have appeared in two or fewer movies.</li>
</ul>
</li>
</ol>
&nbsp;

Output format and sample values (cast_id,cast_name,average_score):

8822,Julia Roberts,53.00

<ol start="40">
<li>[6 points]<em> Creating views. </em><a href="https://sqlite.org/lang_createview.html">Create a view</a> <a href="https://www.w3schools.com/sql/sql_view.asp">(</a><a href="https://www.w3schools.com/sql/sql_view.asp">virtual table</a><a href="https://www.w3schools.com/sql/sql_view.asp">)</a> called good_collaboration that lists pairs of actors who have had a good collaboration as defined here. Each row in the view describes one pair of actors who appeared in at least 3 movies together AND the average score of these movies is &gt;= 40.</li>
</ol>
&nbsp;

The view should have the format: good_collaboration( cast_member_id1, cast_member_id2, movie_count, average_movie_score)

&nbsp;

For symmetrical or mirror pairs, only keep the row in which cast_member_id1 has a lower numeric value. For example, for ID pairs (1, 2) and (2, 1), keep the row with IDs (1, 2). There should not be any “self pair” where the value of cast_member_id1 is the same as that of cast_member_id2.

&nbsp;

&nbsp;

&nbsp;

<h1>Q3 [15 points] D3 (v5) Warmup</h1>
<strong>Read chapters 4-8 of Scott Murray’s </strong><a href="https://learning.oreilly.com/library/view/interactive-data-visualization/9781491921296/ch04.html#setup-chapter4"><strong>Interactive Data Visualization for the Web, 2nd edition</strong></a> (sign in using your GT account, e.g., jdoe3@gatech.edu). You may also briefly review chapters 1-3 if you need additional background on web development. <strong>This simple reading provides important foundation</strong> you will need for Homework 2. This question uses D3 version v5, while the book covers D3 v4. What you learn from the book is transferable to v5. In Homework 2, you will work with D3 extensively.

&nbsp;

&nbsp;

<h1>Q4 [5 points] OpenRefine</h1>
OpenRefine is a Java application and requires Java JRE to run. Download and install Java if you do not have it (you can verify by typing ‘java -version’ in your computer’s terminal or command prompt).

&nbsp;

<ol start="3">
<li>Watch the videos on <a href="http://openrefine.org/">OpenRefin</a><a href="http://openrefine.org/">e</a><a href="http://openrefine.org/">’</a><a href="http://openrefine.org/">s homepage for an overview of its features.</a> Then, <a href="http://openrefine.org/download.html">download</a> and <a href="https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions">install</a> OpenRefine release 3.3. Do not use version 3.4 (which is in beta status).</li>
</ol>
&nbsp;

<ol>
<li>Import Dataset
<ul>
<li><a href="https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions">Run</a> OpenRefine and point your browser at 127.0.0.1:3333.</li>
<li>We use a products dataset from Mercari, derived from a Kaggle <a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge">competition</a> (Mercari Price Suggestion Challenge). If you are interested in the details, visit the <a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge/data">data description page</a><a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge/data">.</a></li>
</ul>
</li>
</ol>
We have sampled a subset of the dataset provided as “properties.csv”.

<ul>
<li>Choose “Create Project” → This Computer → csv”. Click “Next”.</li>
<li>You will now see a preview of the data. Click “Create Project” at the upper right corner.</li>
</ul>
&nbsp;

<ol>
<li>Clean/Refine the data</li>
</ol>
&nbsp;

&nbsp;

<h1>Q5 [5 points] Introduction to Python Flask</h1>
<a href="https://flask.palletsprojects.com/en/1.1.x/">Flask</a> is a lightweight web application framework written in Python that provides you with tools, libraries and technologies to quickly build a web application. It allows you to scale up your application as needed.

&nbsp;

You will modify the given file:

<ul>
<li>wrangling_scripts/wrangling.py</li>
</ul>
