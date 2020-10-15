# ShellCheatSheet
A basic cheat sheet for SHELL commands


 <br />a! <br />a/bin/bash

 <br />a <br />a <br />a <br />a <br />aECHO <br />aCOMMAND
 <br />a <br />aecho <br />aHello <br />aWorld!

 <br />a <br />aVARIABLES
 <br />a <br />aUppercase <br />aby <br />aconvention
 <br />a <br />aLetters, <br />anumbers, <br />aunderscores
 <br />a <br />aNAME="Bob"
 <br />a <br />aecho <br />a"My <br />aname <br />ais <br />a$NAME"
 <br />a <br />aecho <br />a"My <br />aname <br />ais <br />a${NAME}"

 <br />a <br />aUSER <br />aINPUT
 <br />a <br />aread <br />a-p <br />a"Enter <br />ayour <br />aname: <br />a" <br />aNAME
 <br />a <br />aecho <br />a"Hello <br />a$NAME, <br />anice <br />ato <br />ameet <br />ayou!"

 <br />a <br />aSIMPLE <br />aIF <br />aSTATEMENT
 <br />a <br />aif <br />a[ <br />a"$NAME" <br />a== <br />a"Brad" <br />a]
 <br />a <br />athen
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aBrad"
 <br />a <br />afi

 <br />a <br />aIF-ELSE
 <br />a <br />aif <br />a[ <br />a"$NAME" <br />a== <br />a"Brad" <br />a]
 <br />a <br />athen
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aBrad"
 <br />a <br />aelse <br />a
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aNOT <br />aBrad"
 <br />a <br />afi

 <br />a <br />aELSE-IF <br />a(elif)
 <br />a <br />aif <br />a[ <br />a"$NAME" <br />a== <br />a"Brad" <br />a]
 <br />a <br />athen
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aBrad"
 <br />a <br />aelif <br />a[ <br />a"$NAME" <br />a== <br />a"Jack" <br />a]
 <br />a <br />athen <br />a <br />a
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aJack"
 <br />a <br />aelse <br />a
 <br />a <br />a <br />a <br />aecho <br />a"Your <br />aname <br />ais <br />aNOT <br />aBrad <br />aor <br />aJack"
 <br />a <br />afi

 <br />a <br />aCOMPARISON
 <br />a <br />aNUM1=31
 <br />a <br />aNUM2=5
 <br />a <br />aif <br />a[ <br />a"$NUM1" <br />a-gt <br />a"$NUM2" <br />a]
 <br />a <br />athen
 <br />a <br />a <br />a <br />aecho <br />a"$NUM1 <br />ais <br />agreater <br />athan <br />a$NUM2"
 <br />a <br />aelse
 <br />a <br />a <br />a <br />aecho <br />a"$NUM1 <br />ais <br />aless <br />athan <br />a$NUM2"
 <br />a <br />afi

 <br />a <br />a <br />a <br />a <br />a <br />a <br />a <br />a
 <br />a <br />aval1 <br />a-eq <br />aval2 <br />aReturns <br />atrue <br />aif <br />athe <br />avalues <br />aare <br />aequal
 <br />a <br />aval1 <br />a-ne <br />aval2 <br />aReturns <br />atrue <br />aif <br />athe <br />avalues <br />aare <br />anot <br />aequal
 <br />a <br />aval1 <br />a-gt <br />aval2 <br />aReturns <br />atrue <br />aif <br />aval1 <br />ais <br />agreater <br />athan <br />aval2
 <br />a <br />aval1 <br />a-ge <br />aval2 <br />aReturns <br />atrue <br />aif <br />aval1 <br />ais <br />agreater <br />athan <br />aor <br />aequal <br />ato <br />aval2
 <br />a <br />aval1 <br />a-lt <br />aval2 <br />aReturns <br />atrue <br />aif <br />aval1 <br />ais <br />aless <br />athan <br />aval2
 <br />a <br />aval1 <br />a-le <br />aval2 <br />aReturns <br />atrue <br />aif <br />aval1 <br />ais <br />aless <br />athan <br />aor <br />aequal <br />ato <br />aval2
 <br />a <br />a <br />a <br />a <br />a <br />a <br />a <br />a

 <br />a <br />aFILE <br />aCONDITIONS
 <br />a <br />aFILE="test.txt"
 <br />a <br />aif <br />a[ <br />a-e <br />a"$FILE" <br />a]
 <br />a <br />athen
 <br />a <br />a <br />a <br />aecho <br />a"$FILE <br />aexists"
 <br />a <br />aelse
 <br />a <br />a <br />a <br />aecho <br />a"$FILE <br />adoes <br />aNOT <br />aexist"
 <br />a <br />afi

 <br />a <br />a <br />a <br />a <br />a <br />a <br />a <br />a
 <br />a <br />a-d <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />ais <br />aa <br />adirectory
 <br />a <br />a-e <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />aexists <br />a(note <br />athat <br />athis <br />ais <br />anot <br />aparticularly <br />aportable, <br />athus <br />a-f <br />ais <br />agenerally <br />aused)
 <br />a <br />a-f <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />aprovided <br />astring <br />ais <br />aa <br />afile
 <br />a <br />a-g <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />agroup <br />aid <br />ais <br />aset <br />aon <br />aa <br />afile
 <br />a <br />a-r <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />ais <br />areadable
 <br />a <br />a-s <br />afile <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />ahas <br />aa <br />anon-zero <br />asize
 <br />a <br />a-u <br />a <br />a <br />a <br />aTrue <br />aif <br />athe <br />auser <br />aid <br />ais <br />aset <br />aon <br />aa <br />afile
 <br />a <br />a-w <br />a <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />ais <br />awritable
 <br />a <br />a-x <br />a <br />a <br />a <br />aTrue <br />aif <br />athe <br />afile <br />ais <br />aan <br />aexecutable
 <br />a <br />a <br />a <br />a <br />a <br />a <br />a <br />a

 <br />aCASE <br />aSTATEMENT
 <br />a <br />aread <br />a-p <br />a"Are <br />ayou <br />a21 <br />aor <br />aover? <br />aY/N <br />a" <br />aANSWER
 <br />a <br />acase <br />a"$ANSWER" <br />ain <br />a
 <br />a <br />a <br />a <br />a[yY] <br />a| <br />a[yY][eE][sS])
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"You <br />acan <br />ahave <br />aa <br />abeer <br />a:)"
 <br />a <br />a <br />a <br />a <br />a <br />a;;
 <br />a <br />a <br />a <br />a[nN] <br />a| <br />a[nN][oO])
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"Sorry, <br />ano <br />adrinking"
 <br />a <br />a <br />a <br />a <br />a <br />a;;
 <br />a <br />a <br />a <br />a*)
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"Please <br />aenter <br />ay/yes <br />aor <br />an/no"
 <br />a <br />a <br />a <br />a <br />a <br />a;;
 <br />a <br />aesac

 <br />a <br />aSIMPLE <br />aFOR <br />aLOOP
 <br />a <br />aNAMES="Brad <br />aKevin <br />aAlice <br />aMark"
 <br />a <br />afor <br />aNAME <br />ain <br />a$NAMES
 <br />a <br />a <br />a <br />ado
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"Hello <br />a$NAME"
 <br />a <br />adone

 <br />a <br />aFOR <br />aLOOP <br />aTO <br />aRENAME <br />aFILES
 <br />a <br />aFILES=$(ls <br />a*.txt)
 <br />a <br />aNEW="new"
 <br />a <br />afor <br />aFILE <br />ain <br />a$FILES <br />a <br />a
 <br />a <br />a <br />a <br />ado
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"Renaming <br />a$FILE <br />ato <br />anew-$FILE"
 <br />a <br />a <br />a <br />a <br />a <br />amv <br />a$FILE <br />a$NEW-$FILE
 <br />a <br />adone

 <br />a <br />aWHILE <br />aLOOP <br />a- <br />aREAD <br />aTHROUGH <br />aA <br />aFILE <br />aLINE <br />aBY <br />aLINE
 <br />a <br />aLINE=1
 <br />a <br />awhile <br />aread <br />a-r <br />aCURRENT_LINE
 <br />a <br />a <br />a <br />ado
 <br />a <br />a <br />a <br />a <br />a <br />aecho <br />a"$LINE: <br />a$CURRENT_LINE"
 <br />a <br />a <br />a <br />a <br />a <br />a((LINE++))
 <br />a <br />adone <br />a< <br />a"./new-1.txt"

 <br />a <br />aFUNCTION
 <br />a <br />afunction <br />asayHello() <br />a{
 <br />a <br />a <br />a <br />aecho <br />a"Hello <br />aWorld"
 <br />a <br />a}
 <br />a <br />asayHello

 <br />a <br />aFUNCTION <br />aWITH <br />aPARAMS
 <br />a <br />afunction <br />agreet() <br />a{
 <br />a <br />a <br />a <br />aecho <br />a"Hello, <br />aI <br />aam <br />a$1 <br />aand <br />aI <br />aam <br />a$2"
 <br />a <br />a}

 <br />a <br />agreet <br />a"Brad" <br />a"36"

 <br />a <br />aCREATE <br />aFOLDER <br />aAND <br />aWRITE <br />aTO <br />aA <br />aFILE
 <br />a <br />amkdir <br />ahello
 <br />a <br />atouch <br />a"hello/world.txt"
 <br />a <br />aecho <br />a"Hello <br />aWorld" <br />a>> <br />a"hello/world.txt"
 <br />a <br />aecho <br />a"Created <br />ahello/world.txt"

