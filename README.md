Understand difference between .update() & .set()

//Consider a sample database fields as:
'Name' : "Jay", 
'Age' : 14,
'Gender' : 'Male'

Let say we want to change value of Age:
//Using update:
.update({
  'Age' : 15
})
//Result will only change value of Age:
'Name' : "Jay",
'Age' : 15,
'Gender' : 'Male'

//Using set:
.set({
  'Age' : 15
})
//Result will change value of Age, and remove the other fields:
'Age' : 15,


