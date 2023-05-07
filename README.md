Download Link: https://assignmentchef.com/product/solved-icsi410-assignment-3
<br>
Write 10 separate SQL queries, named “Query21” through “Query30”. Put them in the same Access file you used to submit your first and second assignments. Each query will contain a SQL statement that is your solution for the translation of a “plain English” request. Each query is worth one point. The 10 “plain English” queries are:




<ol start="21">

 <li>Display cid, clast, and cfirst for customers whose (last name starts with a “D” and has a “v” in the third position) or (first name ends with an “a”).</li>

 <li>Display all the columns in Invoice for those invoices that have less than the average iprice.</li>

 <li>Display all the columns in Customer for those customers who purchased a vehicle that has the same date value in icontract and isold. In other words, customers who signed a contract and completed the sale of a vehicle on the same day so they could drive it home that same day.</li>

 <li>Display all the columns in Employee for those employees who sold at least one vehicle within 7 days of being hired.</li>

 <li>Display all the columns in Customer for those customers that have relationships but have never been a purchaser. In other words, formed one or more relationships with dealerships shopping for a car, but never became a purchaser by buying one.</li>

 <li>Display all the columns in Employee for those employees who sold at least one vehicle owned by a dealership that is different from the dealership they work for.</li>

 <li>Display all the columns in Dealership whose employees collectively sold more than $200,000 worth of vehicles in the month of February, 2018. The $200,000 limit could be exceeded by just one employee, or by a team of employees working at the same dealership each selling less than $200,000 individually; either case is valid.</li>

 <li>Display all the columns in Invoice for those invoices with the 3 lowest unique iprice values. Note that there may be more than one invoice for each of the 3 lowest iprice values.</li>

 <li>Display all the columns in Vehicle for those vehicles sold two or more times and at least one resale price is more than the first (initial) sale price.</li>

 <li>Display vvin, vyear, vmake, vbody, vcolor, cid, clast, cfirst, cmi for those customers who purchased the same vehicle more than once.</li>

</ol>

The rules for assignment #1 and #2 are still in effect for this assignment. Be sure to re-read them.

There is one additional rule: Use native SQL syntax for date arithmetic; do <strong><u>not</u></strong> use any functions, such as DateDiff, to do date arithmetic.