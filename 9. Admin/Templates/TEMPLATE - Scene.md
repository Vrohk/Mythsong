---
summary: 
thumbnail: 
links: 
aliases: 
tags:
  - "#new"
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
---
<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(`${title}`);}%>
# [[<%* tR += `${title}` %>]]
TOOLTIP - What is it? Summary and Links 
Thumbnail

----

## Scene 1
One line of establishing Details: Area - Setting - Date - Conditions - Tone - _ACTIONS_ - Time

**ACTOR (or NARARATOR)**
Line of dialog, _description of ACTIONS_.

**Scene Transition**

## Scene 2

