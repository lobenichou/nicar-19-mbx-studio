# 🗺️ The Power of Mapbox Studio 🗺️

**Twitter:** [@lobenichou](https://twitter.com/loBenichou/)

**Presentation and Data:** [bit.ly/mapbox-nicar-2019](http://bit.ly/mapbox-nicar-2019)

**Mapbox sign-up:** [bit.ly/mapbox-signup](http://bit.ly/mapbox-signup)

# What is Studio?

Style by Lo:
![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1551852373613_Screen+Shot+2019-02-28+at+8.32.31+AM.png)

Style by Jonni Walker:
![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1551852358959_Screen+Shot+2019-02-27+at+4.37.11+PM.png)

Style by Lo:
![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1551851311199_Screen+Shot+2019-02-28+at+8.32.57+AM.png)



Mapbox Studio is a a powerful tool to help you optimize and visualize your data, and customize your maps.

🚫 Mapbox Studio does NOT allow you to add interactivity


# ☘️ The Mapbox Studio Ecosystem


Dataset  → Tileset → Styles (→ *Libraries)*


---

**Dataset**: Edit your data 📝
**Tileset**: Bake your data into Vector tiles or upload rasters 🗾
**Styles**: Customize your style in the Studio interface 🎨
(***Libraries****: add your style to applications using one of our Mapbox libraries 👩‍💻 )*


# 🤓 This Session
~~Dataset~~ → **Tileset → Styles** ****→ ~~Mapbox GL JS~~

# Tilesets


- Lightweight collections of vector data
- Optimized for rendering
- **Not editable** but can be styled in the Mapbox Studio style editor.


# 📂 Files and Uploads

🔗  [Mapbox upload limits](https://docs.mapbox.com/help/troubleshooting/uploads/#accepted-file-types-and-transfer-limits)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1552098288629_Screen+Shot+2019-03-08+at+6.24.38+PM.png)

# Mapbox-Provided Tilesets

🔗 [Mapbox tilesets](https://studio.mapbox.com/tilesets/)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1552098955085_Screen+Shot+2019-03-08+at+6.35.38+PM.png)


# 🖼️ Styles

🔗 [Mapbox Studio](https://studio.mapbox.com/)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1552100889034_Screen+Shot+2019-03-08+at+7.05.58+PM.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1552100918312_Screen+Shot+2019-03-08+at+7.06.08+PM.png)



# Studio Dashboard

🔗 [Mapbox Studio](https://studio.mapbox.com/)


![](https://lh6.googleusercontent.com/z9OQ_4i4H9FHxMXbfcmIZC057Y3tA5oAQQvvQCoDjTfzcwjv_lF0H91mRQKLuYKW91pUI2CeJVYHnAmU8_IDaUcTzp9SEqVxN1H0Lr9-FLrqydnYyRIcb0JaxZiJkBhyGh1JdLawHRk)

# 👐 Hands-on time
- Open the github repo
- Download it


# 🛠️ What we’ve learned
- Upload a dataset to Studio
- Add the tileset to a style
- Create a new style using our core styles or a designer style
- Filters
- Style data
- Layers
- Terrain
- Mask
- Polygons, lines, points, symbols


# ⚙️ Resources

🔗 [The Guide To Map Design](https://www.mapbox.com/map-design/) by [Amy Lee Walton](https://twitter.com/amyleew)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_23962B8C37497393D9B6FF3F8168412ECF2402DD7564ED836A55E1EC6E22EE20_1552101040477_Screen+Shot+2019-03-08+at+7.10.28+PM.png)


🔗 [Our awesome glossary](https://docs.mapbox.com/help/glossary/) from our Doc Queens 👑


----------


## Session extras:

These are the three main function of Studio. If you are using Mapbox Studio you are trying to do one of these three things:

- Create and maintain datasets
- Create tilesets
- Create and design map styles


### Tileset:

A [**tileset**](https://www.mapbox.com/help/define-tileset) is a collection of raster or vector data broken up into a uniform grid of square tiles at up to 22 preset zoom levels. Tilesets are used in Mapbox libraries and SDKs as a core piece of making maps visible on mobile or in the browser; they are also the main mechanism we use for determining [map views](https://www.mapbox.com/help/define-map-view/).

Tilesets are made up of  vector tiles and are developed for caching, scaling and serving map imagery rapidly.

Mapbox web and mobile-ready vector tiles are 75% smaller than a raster tilesets. This results in fast, smooth zooming from the worldview of a map down to street-level detail.

Tilesets are highly cacheable and load quickly. Vector tiles are developed for caching, scaling and serving map imagery rapidly – to vector data.

As the name suggests, vector tiles contain vector data instead of the rendered image. They contain geometries and metadata – like road names, place names, house numbers – in a compact, structured format. Vector tiles are rendered only when requested by a client, like a web browser or a mobile app. Rendering happens either in the client ([Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/), [Mapbox iOS SDK](https://www.mapbox.com/developers/#gl-ios), [Mapbox Android SDK](https://www.mapbox.com/developers/#android)) or on the fly on the server ([map API](https://www.mapbox.com/developers/api/maps/)).


### Mapbox File types:

#### CSV

![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101439099_Cdb2Yk26asXjvd1a5qozUyhXW78FyAqh7LgwASVZljjIBhk-V9XgsFE2O1PXoQWVYMRXlq6ZT28IEjpk_nps97VUbcoUE8jOI9zJcwHQ_1WFgwVPWh7ZZyArl4yQbKSPoNZuCJ21MUw.png)


The **CSV** (comma-separated values) format is common for table data, like the kind you may use in Excel or other spreadsheets. CSV files aren’t necessarily mappable unless they contain geographic information (like latitude and longitude).
When uploading CSV files, keep the following in mind:

- Check out the [Mapbox Uploads API documentation](https://docs.mapbox.com/api/) for the current size limit for CSV files.
- CSV files must be in UTF-8 encoding.
- CSV files must contain coordinates (latitude and longitude) when uploading in Mapbox Studio or Mapbox Studio Classic.
- CSV files are for point data only.

#### GeoJSON

![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101520402_0SVEgCPUYw-Iq-mhsUDcvmStyYOz4kTFVUYgAVMQ7T16k7IALQlrxYSBHsdSeJRVWsQEFTxxQusW5RGZGUvuVVdTgQcO6Go-2AAzWi94cE5b-aoCAXXjSQd9qggbjrsJgIIBg2QV_N4.gif)


[**GeoJSON**](http://geojson.org/) is a file format for map data served by Mapbox [web services and APIs.](https://docs.mapbox.com/api/) As a subset of the [JSON](https://www.json.org/) format, it can be parsed in modern software and native to the JavaScript language.
There are several open source tools for converting other geospatial data formats to GeoJSON. A few faves:

- [togeojson](https://www.npmjs.org/package/togeojson), a node package for converting KML and GPX (XML formats).
- [ogr2ogr](http://www.gdal.org/ogr2ogr.html), the ultimate 40-in-1 vector data conversion tool.
- [geojson.io](http://geojson.io) for creating, converting, and editing GeoJSON.


#### MBTiles
![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101614814_uKV9VZgC77uTUC697Aek2rOP_BkWUxB9hDFQbS-jizVvqxX0GFpUsUH_5Es0J2eOf-PpgZ9xTccEctDOFw1PWmB-7tKsRBlRvSwa_6r6Idd_YQRn172uxRP2_FedOHFPReyAOXBuhqM.png)


**MBTiles** is a file format for storing [tilesets](https://www.mapbox.com/help/define-tileset). It’s designed so that you can package the potentially thousands of files that make up a tileset and move them around, eventually uploading to Mapbox or using in a web or mobile application. [MBTiles is an open specification](https://github.com/mapbox/mbtiles-spec) and is based on the [SQLite](https://sqlite.org/) database. MBTiles can contain raster or vector tilesets.

#### KML
![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101717660_JHkQUFnA_E4SoLBPpRmx6EXrdnvoGxi9cL4ggnV60HT38fvqTZ6MaCrz6XREULxPv5H6X_au2uGUjnCnR8iz38olTJmKjBmDQ5RQgSGisZm0lG5xjfzZfVau4wxsr42kLVRkxepf37o.png)


[**KML**](https://developers.google.com/kml/documentation/kmlreference) is a file format that is like [GeoJSON](https://www.mapbox.com/help/define-geojson/), but used more commonly in Google products. Like GeoJSON, it can store points, lines, polygons, and other vector data. Unlike GeoJSON, it’s based on [XML](https://en.wikipedia.org/wiki/XML), rather than [JSON](http://www.json.org/). When uploading KML, please note that Mapbox does not support any KML extensions.


#### GPX
![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101729059_sYeff4-sRnxPY6oiQu5RWpKqOktIVkab-gZlqcdtQQr1p1jIfA8o0nt3syQtU4blRZwM3Q1X8tbBfd90-XLfGwsNlvjXwEgKQ_MkT9tpKUzwz0XoaiKNhbWd5INmcqelMh0ODO4_h6E.png)


[**GPX**](http://en.wikipedia.org/wiki/GPS_eXchange_Format), or GPS eXchange format, is a data format commonly created from GPS receivers.
You can upload GPX files to your Mapbox account to use in a custom map style. Please note that Mapbox does not support values along lines (for example, elevation and time at various points along a jogging route). A GPX file with values along a line can be uploaded, but Mapbox will ignore any data along the line.


#### Shapefile
![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101803249_Screen+Shot+2019-03-08+at+7.23.13+PM.png)


A **shapefile**, also known as an [ESRI shapefile](https://en.wikipedia.org/wiki/Shapefile), is a file format for storing geographic vector data.
When uploading shapefiles, keep the following in mind:

- Check out the Mapbox Uploads API documentation for the current size limit for shapefiles. Note that this limit applies to the shapefile’s uncompressed size, not the size of the compressed zip.
- Shapefiles are composed of several individual files, which should be combined into a single zip file before uploading. Of these files, Mapbox can read shp, shx, dbf, prj, and index files. Any other files you upload with your zip file will be ignored.

#### TIFF

![](https://d2mxuefqeaa7sj.cloudfront.net/s_50EEDCA7947791B75F33CD388F18E96B2D817BF4D6A654F9CA53F7D29F431CBD_1552101864821_download.png)


A **TIFF**, or sometimes TIF, is a file format for saving raster images. With Mapbox, a TIFF is often a GeoTIFF, meaning the file is embedded with georeferencing information.
You can upload TIFF files as [tilesets](https://www.mapbox.com/help/define-tileset) in Mapbox Studio and use them in the Mapbox Studio style editor. When uploading a TIFF file, keep in mind the [current size limit for TIFF files](https://www.mapbox.com/help/upload-troubleshooting).
