1. {isActive: true} trovate 51 
2. {age:{$gt: 26}} trovate 54 
3. {age:{ $gt: 26, $lte: 30 }} trovate 19 
4. {eyeColor: { $in: ["brown", "blue"] }} || {$or: [{eyeColor:"brown"}, {eyeColor:"blue"}]} trovate 66 
5. {eyeColor:{$ne:"green"}} trovate 66 
6. {eyeColor: {$nin: ["green", "blue"]}} trovate 35 
7. {company: "FITCORE" } project: {email: true} trovata 1



