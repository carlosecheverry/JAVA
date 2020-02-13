
<img align="right" width="150" height="150" src="https://media-exp1.licdn.com/dms/image/C4E0BAQF7BYCCZt5epw/company-logo_200_200/0?e=2159024400&v=beta&t=qUAFP9bUgBEEXGVQYpUXW1J_OiP8e0r4rFBpqp8OrxA">

# JAVA-12 - Final Project

 <br/>
 <br/>
 It is time to check how much you have learnt about Java and Object Oriented Programming.
 
 ## Part 1: Understanding the Student Gen project
 1. Download the source code and import the project into your favorite IDE (e.g. IntelliJ Idea).
 2. Understand the project stucture: {this instruction is unclear. what should participants do with the info below? read it?}
 * Packages
 * Classes
 * Functionality
 3. Run and test the project to get a deeper understanding of how it works (remember the persistence mindset!) {can we give more clarity about what they should achieve here, e.g. you should be clear about how every step in the process works}
 
  ## Part 2: Implementing the Student and StudentService missing features
  
  1. Open the *Student* class and implement the following methods:
  
   ```java
    public void enrollToCourse( Course course )
    {
        //TODO implement this method
    }
    
    public boolean isCourseApproved( String courseCode )
    {
        //TODO implement this method
        return false;
    }

    public List<Course> findPassedCourses( Course course )
    {
        //TODO implement this method
        return null;
    }

    public boolean isAttendingCourse( String courseCode )
    {
        //TODO implement this method
        return false;
    }
    @Override
    public List<Course> getApprovedCourses()
    {
        //TODO implement this method
        return null;
    }
   ```
   
   2. Open the *StudentService* class and implement the following methods:
   
   ```java
       public boolean isSubscribed( String studentId )
       {
           //TODO implement this method
           return false;
       }

       public void showSummary()
       {
           //TODO implement
       }
   ```

  ## Part 3: Implementing the missing main method features
 
 1. Implement the method to *gradeStudent( StudentService studentService, Scanner scanner )* to have a fully functional programm.
 
 2. Test the program to verify it works as expected:
  * Create a new student.
  * Enrroll the student to a few courses.
  * Grade the student.
  * Show the students and courses summary and verify that data is correct.
  

  ## Part 4: Handling exceptions
  1. Register a new user providing an incorrect date format.
  2. Modify the createStudentMenu so it handles correctly the exception when an incorrect date format is inserted by the user.
  3. Catch the exception and show a proper message to the user. {what does proper mean here?}
  
  ## Challenge Yourself
  1. Implement an additional feature in the menu options that will display the average grade of all the students suscribed to a given course.
