# CricInfoExtracter

#### Script for grabbing all the match infos from 2019 cricket world cup. Save the info in Excel and eventually create a pdf file.

## Setup
npm init -y
npm install minimist
npm install axios
npm install jsdom
npm install excel4node
npm install pdf-lib

## Run
node main.js --excel=Worldcup.csv --dataFolder=data --source=https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415/match-results 
