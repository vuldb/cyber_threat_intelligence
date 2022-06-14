# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 35 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | [85.203.46.99](https://vuldb.com/?ip.85.203.46.99) | - | BumbleBee | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/6/api.php?function=command&class=remote&Cc='ls'` | High
4 | File | `/about.php` | Medium
5 | File | `/admin.php?action=themeinstall` | High
6 | File | `/admin/contenttemp` | High
7 | File | `/admin/modules/system/custom_field.php` | High
8 | File | `/api/crontab` | Medium
9 | File | `/bin/boa` | Medium
10 | File | `/category_view.php` | High
11 | File | `/cgi-bin/wapopen` | High
12 | File | `/cgi-mod/lookup.cgi` | High
13 | File | `/cgi?1&5` | Medium
14 | File | `/config/getuser` | High
15 | File | `/debug/pprof` | Medium
16 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
17 | File | `/iissamples` | Medium
18 | File | `/interface/main/backup.php` | High
19 | File | `/new` | Low
20 | File | `/public/plugins/` | High
21 | File | `/requests.php` | High
22 | File | `/sbin/gs_config` | High
23 | File | `/scripts/cpan_config` | High
24 | File | `/secure/QueryComponent!Default.jspa` | High
25 | File | `/uncpath/` | Medium
26 | File | `/usr/bin/pkexec` | High
27 | File | `/usr/sbin/nagios` | High
28 | File | `/usr/sbin/suexec` | High
29 | File | `/WEB-INF/web.xml` | High
30 | File | `/webman/info.cgi` | High
31 | File | `/wp-admin/admin-ajax.php` | High
32 | File | `/wp-json/oembed/1.0/embed?url` | High
33 | File | `/wp-json/wc/v3/webhooks` | High
34 | File | `/_internal` | Medium
35 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
36 | File | `adclick.php` | Medium
37 | File | `admin.php?m=admin&c=site&a=save` | High
38 | File | `admin.php?page=languages` | High
39 | File | `admin/admin_users.php` | High
40 | File | `admin/bitrix.mpbuilder_step2.php` | High
41 | File | `admin/conf_users_edit.php` | High
42 | File | `admin/ops/reports/ops/news.php` | High
43 | File | `adminer.php` | Medium
44 | File | `administrator/mail/download.cfm` | High
45 | ... | ... | ...

There are 389 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
