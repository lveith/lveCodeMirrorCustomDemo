## Just any codeMirror Demo to show some custom examples

This demo can used as webdev-workbench or as small webdev-helpertool  or for other experiments.

This is just a rudimentary work to pick a few bites or to understand processes and solutions. Preparations are intended to fully integrate an app (e.g. 4D) outside the web area. Prepared JavaScript functions to execute CodeMirror actions via e.g. a 4D command like this:
```
// insertInEditor(myEditorName, mySrc)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"insertInEditor";$resultBool;"mergeleft";$contentText)
```
```
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"setBodyBGColor";$resultBool;"#f7f3f7")
```
```
// insertAnyStyles(myCSS, myID)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"insertAnyStyles";$resultBool;$styles;"mySpecStyles1")
```
```
// setEditorHeight(myEditorName, myHeight)
WA EXECUTE JAVASCRIPT FUNCTION(*;"oWebArea3";"setEditorHeight";$resultBool;"merge";"calc";"3")

```

...and much more...maybe later...

![github-small](https://user-images.githubusercontent.com/65073460/82428184-6c381300-9a8a-11ea-9e84-9cacd433481f.png)
