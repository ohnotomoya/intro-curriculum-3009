# intro-curriculum-3009
入門コースの3章9節の練習  (ISC License)
'use strict';
const fs = require('fs');
const fileName = './test.txt';
for (let count = 0; count < 30; count++) {
  fs.appendFileSync(fileName, 'おはようございます\n', 'utf8');
  fs.appendFileSync(fileName, 'こんにちは\n', 'utf8');
  fs.appendFileSync(fileName, 'こんばんは\n', 'utf8');
}
