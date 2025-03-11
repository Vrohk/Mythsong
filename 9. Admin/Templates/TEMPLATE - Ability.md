---
summary: 
thumbnail: 
links: 
aliases: 
tags:
  - "#new"
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
ability type: 
magic type: 
components: 
max charges: 
costs: 
range: 
recharge: 
duration: 
base level: 
spec tree:
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
## 1st Level
>If given a moment, you can draw from an inner reserve of Willpower. You Grant yourself the Focus Status, Altering the next Spell you Cast, Reducing its WP Cost by Half (min 1).
- [[Mental]] [[Ability]]
- Components: [[Verbal]], [[Somatic]]
- Costs: 1AP
- Range / Targets: Self
- Duration: [[Until Next Rest]]
- Charges: WIS (Min 1) Charges, Fully Recharge each Long Rest

```dataview
list magic-type, ability-type, components, costs, range, duration, max-charges, recharge
where file.name = 

```

---
## 2nd Level
+1 Charge

---
## 3rd Level
Upgrade - Choose 2 Variants:
- Distant - Double Range and WP Cost
- Extended - Double Duration and WP Cost
- Spontaneous - This Spell does not Consume a Charge...
- Quickened? - 
Alterations -
- Amplify
	- Quickened - 
	- Distant - Double Range and WP Cost
	- Extended - Double Duration and WP Cost
- Life Tap? - 
---
## 4th Level
+1 Charge

---
## 5th Level
+1 Charge and Choose 2 Additional Variants.

---

>"...it was then she placed her hand over my own, still trembling from the narrow escape of which we were yet to complete. She breathed out softly, gently pushing the words into my mind...
>
>'*You are more capable than you give yourself credit for, young one.*'
>
>In an instant, I had forgotten all about the bandits. The runes snapped into focus, and with a gentle twist the door sprang open, and we slipped into the coach which had arrived precisely as I had known it would!"
>- ?????
