# XperienceProgressBarForSalesforceClassic


	In Salesforce Experience, we see a beautiful multi-colored progrss bar on Opportunity detail. 
	This app/package helps to replicate the same in Salesforce Classic view of Opportunity. 
	
	This progress bar is based on Opportunity Stage standard field. 
	
	Some post-installation steps are identified below to help you get going.
	
	
	Step #1

    XperienceProgressBarForSalesforceClassic
    Version 1.3
    
      Use this URL to install the package into any organization:
      
      		https://login.salesforce.com/packaging/installPackage.apexp?p0=04t90000000NOPH 
      
      Note: If you are installing into a sandbox organization you must replace the initial portion of the URL with http://test.salesforce.com
   
  Step #2

    Click Install button.
    Some post-installation steps are identified below to help you get going.

  Step #3

    After installation, edit your Opportunity page layout to add a one column Section with '.' (a dot) as its name just above detail section as shown in screen shot below.


  Step #4

    Drag and drop this VF page "Slds_OpportunityProgressBar_Page" inside the added section.

  Step #5

    Set the VF properties(width= 100%; height=80) by clicking on wrench icon as shown in image below.

  Step #6

    Save your page layout to get the view as shown in this image.


Quite simple. Isn't it?   :)

Note: This is designed exclusively for Opportunity stage field. However it can be tweaked to get it working for other objects as well.
