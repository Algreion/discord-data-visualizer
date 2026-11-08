# Discord Data Visualizer
Data visualizer for the "Request my Data" feature from Discord. Fully local.

I was mostly making this for myself, since Discord just gives you hundreds of unreadable JSONs, but thought others would find it useful too.

## Requesting Data
To request your data:
1. Go to Discord > Settings > Data & Privacy.
2. Select "Request my Data" (last option in "How Discord Uses My Data").
3. Select everything, and confirm.
4. Discord will email you in a few days at most with a .zip file.
5. You can then upload the whole .zip in this visualizer.


## Data Quirks
Due to how Discord packages the data they give you, some things are inevitable:
- Discord only gives you your messages, so all conversations are you talking to yourself.
- Most channel names of servers you left will be unknown. Discord doesn't include their names anywhere.
- The content of deleted messages cannot be read.

## DISCLAIMER
The visualizer is fully local, and runs offline perfectly fine. If you load an attachment by clicking on it, it queries discord.com, but all other domains are blocked by the CSP. Changes made, such as renames, are saved in localStorage on your PC.
