1. For the given JSON iterate over all for loops (for, for in, for of, forEach).

For Loop

for(let i in object){
A +=object[i];
}


For in

var object={
“Name” : “john”,
“Age” : “23”
};


For of

var object = {
“Name” : “john”,
“Age” : “23”
}
for(var i of object)
{
console.log(i)};

Foreach

object.keys(obj).foreach(function(k){
console.log(k + ‘--------’+obj[k])
};

2.resume in JSON 

{
  "Personal details": {
    "name": "pavithra",
    "email": "pavithradeevi@gmail.com",
    "phone": "8148867175",
    "location": {
      "address": "106/b,Aswath Nagar",
      "city": "bangalore",
"pincode":: “560094”,
    },
    "work": [{
    "name": "LIVEWIRE",
    "position": "Engineer",
    "url": "www.caddcnter.com",
    "startDate": "2016-07-19",
    "endDate": "2019-11-20",    
    ]
  }],
   }],
  "education": [{
    "institution": "sengunthar engineering college",
    "Course": "Software Development",
    "Degree": "BE",
    "Year of passing": "2016",
    "CGPA": "7.3",
     }],
   "skills": [{
    "keywords": [
      "HTML",
      "Python",
      "JavaScript"
    ]
  }],
  "languages": [{
    "language": 
"English",
”Tamil”
  }],
   "projects": [{
    "name": "Face detection",
    "Githup link": "https://github.com/pavithradeevi/Face-Recognition-attendance-System-using-MYSQL",
       }]
}















