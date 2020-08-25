## Googlebot Checker V1

The notebook verifies that IPs in a .csv file are genuinely from Googlebots, via reverse/forward DNS lookups.

It’s a Jupyter port of [searchtools.io](https://www.searchtools.io/), created by the great [Tyler Reardon](https://twitter.com/TylerReardon).

Note that the script is still in its early days, thus:

*   You may get errors when checking a large amount of IP addresses
*   The reverse-DNS checks are currently limited to Googlebots
*   Bingbots and more user agents will be added soon!

[Reach me out on Twitter](https://twitter.com/DataChaz) if questions - Pull requests are welcome! :)
