- 👋 Hi, I’m @ANDERSONTAVARESS
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ANDERSONTAVARESS/ANDERSONTAVARESS is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# AsianHandiCap API


## HTTP Request 
```POST http:// Please contact us by Telegram to request address +/bet365/v0/api/AsianHandiCap```


### Request Example

```zsh
curl -X POST -H "Authorization: Bearer Please contact us by Telegram to get token" http:// request address +/bet365/v0/api/AsianHandiCap
```
###  Request Header

| Parameter | Required? | Description |
| --------   | ----- | ---- |
| Authorization | Yes |Please contact to get 7 days free trial|
| Method | Yes |POST|

## Response Parameter

|Parameter| Description |
| --------|-----|
| msg |Success or Request failed description|
| code |Request status code, 0 means success, see error code for other details|
| data |Response object|
| data.sync_time |Message synchronization time|
| data.data.channel |Data return channel|
| data.data.data.team_pair |Team name|
| data.data.data.team_score |Total team score|
| data.data.data.play_time |Play time|
| data.data.data.handicap_list |Handicap list|
| data.data.data.odds_list |Odds list|

### HTTP Response

```
{
    "msg": "Success",
    "data": {
        "data": {
            "channel": [
                "æ»šçƒäºšæ´²ç›˜"
            ],
            "data": [
                {
                    "team_pair": [
                        "El è¨æ¢…é›·å…‹",
                        "å¡”æ‹‰åŸƒé˜¿æ°è‰¾æ–¯"
                    ],
                    "team_score": [
                        "1",
                        "1"
                    ],
                    "play_time": [
                        "45:00"
                    ],
                    "handicap_list": [
                        "0.0",
                        "0.0"
                    ],
                    "odds_list": [
                        "1.800",
                        "2.000"
                    ]
                },
                {
                    "team_pair": [
                        "ä¸œé‡Œå‘",
                        "å¸ƒè¾¾äºš"
                    ],
                    "team_score": [
                        "2",
                        "0"
                    ],
                    "play_time": [
                        "51:27"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "1.950",
                        "1.850"
                    ]
                },
                {
                    "team_pair": [
                        "Al-Najmaéº¦çº³éº¦",
                        "é©¬å‹’åŸºäºš"
                    ],
                    "team_score": [
                        "1",
                        "0"
                    ],
                    "play_time": [
                        "57:19"
                    ],
                    "handicap_list": [
                        "0.0",
                        "0.0"
                    ],
                    "odds_list": [
                        "1.950",
                        "1.850"
                    ]
                },
                {
                    "team_pair": [
                        "ä¼Šå¡”å°”è¶³çƒä¿±ä¹éƒ¨",
                        "ç‰¹è¨æ–¯ç§‘å¡žæ´›2015"
                    ],
                    "team_score": [
                        "1",
                        "0"
                    ],
                    "play_time": [
                        "25:03"
                    ],
                    "handicap_list": [
                        "0.0,+0.5",
                        "0.0,-0.5"
                    ],
                    "odds_list": [
                        "1.925",
                        "1.925"
                    ]
                },
                {
                    "team_pair": [
                        "çš‡å®¶æ¢…æ–¯å…‹ä¼¦ç²¾è‹±",
                        "åœ£å›¾å°”ç™»"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "0.0",
                        "0.0"
                    ],
                    "odds_list": [
                        "1.925",
                        "1.925"
                    ]
                },
                {
                    "team_pair": [
                        "ä¼¯æ‹‰æ²»",
                        "æ–¯æ´›æ³¢è¾¾"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "-1.0,-1.5",
                        "+1.0,+1.5"
                    ],
                    "odds_list": [
                        "2.050",
                        "1.750"
                    ]
                },
                {
                    "team_pair": [
                        "é˜¿å°”å§†åŸƒè¾¾",
                        "Al Bidda SC"
                    ],
                    "team_score": [
                        "1",
                        "0"
                    ],
                    "play_time": [
                        "45:00"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "2.050",
                        "1.750"
                    ]
                },
                {
                    "team_pair": [
                        "å…‹å‹’æ‹‰å¸Œ",
                        "Turris-Oltulå›¾å°”åŠªé»˜å¤é›·èŽ±"
                    ],
                    "team_score": [
                        "0",
                        "1"
                    ],
                    "play_time": [
                        "56:55"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "2.050",
                        "1.750"
                    ]
                },
                {
                    "team_pair": [
                        "å­Ÿä¹°åŸŽ",
                        "ä¸œå­ŸåŠ æ‹‰ä¿±ä¹éƒ¨"
                    ],
                    "team_score": [
                        "3",
                        "0"
                    ],
                    "play_time": [
                        "96:16"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "é©¬å¡æ¯”æ¯”å†…æ‹‰çº³",
                        "Hapoel Bnei Arrara Ara"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "45:00"
                    ],
                    "handicap_list": [
                        "-1",
                        "+1"
                    ],
                    "odds_list": [
                        "1.900",
                        "1.900"
                    ]
                },
                {
                    "team_pair": [
                        "é˜¿ä»€å‡¯æ³½å¤æ™®å°”",
                        "ASè€¶è·¯æ’’å†·"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "1.800",
                        "2.000"
                    ]
                },
                {
                    "team_pair": [
                        "åŒˆç‰™åˆ© å¥³å­",
                        "å†°å²› å¥³å­"
                    ],
                    "team_score": [
                        "0",
                        "1"
                    ],
                    "play_time": [
                        "72:05"
                    ],
                    "handicap_list": [
                        "+0.5,+1.0",
                        "-0.5,-1.0"
                    ],
                    "odds_list": [
                        "1.925",
                        "1.875"
                    ]
                },
                {
                    "team_pair": [
                        "ä»¥è‰²åˆ— å¥³å­",
                        "é©¬è€³ä»– å¥³å­"
                    ],
                    "team_score": [
                        "0",
                        "2"
                    ],
                    "play_time": [
                        "70:30"
                    ],
                    "handicap_list": [
                        "0.0",
                        "0.0"
                    ],
                    "odds_list": [
                        "2.200",
                        "1.650"
                    ]
                },
                {
                    "team_pair": [
                        "Im Not Over (PNZ) Esports",
                        "Rattata 522 (NFC) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "0.0,+0.5",
                        "0.0,-0.5"
                    ],
                    "odds_list": [
                        "1.850",
                        "1.850"
                    ]
                },
                {
                    "team_pair": [
                        "Dortmund (BlackStar98) Esports",
                        "Chelsea (xShilito) Esports"
                    ],
                    "team_score": [
                        "2",
                        "0"
                    ],
                    "play_time": [
                        "08:00"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "AC Milan (Foggy) Esports",
                        "Leicester (Inquisitor) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "03:26"
                    ],
                    "handicap_list": [
                        "0.0",
                        "0.0"
                    ],
                    "odds_list": [
                        "1.650",
                        "2.100"
                    ]
                },
                {
                    "team_pair": [
                        "Arsenal (Olle) Esports",
                        "Leverkusen (white_boy1927) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "02:56"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "1.900",
                        "1.800"
                    ]
                },
                {
                    "team_pair": [
                        "Atletico Madrid (FEARGGWP) Esports",
                        "Chelsea (xShilito) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list": [
                        "1.800",
                        "1.900"
                    ]
                }
            ]
        },
        "sync_time": 1606838274
    }
}
```
