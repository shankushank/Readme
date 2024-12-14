# Readme
update

recipes = {
    'dhal': ['cocunut milk','lentails' 'curry leaves', 'spices'],
    "serves" :3,
    "time" : "15 minutes"
    
}
print (recipes["dhal"][2])

   employee =[ {
    "name" : "Matt",
    "title" : "Product Manager/Lead Tutor"
  },
  {
    "name" : "Zaid",
    "title" : "Tutor Practitioner"
  }]

with open("employee.json", "r") as infile:
    employees_large_data = json.load(infile)

    for students in student_r:
        if students ["score"] >80:
            students["grade"] = 'A'
        elif students ["score"] <70 == 'B':