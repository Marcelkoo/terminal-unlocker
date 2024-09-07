# Extension to Unlock Terminal App in Web Telegram

This extension modifies the `iframe` within Telegram Web to unlock the [**Terminal app**](https://t.me/terminalgame_bot/terminalgame?startapp=WJVFEQJI).

# Subscribe

Visit and subscribe to my Telegram channel:

[**t.me/marcelkow_crypto**](https://t.me/marcelkow_crypto)

Here, I post updates, other software, and additional tips.

## Usage Instructions

1. **Install the Extension:**
   - Clone or download this repository to your machine.
   - Navigate to `chrome://extensions/` in Google Chrome.
   - Enable **Developer Mode** in the top right corner.
   - Click on **Load Unpacked** and select the folder where this extension is located.

2. **Open Telegram Web:**
   - Make sure you're using the `/a/` version of Telegram Web by navigating to:
     ```
     https://web.telegram.org/a/
     ```
   - **Do not** use the `/k/` version:
     ```
     https://web.telegram.org/k/
     ```

3. **Unlock the Terminal App:**
   - The extension will automatically detect the `iframe` when you open the Terminal app and modify the platform identifier.
   - Enjoy the unlocked features!

## Limitations

- The extension works only on the domain `https://web.telegram.org/a/`. Ensure you're using this URL format.
- It will **not** function on the `/k/` version of Telegram Web or other versions of Telegram that do not use iframes in the same way.
- The extension does not modify other elements of Telegram Web outside of the `Terminal` iframe.

