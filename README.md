# Ex.2

Ecrivez une requête SQL qui affiche tous les titres et descriptions des films dont la description contient le mot Amazing.

#Input

```sql
dvdrental=> SELECT title, description FROM film WHERE description LIKE '%Amazing%';
```

#Output

```sql
         title         |                                                          description
-----------------------+--------------------------------------------------------------------------------------------------------------------------------
 Annie Identity        | A Amazing Panorama of a Pastry Chef And a Boat who must Escape a Woman in An Abandoned Amusement Park
 Anonymous Human       | A Amazing Reflection of a Database Administrator And a Astronaut who must Outrace a Database Administrator in A Shark Tank
 Brannigan Sunrise     | A Amazing Epistle of a Moose And a Crocodile who must Outrace a Dog in Berlin
 Bucket Brotherhood    | A Amazing Display of a Girl And a Womanizer who must Succumb a Lumberjack in A Baloon Factory
 Bulworth Commandments | A Amazing Display of a Mad Cow And a Pioneer who must Redeem a Sumo Wrestler in The Outback
 Carrie Bunch          | A Amazing Epistle of a Student And a Astronaut who must Discover a Frisbee in The Canadian Rockies
 Casablanca Super      | A Amazing Panorama of a Crocodile And a Forensic Psychologist who must Pursue a Secret Agent in The First Manned Space Station
 Celebrity Horn        | A Amazing Documentary of a Secret Agent And a Astronaut who must Vanquish a Hunter in A Shark Tank
 Champion Flatliners   | A Amazing Story of a Mad Cow And a Dog who must Kill a Husband in A Monastery
 Clash Freddy          | A Amazing Yarn of a Composer And a Squirrel who must Escape a Astronaut in Australia
 Clones Pinocchio      | A Amazing Drama of a Car And a Robot who must Pursue a Dentist in New Orleans
 Deep Crusade          | A Amazing Tale of a Crocodile And a Squirrel who must Discover a Composer in Australia
 Early Home            | A Amazing Panorama of a Mad Scientist And a Husband who must Meet a Woman in The Outback
 Empire Malkovich      | A Amazing Story of a Feminist And a Cat who must Face a Car in An Abandoned Fun House
 Expecations Natural   | A Amazing Drama of a Butler And a Husband who must Reach a A Shark in A U-Boat
 Expendable Stallion   | A Amazing Character Study of a Mad Cow And a Squirrel who must Discover a Hunter in A U-Boat
 Fireball Philadelphia | A Amazing Yarn of a Dentist And a A Shark who must Vanquish a Madman in An Abandoned Mine Shaft
 Frost Head            | A Amazing Reflection of a Lumberjack And a Cat who must Discover a Husband in A MySQL Convention
 Gaslight Crusade      | A Amazing Epistle of a Boy And a Astronaut who must Redeem a Man in The Gulf of Mexico
 Gleaming Jawbreaker   | A Amazing Display of a Composer And a Forensic Psychologist who must Discover a Car in The Canadian Rockies
 Glory Tracy           | A Amazing Saga of a Woman And a Womanizer who must Discover a Cat in The First Manned Space Station
 Greedy Roots          | A Amazing Reflection of a A Shark And a Butler who must Chase a Hunter in The Canadian Rockies
 Halloween Nuts        | A Amazing Panorama of a Forensic Psychologist And a Technical Writer who must Fight a Dentist in A U-Boat
 Haunted Antitrust     | A Amazing Saga of a Man And a Dentist who must Reach a Technical Writer in Ancient India
 Hope Tootsie          | A Amazing Documentary of a Student And a Sumo Wrestler who must Outgun a A Shark in A Shark Tank
 Hysterical Grail      | A Amazing Saga of a Madman And a Dentist who must Build a Car in A Manhattan Penthouse
 Jericho Mulan         | A Amazing Yarn of a Hunter And a Butler who must Defeat a Boy in A Jet Boat
 Jet Neighbors         | A Amazing Display of a Lumberjack And a Teacher who must Outrace a Woman in A U-Boat
 Kramer Chocolate      | A Amazing Yarn of a Robot And a Pastry Chef who must Redeem a Mad Scientist in The Outback
 Kwai Homeward         | A Amazing Drama of a Car And a Squirrel who must Pursue a Car in Soviet Georgia
 Mine Titans           | A Amazing Yarn of a Robot And a Womanizer who must Discover a Forensic Psychologist in Berlin
 Notorious Reunion     | A Amazing Epistle of a Woman And a Squirrel who must Fight a Hunter in A Baloon
 Order Betrayed        | A Amazing Saga of a Dog And a A Shark who must Challenge a Cat in The Sahara Desert
 Psycho Shrunk         | A Amazing Panorama of a Crocodile And a Explorer who must Fight a Husband in Nigeria
 Raiders Antitrust     | A Amazing Drama of a Teacher And a Feminist who must Meet a Woman in The First Manned Space Station
 Records Zorro         | A Amazing Drama of a Mad Scientist And a Composer who must Build a Husband in The Outback
 Rings Heartbreakers   | A Amazing Yarn of a Sumo Wrestler And a Boat who must Conquer a Waitress in New Orleans
 Sleepless Monsoon     | A Amazing Saga of a Moose And a Pastry Chef who must Escape a Butler in Australia
 Slums Duck            | A Amazing Character Study of a Teacher And a Database Administrator who must Defeat a Waitress in A Jet Boat
 Song Hedwig           | A Amazing Documentary of a Man And a Husband who must Confront a Squirrel in A MySQL Convention
 South Wait            | A Amazing Documentary of a Car And a Robot who must Escape a Lumberjack in An Abandoned Amusement Park
 Submarine Bed         | A Amazing Display of a Car And a Monkey who must Fight a Teacher in Soviet Georgia
:
```
