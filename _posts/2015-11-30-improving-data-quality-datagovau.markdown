---
layout: post
title: Improving data quality on data.gov.au
author: Pia Waugh
---

<p>One of the greatest challenges facing data users when trying to use government data has been the extraordinary diversity in data types, formats, quality, currency and other attributes of the data. In the first instance just finding data that suits the user’s need can be hard, then it is often not machine readable, or up to date. Even the most committed data users can give up at some point.</p>
<p>data.gov.au has been on a journey over the past two years. Not just to publish more and higher quality data, while making public data more easily discoverable across jurisdictions, but to improve data literacy, internal publishing practices and the broader public sector culture around data. We are proud of what we have achieved to date. &nbsp;More agencies are now publishing more data more often, and we are seeing higher levels of data literacy skills, outside of the traditional data specialists, and this is contributing to a greater data-driven public service. There remains much more to be done and with the new Public Data agenda being driven from the Department of Prime Minister and Cabinet we intend to take data.gov.au to the next level.</p>
<p>We want to help data users quickly identify what datasets are of high quality and raise private sector confidence in building commercial products on government data. At the same we’ll help agencies identify specifically how to improve the quality of the data and APIs they publish. Below is a draft methodology for measuring some data quality aspects that data users care about. With your feedback, we will implement this over the coming months and then iterate as required.</p>
<p>This Data Quality Framework will apply to all Federal Government datasets. We would also be happy to work with any of our State and Territory colleagues should they wish to be involved. Our intention is to implement an almost fully automated approach, making it a light touch approach for Data Custodians. Quality systems that rely on human input are generally not consistent across large catalogues whereas an automated approach would ensure a more consistent approach across the entire collection.</p>
<p><strong>Data Quality Framework</strong></p>
<p>Below is our draft methodology to measure the most basic aspects of data quality that data users care about. &nbsp;With your help this foundation can be built upon over time, including the possibility of adding specialist data quality metrics for particular data types (spatial, health, statistics) later on. &nbsp;The following four criteria would be rated out of 5 stars and clearly visible on each dataset:</p>
<ul>
<li>
<p><strong>Format quality out of 5 stars</strong> – starting with a localised version of the <a href="https://github.com/okfn/ckan-barnet/wiki/Data-quality">Tim Berners-Lee’s (TBL) &nbsp;5 star plugin used by the UK</a> to give a basic understanding of data formats. We will tweak the model slightly to take into account that a machine readable XLS is just as good as machine readable CSV from a data user perspective. Under the default model, a non-machine readable CSV would get a higher score than a machine readable XLS which is suboptimal from a data user’s perspective. We will iterate where useful.</p>
</li>
<li>
<p><strong>Metadata quality out of 5 stars</strong> – we intend to check the metadata that matters most to data users. &nbsp;As a starting point we intend to award a star for meeting each of the below:</p>
<ul>
<li>
<p>whether the last actual update aligns to the update schedule indicated in the metadata;</p>
</li>
<li>
<p>whether a valid spatial context is indicated;</p>
</li>
<li>
<p>whether any data models, vocabularies, ontologies or other documentation is provided anywhere in the dataset; and</p>
</li>
<li>
<p>whether the licence is one recognised by the Open Definition as an open licence (<a href="http://opendefinition.org/licenses/">http://opendefinition.org/licenses/</a>).</p>
</li>
</ul>
</li>
<li>
<p><strong>API quality out of 5 stars </strong>–APIs are critical for serious data users to build persistent analysis, applications or visualisations on government data. So to raise public confidence in using government data, we need to start looking at API quality. We actively host tabular, spatial and some relational data on the data.gov.au platform. We are looking at a 5 star quality ranking based on latency and uptime.</p>
</li>
<li>
<p><strong>Public quality score out of 5 stars</strong> –The final quality indicator will give you, the data user, a 1-5 star ranking.</p>
</li>
</ul>
<p>We welcome your feedback to this rating methodology and are keen to read your views in the comments below.</p>
<p>Please note, our <a href="https://toolkit.data.gov.au/index.php?title=Discovering_Metadata#Discovering_Metadata" class="toc-filter-processed">metadata standard for data.gov.au</a> is a DCAT profile mapped to ISO19115 (spatial) and a local metadata standard called AGLS. The schema is now used by most Australian Government portals at the Federal and Regional levels and has been mapped to the <a href="http://ands.edu.au/">Australian National Data S</a>ervice.</p>
<p><strong>Background reading</strong></p>
<p>We have considered the following quality frameworks in preparing the above:</p>
<ul>
<li>
<p>The <a href="http://webfoundation.org/2014/06/towards-common-methods-for-assessing-open-data/">Common Assessment Framework for Open Data</a> by the Web Foundation – useful indicators across a broad range of indicators. The quality metrics and performance metrics above are nicely aligned to this work, but a lot of the current version would require human intervention or interpretation, so we will look to extend future iterations on the work as it matures.</p>
</li>
<li>
<p>The <a href="http://www.abs.gov.au/websitedbs/D3310114.nsf/home/Quality:+The+ABS+Data+Quality+Framework">ABS Data Quality Framework</a> – largely focused on metadata quality and statistics specific quality indicators. We have considered the metadata aspects in the framework above and we will consider this Framework for statistical specific datasets in future iterations.</p>
</li>
<li>
<p>Draft quality framework work being done to look at spatial data by the <a href="http://www.crcsi.com.au/">CRC for Spatial Information</a> – we will consider this Framework for spatial specific datasets in future iterations.</p>
</li>
<li>
<p>The <a href="https://theodi.org/guides/maturity-model">Open Data Maturity Model</a> by the Open Data Institute – relies on a lot of useful but interpretative analysis by humans. We will consider this Model in future planning.</p>
</li>
</ul>
