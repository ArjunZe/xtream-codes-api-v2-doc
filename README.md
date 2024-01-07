# xtream-codes-api-v2
Final public Official Xtream-Codes API V2 documentation as published on the now defunct xtream-codes.com forum

Original URL (was):
https://forum.xtream-codes.com/topic/3511-how-to-player-api-v2/

# API Documentation

## Authentication

 > player_api.php?username=X&password=X

## GET Live Stream Categories

 > player_api.php?username=X&password=X&action=get_live_categories

## GET VOD Stream Categories

 > player_api.php?username=X&password=X&action=get_vod_categories

## GET SERIES Categories

 > player_api.php?username=X&password=X&action=get_series_categories

## GET LIVE Streams

 > player_api.php?username=X&password=X&action=get_live_streams (This will get All LIVE Streams)
 
 > player_api.php?username=X&password=X&action=get_live_streams&category_id=X (This will get All LIVE Streams in the selected category ONLY)

## GET VOD Streams
 
 > player_api.php?username=X&password=X&action=get_vod_streams (This will get All VOD Streams)
 
 > player_api.php?username=X&password=X&action=get_vod_streams&category_id=X (This will get All VOD Streams in the selected category ONLY)

## GET SERIES Streams

 > player_api.php?username=X&password=X&action=get_series (This will get All Series)
 
 > player_api.php?username=X&password=X&action=get_series&category_id=X (This will get All Series in the selected category ONLY)

## GET SERIES Info

 > player_api.php?username=X&password=X&action=get_series_info&series_id=X

## GET VOD Info

 > player_api.php?username=X&password=X&action=get_vod_info&vod_id=X (This will get info such as video codecs, duration, description, directors for 1 VOD)

## GET short_epg for LIVE Streams (same as stalker portal, prints the next X EPG that will play soon)
 
 > player_api.php?username=X&password=X&action=get_short_epg&stream_id=X
 
 > player_api.php?username=X&password=X&action=get_short_epg&stream_id=X&limit=X (You can specify a limit too, without limit the default is 4 epg listings)

## GET ALL EPG for LIVE Streams (same as stalker portal, but it will print all epg listings regardless of the day)

 > player_api.php?username=X&password=X&action=get_simple_data_table&stream_id=X

## Full EPG List for all Streams

 > xmltv.php?username=X&password=X
