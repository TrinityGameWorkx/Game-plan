






# Features:




- Game Login

- Game Screen

- Statistics

- Ranking

- Multiplayer

- Leaderboards

- Teams

- Customization

- Guns

- Gui

- Health

- Gun Animation

- Player Animation

- Map Interactive Elements

- Gun Models

- Character Models

- Team Skins

- Networking





Game Login:



- Players Login Attributes

- [Exit] Gui element, closes the game window

- Server authentication & players authoring of credentials via player database

- Once credentials are confirmed player is inputted to game screen if not then this function loops





Game Screen:



- Gui elements [prototype no skin gui]

- Elements: Play | Classes |Account settings | Options | Exit



- Play > Server list > Picks server > Connection established > User inputted to team choice screen



- Class > Primary > Weapon selection list > Weapon chosen > Weapn attachments > primary weapon set

               Secondary > Weapon selection list > Weapon chosen > Weapn attachments > secondary weapon set

               Grenade > Grenades selection list > Grenade chosen > Grenade explosion colour > Grenade set

               Tactical > Tactical selection list > Tactical chosen > Tactical set

               Specialization > Specialization list > Specialization chosen > Specialization > [Specialization lvl / xp]



- Account Settings 

 

Tabs:



- Information > Account name = player name

                       > Time played = in-game time * number of games

                       > Players met = total players in game * number of games

                       > Unique player key = randomly generated 16 character code, includes numbers and letter, Can  be used to purchases to hook premium content into the account



- Login settings > Account email > change email > confirm changes > changes confirmed

                            > Password > change password > confirm changes > changes confirmed



- Game settings > Name > change game name > game name changed





- Options > Graphics > Brightness > Brightness adjust meter > brightness adjusted

                                    > Quality > High > change to high settings

                                                   > Medium > change to medium settings

                                                   > Low > change to low settings



                 > Graphics change confirmation > Yes > Apply changes

                                                                     > No > Set changes to default



- Exit > Player clicks exit gui button > prompted with confirmation > Yes > Closes connection and game window

                                                                                                         > No  > Closes prompt dialog



Statistics:



- Kills > In-game kills tracked



- Deaths > In-game deaths tracked



- KDR > Kills divided by deaths = result inputted on screen, updated every 5 minutes



- Games Played > Total amount of times a player connected to a server > Collect exception and log in games won 



- Games Won > Total games won > get team > (red,blue) > get game team score > which team is higher in score is the winning team > multiplied by number of games played = wins 



- Games Lost >  Total games lost > get team > (red,blue) > get game team score > which team is lower in score is the losing team > multipled by number of games played = losses



- Exp / Level > Per kill xp gained = 10xp

                      > Per death xp gained = 0xp



                       Level = amount of kills to move to next int



                       Max level = 100

                       Default player level = 1

                       Default level kills to level 2 = 5

                       Level increment of kills = 2.0 to next level
