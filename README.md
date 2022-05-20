# Printscreen
 While 1 savescreenandturnpage()  $numberofpages += 1  If $numberofpages = $numberofscreens Then      Send("{Esc}")      EndIf WEnd   Func savescreenandturnpage() Send("{RIGHT}") Sleep($pause) Send ("#{Printscreen}") Sleep(1500) EndFunc
