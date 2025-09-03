<%*
const title = await tp.system.prompt("Title");
await tp.file.rename(title);
console.log("hi");
-%>
<% title.split('.').map(s => `[[${s}]]`).join('/') %>;
<% tp.file.cursor() %>