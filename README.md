# Telegram DeepL Expert Tool 🛠️

[](https://opensource.org/licenses/MIT)
[](https://github.com/LuisAlejandroVega/telegram-deepl-expert-plugin/releases/latest)
[](http://makeapullrequest.com)

An advanced plugin for Telegram clients that integrates the DeepL API for high-quality translations and text improvements, with unparalleled customization.

**Author:** [@luisalejandrovega](https://t.me/luisalejandrovega)
**Current Version:** 10.0.0

> Take your conversations to the next level. Instantly translate, improve your writing, and use glossaries for precise communication, all directly from within Telegram.

## ✨ Key Features

This plugin isn't just a translator; it's a Swiss Army knife for handling text in any language.

  * **🚀 Dual-Mode Operation:**

      * **Translation:** Instantly translate text by choosing from over 30 source and target languages.
      * **Writing (requires API Pro):** Don't just translate. Improve the wording, style (casual, business, academic), and tone of your texts.

  * **⚙️ Advanced API Management:**

      * **Multiple Keys:** Add several API keys (Free or Pro).
      * **Pro/Free Support:** Switch between the free and pro API endpoints with a single click.

  * **🌐 Expert Translation:**

      * **Smart Context:** The plugin can use the messages you reply to, providing more context to the translation for incredibly accurate results.
      * **Formality Control:** Adjust whether you want the translation to be formal or informal. Ideal for languages that support it.
      * **Glossary Management:** Full integration with DeepL glossaries\! Load and select your glossaries to ensure that specific jargon or terms are always translated the way you want.

  * **🎨 Customizable Interface & Commands:**

      * **Multi-language Interface:** The settings menu is available in **English, Spanish, Russian, German, French, and Traditional Chinese**.
      * **100% Flexible Commands:** Don't like the default commands? Change them all from the settings\!

## ⚙️ Installation

Installing the plugin is a breeze. Follow these steps:

1.  Go to the **[Releases](https://github.com/LuisAlejandroVega/telegram-deepl-expert-plugin/releases/latest)** section in this repository.
2.  Download the `.plugin` file from the latest version (e.g., `DeepLAutoTranslate-10.0.0.plugin`).
3.  Install the plugin in your Telegram client (Ayugram/ExteraGram).
4.  Restart the client or reload the plugins from the settings. Done\!

## 🚀 Usage and Configuration

The easiest way to set everything up is through the **plugin's settings menu** in your Telegram client. The interface is super intuitive and lets you tweak all the options.

For those who prefer speed, you can also use commands in any chat. Here are the default commands (remember you can change them):

| Command                 | Description                                                    |
| ----------------------- | -------------------------------------------------------------- |
| `.dltoggle`             | Enables or disables the plugin completely.                     |
| `.dlmode <t\|w>`        | Switches between **t**ranslation and **w**riting mode.         |
| `.dlhelp`               | Shows the help message with all commands.                      |
| `.dlinfo`               | Shows a summary of your current configuration.                 |
| **Translation** |                                                                |
| `.dltarget <code>`      | Changes the target language (e.g., `.dltarget DE`).            |
| `.dlswap`               | Swaps the source and target languages.                         |
| `.dlformal <option>`    | Sets the formality (auto, more, less, prefer\_more, etc).      |
| `.dlcontext <on\|off>`  | Enables or disables using the reply as context.                |
| `.dlglos <id\|name>`    | Selects a glossary by its name or ID.                          |
| `.dl.to <code> <text>`  | Performs a quick, one-time translation without changing your settings. |
| **API & Settings** |                                                                |
| `.dlkey <key(s)>`       | Sets your API key(s) (separated by commas).                    |
| `.dlpro`                | Enables or disables the Pro API mode.                          |
| `.dlusage`              | Shows the current usage of your API keys.                      |
| `.dllangs`              | Lists all languages supported by DeepL.                        |
| `.dllang <code>`        | Changes the plugin's interface language (e.g., `.dllang en`).  |

## ❤️ Support the Development

If this plugin saves you time and you find it useful, you can buy me a coffee to support future updates.

  * **Support & Community Group:** [Join the Telegram group](https://t.me/plugins_luisalejandrovega)
  * **PayPal:** [Donate via PayPal](https://www.paypal.com/paypalme/LuisAlejandroVega)
  * **USDT (TRC20):** `TYpoRvAZn1wYEJ9ao2CStDWQFbH6uA8uFG`
  * **TON / USDT (TON):** `UQBcMQhWdjHWWwqWVe5_yQk1dWXJm4AGZmfQN5YX0zFY2zfwO`

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
