# Workshop: Critical Approach to Data Visualization
This repo is the home for DataLab's Data Feminism Research and Learning Cluster led "Critical Approach to Data Visualization" workshop which unpacks the subjective process of data visualization and its relationship to concepts of diversity, equity and inclusion. This workshop critically explores how data can be used to uphold and perpetuate, or quantify and demonstrate structural oppression. Through this workshop learners practice the technique of “data visceralization,” the process of experiencing differences in data and understanding them viscerally,

### Maintainers
* Pamela Reynolds, UC Davis DataLab

### Contributors
* Emily Merchant, UC Davis Science and Technology Studies
* Lindsay Poirier, UC Davis Science and Technology Studies

### Links
* 2021 workshop offering reader: https://ucdavisdatalab.github.io/workshop_critical_data_viz/
* 2021 workshop offering event webpage: https://datalab.ucdavis.edu/eventscalendar/critical-approach-to-data-visualization/

### Protocols

The course reader is a live webpage, hosted through GitHub, where you can enter curriculum content and post it to a public-facing site for learners. Supplementary examples for other readings are also appropriate, but please refrain from using it as a space to host slides.

To make alterations to the reader, download this repo and open both index.Rmd and gen_html.R. You should enter your text, links, and any supporting media directly into index.Rmd; use gen_html.R (which is a single line of code) to generate a new index.html page. This latter file lives under the docs directory. Once you have made your changes, commit and push both index.Rmd and docs/index.html. The live web page will update accordingly.

Follow the established style and formatting conventions in index.Rmd, including those for linking to media on the ds.lib server. On the ds.lib server, the course media directory is in the public-facing portion of the DataLab website (ds.lib.ucdavis.edu). Outbound URLs that point to course media should be given their own, sequentially numbered variable in the header (url1, url2, ... url26, etc.) and should then be called from that variable in the body text of index.Rmd.

### Issue tracking:

If, as you're teaching, you notice students having trouble with a sequence of commands, a workflow configuration, or the particular setup of their machines, please make note of this. We'd like to keep track of these problems so that the next time this content is taught, they can be used as a reference. Please be mindful that the issues are publically hosted; specific examples and any PII are prohibited.
