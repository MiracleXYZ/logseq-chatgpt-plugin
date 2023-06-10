# Logseq ChatGPT Plugin [<img align="right" src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" height="30"/>](https://www.buymeacoffee.com/debanjandhar12)

<h3 align="center">A tightly integrated ChatGPT plugin for Logseq. Powered by Langchain.js.</h3>

## Features
<ul><li>
<details open>
  <summary><b>🚀 In-build powerful prompts</b></summary>
  <div>
   The plugin comes packed with several powerful prompts:
   <img src='https://user-images.githubusercontent.com/49021233/230309525-837f62f9-baaf-4eff-9729-51ca062db046.gif' height='400' /> <br/>
  </div>
</details></li><li>
<details>
  <summary><b>🚀 Custom Prompts</b></summary>
  <div>
   The plugin provides GUI for custom prompt creation. The custom prompts can use langchain.js tools like Web Browser, Zapier, and even external custom API Endpoints 😲.<br/>
    <img src='https://github.com/debanjandhar12/logseq-chatgpt-plugin/assets/49021233/c770ed24-0744-46af-9ef0-549a0d8eaca5.gif' height='400' /> <br/>
  </div>
</details></li><li>
<details>
  <summary><b>📚 ChatGPT Page Management</b></summary>
  <div>
   <img src='https://user-images.githubusercontent.com/49021233/226954450-230185c7-f9ea-4a8f-bda1-0d29cf550ba4.gif' height='400' />
  </div>
</details></li><li>
<details>
  <summary><b>📥 DWIM Commands and Shortcuts</b></summary>
  <div>
      The plugin has the following <i><b>D</b>o <b>W</b>hat <b>I</b> <b>M</b>ean (DWIM)</i> commands:
      <ul>
          <li><b>Ask ChatGPT -</b> This will call chatgpt API when the user is inside ChatGPT page. Otherwise, it creates a new chatgpt page with prompt from selected blocks or an empty chatgpt page incase no blocks are selected.</li>
          <li><b>Create ChatGPT page -</b> This will create a new chatgpt page with prompt from selected blocks or an empty chatgpt page incase no blocks are selected. Useful only when you want to create chatgpt page from another chatgpt page.</li>
          <li><b>Show ChatGPT Page List -</b> Opens the ChatGPT Page list dialog.</li>
      </ul>
      <br/>
      By default, there are following keyboard shortcuts for the above commands:
      <ul>
          <li><kbd>cmd/ctrl</kbd>+<kbd>shift</kbd>+<kbd>/</kbd> - Ask ChatGPT</li>
          <li><kbd>cmd/ctrl</kbd>+<kbd>shift</kbd>+<kbd>l</kbd> - Show ChatGPT Page List</li>
      </ul>
      The above shortcuts can be changed from settings.
  </div>
</details></li><li>
<details>
  <summary><b>🐾 Support for Logseq Syntax</b></summary>
  <div>
   THe plugin is built with Logseq in mind. It parses the block refs and block embeds before sending request to ChatGPT. This means you can use block refs and embeds anywhere in your conversation.
   Support for page embeds will be coming soon.<br/>
   Additionally, the plugin sanitizes ChatGPT result using mldocs so that logseq supports rendering the output.<br/>
   <img src='https://github.com/debanjandhar12/logseq-chatgpt-plugin/assets/49021233/042afa23-5219-46eb-8506-4aaadaa5d085.gif' height='400' />
  </div>
</details></li>
</ul>

## Installation
1. Install Logseq ChatGPT Plugin from Marketplace.
   * Go to `⋯` > `Settings` > `Features` and enable `Plugins`.
   * Now, go to `⋯` > `Plugin` > `Marketplace` and find Logseq ChatGPT Plugin and click install
2. Get and Setup OpenAI API Key.
   * OpenAI gives away free credits worth $5 to $18 for ChatGPT that can last for up to 120 days. [Get an OpenAI API Key here](https://openai.com/api/).
   * Go to Logseq ChatGPT Plugin Settings and enter the API key there.
3. Have fun!

## 🙏 Support
Loved the tool? Please consider donating to help continue development!<br/>
<p align="center">
<a href="https://www.buymeacoffee.com/debanjandhar12" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="55" style="border-radius:1px" />
</p>
