# CBT584
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 584 is from Ugur Cilesiz, and contains a job with REXX    *   FILE 584
//*           execs and other nice things, which automates the      *   FILE 584
//*           initialization of DASD.  This job is useful in a      *   FILE 584
//*           disaster recovery situation, and is also good for     *   FILE 584
//*           "everyday" use, too.  The job is called AUTOINIT.     *   FILE 584
//*                                                                 *   FILE 584
//*           Phone extern   : +49-2181-285-218                     *   FILE 584
//*           Phone Fax      : +49-2181-285-203                     *   FILE 584
//*           MailTo:Ugur.Cilesiz@Rwesystems.com                    *   FILE 584
//*                                                                 *   FILE 584
//*      DESCRIPTION:  DASD MANAGEMENT IN BATCH                     *   FILE 584
//*                                                                 *   FILE 584
//*                   *  VARY OFFLINE THE UNITS                     *   FILE 584
//*                   *  ICKDSF INIT DASD                           *   FILE 584
//*                   *  VARY ONLINE THE UNITS                      *   FILE 584
//*                   *  IDCAMS DEFINE VVDS                         *   FILE 584
//*                   *  IDCAMS DEFINE GDG'S FOR DISASTER REC.      *   FILE 584
//*                                                                 *   FILE 584
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 584
//*                                                                 *   FILE 584
//*      HOW TO USE :  1. FIND //INITIAL                            *   FILE 584
//*                    2. FILL IN THE SYSUT1 CARD THE FIELDS        *   FILE 584
//*                       NEWVOLUME  OLDVOLUME UNITADR SMS-BIT      *   FILE 584
//*                       AND STYPE                                 *   FILE 584
//*                                                                 *   FILE 584
//*                       SMS-BIT :  1 = SMS MANAGED                *   FILE 584
//*                                  0 = NOT SMS MANAGED            *   FILE 584
//*                                                                 *   FILE 584
//*                       STYPE   :  0 = NO BACKUP                  *   FILE 584
//*                                  T = DAILY BACKUP               *   FILE 584
//*                                  N = WEEKLY BACKUP              *   FILE 584
//*                                  B = BOTH ( T + N )             *   FILE 584
//*                                                                 *   FILE 584
//*                       OLDVOLUME: + = NOVERIFY                   *   FILE 584
//*                                                                 *   FILE 584
//*                    3. SUBMIT THE JOB                            *   FILE 584
//*                                                                 *   FILE 584
```
