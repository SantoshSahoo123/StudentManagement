# save list of all students

POST: localhost:1010/api/save/students
body: [
    {
        "name": "santosh",
        "dob": "12-08-2000"
    },
    {
        "name": "chinmay1",
        "dob": "02-06-2001"
    }
]

# find all students

GET: localhost:1010/api/find/all

# find all students between age

GEt: localhost:1010/api/find/age/between/20/24

# sample recoed at mongo

mydatabase.students.json
