iOS Interview Questions
=======================

iOS Interview Questions @ http://bizzydevapps.weebly.com/

Three Ways to Navigate Data:
============================
    1. Menu Display.
    2. Tree View.
    3. Tabbed Raw Text.

![Think Link Master](http://medbuy.in/ThinkLinkMaster/MenuDisplay.jpg)

Works well in tandem with Notepad++:
====================================

![Notepad++ Integration](http://medbuy.in/ThinkLinkMaster/Export.PNG)

Keys:
=====
1. Ctrl + N : New Sub MenuItem.
2. Ctrl + Shift + N : New Multiple MenuItems at the same level of indent.
3. Ctrl + Alt + N : New Multiple Cascading Sub-MenuItems.
4. Ctrl + S or Click Save Button in Status Bar : Save XML to file(menu.xml).
5. Ctrl + L or Click Load Button in Status Bar : Loads XML to Menu.
6. Ctrl + Q : Quick Refresh = Saves and Loads.
7. Ctrl + D : CDATA or Content Data for Annotating Defnitions with details(eg: Sample Code).
8. Ctrl + G : Generates new GUID.
              This will be useful if you Copy + Paste a MenuItem. 
              You would need to replace the GUIDs in the MenuItem and its Sub MenuItems...
              ... with new GUIDs for uniqueness.
9. Ctrl + ; : Pastes Current Day and Date.
10. Ctrl + Shift + ; : Pastes Current Time.
11. Ctrl + U : Finds the Parent/ Upper node.
12. Ctrl + F : Find.
13. Ctrl + H : Replace.
14. Ctrl + R : Refresh all GUIDs.
		This will be useful when you've copied and pasted a lot of MenuItems...
		and need to assign new GUIDs to all of the pasted values to maintain uniqueness.
15. Tab : Tabifies Selection.
16. Shift + Tab : Untabifies Selection.
17. Ctrl + I : Imports from tabbed Clipboard data.
For Eg:
-------
a
	b
	c
		d
			e
		f
	g
	e
h
i
	j
		k
			1
				2
					3
						4
							5
								6
									7
										8
l
m
n
o
	p
		q
18. Ctrl + Shift + I : Replaces data (value of id attribute) in Xml with tabbed clipboard data.
For Eg:
-------
abc
def
ghi
kml
19. Ctrl + E : Exports to Clipboard as tabbed data.

Usage:
======
1. To add new concepts or definitions:
	Insert a new MenuItem(Ctrl + N) as a concept and its definition as a Sub-MenuItem(Ctrl + N).. 
	..inside the prior created concept MenuItem.
2. To add any Code sample to the definition, add a CDATA section(Ctrl + D) within the definition Sub-MenuItem.
3. Click Menu to locate it in XML using GUID.(Works only for leaf nodes.)
