<html>

<h1>This dataset contains JSON files</h1>

<h2>Description</h2>
<ul>
<li> 
<h3>"labeled_neg.json" contain non security-related bug reports</h3>
Each JSON item is structured like
<ul>
<li> "id" : that contain the id of the bug report</li>
<li> "title" : that contain the title of the bug report</li>
<li> "desc" : that contain the description of the bug report</li>
</ul>
</li>
<li> 
<h3>"labeled_pos.json" contain security-related bug reports</h3>
Each JSON item is structured like
<ul>
<li> "id" : that contain the id of the bug report</li>
<li> "title" : that contain the title of the bug report</li>
<li> "desc" : that contain the description of the bug report</li>
</ul>
</li>

</ul>
<h2>Data collection</h2>
Concretely, the first part of security-relevant bug reports have been manually collected by relying on a publicly available security-commits dataset release in 2018 [17]. <br>
The second part of this dataset is collected by checking the tracking  systems  of  Mozilla  and  RedHat  projects. We were able to rely on the publicly-visible security tags put by development teams to collect 202 and 4 702 security-relevant bug reports, respectively from Mozilla and RedHat.<br>
The last part contains bug reports available in the dataset proposed by Mostafa et al (S. Mostafa, X. Wang, Automatic identification of security bug reports via semi-supervised learning and cve mining).
<h2>Application</h2>
  Early Detection of Security-Relevant Bug Reports using Machine Learning: How Far Are We?
</html>
