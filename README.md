# FoxTools.FLL Documentation

In this repo, we have extracted the Help info for FoxTools.fll from the old ToolHelp.hlp file originally created by George Tasker and posted to Universal Thread (now Level Extreme) at this link: https://www.levelextreme.com/ShowHeaderDownloadOneItem.aspx?ID=9333 way back in February 1998.

# Extended Foxtools Help

A complete, cross-referenced, comprehensive help file containing all the functions in the FOXTOOLS.FLL library for Visual FoxPro for Windows. Includes a number of samples as to how to use the functions.


## About Extended Foxtools Help

Information contained (exctracted) in this help file has been obtained from a number of sources. These include the FOXTOOLS.WRI file included in FoxPro for Windows 2.x, the Microsoft Knowledge Base, the Library Construction Kit, and the Visual FoxPro 5.0 Help File.

Additional information, especially that connected with the FoxPro API functions exposed by FOXTOOLS, has been obtained mostly been through trial and error by the author. Naturally, no warranty is either intended or implied by the publication of this document. Indeed, since the library was first released, Microsoft’s stated position has been and is one of no guarantee of current or future support. However, through five versions, no functions have been removed except those incorporated into the language proper, but some have been added. This help file is complete through version 6.0.

I would appreciate any feedback regarding this work. This includes correction of any errors found, or suggestions as to providing additional examples. Feel free to email me at : gtasker@compuserve.com

George Tasker
February 21, 1998

## Acknowledgements

I would like to acknowledge the following people:

Rick Strahl of West Wind Technologies, for sparking my interest in the API functions.

Steve Despres and Roxanne Seibert for their words of encouragement.

David Frankenbach for pointing out the FoxTouch() function and a source of information about it.

Robert Green of Microsoft, for encouraging me to expand this project

Michel Fournier of Fournier Transformation, Inc., for providing the Universal Thread as a means of distribution.

Joshua D. Weiss of Boston Microcomputer Consulting, for providing the information regarding the functions from the library added to the language in version 6.0.

Christof Lange, The Foxpert!, for information on a documentation source for the functions _WsockStartUp(), _WSockGetHostByAddr(), and _WSockCleanUp(). Christof also provided additional information for the last element of the array populated by _EdGetEnv(). Further, Christof’s feedback on one of his projects led directly to the section entitled, “Invalid whandles” and additional information on _EdGetLNum() and _EdGetLPos(). My thanks to him for his continuing feedback and support of this project. Most recently he has provided information regarding problems with _EGetEnv(). His continued support of this project is greatly appreciated.

## Alphabetical Function List
AddBS  
CallFN  
CleanPath  
CloseClip  
CountClipF  
DefaultExt  
DriveType  
EmptyClip  
EnumClipFm  
ForceExt  
ForcePath  
FoxToolVer  
FoxTouch  
GetClipDat  
GetClipFmt  
GetFileVersion  
GetProStrg  
IsClipFmt  
JustDrive  
JustExt  
JustFName  
JustPath  
JustStem  
MainHwnd  
MkDir  
MsgBox  
NextWord  
OpenClip  
PutProStrg  
Reduce  
RegClipFmt  
RegFN  
RegFN32  
RGBComp  
RmDir  
SetClipDat  
StrFilter  
ValidPath  
WordNum  
Words  

## Clipboard Functions
CloseClip  
CountClipF  
EmptyClip  
EnumClipFm  
GetClipDat  
GetClipFmt  
IsClipFmt  
OpenClip  
RegClipFmt  
SetClipDat  

## File and Drive Functions
AddBS  
CleanPath  
DefaultExt  
DriveType  
ForceExt  
ForcePath  
FoxTouch  
JustDrive  
JustExt  
JustFName  
JustPath  
JustStem  
MkDir  
RmDir  
ValidPath  

## String Functions
NextWord  
Reduce  
StrFilter  
WordNum  
Words  

## Exposed FoxPro Editor API Functions
_EdActive  
_EdCloseFi  
_EdComment  
_EdCopy  
_EdCut  
_EdDelete  
_EdGetChar  
_EdGetEnv  
_EdGetLNum  
_EdGetLPos  
_EdGetPos  
_EdGetStr  
_EdIndent  
_EdInsert  
_EdLastErr  
_EdOpenFil  
_EdPaste  
_EdPosInvi  
_EdProcList  
_EdProperties  
_EdRedo  
_EdRevert  
_EdSelect  
_EdSendKey  
_EdSetEnv  
_EdSetPos  
_EdSkipLin  
_EdStoPos  
_EdStoSel  
_EdUndo  
_EdUndoOn  

## Exposed FoxPro Window API Functions
_FindWindo  
_FindWindp  
_GetWRect  
_WAttr  
_WBottom  
_WBottomP  
_WClear  
_WClearRec  
_WClearRep  
_WClose  
_WFindTitl  
_WFooter  
_WGetCurP  
_WGetCurso  
_WGetPort  
_WHeight  
_WHeightP  
_WHide  
_WHToHWnd  
_WLeft  
_WLeftP  
_WMainWind  
_WMove  
_WMoveP  
_WOnTop  
_WOpen  
_WOpenP  
_WPosCurP  
_WPosCurso  
_WPutChr  
_WPutStr  
_WRight  
_WRightP  
_WScroll  
_WScrollP  
_WSelect  
_WSendBehi  
_WSetAttr  
_WSetPort  
_WSetTitle  
_WShow  
_WSize  
_WSizeP  
_WTitle  
_WTop  
_WTopP  
_WWidth  
_WWidthP  
_WZoom  



## Miscellaneous Functions
CallFN  
FoxToolVer  
GetFileVersion  
GetProStrg  
MainHwnd  
MsgBox  
RegFN  
RegFN32  
PutProStrg  
RGBComp  






