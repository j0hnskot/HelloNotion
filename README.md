# Notion API - Hello World

## (just look at [https://developers.notion.com/docs/getting-started](https://developers.notion.com/docs/getting-started)) 

- Create a new integration at [https://www.notion.com/my-integrations](https://www.notion.com/my-integrations) and grab the secret

- On Notion, create a new "Database - Full page" and “share” with the integration

- Note the DB's ID from the URL. E.g:  e90b7c600ea049bcb69985a80d7adced

- somehow EXPORT the keys. E.g, if on windows, use something like:
```powershell
$env:NOTION_KEY="secret_8b3sdayk0JWpf6ApRenO112WuioeHhx"; 
$env:NOTION_DATABASE_ID="e90b7c600ea049bcb69985a80d7adced";
node .\index.js
```