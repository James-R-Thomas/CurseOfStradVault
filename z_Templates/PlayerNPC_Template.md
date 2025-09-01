---
type: PlayerNPC
tokenLink: "[[<% await tp.system.prompt("Please enter a token link") %>]]"
LastKnownStatus:
Location:
KnownByParty: false
---
    <%*
    let title = await tp.system.prompt("Enter the note title:");
    await tp.file.rename(title);
    %>
`="!"+this.tokenLink`
##### Name: `= this.file.name`
##### Last Known Status: `= this.LastKnownStatus`
##### Last Known Location: `= this.Location`
### Notes:

