Download Link: https://assignmentchef.com/product/solved-geologic-computing-homework-4-earthquakes-and-the-gutenberg-richter-law
<br>
Save your scripts to a directory named <em>Homework-4 </em>in your home account on the server computer in SCA 219 (131.247.211.166); do not email your answers. A short report should be typed and submitted in PDF format; drawings and/or flowcharts may be hand-drawn, just be legible! Multiple pages should be stapled together. Some additional explanation is helpful and often necessary for the person reading your assignment to understand exactly what you are doing and why. Assume that the person grading your assignment does not have a copy of the assignment. What is important here is that <em>(1) </em>you understand what you are doing, and <em>(2) </em>that you can communicate what you are doing to others.

<h3>Introduction</h3>

According to the Gutenberg-Richter Law, earthquakes should be distributed by frequency in a logarithmic manner. Often this distribution is expressed as the sum of magnitude 2 (M2) earthquakes being ten times more frequent than the sum of magnitude 3 (M3) earthquakes, the sum of M3 earthquakes being ten times more frequent than the sum of M4 earthquakes, etc. This is incorrect! In reality the Gutenberg-Richter Law deals with <em>bins</em>. For example, the M3 <em>bin </em>includes all earthquakes greater than or equal to magnitude 3; the M4 <em>bin </em>includes all earthquakes greater than or equal to magnitude 4. Note that according to the Gutenberg-Richter relationship, the cumulative number of earthquakes in the <em>bin </em>M3 should be approximately ten times more than the cumulative number of earthquakes in the <em>bin </em>M4. Given an earthquake catalog, it is possible to determine the frequency-magnitude relationship for earthquakes within some defined region during some specific period of time. The question is, does this frequency-magnitude relationship follow the Gutenberg-Richter Law?

<h2>Problem 1</h2>

Determine the frequency-magnitude relationship for earthquakes that occurred within the western US between 1980 and 2001 based on the earthquake catalog contained in the file, <em>earthquake catalog example.dat</em>. This file can be downloaded from the following link: <a href="ftp://gly6739:che309@131.247.211.166/Assignment4/earthquake_catalog_example.dat">ftp://gly6739:<span class="__cf_email__" data-cfemail="81e2e9e4b2b1b8c1b0b2b0afb3b5b6afb3b0b0afb0b7b7">[email protected]</span>/Assignment4/earthquake_catalog_example.dat</a><a href="ftp://gly6739:che309@131.247.211.166/Assignment4/earthquake_catalog_example.dat">.</a> The data in this catalog include earthquakes equal to or greater than M2. Does this frequency-magnitude relationship follow the Gutenberg-Richter Law?

Develop a flowchart by using the flowchart tools described in Homework 2. Make sure your flowchart diagrams a method for counting the number of earthquakes <em>greater than or equal to </em>each magnitude category or <em>bin </em>(as described above): M2, M3, M4, M5, M6, M7, M8, M9. One way to accumulate these counts is by using an array of 8 elements. Each element in the array will accumulate and hold the number of earthquakes that fit one magnitude category.

Write a Perl or Python script to implement this flowchart. Be sure to add comments to your script so the lines in your code can be related to your flow chart.

Execute the script to determine the frequency-magnitude relationship for the earthquakes found in the supplied data file: <em>earthquake </em><em>catalog example.dat</em>

Answer this question, do the earthquakes in the catalog follow a Gutenberg-Richter relationship?

1

Turn in the problem statement, your flowchart for solving this problem, your final counts of earthquakes in each magnitude bin (this should be the <em>output </em>of your script), and a paragraph discussing your results. Be sure to upload your script to your home account as described above.

<h2>Problem 2</h2>

The US Geological Survey (USGS) maintains an online earthquake catalog, Determine the frequency-magnitude relationship for a

subset of this USGS earthquake catalog and determine if the frequency-magnitude relationship follows the Gutenberg-Richter Law.

Navigate to this website and follow the directions below. Download and selection instructions are also listed on the USGS web site.

Navigate to the <em>Search Earthquake Catalog: </em>website:

<a href="http://earthquake.usgs.gov/earthquakes/search">http://earthquake.usgs.gov/earthquakes/search</a><a href="http://earthquake.usgs.gov/earthquakes/search">.</a>

Select Magnitude = 2.5+, and a Date &amp; Time range and Geographic Region that is of interest to you from the Basic Options section. Use the <em>Draw Rectangle on Map </em>button to fine-tune your area of interest. Click the <em>Search </em>button once your selections are made. Click on the number of <em>Search Results </em>and a <em>Download Earthquakes </em>button will appear.

Download the earthquake data for your selected area as a <em>CSV </em>file (a file of comma separated values). Notice that you can click on an individual earthquake location and get a pop-up box of information about that earthquake.

Modify and execute your script using the new data file that you just downloaded and determine the earthquake magnitude-frequency relationship for this dataset. You will need to modifying your script to read the <em>CSV </em>file format.

Answer these questions: <em>(1) </em>What area did you choose and why?                    <em>(2) </em>Does this new area from the USGS catalog follow a

Gutenberg-Richter relationship?

Turn in your problem statement, the name of your data file, your final count of earthquakes in each magnitude bin and a paragraph discussing your results. Be sure to include a copy of your modified script and your data file in your homework-4 directory of your home account as described above.

2