# Kimsuky - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kimsuky](https://vuldb.com/?actor.kimsuky). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kimsuky](https://vuldb.com/?actor.kimsuky)

## Campaigns

The following _campaigns_ are known and can be associated with Kimsuky:

* AppleSeed
* PebbleDash
* RftRAT/Amadey

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kimsuky:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [KR](https://vuldb.com/?country.kr)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kimsuky.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.59.53](https://vuldb.com/?ip.5.61.59.53) | - | - | High
2 | [23.106.122.239](https://vuldb.com/?ip.23.106.122.239) | - | - | High
3 | [23.236.181.108](https://vuldb.com/?ip.23.236.181.108) | 108.181.236.23.in-addr.arpa | RftRAT/Amadey | High
4 | [27.102.102.70](https://vuldb.com/?ip.27.102.102.70) | - | - | High
5 | [27.102.107.63](https://vuldb.com/?ip.27.102.107.63) | - | AppleSeed | High
6 | [27.102.112.44](https://vuldb.com/?ip.27.102.112.44) | - | - | High
7 | [27.102.112.58](https://vuldb.com/?ip.27.102.112.58) | - | - | High
8 | [27.102.114.63](https://vuldb.com/?ip.27.102.114.63) | - | - | High
9 | [27.102.114.79](https://vuldb.com/?ip.27.102.114.79) | - | - | High
10 | [27.102.114.89](https://vuldb.com/?ip.27.102.114.89) | - | AppleSeed | High
11 | [27.102.127.240](https://vuldb.com/?ip.27.102.127.240) | - | - | High
12 | [27.102.128.169](https://vuldb.com/?ip.27.102.128.169) | - | - | High
13 | [27.255.79.204](https://vuldb.com/?ip.27.255.79.204) | - | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kimsuky_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kimsuky. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Netwrix Auditor\Logs\ActiveDirectory\` | High
2 | File | `/?/admin/snippet/add` | High
3 | File | `/Admin/add-student.php` | High
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/categories/manage_category.php` | High
6 | File | `/admin/categories/view_category.php` | High
7 | File | `/admin/index.php` | High
8 | File | `/admin/inquiries/view_inquiry.php` | High
9 | File | `/admin/manage_academic.php` | High
10 | File | `/admin/orders/update_status.php` | High
11 | File | `/admin/products/manage_product.php` | High
12 | File | `/admin/products/view_product.php` | High
13 | File | `/admin/reminders/manage_reminder.php` | High
14 | File | `/admin/sales/manage_sale.php` | High
15 | File | `/admin/sales/view_details.php` | High
16 | File | `/admin/services/manage_service.php` | High
17 | File | `/admin/user/manage_user.php` | High
18 | File | `/api/` | Low
19 | File | `/api/upload` | Medium
20 | File | `/assets/something/services/AppModule.class` | High
21 | File | `/bin/false` | Medium
22 | File | `/blog` | Low
23 | File | `/cgi-bin/ExportLogs.sh` | High
24 | File | `/cgi-bin/luci/api/wireless` | High
25 | File | `/cgi-bin/webproc` | High
26 | File | `/classes/Master.php?f=delete_inquiry` | High
27 | File | `/classes/Master.php?f=save_service` | High
28 | File | `/classes/Users.php` | High
29 | File | `/editsettings` | High
30 | File | `/etc/postfix/sender_login` | High
31 | File | `/export` | Low
32 | File | `/forgetpassword.php` | High
33 | File | `/forum/away.php` | High
34 | File | `/function/login.php` | High
35 | File | `/hrm/controller/employee.php` | High
36 | File | `/images/browserslide.jpg` | High
37 | File | `/inc/HTTPClient.php` | High
38 | File | `/includes/lib/get.php` | High
39 | File | `/lists/index.php` | High
40 | File | `/login` | Low
41 | File | `/main?cmd=invalid_browser` | High
42 | File | `/manager?action=getlogcat` | High
43 | File | `/mgmt/tm/util/bash` | High
44 | File | `/mkshop/Men/profile.php` | High
45 | File | `/mkshope/login.php` | High
46 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/30532/
* https://asec.ahnlab.com/en/57873/
* https://asec.ahnlab.com/en/59590/
* https://blog.alyac.co.kr/2234
* https://blog.alyac.co.kr/4892
* https://blog.malwarebytes.com/threat-analysis/2021/06/kimsuky-apt-continues-to-target-south-korean-government-using-appleseed-backdoor/
* https://community.blueliv.com/#!/s/5fa1234a82df413ea9349a07
* https://github.com/blackorbird/APT_REPORT/blob/master/kimsuky/Kimsuky%20APT%20Group%20targeted%20on%20South%20Korean%20defense%20and%20security%20departments.pdf
* https://github.com/blackorbird/APT_REPORT/tree/master/kimsuky
* https://github.com/eset/malware-ioc/tree/master/kimsuky/hotdoge_donutcat_case
* https://threatfox.abuse.ch
* https://twitter.com/shadowchasing1/status/1500778382966939653
* https://twitter.com/souiten/status/1473862308132651011
* https://www.sentinelone.com/labs/kimsuky-new-social-engineering-campaign-aims-to-steal-credentials-and-gather-strategic-intelligence/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
