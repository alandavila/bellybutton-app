# Belly Button App
Belly button microbial diversity dashboard.
### Web site: https://bellybutton-app.herokuapp.com

# Usage

Select belly button sampled by sample id using the dropdown box.

![dropdown](resources/Dropdown_btn.png)

* The meta data table displays information of the person that corresponds to the selected sample
* The pie chart show the relative abundance of the different king of microbes (operational taxonomic units or OTUs) found in the sample
* The scatter chart shows the values frequency for each OTU in the given sample. Each OTU ID is plotted in different color and the marker's size correspond to the OTU frequency.

![dashboard](resources/dashboard_view.png)

Original study-data come from the [Rob Dunn Lab ](http://robdunnlab.com/projects/belly-button-biodiversity/)

# App requirements.

## Back End

### Python modules (requirements.txt)

  * certifi==2018.4.16
  * click==6.7
  * Flask==1.0.2
  * gunicorn==19.8.1
  * itsdangerous==0.24
  * Jinja2==2.10
  * MarkupSafe==1.0
  * numpy==1.14.2
  * pandas==0.22.0
  * python-dateutil==2.7.2
  * pytz==2018.4
  * six==1.11.0
  * SQLAlchemy==1.2.7
  * Werkzeug==0.14.1
  * wincertstore==0.2

## Front End

### Bootstrap v3.3.7
  https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
  * Copyright 2011-2017 Twitter, Inc.
  * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
  * (Glyphiconas as available from bootstrap. http://glyphicons.com/)

### Plotly
  * https://cdn.plot.ly/plotly-latest.min.js
