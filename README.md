# ERP-Software-testing-bug-reporting
[ERP software testing & bug report - Project.csv](https://github.com/user-attachments/files/24111921/ERP.software.testing.bug.report.-.Project.csv)
Test Case ID,Menu,Bug Type,Test Steps,Expected Result,Actual Result,Priority,Status,Notes
BUG-PRO-008,Project>Inventory> Products> brand,Controller Response / Debug Code,"1. Go to Inventory> Products > Add Brand
2. Click Submit.",User should see a success message,Error popup displayed with raw dump code,High,Pending,
BUG-PRO-009,Dashboard > Project Summary,Functional Issue,"1. Open Dashboard.
2. Click on Task count.",System should redirect to the Task list page.,No response,High,Pending,
BUG-PRO-010,Dashboard > Project Summary,Functional Issue,"1. Open Dashboard.
2. Click on Sub Task count.
",System should redirect to the Sub Task list page.,No response,High,Pending,
BUG-PRO-011,Setting> Approval Layer,Page Layout issue,"1. Go to setting 
2. Dropdown the menu 
3. Click on approval layer",all element showing properly,invoice showing nvoice,Low,Pending,
BUG-PRO-012,Project → BOQ Titles,Database/ Migration Issue,"1. Go to project 
2. click on project detials",System should display BOQ titles without any error.,1146 Table 'parcintegrate.boq_titles' doesn't exist,High,Pending,Parc Integrate ltd
BUG-PRO-013,Project > Project type,Route Not Define,"1. Login 
2. Navigate to Project and click on Project type",Page should load,Internal Server Error,High,Done,
BUG-PRO-014,Project > Project> Reports,Syntax error or access violation,"1. Go to Pms
2. Navigate to project and go to reports
3. Click on Search Project summary reports ",Genarate summary reports,Internal Server Error,High,Done,
BUG-PRO-015,Project > Project> Reports,Backend Integration / Data Load Issue,"1. Login to System
2. Go to project> Reports
3. Project Financial Reports",DataTable should fetch and display records without error.,"Popup shows: ""DataTables warning: table id=dataTable - Ajax error.""
No data loaded.",High,Done,
BUG-PRO-016,Investment> Configaration,Database Error,"1. Login to system.
2. Navigate to Investment Configurations menu
3. System tries to fetch data from DB.",System should load the page and display investment configuration records (or show empty state if no records).,"Popup/Error shown:""SQLSTATE[42S02]: Base table or view not found: 1146 Table 'pms.investment_configurations' doesn't exist""",High,Done,
BUG-PRO-017,Share Project>share Reports,Syntax error or access violation,"1. Login to system
2. Navigate to share project
3. Go to share reports 
4. Click on Share Collection Reprots",Genarate share collection reports,Internal Server Error,High,Done,
BUG-PRO-018,Flat/Land,DataTables warning,1. Navigate to Flat/land,DataTable should fetch and display records without error.,Popup Shows: table id=designation_table - Ajax error,High,Done,
BUG-PRO-019,Billing > BOQ> Add Boq,General error,"1. go to billing
2. add to BOQ ",contract id should be null,database error,High,Done,
