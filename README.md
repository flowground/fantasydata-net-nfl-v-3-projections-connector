# ![LOGO](logo.png) NFL v3 Projections **flow**ground Connector

## Description

A generated **flow**ground connector for the NFL v3 Projections API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nfl-v3-projections/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:36+03:00

## API Description

NFL projected stats API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### DFS Slates by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the slates.
<br>Examples: <code>2017-SEP-25</code>, <code>2017-10-31</code>.

### DFS Slates by Week

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>

### Projected Fantasy Defense Game Stats (w/ DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Projected Fantasy Defense Season Stats (w/ Bye Week, ADP)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### IDP Projected Player Game Stats by Player (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `playerid` - _required_ - Each NFL player has a unique ID assigned by FantasyData. Player IDs can be determined by pulling player related data. Example:<code>14257</code>.

### IDP Projected Player Game Stats by Team (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `team` - _required_ - Abbreviation of the team. Example: <code>WAS</code>.

### IDP Projected Player Game Stats by Week (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Projected Player Game Stats by Player (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - 
          Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `playerid` - _required_ - Each NFL player has a unique ID assigned by FantasyData. Player IDs can be determined by pulling player related data. Example:<code>14257</code>.

### Projected Player Game Stats by Team (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `team` - _required_ - Abbreviation of the team. Example: <code>WAS</code>.

### Projected Player Game Stats by Week (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - 
          Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Projected Player Season Stats (w/ Bye Week, ADP)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Projected Player Season Stats by Player (w/ Bye Week, ADP)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `playerid` - _required_ - Each NFL player has a unique ID assigned by FantasyData. Player IDs can be determined by pulling player related data. Example:<code>14257</code>.

### Projected Player Season Stats by Team (w/ Bye Week, ADP)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `team` - _required_ - Abbreviation of the team. Example: <code>WAS</code>.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nfl-v-3-projections-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
