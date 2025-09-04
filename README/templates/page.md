<%*
const title = await tp.system.prompt("Title");
await tp.file.rename(title);
-%>
<% title.split('.').map(s => `[[${s}]]`).join('/') %>;

## ️️❄️ H1 #1997-31-03-Saturday

### H2

☁️ Lorem ipsum <% tp.file.cursor() %>
+
    - item
    - item

```sh
    script
```
