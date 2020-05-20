## Just any codeMirror Demo to show some custom examples

This demo can used as webdev-workbench or as small webdev-helpertool  or for other experiments.

This is just a rudimentary work to pick a few bites or to understand processes and solutions. Preparations are intended to fully integrate an app (e.g. 4D) outside the web area. Prepared JavaScript functions to execute CodeMirror actions via e.g. a 4D command like this:
```
// JS: function insertInEditor(myEditorName, mySrc)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"insertInEditor";$resultBool;"mergeleft";$contentText)
```
```
// JS: function setBodyBGColor(myBGColor)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"setBodyBGColor";$resultBool;"#f7f3f7")
```
```
// JS: function insertAnyStyles(myCSS, myID)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"insertAnyStyles";$resultBool;$styles;"mySpecStyles1")
```
```
// JS: function setEditorHeight(myEditorName, myHeight)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"setEditorHeight";$resultBool;"merge";"calc";"3")

```
```
function replaceTextFragments(myEl, myOldTxt, myNewTxt)
function setMyEditorOpt(myEditor, mySel)
function setSpecials(myEditor, mySel)
function commandEditor(myEditorName, myCommand, myP1, myP2)
function optionEditor(myEditorName, myOpt, myP1, myP2, myP3, myP4, myP5)
function toggleShowHide(mySel)
function showBox(myName)
function hideBox(myName)
function insertSource(mySrc)
function mergeWith(mySrc, myLeftRight)
function refreshEditor(myEditorName)
function selectAllEditor(myEditorName)
function formatSelection(myEditorName)
function formatAll(myEditorName)
function openBox(myBoxName)
function closeBox(myBoxName)
function updatePreview()
function initUI()
function toggleDifferences()
function mergeViewHeight(mergeView)
function resize(mergeView)
function getSelectedRange(myEditor)
function getAllRange(myEditor)
function autoFormatSelection(myEditor)
function autoFormatAll(myEditor)
function commentSelection(myEditor, isComment)
...
```

...and much more...maybe later...

![github-small](https://user-images.githubusercontent.com/65073460/82428184-6c381300-9a8a-11ea-9e84-9cacd433481f.png)
