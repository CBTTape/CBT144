# CBT144
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 144 IS FROM PAT SHROUT OF WASHINGTON STATE DEPARTMENT OF  *   FILE 144
//*           TRANSPORTATION. THIS FILE CONTAINS A MODIFIED VPS     *   FILE 144
//*           USER EXIT 14 (DATASET ADD EXIT)                       *   FILE 144
//*                                                                 *   FILE 144
//*           THIS EXIT ALLOWS INSERTION OF DATA (PRINT OR          *   FILE 144
//*           CONTROL) BOTH BEFORE AND AFTER EACH DATASET AND       *   FILE 144
//*           SEPARATOR PROCESSED BY VPS.                           *   FILE 144
//*                                                                 *   FILE 144
//*           THIS EXIT IS USED TO SEND PRINTER CONTROL             *   FILE 144
//*           INFORMATION TO THE XEROX LASER PRINTERS AHEAD OF A    *   FILE 144
//*           DATASET.  BEFORE PROCESSING A DATASET, THIS EXIT      *   FILE 144
//*           CHECKS TO SEE IF A FORM WAS ENTERED.  IF A FORM WAS   *   FILE 144
//*           ENTERED, THIS EXIT USES THE FORM NAME AS THE MEMBER   *   FILE 144
//*           NAME AND OPENS A FORMS FILE.  THE MEMBER              *   FILE 144
//*           INFORMATION IS THEN READ AND SENT TO THE PRINTER TO   *   FILE 144
//*           SET IT UP AHEAD OF THE DATASET.  IF THERE WAS NO      *   FILE 144
//*           FORM ENTERED, THIS EXIT IS EXITED.  AFTER PRO-        *   FILE 144
//*           CESSING A DATASET ON A LASER PRINTER, REGARDLESS OF   *   FILE 144
//*           WHETHER A FORM WAS ENTERED OR NOT, A RESET COMMAND    *   FILE 144
//*           IS SENT TO THE PRINTER.                               *   FILE 144
//*                                                                 *   FILE 144
//*           THIS EXIT WAS CODED TO BE USED WITH XEROX LASER       *   FILE 144
//*           PRINTERS, BUT THE ONLY XEROX DEPENDENT CODE IS THE    *   FILE 144
//*           RESET COMMAND.  THIS EXIT COULD EASILY HANDLE ANY     *   FILE 144
//*           OTHER TYPE, OR MANY OTHER TYPES, OF PRINTERS BY       *   FILE 144
//*           CHECKING THE VALUE IN THE PRASEPI FIELD AND TAKING    *   FILE 144
//*           THE APPROPRIATE ACTION.  THIS COULD BE, MOVING IN A   *   FILE 144
//*           DIFFERENT DDNAME, ISSUING A DIFFERENT RESET           *   FILE 144
//*           COMMAND, SENDING OUT A CONTROL STRING, OR WHATEVER.   *   FILE 144
//*                                                                 *   FILE 144
```
