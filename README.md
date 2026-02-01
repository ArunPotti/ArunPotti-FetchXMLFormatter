# Arun Potti's FetchXML Formatter

Arun Potti's FetchXML Formatter is a lightweight web tool for Dataverse / Dynamics 365 developers to **format FetchXML** and instantly generate **ready-to-use JavaScript, C#, and Web API snippets** from a single FetchXML input.

<img width="676" height="502" alt="image" src="https://github.com/user-attachments/assets/b5921d47-0be5-405b-a981-8667b1285233" />

---

## Features

- 🔹 **Single FetchXML input**
  - Paste FetchXML in standard XRM / Dataverse format
  - Basic XML validation (parse + root `<fetch>` check)

- 🔹 **Automatic formatting**
  - Auto-beautifies FetchXML on input/change
  - Fixes indentation and line breaks for readability

- 🔹 **Code generation**
  - **JavaScript** snippet for `Xrm.WebApi.retrieveMultipleRecords` or Web API calls
  - **C#** verbatim string snippet for plugins, custom workflow activities, or console apps
  - **Web API** URL parameter (`fetchXml`) with URL-encoded FetchXML

- 🔹 **Copy to clipboard**
  - One-click **Copy** for:
    - JavaScript output
    - C# output
    - Web API output
    - Formatted FetchXML

- 🔹 **Sample FetchXML**
  - Insert a sample FetchXML query with one click to test the tool

- 🔹 **Clean, responsive UI**
  - Modern layout that works on desktop and mobile
  - Clear separation between input and the three outputs
