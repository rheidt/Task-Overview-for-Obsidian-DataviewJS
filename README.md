# Task Overview for Obsidian DataviewJS

Here is my complex task overview for Obsidian with DataviewJS. In the metadata various parameters can be changed and so the appearance of the overview can be customized. Also the stored regex parameters for the recognition of date, time and archived tasks can be customized as desired. This template is currently designed for use with the Kanban plugin for Obsidian, but can also be adapted for all other task management methods as needed.

Like a Kanban, each task is displayed as a card and can be customized via metadata.

```
# --- REGEX -------------
timeRegex: '@@{(\d{2}\:\d{2})}'
dateRegex: '@{(\d{4}\-\d{2}\-\d{2})}'
archiveRegex: 'archive{(\d{4}\-\d{2}\-\d{2})}'

# --- LAYOUT ------------
pages: '"Inbox"'
checkboxes: false
cleanedText: true
date_time: true
relativeDate: true
tags: true
subpath: true
subpathOnly: true

# --- SECTIONS ----------
overdue: true
today: true
upcoming: true
undated: true
completed: true
archived: false

# --- COLORS ------------
overviewColors: true
kanbanColors: true
borderPosition: left
borderThickness: 5
overdueColor: red
todayColor: yellow
upcomingColor: purple
undatedColor: 
completedColor: green
archivedColor: 
---
```

<img width="306" alt="Bildschirmfoto 2021-10-17 um 21 17 36" src="https://user-images.githubusercontent.com/59178587/137641701-bcc06f05-a826-475d-8fdf-e20cec02cd4a.png">

Checkboxes, separated metadata like date, relative date, time, tags, cleaned up task texts, subpathes, as well as color markers can be set as desired.

<img width="308" alt="Bildschirmfoto 2021-10-17 um 21 16 40" src="https://user-images.githubusercontent.com/59178587/137641680-fb0d19c6-0873-45ed-b60a-c4e5d2032747.png">

All tasks can be displayed in the categories Overdue, Today, Upcoming, Undated, Completed and Archived. Which categories are displayed is up to you.

<img width="308" alt="Bildschirmfoto 2021-10-17 um 21 18 44" src="https://user-images.githubusercontent.com/59178587/137641729-97adc766-6554-4d74-a52b-5d640641730e.png">

Each task card can be marked with any color depending on the category. If desired, the same marking can be applied to the cards of your kanban. You can also choose the thickness and position of the marking.

<img width="856" alt="Bildschirmfoto 2021-10-17 um 21 19 09" src="https://user-images.githubusercontent.com/59178587/137641842-1149149f-58d9-4582-89a7-9cf7c7080ff2.png">

