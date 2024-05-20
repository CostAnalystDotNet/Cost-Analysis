# Spend Plan Line Item Transformation (SPLIT) Tool

## Version 1.0

## Description
The Spend Plan Line Item Transformation (SPLIT) Tool is an open-source tool designed to streamline the process of transforming spend plan data into more granular, Technology Business Management taxonomy-aligned data.

The Spend Plan Line Item Transformation (SPLIT) Tool is meant to be used along side Spend Plan Allocation Method (SPAM) templates, which are included in this package.

Please follow the installation instructions carefully.

## Features
- Transform Spend Plan data into a standardized cost model and data visualization compatible output
- Automatically import Spend Plan Data and Allocation Method data
- Override previously assigned allocation methods with custom allocation methods

## Installation Instructions
For simplicity's sake, the Spend Plan Line Item Transformation (SPLIT) Tool and related tools and templates are meant to be run from your desktop.

Download the package from GitHub at the following link: https://github.com/CostAnalystDotNet/Cost-Analysis/tree/main

Copy or extract the "CostAnalysis" folder and all its contents to your desktop. NOTE: You may add new sub folders, but do not change existing folder names, including the "CostAnalysis" root folder, unless you know what you are doing.

It is recommended to create a copy of the "Spend Plan Line Item Transformation (SPLIT) Tool" folder and rename it for each instance of the tool you plan to work on (e.g., "Spend Plan Line Item Transformation (SPLIT) Tool - FY23", "Spend Plan Line Item Transformation (SPLIT) Tool - FY24", "Spend Plan Line Item Transformation (SPLIT) Tool - FY25", etc.) 

## Configuration Instructions
You will need to change the file path of your tool before you can use it. Follow the instructions below carefully.

1. Open the CostAnalyst.net folder on your desktop, then open the folder you created for your project (e.g., "C:\Users\JohnSmith\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool - FY23").

2. In Window's file explorer, copy the folder path (e.g., "C:\Users\JohnSmith\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool - FY23").

3. Open the "SPLIT Tool.xlsx" file.

4. On the menu bar at the top of the screen, choose 'Data', then click on "Get Data" and finally choose "Launch Power Query Editor..." from the dropdown menu.

5. You will now update the following queries to include your personal file folder path. Please follow the instructions below carefully.
	
	"Sample File" query
	a. Choose the "Sample File" query in the Helper Queries [3] folder and click on Advanced Editor at the top of your screen.
	b. In the advanced editor, you want to replace the file path found here with your the file path of your project. Carefully replace ONLY the following text in the following manner:
		- find "C:\Users\CostAnalyst.net\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool"
		- replace with the file path of your project (e.g., "C:\Users\JohnSmith\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool - FY23")
		NOTE: Only replace the exact text found here. Do not delete any follow-on text or file path.
	c. Click done. The error indicator for this query should now go away. Proceed to next query.
	
	"SPAR Data" query
	a. Choose the "SPAR Data" query in the Other Queries [6] folder and click on Advanced Editor at the top of your screen.
	b. In the advanced editor, you want to replace the file path found here with your the file path of your project. Carefully replace ONLY the following text in the following manner:
		- find "C:\Users\CostAnalyst.net\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool"
		- replace with the file path of your project (e.g., "C:\Users\JohnSmith\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool - FY23")
		NOTE: Only replace the exact text found here. Do not delete any follow-on text or file path.
	c. Click done. The error indicator for this query should now go away. Proceed to next query.

	"Allocation Method Library" query
	a. Choose the "Allocation Method Library" query in the Other Queries [6] folder and click on Advanced Editor at the top of your screen.
	b. In the advanced editor, you want to replace the file path found here with your the file path of your project. Carefully replace ONLY the following text in the following manner:
		- find "C:\Users\CostAnalyst.net\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool"
		- replace with the file path of your project (e.g., "C:\Users\JohnSmith\Desktop\Cost Analysis\Spend Plan Line Item Transformation (SPLIT) Tool - FY23")
		NOTE: Only replace the exact text found here. Do not delete any follow-on text or file path.
	c. Click done. The error indicator for this query should now go away. This was the final query to update.

6. In the Power Query Editor, check that all errors have been cleared then click "Save & Load". 

7. If you have already populated a "Spend Plan Alignment Review (SPAR) Tool", copy the file and paste it into the "Spend Plan Alignment Review (SPAR) Tool" subfolder. If you have not yet completed a Spend Plan Alignment Review Tool for your project, please follow the link below to learn more.

https://github.com/CostAnalystDotNet/Cost-Analysis/tree/main/Spend%20Plan%20Alignment%20Review%20(SPAR)%20Tool

8. If you have already populated one or more "Spend Plan Allocation Method (SPAM) Template", copy the file(s) and paste into the "Spend Plan Allocation Method (SPAM) Template" subfolder. If you have not yet completed a Spend Plan Allocation Method (SPAM) Template for your project, please follow the link below to learn more.

https://github.com/CostAnalystDotNet/Cost-Analysis/tree/main/Spend%20Plan%20Allocation%20Method%20(SPAM)%20Template


## Usage Instructions
1. Open the "SPLIT Tool.xlsx" in your root folder. NOTE: Never change the name of this file. If you'd like to create 
2. Refresh and review the query on each of the following tabs:


## License
This project is licensed under the GNU General Public License version 3.0 [Here is a link to the full license text](https://github.com/CostAnalystDotNet/Cost-Analysis/blob/main/LICENSE).

## Contributing
If you'd like to contribute to this project, please fork the repository and issue a pull request. 

## Credits
CostAnalystDotNet (CostAnalystDotNet@Gmail.com)

## Contact Information
For questions or feedback, contact [Your Contact Information].

## Legal Disclaimer
License Overview		
		
	GNU General Public License (GPL) Overview	
		
	This tool is distributed under the GNU General Public License (GPL), which is a widely used free software license that guarantees end users the freedom to run, study, share, and modify the software. The GPL is designed to ensure that the software remains free for all its users. Here are the key features:	
		
	Freedom to Use: Users can run the software for any purpose without restrictions.	
	Freedom to Modify: Users have the freedom to modify the software according to their needs. Any modifications must also be made available under the GPL if they are distributed.	
	Freedom to Share: Users can copy and share the software with others. This is aimed at helping the community benefit from shared knowledge and enhancements.	
	Source Code: The GPL requires that the source code be made available to anyone who receives a copy of the software. This ensures that users can access and modify the source code.	
		
	The GPL aims to protect these freedoms, ensuring that all users have the legal right to control their own computing. For detailed terms, please refer to the full text of the GPL (https://www.gnu.org/licenses/gpl-3.0.en.html).	
		
	Full GPL Text:	
	https://www.gnu.org/licenses/gpl-3.0.en.html	
		
		
Copyright Notice		
		
	Copyright © 2024 by CostAnalystDotNet. All rights reserved.	
		
		
Disclaimer of Warranty		
		
	This tool is provided 'as is', without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors, copyright holders, or distributors be liable for any claim, damages, or other liability, whether in an action of contract, tort or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.	
		
	Use of this tool is at your own risk and discretion and you should ensure that the tool is suitable for your use and complies with all applicable laws and regulations.	
		
		
Contribution Guidelines		
		
	As of now, this tool is developed independently, and I am still exploring the best ways to manage and integrate contributions from others. While I'm not actively seeking contributions at this time, I am open to feedback and suggestions which can be submitted via email to costanalystdotnet@gmail.com .	
		
	I appreciate the interest and support from the community, and I am committed to learning more about open source collaboration. As I become more familiar with the process and community practices, I plan to update these guidelines to reflect a more structured approach for contributions.	
		
		
Attribution and Acknowledgments		
		
	This tool utilizes the Technology Business Management (TBM) taxonomy, specifically Version 4.0 as of December 2020. The TBM taxonomy is developed and maintained by the Technology Business Management Council, and it is an integral framework designed to standardize the categorization and understanding of IT costs and services. We acknowledge and appreciate the efforts of the TBM Council in developing and providing this taxonomy, which has been instrumental in shaping this tool. For more information about TBM, the TBM Council, or the TBM Taxonomy, please visit the TBM Council website at the following link:	
	https://www.tbmcouncil.org/	
		
	Always refer to the TBM Council for the most up-to-date information on the TBM taxonomy. Please visit the TBM Council's official documentation at the following link:	
	https://community.tbmcouncil.org/viewdocument/tbm-taxonomy-v40-final-documents	
		
	We encourage interested parties to consider joining the TBM community for more resources and networking opportunities. For TBM community membership details, please visit TBM Council Membership website at the following link:	
	https://www.tbmcouncil.org/get-involved/membership	
		
	Thank you again to the TBM Council for their valuable work and for providing the resources that support the IT and business management communities.	
		
		
Usage Guidelines		
		
	This tool is provided under the GNU General Public License (GPL), which allows users to freely use, modify, and distribute the software. Here are some key points to consider when using or modifying this tool:	
		
	Freedom to Use and Modify: You are free to use and modify this tool for any purpose. This freedom ensures that all users can adapt the tool to meet their specific needs without any restrictions.	
	Sharing Modifications: If you choose to modify this tool and distribute the modified version, the GPL requires that these modifications also be made available under the same GPL license. This ensures that the modified versions remain free and open, contributing to the community and preventing proprietary forks.	
	Contributing Back: While not mandatory, if you make improvements or modifications to the tool, contributing back to the original project can help improve the tool for everyone. Sharing improvements can foster a collaborative environment and enhance the tool's capabilities.	
	Compliance with the GPL: It is important to understand and comply with the terms of the GPL when using or modifying this tool. Compliance ensures that the rights and freedoms intended by the GPL are upheld, benefiting users and developers alike.	
		
	For a complete understanding of your rights and responsibilities under the GPL, please review the full license text.	
		
	Full GPL Text:	
	https://www.gnu.org/licenses/gpl-3.0.en.html	
		
		
Contact Information		
		
	Email:	costanalystdotnet@gmail.com
	GitHub: https://github.com/CostAnalystDotNet
