ER Model:

See ER_Model_Draft.

```
Players:
		pid (player id, integer)
		name (player name, string)
		
Positions:
		posid (position id, integer)
		name (position name): PG, SG, SF, PF, C
		
Owners:
		oid (owner id, integer)
		name (owner name, string)
		
Conferences:
		name (conference name, string): Western, Eastern
		team num (number of teams in the conference): 15 for each
		
Coaches:
		coid (coach id, integer)
		name (coach name, string)
		
Teams:
		tid (team id, integer)
		name (team name, string)
		city (team city, string)
		court (team home court, string)
		
Statics:
		pid (player id, integer)
		pts (points, numeric)
		reb (rebounds, numeric)
		ast (assists, numeric)
		blk (block, numeric)
		stl (steal, numeric)
		pf (personal foul, numeric)
		to (turnover, numeric)
		FG% (field goal percentage, numeric)
		3P% (3 points percentage, numeric)
		FT% (free throw percentage, numeric)
		gp (game played, integer)
		min (minutes per game, numeric)
```

