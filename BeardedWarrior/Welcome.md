---
created: 2026-06-25T18:43
updated: 2026-06-26T02:59
topics:
  - agile
  - scrum
related:
  - "[[Christophers study recommendations]]"
---
This is your new *vault*.

Make a note of something, [[create a link]], or try [the Importer](https://help.obsidian.md/Plugins/Importer)!


---
# The basics

All notes automatically have a `created` and `updated` property. So you can keep track of when you created and updated each note. *Except for templates.*

link to a note that doesn't yet exist by typing `[[]]` then `[[write something new here]]` it should be greyed out, this is handy for when you know you want to talk about this new topic on [[example of note that is not created yet]].

You can also link to notes that have already been created by typing `[[]]` then starting to type the notes name and selecting it. 

Try searching `2026-06-25`
yes... do it :) 
[[]]

A Vault refers to the folder that stores all your notes.
Each note has a file name, the file name or alias is the name of the thing you are writing about. This notes name is *Welcome*. When I create a new note I can link to this note by typing [[Welcome]] or give it a new name like [[Welcome|Welcome to Obsidian]]. 

Hold `Ctrl` and hover over a link to see a preview of that file. 


---

*Properties drive concept/file organisation in your vault.*

See [[all properties of the Bearded Warrior Vault|this note]] for examples of vault properties. I recommend dedicating this note to capture all properties so you can see what you have AND by adding and filling out the `list` properties with demo values [[all properties of the Bearded Warrior Vault|here]] new notes with the same property can suggest previously added texts.

Try adding the `tech-tip` text to the `topics` property in this note.
yes... do it :) 
Scroll up ↑ 


---

# *Formatting Examples:* 
When in doubt right click but here are some examples of markdown format `.md`

`**Ctrl + B**` **Ctrl + B for bold**
`*Ctrl + I*` *Ctrl + I for italics*
`~~strike though~~` ~~strike through~~
`==Highlight==` ==highlight==


Headers:
```ts
# h1 
## h2
### h3
#### h4
##### h5
###### h6
```

horizontal rule with `---`

---
---
- [ ] Example of a check box
- [x] Example of a ticked check box

- `-` used for a bullet list
1. Numbered list
2. like this
	1. indenting with `tab` creates a new number list sequence

`Right Click ... Insert ... Callout`
> [!tip]+ This callout can be collapsed ... click me
> Hide the note by default with `[!NOTE]-` or force it to always be open with `[!NOTE]+`
> If it doesn't want to close or open then add the `+` or `-` to `[!tip]here`
> 

`Right click ... Insert... Table`

| Table | Example |
| ----- | ------- |
| 1     | 2       |
This is a code block, you can quickly copy text or code when you are in reading mode.
```python
print "hello champion"
```

This is an `inline code block` .

---
# General onboarding

A note can be in 2 states, *reading view* or *edit view*. 
	If you can type you are in edit view. I almost never use reading view except when I am learning from my notes and dont want to accidently edit or delete something. 

![[Example of Reading View - 2026-06-25.png|500]]

You can resize any image with `![[Example of Reading View - 2026-06-25.png|500]]` a size here.

---

[[2026-06-25|This is an example of a link to another note that you can rename]] with the pipe symbol `|` like `[Welcome|new name]`. Or you can just link to any note like [[Example Note on Agile]].

*Commands*
`Ctrl + P` is used when you want to do a command.
`Ctrl + O` is used when you want to open a note. 
`Alt + E` is used when you want to apply a template.

*Templates*
A **template** is a blueprint or template that contains text or structure that you can apply to a note or inside a note.

Try out by creating a new note with  `Ctrl + n` and then `Alt + E` then select or search by typing the name of the template you want to implement. 

---
*Bases*

**Bases** are useful when used with file properties as you can do SQL like queries on all notes on a specific topic or selected properties. Here are notes with `topics` property that has the `scrum` tag.  

![[ExampleBase.base]]


---
Other useful Commands using `Ctrl + P`:
- Open a web browser `Web viewer`
- `Search in all files`
- `Export to PDF`, note that in dark mode the colours may be a bit weird, best suited for light mode or default light mode theme.
- `Open local graph view` Show a graph with notes to links connected to the selected note. In the Settings you can move the *depth slider* under *Filters* to see a deeper note connection.


---

# Stuff about the current interface/layout
#### Footnotes
Find Footnotes here:
![[Example of Footnote location - 2026-06-26.png|550]]

watch this https://youtu.be/FIimThW6SXQ?si=PxxyJx7z0SG_9BYl to learn how they work

---
### Right Pane

Blue Arrow: Show Calendar, click on a day to create a note for that day or week.
Red Arrow: Show local graph, all notes that are linked to the selected note.
Green Arrow: Shows like a table of contents of all headings in selected note.
![[Right pane tips- 2026-06-26.png|400]]

---
### Left Pane

Blue Arrow: Folders
Red Arrow: Search or `Ctrl + p ... serach all files`
Yellow Arrow: Bookmarks
Green Arrow: Recent files
Orange Arrow: Vault Graph view (all notes created)
White Arrow: Random note
![[Left Pane tips- 2026-06-26.png|550]]

--- 
# Settings to change or undo
- Toggle Line numbers *Editor* | recommend ON, currently
- Readable line length *Editor* | recommend OFF, currently
- Web viewer default search engine | under *core plugins* `https://www.google.com/` + `Brave` +  `Enable add blocker`
- Calendar week start date | under *community plugins* recommend Sunday, currently as Monday
- Change colours with **Style Settings plugin** under *community plugins*. But would recommend to do so with a Theme like `Things` OR keep it as it currently is for now...
- Change Theme & colour to white..? 👀 | under *Appearance*


# About Vault, *INFO overload warning*

## Folders and New notes
`Attachments`: All new images or files should automatically get stored here.
`Boards etc`: Recommend to manually right click or drag-&-drop other file types like Canvas, Bases, Kanban, Excalidraw, etc.  
`Daily Notes`: The Periodic Notes and Calendar plugin automatically store daily/weekly notes here. 
`Notes`: All notes that you create will automatically get saved here.
`Templates`: All vault templates are stored here. 
Welcome - outside folder structure for you to start with.

You are welcome to add more folders... but the whole idea behind using obsidian is not to organise your notes at all! If you want to find something you can use the search tool or use bases in combination with file properties to sort or organise your notes :) 

---

*Vault Defaults*
At the moment I have set it up that all notes have a `created` and `updated` property.
And have set the [[base_note_template|this base note]] as a template for all created notes to have the `domain` property, `category` property and alias property.

Learn more about them [[all properties of the Bearded Warrior Vault|here]]


## Normal Templates and Utility Templates
`Alt + E` to open template suggester (do in a new note)

*Normal templates:* these are used to add structure or properties to your file/concept. I have set up [[daily_note_template|a daily note template]] and [[weekly_note_template|a weekly note template]] that will get used each time you create a new daily or weekly note by clicking on a date in the calendar or creating it via commands. By changing these notes you can change the structure or template for daily or weekly notes.

*Utility templates*: I would like to say they are my idea but others also use this implementation of templates. I use utility templates to do or enter only a specific thing in my note.  
- `datenow_template` -> add YYYY-MMM-DD of current date.
- `rename_add_date` -> rename file add todays date to end of file name. (I find this useful as I may pick up the same topic or concept many times but dont feel like updating/changing old notes for that concept)
- `rename_without_date` -> rename file without, may not always work depending on kind of file... can always just `left click file ... rename`.
- `sml_select_symbol` -> Suggester used to add frequently used custom symbols in notes
- `strs_rating_stars` -> Suggester used to add stars, like a rating 
- `timenow_template` -> add HH:MM of current time

---
*Template organsation*
You will see the `Templates/Category`. The idea is that you can create note templates based on kinds of notes in different categories. Like journal notes for when you want to do a diary entry thing, or recipes template (used in my personal vault) that add the file/note structure of *notes related to the umbrella category of x thing*

*Why templates are great*
You can add templates with these properties/structure to any note. The beauty of this is that any note can be a journal entry, recipe and something else... then when I create a base on all notes with the category property of journal it will show all notes that contain that tag, no need for me to organise it at all! 

---



## Cool Community Plugins to check out eventually...
*Project Manager plugin* - create Gantt charts in obsidian... even useful for personal progress tracking... :) 
	OR just use the [[Progress_Tracker_Kanban|Kanban progress tracker]] that I created for you. 
*Data view plugin* - what everyone used before obsidian bases... can use SQL.
*Omni search plugin* - better search functionality with OCR. 
*PDF++ plugin* - finicky but works ¯\\_( ͡° ͜ʖ ͡°)_/¯
*Diagrams plugin* - the draw.io implementation for local diagrams in notes
*URL preview plugin* - `Ctrl + hover` to preview websites
*Wheel Tab switcher plugin* - use scroll wheel to cycle between tabs
*Vertical Tabs plugin* - better tab/open file management 


