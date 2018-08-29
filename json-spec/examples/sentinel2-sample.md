Create an Item per day 
type - Feature
id - metadata.xml /Level-2A_Tile_ID/General_Info/TILE_ID
// convert these from UTM
bbox = [ll_lon, ll_lat, ur_lon, ur_lat]
   /Geometric_Info/Tile_Geocoding/Geoposition 
geometry/type = Polygon
geometry/coordinates = [[[(ll_lon, ll_lat), (lr_lon, lr_lat), (ur_lon, ur_lat), (ul_lon, ul_lat), (ll_lon, ll_lat) ]]]

* assets
    * metadata
    * thumbnail    

asset fields
        * href s3 URI
        * name e.g., "Visual RGB Image", "Analytic 4-band Image"
        * format geotiff, json, xml, jp2, hdf4
        * eo:bands: ["1"]
/properties/datetime - /Level-2A_Tile_ID/General_Info/SENSING_TIME      

eo:cloud_cover /Level-2A_Tile_ID/Quality_Indicators_Info/Image_Content_QI/CLOUDY_PIXEL_PERCENTAGE 
/Level-2A_Tile_ID/Geometric_Info/Tile_Angles/Mean_Sun_Angle/ZENITH_ANGLE
eo:sun_azimuth /Level-2A_Tile_ID/Geometric_Info/Tile_Angles/Mean_Sun_Angle/AZIMUTH_ANGLE

    "eo:gsd": 30.0,
    "eo:off_nadir" : 0.000,
    "eo:sun_azimuth" : 176.091667178268,
    "eo:sun_elevation" : 59.21424700,
