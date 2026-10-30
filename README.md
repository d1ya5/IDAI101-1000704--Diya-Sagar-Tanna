# ParentConnect

ParentConnect is an AI-powered school communication chatbot designed to help parents and guardians access quick, accurate, and reliable school-related information anytime, anywhere. It provides instant responses to common enquiries regarding attendance, examinations, school updates, and other important information. Available 24/7, ParentConnect makes communication between parents and the school easier, faster, and more efficient. By reducing repeated enquiries and response delays, it also allows school staff to dedicate more time and attention to students.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Intents](#intents)
- [Entities](#entities)

## Features

- **24/7 Instant Assistance**, Gives the parent with quick an accurate answers to common questions related to their children at any time without having to reach out to staff.
- **Centralised School Information**, ParentConnect provides easy access to important updates in temrs of homework, attendance, fees, exam timetables, bus tracking, holidays, events and school notices.
- **Efficient Parent-School Communication**, Reduces repetitive calls, emails, and messages, allowing staff to spend less time answering common enquiries and more time focusing on students.

## Intents 
- HomeworkIntent
 This intent identifies questions regarding kids homework, assignments, pending tasks, and any upcoming deadlines. It helps parents be more aware about their childs academic responsibilities.

- HolidayDatesFollowupIntent
  This intents purpose is to handle any follow up questions regarding the date of holidays, which could be asked in the HolidayDatesIntent. It allows parents to request for additioal detials about specific holidays.
  
- AttendanceIntent
  This intent processes questions regarding the student attendance, and provides the user with information on the overall grades attendance (for each grade).
  
- FeesIntent
  Since each parents information for their fees payment would vary, this intent helps direct parents to staff or teachers as it is trained to direct them to a human who can help them regarding the fees better.
  
- DailyTimeTableIntent
  This intent is trained to recognise questions regarding the daily timetable  for the speicified school, it helps parents gain an understanding of their child's daily schedule.
  
- ConnectWithStaffIntent
  This intent identifies when the parents choose to escalate it and speak to an actual teacher or staff. The responses direct them to the appropriate person.
  
- DailyUpdatesIntent
  Gives the user information on daily reminders, notices, or any important updates. This helps parents get simple updates without reaching out to staff.
  
- SchoolTimingIntent
  This intent helps the bot respond to any questions regarding the school timings, as well as gives information about school hours.
  
- HolidayDatesIntent
  Identifies questions about upcoming school holidays, vacations, and academic breaks. Provides relevant dates to help parents plan ahead. Adiitionally, it doesn't provide the date but its follow up intent does, since this makes the conversation more interactive.
  
- ExamScheduleIntent
  This intent is important as parents like to know when their kids exams take place as that not only allows them to know about their kids academics but also allows them to encourage or help his or her child prepare. The response includes date and time of the exams.
  
- BusTrackingIntent
  This bus tracking intent recognises the parents question, and provides 3 route chips, which makes it easy for the parent to identify nand click on either of the 3. Keeps parents informed about their child's commute.
  
- ExamSyllabusIntent
  Provides info about the upcoming exam syllabus, subjects, chapters, and topics which could possibly be included. It allows parents to undersstand how their kids need to study for exams, again limits friction between parents and staff members.
  
- EventsIntent
  Handles quesitons about any upcoming school events, celebrations, competitions and activities, if any. It provides this info through special chips, as that brings attention to it.
  
- FallbackIntent
  If the bot can't provide a reply to the user then this intent will by default give a reply, it encourages parents to rephrase their questions or contact school staff for assistance.
  
- WelcomeIntent
  It is trained to recognise greetings and welcomes parents to the bot, this makes the conversation more inviting, which encourages them to ask theh bot questions.
  
- PTMScheduleIntent
  Handles questions or enquireies about PTM'S (Parent Teacher Meetings), inclduing its timings, date, and slots for the meetings. Helps parents be informed and know when to attend.
  
- GoodbyeIntent
  Recognises when a parent wants to end the convo, and replies enthusiastically, which allows the parent to reach out again if needed.
  
- Route1
  Directs the conversation through the first predefined chatbot route based on the parent's query or selected option.
  
- Route2
  Manages the second conversation route, guiding parents towards the relevant information or next step.
  
- Route3
  Handles the third conversation route, ensuring parents are directed to the appropriate response or action.



## Entities

- Attendance:
  Identifies questions that are related to student's attendance, which includes their presence, absence, and attendance records.
  
- Bustracking:
  Identifies questions from the user related to school transport, including bus routes, bus locations and if any delay, provides status.

- Dates:
  Identifies the word dates, and synoms like days, and times mentioned in question, and connects it to the intent accordingly.

- Events:
  Identifies questions regarding any school events, activities, celebrations, and other occasions that could be organised by the school, it identifies the same and connects to intents.

- ExamSchedule:
  Identifies questions related to examination schedules, including exam dates, timings, timetables, and upcoming tests.

- Holiday:
  Identifies questions about school holidays, vacations, school closures, and upcoming breaks during the academic year.

- Homework:
  Identifies questions related to homework and assignments, including assigned tasks, practice worksheets, schoolwork, and submission details.

- PTM:
  Identifies questions about Parent-Teacher Meetings, including meeting dates, timings, schedules, and opportunities for parents to interact with teachers.

- SchoolTime:
  Identifies questions about regular school timings, including school opening and closing hours, the duration of the school day, and full-day schedules.

- Staff:
  Identifies questions about school staff members, including teachers, their roles, contact details, and availability.

- Timetable:
Identifies questions about class timetables and daily schedules, including subject periods, weekly plans, and classroom schedules.

- Updates:
  Identifies questions about the latest school announcements, notices, news, and important information shared by the school.

 Note: Each entity explanation mentions the synonms that were defined as well.


## Screenshots
- As seen below the web demo link provided through dialouge is not accsessible. Therefore I've attached a zip file of the project.
<img width="1240" height="808" alt="Screenshot 2026-10-30 at 2 12 31 PM" src="https://github.com/user-attachments/assets/306ea0f9-0a1d-44fd-8630-df21a4abe533" />
---

Made with ❤ by [d1ya5](https://github.com/d1ya5)
