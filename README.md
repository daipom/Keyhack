# Config of Keyhac for vim customization

- About Keyhac
	- https://sites.google.com/site/craftware/Home
	- Key customization tool for Windows
- About this config
	- Vim customization for Japanese layout(JIS) keyboard.
	- While pushing `無変換` key, vim VIEW mode is applied.
	- This provides you very smooth editing in all applications.
- How to use
	- Install Keyhac from the above url.
	- Replace the `~/AppData/Roaming/Keyhac/config.py` file.
- Note
	- This changes `無変換` key to an additional define modifier key(`User0` key).
		- So you cannot use `無変換` key itself.
		- If you need `無変換` key itself, you have to fix this config.
			- This replaces id-29(`無変換`) key to `User0`(additional define modifier) key.
			- You can change this replacement.
