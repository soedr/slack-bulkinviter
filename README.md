### Slack-Bulkinviter

Super quick and dirty Python script to bulk invite ALL users in a slack team to a specific channel. Forked from [robby-dermody/slack-bulkinviter](https://github.com/robby-dermody/slack-bulkinviter).

To use:
* Install the [slacker](https://github.com/os/slacker) library via `pip`
* [Get an API key](hhttps://api.slack.com/slack-apps)
* Store your API key as an environment variable; change the varname according to your needs.
* Execute the script, passing the name of the channel where all users will be invited. Example:

	`./slack-bulkinviter.py --channel mychannel`

* Sit back and let it do its work.

Additional info:
* The tool does not allow you to invite bots or yourself to a channel. 
