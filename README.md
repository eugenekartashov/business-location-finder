# Business Place Finder

The source code I wrote for the article [https://medium.com/@eugenekartashov/%D0%B2%D1%8B%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC-%D0%BC%D0%B5%D1%81%D1%82%D0%BE-%D0%B4%D0%BB%D1%8F-%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81%D0%B0-%D1%81-%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0-%D0%B3%D0%B5%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D0%B2-python-cdd01bbbfcc0]("Selecting a location for business using Python geodata analysis"** (on Russian).)

It's goal is to find a suitable district for microbusiness in the city based on geospatial data on competitors and other factors that are openly available.

Source of geographic data: Yandex.maps parsed data
Data cleaning: [https://jsonbeautifier.org/json-formatter/](JSON Beautifier) + Pandas
Data processing and analysis: Pandas, GeoPandas
Data visualization: Bokeh