# Everton-17-18
A datasets of Everton 17-18 results
1) passingevents.csv

~~~~~~~~~~~~~~~
MatchID
A unqiue identifier for each match played during the season (see matches.csv).

TeamID
A unqiue identifier for the team involved in the pass (either 'Everton' or OpponentID from matches.csv).

OriginPlayerID
A unqiue identifier for the Player at the origin of the pass.

DestinationPlayerID
A unqiue identifier for the Player at the destination of the pass.

MatchPeriod
The half in which the event took place.  '1H': first half, '2H': second half

EventTime
The time in seconds during the MatchPeriod (1st or 2nd half) at which the event took place.

EventSubType
The type of pass made. Can be one of: 'Head pass', 'Simple pass', 'Launch', 'High pass', 'Hand pass', 'Smart pass', 'Cross'.

EventOrigin_x
The x-coordinate on the field at which the pass originated. The x-coordinate is in the range [0, 100] and is oriented from the perspective of the attacking team, where 0 indicates the team's own goal, and 100 indicates the oppositing team's goal.

EventOrigin_y
The y-coordinate on the field at which the pass originated. The y-coordinate is in the range [0, 100] and is oriented from the perspective of the attacking team, where 0 indicates the team's left-hand side, and 100 indicates the team's right-hand side.

EventDestination_x
The x-coordinate on the field at the pass destination.  (see EventOrigin_x)

EventDestination_y
The y-coordinate on the field at the pass destination.  (see EventOrigin_y)
~~~~~~~~~~~~~~~

2) substitution.csv
~~~~~~~~~~~~~~~
MatchID
A unqiue identifier for each match played during the season (see matches.csv).

TeamID
A unqiue identifier for the team involved in the pass (either 'Everton' or OpponentID from matches.csv).

OriginPlayerID
A unqiue identifier for the Player who substituted.

DestinationPlayerID
A unqiue identifier for the Player who was substituted.

MatchPeriod
The half in which the event took place.  '1H': first half, '2H': second half

EventTime
The time in seconds during the MatchPeriod (1st or 2nd half) at which the event took place.



