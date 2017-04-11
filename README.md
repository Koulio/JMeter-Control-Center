# Description
Jmeter Load Test Online Monitor

Online web-application for analyzing JMeter test results and monitoring the running tests.
Designed for integration with Jenkins. In post-job script need to include script datagenerator_linux.py which will populate database with all necessary data.


# Create dynamic report for tests
![alt tag](https://github.com/v0devil/jltom/blob/master/pics/report.png)

# Test results
Get fancy good-readable aggregate table for the test with graphs for every executed action:
![alt tag](https://github.com/v0devil/jltom/blob/master/pics/aggregate.png)

Get response times, rps, errors data from test:
![alt tag](https://github.com/v0devil/jltom/blob/master/pics/graph.png)

# Online test monitoring
Provides online test monitoring, reads .csv result files and builds graphs online without Graphite,plugins,etc:
![alt tag](https://github.com/v0devil/jltom/blob/master/pics/online.png)

# JLTOM 
Jmeter Load Test Online Monitor

Written on python.

Requirements

python=2.7

django_debug_toolbar==1.7

Django==1.10.5

matplotlib==1.4.3

numpy==1.10.0

pandas==0.17.0

psutil==5.2.1

matplotlib==1.4.3

SQLAlchemy==1.1.3


Uses c3/j3 graphs 
For data storage uses Postgres.

# Start

nohup python manage.py runserver 8888 &
