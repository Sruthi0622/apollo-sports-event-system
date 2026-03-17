Sports Event Management System – Test Cases
Test Case 1 – Landing Page Load

Expected Result:

Page loads without delay

Apollo University name is visible

Current event is displayed

Navigation menu works

Test Case 2 – View Games Page

Expected Result:

Games displayed:

Cricket

Kabaddi

Volleyball

Badminton

No missing or duplicate entries

Test Case 3 – Open Game Details

Expected Result:

Game name is correct

Rules are displayed properly

Register button is visible

No layout issues

Test Case 4 – Valid Player Registration

Expected Result:

Data saved in database

Player appears in list immediately

No duplicate entry created

Test Case 5 – Invalid Registration (IMPORTANT)

Add more strict checks:

Test inputs:

Empty name

Invalid phone (letters)

Short phone number

Expected Result:

Proper error message shown

Form should NOT submit

Test Case 6 – Multiple Game Registration

👉 You completely missed this (but your system supports it)

Expected Result:

Same player can register for multiple games

Data stored correctly for each game

Test Case 7 – Player List Display

Expected Result:

Correct player names shown

No duplicates

Data matches database

Test Case 8 – Role-Based Score Update (CRITICAL)

You wrote login, but didn’t test restriction.

Check BOTH:

Case A (Authorized user)

Volunteer/PT can update score ✅

Case B (Normal user)

Cannot edit score ❌

Test Case 9 – Live Score Visibility

Expected Result:

Score visible to all users

Updates reflect instantly

Test Case 10 – Winner Display

Expected Result:

Winner name correct

Matches score data

Visible in game + history

Test Case 11 – View Past Events

Expected Result:

Old events visible

Data is read-only

No editing allowed

Test Case 12 – Navigation Flow

Expected Result:

No broken links

No page crashes

Back/forward works