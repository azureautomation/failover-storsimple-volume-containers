Failover StorSimple Volume Containers
=====================================

            
 

 

This runbook performs a failover of the StorSimple volume containers in the context of Azure Site Recovery(ASR) recovery plan.


 

 

Unplanned failover - The specific volume containers are failed over to the target StorSimple device.

 

Planned failover - Backups of all the volumes in the volume container are taken based on th ebackup policies and then the volume containers are failed over to the target StorSimple device.

 

Test failover - All the volumes in the volume container are cloned to the target StorSimple device.

 

Failback - It performs the same steps as the planned failover with source device and the target device swapperd.

 

 

 

 



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
