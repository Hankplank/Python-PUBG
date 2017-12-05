# PYPUBG
Python wrapper for the PUBG API found at https://pubgtracker.com/site-api
Quick wrapper for the API wrote
Example uses:
```python
   api = pubgapi.PUBGAPI(api_key_here), season_here)  Creates new API object using strings with API key and the pubg season you want to gather stats for
   api = pubgapi.PUBGAPI(00000000000000, '2017-pre6') 
   player = PLAYER(player_name, player_region, player_mode, fpp)
   player = PLAYER('almostfamous', 'na', 'squad', 'tpp')
   player = PLAYER('almostfamous', 'na', 'squad', 'fpp')```
