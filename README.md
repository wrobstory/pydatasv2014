pydatasv2014
============

PyData Silicon Valley 2014 Code + Presentation

If using nbviewer, I would recommend using the gist host of this repo, as the maps link/work properly: 

http://nbviewer.ipython.org/gist/wrobstory/1eb8cb704a52d18b9ee8/Up%20and%20Down%20PyData%202014.ipynb

Vincent, Folium, Bearcart, and Sticky all need to be on latest Github master- I will push to PyPi very shortly to enable pip-ing. 

This is the source of the USGS/FAA dataset: http://pubs.usgs.gov/ds/817/downloads/

Here is the complete dependency list: 

```
Flask==0.10.1
Jinja2==2.7.2
Markdown==2.4
MarkupSafe==0.21
PyYAML==3.11
Pygments==1.6
Sphinx==1.2.2
Werkzeug==0.9.4
backports.ssl-match-hostname==3.4.0.2
-e git+https://github.com/wrobstory/bearcart@8a65684830f4f0d63b455120ae329c3ebb479572#egg=bearcart-master
bokeh==0.4.4
brewer2mpl==1.4
colorama==0.3.0
docutils==0.11
-e git+https://github.com/wrobstory/folium@ddb08c9b509df5f8c48ac8531f6ee146e9142778#egg=folium-master
gevent==1.0
gevent-websocket==0.9.3
ggplot==0.5.2
gnureadline==6.2.5
greenlet==0.4.2
ipdb==0.8
ipython==2.0.0
itsdangerous==0.24
matplotlib==1.3.1
mock==1.0.1
mpld3==0.1
nose==1.3.1
numpy==1.8.1
numpydoc==0.4
pandas==0.13.1
patsy==0.2.1
pyparsing==2.0.2
pystache==0.5.3
python-dateutil==2.2
pytz==2013b
pyzmq==14.1.1
redis==2.9.1
requests==2.2.1
scipy==0.13.3
seaborn==0.3
six==1.6.1
statsmodels==0.5.0
-e git+https://github.com/wrobstory/sticky@115f5fbaca00b54836daa0599c5e50431e4a857e#egg=sticky-master
tornado==3.2
-e git+https://github.com/wrobstory/vincent@f3bcabd772fc7ccb1d92d34777d4aedc7547ca00#egg=vincent-master
websocket==0.2.1
wsgiref==0.1.2
```




