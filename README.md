# DDNSService
# THIS APPLICATION IS DEPRECIATED. PLEASE USE <https://github.com/BananasRule/DDNS-Servicev2>
## THIS APPLICATION IS NOT ENDORSED, SPONSORED OR ASSOCIATED WITH CLOUDFLARE
## THIS APPLICATION USES THE CLOUDFLARE API V4

## Discription
This is a python program that allows you to dynamically update your Cloudflare® dns records. This can be useful with a home system where your ip is dynamically assigned and changes. 

## Installation
One click install is supported via this command
> wget https://raw.githubusercontent.com/BananasRule/DDNSService/main/setup.sh && sudo bash setup.sh

If you are running as root try
> wget https://raw.githubusercontent.com/BananasRule/DDNSService/main/setup.sh && bash setup.sh

Once the script is finished please fill in the open config file (DDNSConfig.conf)


## Features
- Easy to run
- SMTP (Mail) notifications when a change is made or an error occours

## License
This repository is licensed under MPL 2.0. Please also include the atribution '© Jacob Gray 2022'.
Please see LICENSE.md for information. Please note that markdown may make the license appear weird. The raw file is the license. 

## Acknowledgements
This software uses the requests library licensed under the Apache License 2.0
> Requests <br>
> Copyright 2019 Kenneth Reitz

This software uses libaries from the standard python library under the PSF LICENSE AGREEMENT
> Copyright © 2001-2022 Python Software Foundation; All Rights Reserved 

Cloudflare, the Cloudflare logo, and Cloudflare Workers are trademarks and/or registered trademarks of Cloudflare, Inc. in the United States and other jurisdictions.



