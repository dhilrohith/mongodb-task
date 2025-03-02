Zen Class Programme - Mongo DB Task

1. The 7 Collections namely Users, Codekata, Attendance, Topics, Taks, Company_Drives and Mentors are initially made. Then I attached the screenshots of those collections.

2. Then I added the 6 queries and their o/p to fetch those data. Screenshot of Queries attached along with the code at the start of the doc for your reference.

Collections:
![alt text](<Screenshot (1).png>)
![alt text](<Screenshot (2).png>)

Queries:

Database Creation:

1. Users Creation:

[
  { "name": "John Doe", "email": "john@example.com", "batch": "Batch A" },
  { "name": "Jane Smith", "email": "jane@example.com", "batch": "Batch B" },
  { "name": "Alice Johnson", "email": "alice@example.com", "batch": "Batch A" },
  { "name": "Mark Brown", "email": "mark@example.com", "batch": "Batch C" },
  { "name": "Emily Davis", "email": "emily@example.com", "batch": "Batch A" },
  { "name": "Chris White", "email": "chris@example.com", "batch": "Batch B" },
  { "name": "Anna Lewis", "email": "anna@example.com", "batch": "Batch C" },
  { "name": "Tom Wilson", "email": "tom@example.com", "batch": "Batch A" },
  { "name": "Sarah Moore", "email": "sarah@example.com", "batch": "Batch B" },
  { "name": "James Taylor", "email": "james@example.com", "batch": "Batch C" },
  { "name": "Grace Hall", "email": "grace@example.com", "batch": "Batch A" },
  { "name": "Mia Young", "email": "mia@example.com", "batch": "Batch B" },
  { "name": "Daniel King", "email": "daniel@example.com", "batch": "Batch C" },
  { "name": "Sophia Scott", "email": "sophia@example.com", "batch": "Batch A" },
  { "name": "Liam Adams", "email": "liam@example.com", "batch": "Batch B" }
]

2. Codekata Creation:

[
  { "user_id": "648f1a1b1c9d440000d7a1e1", "problems_solved": 150 },
  { "user_id": "648f1a1b1c9d440000d7a1e2", "problems_solved": 200 },
  { "user_id": "648f1a1b1c9d440000d7a1e3", "problems_solved": 180 },
  { "user_id": "648f1a1b1c9d440000d7a1e4", "problems_solved": 120 },
  { "user_id": "648f1a1b1c9d440000d7a1e5", "problems_solved": 250 },
  { "user_id": "648f1a1b1c9d440000d7a1e6", "problems_solved": 300 },
  { "user_id": "648f1a1b1c9d440000d7a1e7", "problems_solved": 350 },
  { "user_id": "648f1a1b1c9d440000d7a1e8", "problems_solved": 100 },
  { "user_id": "648f1a1b1c9d440000d7a1e9", "problems_solved": 175 },
  { "user_id": "648f1a1b1c9d440000d7a1e10", "problems_solved": 125 },
  { "user_id": "648f1a1b1c9d440000d7a1e11", "problems_solved": 220 },
  { "user_id": "648f1a1b1c9d440000d7a1e12", "problems_solved": 400 },
  { "user_id": "648f1a1b1c9d440000d7a1e13", "problems_solved": 310 },
  { "user_id": "648f1a1b1c9d440000d7a1e14", "problems_solved": 210 },
  { "user_id": "648f1a1b1c9d440000d7a1e15", "problems_solved": 95 }
]

3. Attendance Creation:

[
  { "user_id": "648f1a1b1c9d440000d7a1e1", "date": "2020-10-01", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e2", "date": "2020-10-02", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e3", "date": "2020-10-03", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e4", "date": "2020-10-04", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e5", "date": "2020-10-05", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e6", "date": "2020-10-06", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e7", "date": "2020-10-07", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e8", "date": "2020-10-08", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e9", "date": "2020-10-09", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e10", "date": "2020-10-10", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e11", "date": "2020-10-11", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e12", "date": "2020-10-12", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e13", "date": "2020-10-13", "status": "Absent" },
  { "user_id": "648f1a1b1c9d440000d7a1e14", "date": "2020-10-14", "status": "Present" },
  { "user_id": "648f1a1b1c9d440000d7a1e15", "date": "2020-10-15", "status": "Present" }
]

4. Topics Creation:

[
  { "topic_name": "HTML Basics", "date": "2020-10-01" },
  { "topic_name": "CSS Fundamentals", "date": "2020-10-02" },
  { "topic_name": "JavaScript Basics", "date": "2020-10-03" },
  { "topic_name": "DOM Manipulation", "date": "2020-10-04" },
  { "topic_name": "Responsive Design", "date": "2020-10-05" },
  { "topic_name": "ES6 Features", "date": "2020-10-06" },
  { "topic_name": "Node.js Basics", "date": "2020-10-07" },
  { "topic_name": "Express.js Overview", "date": "2020-10-08" },
  { "topic_name": "MongoDB Introduction", "date": "2020-10-09" },
  { "topic_name": "React Basics", "date": "2020-10-10" },
  { "topic_name": "Redux Overview", "date": "2020-10-11" },
  { "topic_name": "Authentication Basics", "date": "2020-10-12" },
  { "topic_name": "Unit Testing", "date": "2020-10-13" },
  { "topic_name": "Git and GitHub", "date": "2020-10-14" },
  { "topic_name": "Deployment", "date": "2020-10-15" }
]

5. Tasks Creation:

[
  { "task_name": "HTML Assignment", "topic_name": "HTML Basics", "due_date": "2020-10-05", "status": "Submitted" },
  { "task_name": "CSS Project", "topic_name": "CSS Fundamentals", "due_date": "2020-10-06", "status": "Submitted" },
  { "task_name": "JS Exercise", "topic_name": "JavaScript Basics", "due_date": "2020-10-07", "status": "Not Submitted" },
  { "task_name": "DOM Mini-Project", "topic_name": "DOM Manipulation", "due_date": "2020-10-08", "status": "Submitted" },
  { "task_name": "Responsive Design Demo", "topic_name": "Responsive Design", "due_date": "2020-10-09", "status": "Not Submitted" },
  { "task_name": "ES6 Features Practice", "topic_name": "ES6 Features", "due_date": "2020-10-10", "status": "Submitted" },
  { "task_name": "Node.js API", "topic_name": "Node.js Basics", "due_date": "2020-10-11", "status": "Submitted" },
  { "task_name": "Express.js Routing", "topic_name": "Express.js Overview", "due_date": "2020-10-12", "status": "Not Submitted" },
  { "task_name": "MongoDB CRUD", "topic_name": "MongoDB Introduction", "due_date": "2020-10-13", "status": "Submitted" },
  { "task_name": "React Component", "topic_name": "React Basics", "due_date": "2020-10-14", "status": "Not Submitted" },
  { "task_name": "Redux State Management", "topic_name": "Redux Overview", "due_date": "2020-10-15", "status": "Submitted" },
  { "task_name": "Authentication API", "topic_name": "Authentication Basics", "due_date": "2020-10-16", "status": "Not Submitted" },
  { "task_name": "Unit Testing Script", "topic_name": "Unit Testing", "due_date": "2020-10-17", "status": "Submitted" },
  { "task_name": "Git Branching", "topic_name": "Git and GitHub", "due_date": "2020-10-18", "status": "Submitted" },
  { "task_name": "Deployment Pipeline", "topic_name": "Deployment", "due_date": "2020-10-19", "status": "Not Submitted" }
]

6. Company Drive Creation:

[
  { "company_name": "Google", "drive_date": "2020-10-15", "students_attended": 12 },
  { "company_name": "Microsoft", "drive_date": "2020-10-16", "students_attended": 10 },
  { "company_name": "Facebook", "drive_date": "2020-10-17", "students_attended": 8 },
  { "company_name": "Amazon", "drive_date": "2020-10-18", "students_attended": 15 },
  { "company_name": "Apple", "drive_date": "2020-10-19", "students_attended": 14 },
  { "company_name": "Netflix", "drive_date": "2020-10-20", "students_attended": 9 },
  { "company_name": "Adobe", "drive_date": "2020-10-21", "students_attended": 11 },
  { "company_name": "Intel", "drive_date": "2020-10-22", "students_attended": 13 },
  { "company_name": "IBM", "drive_date": "2020-10-23", "students_attended": 7 },
  { "company_name": "Salesforce", "drive_date": "2020-10-24", "students_attended": 12 },
  { "company_name": "Accenture", "drive_date": "2020-10-25", "students_attended": 10 },
  { "company_name": "TCS", "drive_date": "2020-10-26", "students_attended": 14 },
  { "company_name": "Infosys", "drive_date": "2020-10-27", "students_attended": 11 },
  { "company_name": "Cognizant", "drive_date": "2020-10-28", "students_attended": 13 },
  { "company_name": "Wipro", "drive_date": "2020-10-29", "students_attended": 8 }
]

Queries:

1. Find all the topics and tasks which are thought in the month of October:
db.topics.find({
  date: {
    $gte: "2020-10-01",
    $lte: "2020-10-31"
  }
});

2. Find all the company drives which appeared between 15 oct-2020 and 31-oct-2020:
db.company_drives.find({
  drive_date: {
    $gte: "2020-10-15",
    $lte: "2020-10-31"
  }
});

3. Find all the company drives and students who are appeared for the placement.:
db.company_drives.aggregate([
  {
    $lookup: {
      from: "users",
      localField: "appeared_by",
      foreignField: "_id",
      as: "students"
    }
  }
]);

4. Find the number of problems solved by the user in codekata:
db.codekata.aggregate([
  {
    $group: {
      _id: "$user_id",
      total_problems_solved: { $sum: "$problems_solved" }
    }
  },
  {
    $lookup: {
      from: "users",
      localField: "_id",
      foreignField: "_id",
      as: "user"
    }
  }
]);

5. Find all the mentors with who has the mentee's count more than 15:
db.mentors.find({
mentee_count:{$gte:15}});

6. Find the number of users who are absent and task is not submitted  between 15 oct-2020 and 31-oct-2020: