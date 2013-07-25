wms_using_ssmis_browse
======================

Tools for serving ssmis browse files through WMS


## Files

( and rough order of execution )

* `update_confs`     -- [all] create per-set configuration files using hardcoded values
* `create_table`     -- [set] create tileindex table
* `update_vrts`      -- [set] create a GDAL virtual raster files (.vrt) for each browse file
* `update_tileindex` -- [set] update tileindex table
* `update_map`       -- [all] rebuild Mapserver map file

