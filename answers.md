# Solutions sheet

## Iteration 1

db.users.find({},{name:1, \_id:0})

## Iteration 2

db.users.find({hasInsurance:true})

## Iteration 3

db.users.find({age:{$gte: 18}})
//db.users.find({age:{$gte: 18}},{name:1,age:1,\_id:0})

## Iteration 4

db.users.findOne({country:"Italy"},{name:1,email:1,\_id:0})
