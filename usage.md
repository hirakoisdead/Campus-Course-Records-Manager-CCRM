# Usage Guide for CCRM

## Sample Commands

### Add Student
```
Choice: 1
1-Add 2-List
1
RegNo: R1001
Name: Alice Kumar
Email: alice@example.com
```


### Enroll Student
```
Choice: 3
StudentId: 1
Course code: CS-108
```

### Export
```
Choice: 4
Action: 2
Export completed → see output/students.json, courses.json
```


## Data Files
### test-data/students_sample.csv
```
id,regNo,fullName,email,active
S1,24BCE93421,Aarav,aarav@vit.ac.in,true
S2,24BCE15873,Tanya,tanya@vit.ac.in,false
S3,24BCE48290,Nikhil,nikhil@vit.ac.in,true
S4,24BCE71345,Diya,diya@vit.ac.in,false
S5,24BCE65982,Kunal,kunal@vit.ac.in,true

```

### test-data/courses_sample.csv
```
code,title,credits,department,semester,instructor
CS101,Intro to CS,4,CS,FALL,Dr. Rao
MA101,Calculus,3,Math,FALL, Dr. Bhim

```
