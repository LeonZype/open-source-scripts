# FILMHUB (FH) PACKAGE INGESTOR (FPI)
#### Filhmub > MRSS Transformer > Configuration JSON
This script is available as is and without warranty.

- Author: Scott Cliburn
- open-source/FilmhubIngestor

#### CONFIGURATION
{
    "config_name": "default",
    "data_folder": "data/default/",
    "new_data_onrun": "false",
    "sess_data_folder": "sessions/",
    "root_prefix": "",
    "local_s3": "local",
    "http_root_prefix": "https://zype-filmhub.s3.us-west-2.amazonaws.com/",
    "http_uri_prefix": "https://zype-filmhub.s3.us-west-2.amazonaws.com/",
    "s3Bucket": "zype-filmhub",
    "dirLocation": "dir",
    "dirFile": "s3_dir",
    "badskuidsFile": "invalid_skuids.json",
    "skuidsFile": "valid_skuids.json",
    "allskuidsFile": "all_skuids.json",
    "objectsFile": "all_objects.json",
    "yamlFile": "_yaml.yml",
    "xmlItemFile": "_xmlitem.json",
    "xmlItemSeriesFile": "_series_xmlitem.json",
    "xmlItemTrailerFile": "_trailer_xmlitem.json",
    "mrssXMLItem": "_xml.xml",
    "yamlJSONFile": "_yaml.json",
    "dir": {
        "YMLJSON": "yaml_json/",
        "YAML": "yaml/",
        "XMLITEMS": "xmlitems/",
        "XMLSERIESITEMS": "xmlitems_series/",
        "XMLTRAILERITEMS": "xmlitems_trailers/",
        "DIRLIST": "dirlist/",
        "OBJECTS": "objects/",
        "SKUIDS": "skuids/",
        "BADSKUIDS": "badskuids/",
        "MRSSITEMS": "mrssitems/",
        "MRSSIMPORT": "mrssimport/",
        "POSTINGEST": "postingest/"
    },
    "video_ext": [".mov", ".mp4"],
    "image_ext": [".png", ".jpg"],
    "cc_ext": [".srt"],
    "yaml_ext": ["yaml", ".yml"],
    "genre_folders": {
        "Action/Adventure": "mrssitems/actionadventure/",
        "Animation": "mrssitems/animation/",
        "Comedy": "mrssitems/comedy/",
        "Crime": "mrssitems/crime/",
        "Documentary": "mrssitems/documentary/",
        "Fantasy": "mrssitems/fantasy/",
        "Horror": "mrssitems/horror/",
        "Informational & Educational": "mrssitems/infoandedu/",
        "Musical/Dance": "mrssitems/musicaldance/",
        "Music & Performances": "mrssitems/musicperformance/",
        "Mystery": "mrssitems/mystery/",
        "Reality Show": "mrssitems/realityshow/",
        "Sci-Fi": "mrssitems/scifi/",
        "Sport & Fitness": "mrssitems/sportsfitness/",
        "Thriller": "mrssitems/thriller/",
        "Unknown": "mrssitems/unknown/",
        "War": "mrssitems/war/",
        "Western": "mrssitems/western/"
    },
    "s3_config_dir": "s3conf/"
}
