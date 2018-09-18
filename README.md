# clock-process
1.User call to call center
2. System require user choose language: 1: for English, 2. For Vietnamese
3. User choose language, system verify, set language and move to next step
4. System require Employee input employee ID
5. System verify employee ID make sure it's valid, if valid move to next step, if not require enter again
6. System require user input shift ID
7. System verify shift ID make sure, shift ID exist and correct time (shifts have start_time, end_time (Y-m-d H:i)). If existed move to next step
8. System require enter 1: for clock in, 2: for clock out.
9. System verify clock action. System only clock in earlier or late than start time 15 mins. Clock out valid if: shift already clocked in, time for clock earlier or late than end_time 15 mins.

Request:
- Implement classes in PHP OOP or Laravel to do this requirement.
