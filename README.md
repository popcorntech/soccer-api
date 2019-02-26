# soccer-api
Free Soccer Restful Api service for developers

League Titles:
turkey		(Turkish Super Lig)
germany		(Bundesliga)
france		(Ligue 1)
italy		(Serie A)
spain		(La Liga)
england		(Premier League)
spor-toto	(Turkish 1.League)



You can get standings, top scorers, and fixtures datas of European Leagues with this free restful api service.
Important Note: Home and away scores of unplayed matches return -1 value!


/standings/{league-title}

/scorers/{league-title}

/fixtures/{league-title}

Query for getting fixtures of English League;
https://springboot-soccer-api.herokuapp.com/fixtures/england

Result:
        [{id: 1,
        country: "england",
        home: "Cardiff City",
        away: "Everton",
        homeScore: 0,
        awayScore: 1,
        date: "6 Şubat 2019 Salı 22:45"},...]

Query for getting top scorers of Italian League;
https://springboot-soccer-api.herokuapp.com/scorers/italy

Result:
        [{id: 1,
        name: "Cristiano Ronaldo",
        team: "Juventus",
        goals: 19,
        matches: 25},...]


Query for getting standings of Spanish League;
https://springboot-soccer-api.herokuapp.com/standings/spain

Result:
        [{{id: 1,
        name: "Barcelona",
        om: 25,
        g: 17,
        b: 6,
        m: 2,
        ag: 65,
        yg: 25,
        av: 40,
        p: 57},...}]
