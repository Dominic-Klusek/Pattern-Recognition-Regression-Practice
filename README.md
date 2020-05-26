# Pattern-Recognition-Regression-Practice
Project from my CSC 732: Pattern Recognition and Neural Networks class for the Spring 2020 term at CUNY College of Staten Island. The assignment centered around working with different datasets and observing the pros and cons between different regression models: Linear, Polyunomial, Logistic, Decision Trees, and Random Forest Regression.

<h1>Datasets Used:</h1>
<h2>SkillCraft</h2>
<p>This dataset contains player statistics of ranked players for the game StarCraft. In the game players build forces of soldiers to claim objectives, and ultimately defeat the other player. The players primarily use the mouse to move and select units, and use the keyboard to use hotkeys to select and build units and upgrades. The authors aggregated screen movements into screen-fixations using a Salvucci & Goldberg (2000) dispersion-threshold algorithm, and defined Perception Action Cycles (PACs) as fixations with at least one action. </p>

<ul>
    <li><strong>Number of Instances: </strong>3395</li>
    <li><strong>Number of Attributes: </strong>20</li>
</ul>

<h3>Attribute Information:</h3>
<ol>
    <li><code>GameID</code>: Unique ID number for each game (integer)</li>
<li><code>LeagueIndex</code>: Bronze, Silver, Gold, Platinum, Diamond, Master, GrandMaster, and Professional leagues coded 1-8 (Ordinal)</li>
<li><code>Age</code>: Age of each player (integer)</li>
<li><code>HoursPerWeek</code>: Reported hours spent playing per week (integer)</li>
<li><code>TotalHours</code>: Reported total hours spent playing (integer)</li>
<li><code>APM</code>: Action per minute (continuous)</li>
<li><code>SelectByHotkeys</code>: Number of unit or building selections made using hotkeys per timestamp (continuous)</li>
<li><code>AssignToHotkeys</code>: Number of units or buildings assigned to hotkeys per timestamp (continuous)</li>
<li><code>UniqueHotkeys</code>: Number of unique hotkeys used per timestamp (continuous)</li>
<li><code>MinimapAttacks</code>: Number of attack actions on minimap per timestamp (continuous)</li>
<li><code>MinimapRightClicks</code>: number of right-clicks on minimap per timestamp (continuous)</li>
<li><code>NumberOfPACs</code>: Number of PACs per timestamp (continuous)</li>
<li><code>GapBetweenPACs</code>: Mean duration in milliseconds between PACs (continuous)</li>
<li><code>ActionLatency</code>: Mean latency from the onset of a PACs to their first action in milliseconds (continuous)</li>
<li><code>ActionsInPAC</code>: Mean number of actions within each PAC (continuous)</li>
<li><code>TotalMapExplored</code>: The number of 24x24 game coordinate grids viewed by the player per timestamp (continuous)</li>
<li><code>WorkersMade</code>: Number of SCVs, drones, and probes trained per timestamp (continuous)</li>
<li><code>UniqueUnitsMade</code>: Unique unites made per timestamp (continuous)</li>
<li><code>ComplexUnitsMade</code>: Number of ghosts, infestors, and high templars trained per timestamp (continuous)</li>
<li><code>ComplexAbilitiesUsed</code>: Abilities requiring specific targeting instructions used per timestamp (continuous)</li>
</ol>

<h2>Credit-Risk</h2>
<p>This dataset contains information about applicants applying for a loan. </p>

<ul>
    <li><strong>Number of Instances: </strong>981</li>
    <li><strong>Number of Attributes: </strong>13</li>
</ul>

<h3>Attribute Information:</h3>
<ol>
    <li><code>Loan_ID</code>: unique identifier of applicant</li>
    <li><code>Gender</code>: gender of the applicant (binary)</li>
    <li><code>Married</code>: marital status of applicant(binary)</li>
    <li><code>Dependent</code>: number of dependents of the applicant(integer 1-3)</li>
    <li><code>Education</code>: education level of applicant(binary)</li>
    <li><code>Self_Employed</code>: self employment status of applicant(binary)</li>
    <li><code>ApplicantIncome</code>: monthly income of applicant(integer)</li>
    <li><code>CoapplicantIncome</code>: monthly income of Coapplicant(integer)</li>
    <li><code>LoanAmount</code>: amount requested by applicant(continuous)</li>
    <li><code>Loan_Amount_Term</code>: term of loan(integer)</li>
    <li><code>Credit_History</code>: meansure of credit history(continuous)</li>
    <li><code>Property_Area</code>: type of area in which applicant lives(binary)</li>
    <li><code>Loan_Status</code>: whether the loan was approved or not(binary)</li>
</ol>
