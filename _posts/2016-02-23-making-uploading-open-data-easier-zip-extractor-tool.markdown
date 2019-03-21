---
layout: post
title: Making Uploading Open Data Easier - Zip Extractor Tool
author: Allan Barger
---

<p>The zip extractor tool gives data custodians a more effective avenue to publish open data. This <em>opt-in</em> tool will automatically search for and extract ‘<em>interesting</em>’ files from zipped resources. Nominated interesting files currently include;&#8203;</p>
<ul>
<li>CSV</li>
<li>XLS</li>
<li>XLSX</li>
<li>JSON</li>
<li>GeoJSON</li>
<li>SHP</li>
<li>KML</li>
</ul>
<p>The zip extractor follows some simple rules;</p>
<ol>
<li>Multiple zip files within a single dataset can be enabled for automatic extraction.</li>
<li>There must be more than one interesting file per zip for the extractor to run.</li>
<li>If the zip extractor encounters a folder in a zipped file with ‘interesting’ files inside it will extract the folder as an additional zipped resource.</li>
<li>Any additional extracted files will be placed at the bottom of the resource list of a dataset.</li>
<li>New resource names will reflect their filename.</li>
</ol>
<p>Extracting ‘<em>interesting’</em> files allows data.gov.au to create APIs for correctly formatted data files.</p>
<p>This tool improves workflow for data custodian when adding datasets with a large number of resource files. Instead of uploading all files individually, users can combine all related files into a single zipped upload. The tool will then automatically extract any interesting files.</p>
<p>The zip extractor is a scheduled task and runs daily across new resources at 18:00 AEST.</p>
<p><strong>Enabling Zip Extractor Tool</strong></p>
<p>The zip extractor tool can be enabled for new resources at the Add Data screen by selecting the ‘Extract Resources from Zip Files’ tick box.</p>
<p>For existing resources users can enable the extractor tool by;</p>
<ol>
<li>Browsing to the zipped resource</li>
<li>Clicking the Manage button</li>
<li>Selecting the <em>Extract Resources from Zip Files</em> tick box</li>
</ol>
<p>The extraction of the files inside the zip will be queued for the next scheduled run and will not happen right away.</p>
