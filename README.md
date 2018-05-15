A basic emojis data package.

# Data
Dataset contains, emoji copdepoints as per unicode standards, english names, emoji sequences of various types and emoji groups and sub groups.

# Preparation
Python version: 3.6
Preparation was carried out keeping in view the utilization and reuzibility of datapackage.json and code respectively. For this purpose couple of script files (`process.py` and `wrapper.py`) were included in scripts folder. `wrapper.py` has the abstract class with generic methods to download raw files and appending data to CSVs. `process.py` has the concrete class, implementing the `setData()` method.

# License
Please follow [this]("http://www.unicode.org/copyright.html#License") for License information
