## Cacti RCE - CVE-2024-29895

![image](https://github.com/Stuub/CVE-2024-29895-CactiRCE-PoC/assets/60468836/04ffb7ff-cf58-47be-90d7-d0422e4cb100)

## Usage:

`python3 cve-2024-29895.py -u https://target.com/ -c id`

Affecting Cacti versions 1.3.X on DEV builds where `cmd_realtime.php` is present and `POLLER_ID` is enabled.

Command Injection is possible via this endpoint, by requesting via GET with payload as HTML Query Parameters

## Dork:
Google: `inurl:cmd_realtime.php`

Shodan: `Cacti`

Hunter.how: `/product.name="Cacti"`

FOFA: `app="Cacti-Monitoring"`

## Version Checking

![image](https://github.com/Stuub/CVE-2024-29895-CactiRCE-PoC/assets/60468836/992fb9e6-426a-452c-b168-aa6e10303bc9)

## Disclaimer

Please exercise caution when using this PoC. It has been strictly developed to serve as a tool automate the validation of the vulnerability.
Any misuse caused is at your own responsibility.


