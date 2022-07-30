# Telegram-Name-Updating

Update (first/last/user) name of Telegram user every 30 seconds.

Reference documentation：<a href="https://telethon.readthedocs.io/en/stable/">Telethon</a>

## 0. prerequisites

Operating environment：VPS，python3，python3-pip

Create an app：<a href="https://my.telegram.org/">https://my.telegram.org/</a>。Just fill in the App title and Short name.  Get api_id and api_hash.
## 1. Download the Demo applet to the VPS

<code>git clone https://github.com/8838/Telegram-Name-Updating.git</code>\
<code>cd Telegram-Name-Updating</code>

## 2. Install telethon

<code>pip3 install -r requirements.txt</code>

## 3. Run the Demo applet

<code>python3 tg_username_update.py</code>

## 4. api authentication and user login

Enter api_id and api_hash as prompted.  Then enter the mobile phone number and verification code. If the account has enabled secondary verification, please enter the secondary verification password according to the prompts.  Finally seeing It works! indicates success.  The default is to update lastname to a specific mode with a certain probability every 30 seconds.

## 5. Temporarily CTRL+C to end the applet and re-hang it to run in the background

<code>nohup python3 tg_username_update.py &</code>
