# Using-ML-to-Aid-in-SBA-Loan-Approvals
Thesis project for my MS in Data Science, "Using ML to Aid in SBA Loan Approvals"

Objective
The goal of this project will be to create a machine learning model that will aid a banker in deciding if a business owner should or should not be approved for a Small Business Administration (SBA) loan based on the likelihood the loan will go into default.

Background
Small Business Administration Backed Loans, or SBA loans for short, is a lending product designed to help small business owners fund, expand, or continue the operations of their businesses (1). This program allows the federal government to guarantee a loan for the bank to offer to a small business owner. This is an important, win-win-win, program. It allows the federal government to directly invest into new businesses and the growth they bring. This program builds the bank’s confidence to lend to a group that would normally be too risky to lend to thus securing itself a whole new client base. Finally, this allows the average business owner, who doesn’t have a rich family or investor friends, to secure the financing they need to make their dreams come to fruition.

The use of a model like this could be twofold. For the banker to have a model to use to quickly estimate if a business owner is likely to pay on their loan and not go into default. I think this model could also be helpful in the hands of the business owner. Preparing to secure an SBA loan can be intimidating. The business owner needs to assemble a business plan, current financials, projected financials and other items to persuade the banker that you would grow your business and be able to pay it back faithfully (2). This model could then be used to help test if the business owner has a compelling case before meeting with the banker to secure the SBA loan.

I have a secondary objective from this model creation. Coming from a background of franchise consulting and seeing how SBA loans can be critical to securing a franchise I am interested in seeing what could help my clients prepare. In the process I am also hoping to learn how investing in a franchise versus starting a new business could lead to a better or worse approval rating for SBA loans.

My hypothesis is that securing an SBA loan to fund the purchase of a franchise will have a positive correlation with SBA loan approval. The U.S. Small Business Administration website even explains some of the advantages of buying a franchise or existing business over the creation of a new one, as well as some of its shortcomings (3). Likewise, I think the SBA loan officer in the local bank would be aware of the differences and see the advantage in lending to a franchisee over someone starting from scratch.

My goal is to gather data from the small business association database that I found in an article for the Journal of Statistics Education entitled ”’Should This Loan be Approved or Denied?’: A Large Dataset with Class Assignment Guidelines” (4). After that I plan to review the data thoroughly, clean, and prepare it for use in training a machine learning model. After the model is created I will create an interface for bankers approving SBA loans, and those interested in applying for them, can use it to make more educated decisions of which loans to approve and which to deny.

Loans. (n.d.). Retrieved from U.S. Small Business Administration: https://www.sba.gov/funding-programs/loans
Fund Your Business. (n.d.). Retrieved from U.S. Small Business Administration: https://www.sba.gov/business-guide/plan-your-business/fund-your-business
Buy an existing business or franchise. (n.d.). Retrieved from U.S. Small Business Administration: https://www.sba.gov/business-guide/plan-your-business/buy-existing-business-or-franchise
Min Li, Amy Mickel & Stanley Taylor (2018) “Should This Loan be Approved or Denied?”: A Large Dataset with Class Assignment Guidelines, Journal of Statistics Education, 26:1, 55-66, DOI: 10.1080/10691898.2018.1434342
Data Description
The data was taken from Min Li, Amy Mickel & Stanley Taylor (2018) “Should This Loan be Approved or Denied?”: A Large Dataset with Class Assignment Guidelines, Journal of Statistics Education, 26:1, 55-66, DOI: 10.1080/10691898.2018.1434342.

This data was collected from the SBA from the years 1987 to 2014.

Code taken from this source: https://www.delftstack.com/howto/python/python-display-image/
import IPython.display as display
from PIL import Image
display.display(Image.open('DataSBADescriptions.png'))

