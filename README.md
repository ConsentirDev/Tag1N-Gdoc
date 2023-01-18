# Tag1N-Gdoc
A google docs editor extension that uses GPT3 completions and edit APIs to allow the user to use Natural language editing in situ.

Google Docs Editor Add-on Deployment Instructions
====================================


This quickstart creates a Google Docs Editor Add-on that allows the user to use Natural language editing in situ.

Objectives
----------

*   Set up the script.
*   Run the script.
*   Use the script for your preferred use case.

Prerequisites
-------------

To use this example, you need the following prerequisites:

*   A Google Account (Google Workspace accounts might require administrator approval).
*   A web browser with access to the internet.
*   An OpenAI API Key >> Sign up here if needed[Sign Up](https://beta.openai.com/signup).

Set up the script
-----------------

1.  Create a Google Docs document at [docs.new](https://docs.google.com/document/create).
2.  Click **Extensions** \> **Apps Script**.
3.  Click **Untitled project**.
4.  Rename the Apps Script project **Tag1n** and click **Rename**.
5.  Next to the `Code.gs` file, click More more\_vert \> **Rename**. Name the file `TAGmain`.
6.  Click Add a file add \> **HTML**. Name the file `sidebar`.
7.  Replace the contents of each file with the corresponding code found in this repo, then click Save ![Save icon](https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/save/default/24px.svg).

Run the script
--------------

1.  In your Docs document, reload the page.
2.  Click **Extensions** \> **Add-ons** \> **Tag In** \> **Start**.
3.  When prompted, authorize the add-on.
4.  Again, click **Extensions** \> **Add-ons** \> **Tag In** \> **Start**.  This should only occur on first run.
5.  Copy your OpenAI API key into the field: **Your OpenAI API Key**

Use case 1. (I have written something and would like to transform, extend or edit)
--------------

1.  Type some text into your document and select it.
2.  In the Sidebar, Type your editing instructions in the field: **What would you like to create?:**
3.  Click **Edit**. To replace the text in the document, click **Insert**.

Use case 2. (I require assistance with what or how to write something, and/or an example)
--------------

1.  In the Sidebar, Type your request in the field: **What would you like to create?:**
2.  Click **Generate**. To place the text in the document, click **Insert**. Text will be inserted at the location of the cursor.
