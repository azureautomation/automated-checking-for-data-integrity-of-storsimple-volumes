Automated checking for data integrity of StorSimple Volumes
===========================================================

            

 

 

This script lets you set up scheduled checks for data corruption in StorSimple volumes and sends a report with the results after every check. It works by cloning StorSimple volumes on to a StorSimple Cloud appliance, connects the volumes to a VM in Azure
 and runs chkdsk utility on those volumes. Since all this happens in a sandbox environment in Azure, your primary StorSimple device is not impacted at all.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
