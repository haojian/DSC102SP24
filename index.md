---
layout: home
---

This course covers the principles of computing systems and tools for scaling data analytics to large datasets. Scalable analytics systems are a central part of modern data science in numerous application domains spanning enterprise business intelligence, Web search, e-commerce, social media, natural and social sciences, healthcare, digital humanities, e-governance, Internet of Things, and more.

Topics include basics of computer organization, memory hierarchy, operating systems, and cloud computing; principles of scalable and parallel data-intensive computing; design and use of parallel dataflow systems (MapReduce/Hadoop and Spark); and scaling of end-to-end machine learning (ML) workloads. It will cover how relational algebra, SQL, linear algebra, and more general dataflow operations in such systems can be used to perform data preparation and feature engineering for ML at scale, how to scale ML model building, and how to handle data heterogeneity.

A major component of this course is hands-on Python programming to implement data exploration, data preparation, and model selection pipelines on large real-world data using scalable analytics tools and cloud resources, both Amazon Web Services (AWS) public cloud and SDSC’s private cloud.

## Administrivia

**Lectures**: MWF 03:00PM-03:50PM; CENTR 214

**Instructor**: [Haojian Jin](http://haojianj.in/); Office: HDSI 341; Office Hours: Wednesday 4:00 pm-5:00 pm

**Discussion**: The TAs will conduct one dicussion session before each PA on Zoom to help you get started with the assignment.

## Course Content and Format

- The class meets 3 times a week for 50-minute lectures in person.
    <!-- - All lectures will be automatically podcast here afterward. -->
    - Attending the lectures is not mandatory. But there are Peer Instruction activities involving discussing questions with peers in class only (details below). There will be other interactive activities as well.
    - We will use Slack for asynchronous discussions and questions.

- 3 Programming Assignments (PAs).
    - See the PAs page for the PA schedule and details.
    - There are no late days for the PAs. Plan your work accordingly.

- 12 Peer Instruction activities via iClickers.
    - They will be held live in class using iClicker, spread randomly across the quarter.
    - Each activity will have 2 multiple-choice questions (MCQ). Quantitative problems may exist but only the final answer will need to be selected. No partial credits.
    - For each question, you must first answer individually. Then you can discuss the question with you neighbor(s). After that, you can answer the question again.
    - These activities are also open books/notes/electronics/Web.
    - Grading is based on earnest participation in the whole activity.
    - If you miss an activity, you will get no credit for it, unless you notify the instructor in advance with a university approved reason.
    - You can miss up to 2 activities out of the 12 without losing credit.
    - Make sure to bring your clicker to every lecture. If you happen to forget it one day, submit your written answers on a sheet.
    - You are allowed to possess only your own clicker. Using someone else's clicker is an academic integrity violation that will entail serious consequences as listed below.

- Midterm exam and cumulative final exam.
    - The midterm and final exams will be held in-person only.
    - The exams will have primarily multiple choice questions (MCQ). Quantitative/longer problems wil exist but only the final answer may need to be selected. Some questions will have partial credits.
    - The guideline for time per question is a max of 1min per point. The points of each question will be calibrated accordingly.
    - If you miss an exam, you will get no credit for it, unless you notify the instructor in advance with a university approved reason and receive a makeup exam slot.
    - The midterm and final are closed books/notes/electronics/web. You are allowed to keep with you two A4-sized sheets (four sides) with any content you want for the midterm, and four A4-sized sheets (eight sides) for the final. You may also use pocket calculators (i.e. the ones that don’t have non-volatile memory) as there will be some light math involved.

- The discussion slots will be used by the TAs to give talks about the PAs. I might also use them for review discussions before the two exams.

## Pre-requisites

1. DSC 100 (Introduction to Data Management); or substantial practical experience with scalable data systems and ML, subject to the consent of the instructor.

2. Proficiency in Python programming.

## Grading (Tentative)

**Components**: 

- Midterm exam: 15%
- Programming assignments: 8% + 16% + 16%
- In-class peer instruction activities: 10%
- Cumulative final: 35%
- Extra credit: 4% (likely)


**Cutoffs**: 
The grading scheme is a hybrid of absolute and relative grading. The absolute cutoffs are based on your absolute total score. The relative bins are based on your position in the total score distribution of the class. The better grade among the two (absolute-based and relative-based) will be your final grade.


<table style="border: 1px solid black;">
  <tr>
    <td width="200px">Grade</td>
    <td width="200px">Absolute Cutoff (>=)</td>
    <td>Relative Bin (Use strictest)</td>
  </tr>
  <tr>
    <td>A+</td>
    <td width="200px">95</td>
    <td>Highest 5%</td>
  </tr>
  <tr>
    <td>A</td>
    <td width="200px">90</td>
    <td>Next 10% (5-15)</td>
  </tr>
    <tr>
    <td>A-</td>
    <td width="200px">85</td>
    <td>Next 15% (15-30)</td>
  </tr>
  <tr>
    <td>B+</td>
    <td width="200px">80</td>
    <td>Next 15% (30-45)</td>
  </tr>
    <tr>
    <td>B</td>
    <td width="200px">75</td>
    <td>Next 15% (45-60)</td>
  </tr>
    <tr>
    <td>B-</td>
    <td width="200px">70</td>
    <td>Next 15% (60-75)</td>
  </tr>
    <tr>
    <td>C+</td>
    <td width="200px">65</td>
    <td>Next 5% (75-80)</td>
  </tr>
    <tr>
    <td>C</td>
    <td width="200px">60</td>
    <td>Next 5% (80-85)</td>
  </tr>
  <tr>
    <td>C-</td>
    <td width="200px">55</td>
    <td>Next 5% (85-90)</td>
  </tr>
  <tr>
    <td>D</td>
    <td width="200px">50</td>
    <td>Next 5% (90-95)</td>
  </tr>
  <tr>
    <td>F</td>
    <td width="200px">< 50</td>
    <td>Lowest 5%</td>
  </tr>
</table>
		
**Example**: Suppose the total score is 82 and the percentile is 33. So, the relative grade is B-, while the absolute grade is B+. The final grade then is B+.

**Non-Letter Grade Options**: You have the option of taking this course for a non-letter grade. The policy for P in a P/F option is a letter grade of C- or better; for S in an S/U option is a letter grade of B- or better.


## Exam Dates

- Midterm (TBD)
- Final Exam: 3:00-6:00 PM PT, 15 December 2023

## Classroom Rules
- <code>No late days</code> for submitting the PAs. No extensions on the final exam time window. Plan all your work well up front accordingly.
- Students are encouraged to ask questions and participate in discussions in class and on Slack. Please raise your hand before speaking and the instructor will call on you to speak.
- Please review UCSD's honor code and policies and procedures on [academic integrity](https://academicintegrity.ucsd.edu/) here. If plagiarism is detected in your code, or if we detect collusion on the graded quizzes or exams, or if you are found to be using someone else's clickers, or if any other form of academic integrity violation is identified, you will get zero for that component of your score and get downgraded substantially. I will also notify the University authorities for appropriate disciplinary action to be taken, up to and including expulsion from the University.
- Please review UCSD's principles of community and our commitment to creating an inclusive learning environment on [this website](https://ucsd.edu/about/principles.html).
- Harassment, discrimination, or intimidation of any form against any student will not be tolerated in class or on Slack. Please review UCSD's policies on dealing with harassment and discrimination on [this website](https://ophd.ucsd.edu/).

