# StreamWhack
## Open-source lightweight streamer control console

This is a very light implementation of a control console for streamers. The idea is that, with some configuration, you can control various aspects of your stream (e.g. Start Broadcast, Cue Audio, Redeem Points) from any computer that is able to open the html file.

The interface is very basic by design, and configuration to work for each streamer's needs will require some mucking with API permissions. The tradeoff is, hopefully, that the software is easy to deploy (just open the HTML file) and, perhaps more importantly, free.

## Use
When you first set up, open ```config_EXAMPLE.js``` in a text editor and update the placeholder values to your data. You can read more about the IDs you need at: https://dev.twitch.tv/docs/api/.

Once this is done __rename the file to ```config.js```__

Then open ```streamwhack.html``` in a browser and you should be good to go. To change the functions of each button you need to edit the html file.

## Contributing
This is a pretty light treatment. Feel free to fork and improve upon. Don't commit your api keys please!