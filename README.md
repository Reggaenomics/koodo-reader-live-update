Original Koodo: [HERE](https://github.com/koodo-reader/koodo-reader)
This adds functionality to Discord's RPC call such that page turns will update percentages in the view of the Discord blurb.
Only sends whole percent changes to prevent repeated/excessive sends to Discord
23.92% > 23.95% will not send an update.
