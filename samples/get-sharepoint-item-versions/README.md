Here in GitHub
- Copy the entirety of [scope_definition.json](https://github.com/ohthreesixtyfive/power-automate/blob/main/samples/hide-sharepoint-list/scope_definition.json) to your clipboard.

In Power Automate
- In Power Automate/Flow, click ` + New step `.
- Select ` My clipboard `.
- Press ` [Ctrl] ` + ` V ` to make the Scope available in Microsoft Flow.
- Select ` Get-Item-Version-History ` to insert the Scope into your Flow.
- Provide inputs to the ` Site-Address `, ` List-Title `, and ` List Item Id ` actions.
  - [Optional] Provide input for the ` Version-Label ` action to retrieve a specific version (eg: "2.0").
    - Version-Label **MUST** be encapsulated in double quotes.
- Update ` Get-Item-Versions ` action with the proper Connection Reference.
