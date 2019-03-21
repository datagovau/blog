---
layout: post
title: WofG Web Reporting Service - Crawl Data
author: Gordon Grace
---

<p>The Digital Transformation Agency (DTA) works to deliver better, faster, simpler digital services. As part of our charter, we’ve undertaken work to examine the adoption of DTA’s guidance, products and services by agencies on publicly-facing Australian Government websites.</p>
<p>This service is in an early beta stage, and we’ve recently gathered over 5 million URLs as part of this exercise.</p>
<h2>The dataset</h2>
<p>The DTA has published the <a href="https://data.gov.au/dataset/whole-of-australian-government-web-crawl/?utm_source=blog&amp;utm_medium=web&amp;utm_campaign=gh">Whole-of-Australian Government Web Crawl dataset</a>&nbsp;on data.gov.au as Web ARChive (WARC) files, in parts and whole.</p>
<p>The dataset is large - the largest so far on data.gov.au. We’ve made it available both as a single 66GB WARC file, and as a series, split into 57 smaller WARC files. We’d suggest you download a&nbsp;<a href="https://data.gov.au/dataset/whole-of-australian-government-web-crawl/resource/5e0f3ec0-e6b0-4584-9633-307c0c978668/?utm_source=blog&amp;utm_medium=web&amp;utm_campaign=gh">smaller WARC file</a> (approx. 1.1GB) as a sample first.</p>
<p>WARC files are a recognised <a href="https://www.iso.org/standard/68004.html">ISO standard</a> for web archiving. We’re planning to filter these WARC files further to examine metrics like:</p>
<ul>
<li>Size (number of domains, websites and URLs published by a given agency or portfolio, seeded by the <a href="https://data.gov.au/dataset/australian-government-organisations-register/">Australian Government Organisations Register</a>)</li>
<li>Technology (examining whether agencies may be leveraging whole-of-government platforms, services and products, like <a href="https://www.govcms.gov.au">GovCMS</a>, <a href="https://beta.dta.gov.au/our-projects/google-analytics-government">GA360</a> and <a href="https://designsystem.gov.au">Design System</a>)</li>
<li>Quality (examining whether agencies are applying guidance from the <a href="https://guides.service.gov.au/content-guide/">Content Guide</a> or the <a href="https://www.dta.gov.au/what-we-do/policies-and-programs/style-manual/">Style manual</a>)</li>
<li>Accessibility (examining readability levels, machine-checkable portions of WCAG 2.1, use of CAPTCHA, and non-English usage)</li>
<li>Usage (to ensure, where feasible, &nbsp;any efforts spent on improvements are focused on the most-frequently-used content)</li>
</ul>
<p>Once filtered, each URL’s metadata will be injected as JSON into an ElasticSearch stack, visualised by Kibana. This will allow DTA’s policy and product owners to visualise and explore a large, complex time series of reporting metrics in a browser-based reporting environment, ensuring changes to products and policies are backed by sound, reproducible evidence.</p>
<h2><img alt="Flow diagram indicating current state of service (1-4) and next steps (5-9)" src="/assets/img/wogprocessgraph-750-1-4.png" width="100%">Future plans</h2>
<p>We’re planning to conduct three more crawls - one every 90 days - examining environmental changes over time.</p>
<p>There’s likely to be several other uses for this raw WARC store - in discussions with research organisations and universities, we’re anticipating that this snapshot will be used for reporting on Linked Data usage, the generation of government ontologies, and informing corpus work for Australian dictionaries.</p>
<p>As always, we’d love to hear your comments and feedback on this dataset - feel free to join the discussion at <a href="https://community.digital.gov.au/t/whole-of-australian-government-web-crawl-dataset/868">Open Data’s communities of practice</a>.</p>
<p><em>Gordon Grace is the product owner for the Whole-of-Australian Government Web Reporting Service at the Digital Transformation Agency.</em></p>
