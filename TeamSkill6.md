

# Team Skill 6: Building the Right System #

## Sample Test Set 01 - Use Case Under Test: Submit Incident Report ##

### Description ###

This test set is used to test instances of the **Submit Incident Report** use case, specifically filling in fields and submitting or saving the form.

### Fields and Buttons Included on Submit Incident Report Screen ###

  * **Description:** Text area - Alphanumeric characters accepted in this field (Required)
  * **Persons Involved:** Text area - Alphanumberic characters accepted in this field. Names of students to be entered one per line (Required)
  * **Location:** Text line - Alphanumeric characters accepted in this field (Required)
  * **Date:** Text line - Date to be entered in MM/DD/YYYY format (Required)
  * **Time:** Text line - Only a 12-hour clock format allowed (HH:MM, HH - A number between 1 and 12, MM - A number between 0 and 60). AM or PM to be specified (Required)
  * **Want to be anonymous:** Checkbox (Optional)
  * **Save:** Button - When clicked, all the filled in information is saved to the database
  * **Submit:** Button - When clicked, all the filled in information is saved to the database and a notification e-mail is sent to the concerned people

### Identified Flows ###

  * **Basic Flow:** User fills in all required fields and optional fields with valid inputs and clicks the Submit button
  * **Alternate Flow 1:** User fills in all required fields and optional fields with valid inputs and clicks the Save button
  * **Alternate Flow 2:** User does not fill in all required fields and clicks the Submit button
  * **Alternate Flow 3:** User does not fill in all required fields and clicks the Save button
  * **Alternate Flow 4:** User does not fill in all optional fields and clicks the Submit button
  * **Alternate Flow 5:** User does not fill in all optional fields and clicks the Save button
  * **Alternate Flow 6:** User enters invalid input and clicks Submit button
  * **Alternate Flow 7:** User enters invalid input and clicks Save button

![http://studentconductsystem.googlecode.com/files/Flow10.jpg](http://studentconductsystem.googlecode.com/files/Flow10.jpg)

### Identified Scenarios ###

![http://studentconductsystem.googlecode.com/files/Scenes.jpg](http://studentconductsystem.googlecode.com/files/Scenes.jpg)

**_Note:_** Not all feasible scenarios are covered, though all alternate flows are traversed and several general combinations are chosen.

### Variables Used to Realize Scenarios ###

![http://studentconductsystem.googlecode.com/files/TS6-Var.jpg](http://studentconductsystem.googlecode.com/files/TS6-Var.jpg)

### Test Cases ###

Test cases are generated based on flow path and variable options. All variable options are used at least once and most of the scenarios are realized.

![http://studentconductsystem.googlecode.com/files/TS6-TC.jpg](http://studentconductsystem.googlecode.com/files/TS6-TC.jpg)