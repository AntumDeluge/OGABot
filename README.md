## IRC bot for OpenGameArt.org

This is a [Limnoria/Supybot](https://github.com/ProgVal/Limnoria) bot configuration for the [OpenGameArt.org](https://opengameart.org/) IRC channel.

### Usage:

#### Limnoria/Supybot Installation:

- [Linux/Unix](https://docs.limnoria.net/use/install.html)
- [Windows](https://docs.limnoria.net/use/install_windows.html)

#### Setting up owner account:

1. Register username with `owner` capability using the `supybot-adduser` script (alternatively, add the line "capability owner" to the `users.conf` file if you have already registered):

> `supybot-adduser --user=<username> --password=<password> --capability=owner /path/to/users.conf`

2. Launch bot by executing: `supybot /path/to/OGABot.conf`
3. Identify the account to the bot in IRC:

> `/tell OGABot identify <username> <password>`
