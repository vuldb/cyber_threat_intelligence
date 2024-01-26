# Crimson RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Crimson RAT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Crimson RAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Crimson RAT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT36](https://vuldb.com/?actor.apt36) | High
2 | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Crimson RAT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.189.170.4](https://vuldb.com/?ip.5.189.170.4) | vmi1296570.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
2 | [5.189.170.84](https://vuldb.com/?ip.5.189.170.84) | ip-84-170-189-5.static.contabo.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
3 | [5.189.176.185](https://vuldb.com/?ip.5.189.176.185) | vmi513888.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
4 | [5.189.183.63](https://vuldb.com/?ip.5.189.183.63) | vmi559729.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
5 | [23.226.132.105](https://vuldb.com/?ip.23.226.132.105) | 23.226.132.105.static.quadranet.com | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
6 | [38.242.211.87](https://vuldb.com/?ip.38.242.211.87) | vmi1506647.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
7 | [45.14.194.253](https://vuldb.com/?ip.45.14.194.253) | vmi1497978.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
8 | [62.171.130.47](https://vuldb.com/?ip.62.171.130.47) | ip-47-130-171-62.static.contabo.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
9 | [62.171.135.174](https://vuldb.com/?ip.62.171.135.174) | vmi875832.contaboserver.net | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
10 | [64.188.19.199](https://vuldb.com/?ip.64.188.19.199) | 64.188.19.199.static.quadranet.com | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
11 | [64.188.25.43](https://vuldb.com/?ip.64.188.25.43) | 64.188.25.43.static.quadranet.com | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
12 | [64.188.25.205](https://vuldb.com/?ip.64.188.25.205) | 64.188.25.205.static.quadranet.com | [APT36](https://vuldb.com/?actor.apt36) | High
13 | [66.154.103.101](https://vuldb.com/?ip.66.154.103.101) | 66.154.103.101.static.quadranet.com | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
14 | [66.235.175.91](https://vuldb.com/?ip.66.235.175.91) | - | [Crimson RAT](https://vuldb.com/?actor.crimson_rat) | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Crimson RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Crimson RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/inventory/manage_stock.php` | High
3 | File | `/admin/login.php` | High
4 | File | `/admin/maintenance/view_designation.php` | High
5 | File | `/admin/new-content` | High
6 | File | `/admin/reportupload.aspx` | High
7 | File | `/api/admin/system/store/order/list` | High
8 | File | `/api/upload` | Medium
9 | File | `/app/tag/controller/ApiAdminTagCategory.php` | High
10 | File | `/common/info.cgi` | High
11 | File | `/csms/?page=contact_us` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/ecodesource/search_list.php` | High
14 | File | `/etc/tcsd.conf` | High
15 | File | `/file` | Low
16 | File | `/filemanager/upload.php` | High
17 | File | `/forum/away.php` | High
18 | File | `/fudforum/index.php` | High
19 | File | `/horde/imp/search.php` | High
20 | File | `/index.php?page=search/rentals` | High
21 | File | `/login.php` | Medium
22 | File | `/modules/profile/index.php` | High
23 | File | `/modules/registration_admission/patient_register.php` | High
24 | File | `/netflow/jspui/selectDevice.jsp` | High
25 | File | `/oauth/idp/.well-known/openid-configuration` | High
26 | File | `/out.php` | Medium
27 | File | `/plugin/rundeck/webhook/` | High
28 | File | `/pms/admin/crimes/view_crime.php` | High
29 | File | `/scheduler/addSchedule.php` | High
30 | File | `/spip.php` | Medium
31 | File | `/student/bookdetails.php` | High
32 | File | `/uncpath/` | Medium
33 | File | `/upload` | Low
34 | File | `/wp-admin/admin-ajax.php` | High
35 | File | `4.edu.php` | Medium
36 | File | `5.2.9\syscrb.exe` | High
37 | File | `adclick.php` | Medium
38 | File | `add-vehicle.php` | High
39 | File | `addentry.php` | Medium
40 | File | `admin.php` | Medium
41 | File | `admin/admin.php` | High
42 | File | `admin/conf_users_edit.php` | High
43 | File | `adminHome.php` | High
44 | File | `admin_add.php` | High
45 | ... | ... | ...

There are 391 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.malwarebytes.com/threat-analysis/2020/03/apt36-jumps-on-the-coronavirus-bandwagon-delivers-crimson-rat/
* https://threatfox.abuse.ch
* https://twitter.com/0xrb/status/1492030514035060741?s=20&t=LxxFCank6LgKGEWxOnVa0Q
* https://twitter.com/0xrb/status/1704827410695528554
* https://twitter.com/RedDrip7/status/1622908094606094338
* https://twitter.com/StopMalvertisin/status/1645805949234597889
* https://twitter.com/StopMalvertisin/status/1670660520540770305
* https://twitter.com/StopMalvertisin/status/1676869449394327553
* https://twitter.com/StopMalvertisin/status/1689669636940570624
* https://x.com/0xrb/status/1702542474911371578?s=20

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
