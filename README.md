# Empowering-Small-Businesses-Understanding-SBA-Loan-Inspections
We inspected a data set produced by the Small Business Administration (SBA), a federal agency that helps American business owners by providing loans, grants, information, training, and other resources.

There were 899,164 loans included in the data overall, with 27 columns. Each row corresponded to a single loan.

We focused on the following columns:
State
NAICS (Industry Code)
ApprovalDate
NewExist (whether the business was a new or existing business)
CreateJob (number of jobs created)
RetainedJob (number of jobs retained)
DisbursementGross
BalanceGross
MIS_Status (whether the loan was charged off (went into default) or paid in full)
SBA_Appv (the total amount of SBA loan approval for the client)
# Purpose:
Using these columns we made predictions through models like LogisticRegression, Nearest Neighbors, and Confusion Matrices to predict if a loan was likely to default or be paid in full
