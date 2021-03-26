# Many abilities that initiate a run contain a conditional ability with the trigger condition “If successful”. This means, “After the run created this way becomes successful”.

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. If an effect that initiates a run specifies that that run must be made against a specific server or servers, any “If successful” abilities associated with that effect are tied to that server or servers. If the attacked server has changed since the run was initiated, and no longer is a server that could have been chosen for this run, the “If successful” abilities do not **meet their trigger conditions**.

*Example: The Runner plays Because I Can, which directs them to make a run on a remote server. If an effect moves the run to a central server, the “If successful” effect on Because I Can will not apply. However, if the run is moved instead to another remote server, the “If successful” effect is still applied, since Because I Can would have allowed a run on the second remote server to begin with.*

***
_Created with the Personal Edition of HelpNDoc: [Create help files for the Qt Help Framework](<https://www.helpndoc.com/feature-tour/create-help-files-for-the-qt-help-framework>)_
