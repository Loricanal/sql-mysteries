# SQL Murder Mystery

![Illustration of a detective looking at evidence](174092-clue-illustration.png)

There's been a Murder in SQL City! The SQL Murder Mystery is designed to be both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.

The game instance is based on the structure of https://github.com/NUKnightLab/sql-mysteries/blob/master/sql-murder-mystery.db.
In this alternative version of the game, beyond identifying the murderer as in the original, participants are tasked with uncovering all individuals connected to the murder. Furthermore, the SQL queries required involve more intricate constructs, tailored to the learning objectives of a database fundamentals course for cinema and media engineers at the Polytechnic University of Turin. 

For insights into the implementation of this game in the classroom and its learning outcomes, refer to the article available at [IEEE Xplore](https://ieeexplore.ieee.org/document/9842627). The citation for the article is as follows:

```plaintext
@INPROCEEDINGS{9842627,
  author={Canale, Lorenzo and Farinetti, Laura},
  booktitle={2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC)}, 
  title={SQL Murder Mystery: a serious game to learn querying databases}, 
  year={2022},
  volume={},
  number={},
  pages={129-138},
  doi={10.1109/COMPSAC54236.2022.00027}
}


## Getting Started
To getting started you need to download the db: **cluedo.sql** for MySql and **cluedo.sqlite** for SQLLite.

The game starts with the following message:
*A crime has taken place and the detective needs your help. The detective gave you the crime scene report, but you somehow lost it. You vaguely remember that the crime was a murder that occurred sometime on Jan.15, 2018 and that it took place in SQL City. Start by retrieving the corresponding crime scene report from the police department’s database.*
