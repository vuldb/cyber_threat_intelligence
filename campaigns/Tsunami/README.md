# Tsunami - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Tsunami_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tsunami:

* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Tsunami or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tsunami.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [51.254.25.115](https://vuldb.com/?ip.51.254.25.115) | ip115.ip-51-254-25.eu | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
3 | [51.255.48.78](https://vuldb.com/?ip.51.255.48.78) | vps-ede152ed.vps.ovh.net | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Tsunami. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Tsunami. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `.pref.xml` | Medium
3 | File | `/bin/appmgr` | Medium
4 | File | `/cgi-bin/editBookmark` | High
5 | File | `/cgi-bin/koha/acqui/supplier.pl?op=enter` | High
6 | File | `/cgi-bin/luci` | High
7 | File | `/cgi-bin/pass` | High
8 | File | `/cgi/ansi` | Medium
9 | File | `/ClickAndBanexDemo/admin/admin.asp` | High
10 | File | `/config/getuser` | High
11 | File | `/etc/gsissh/sshd_config` | High
12 | File | `/etc/passwd` | Medium
13 | File | `/etc/sudoers` | Medium
14 | File | `/getcfg.php` | Medium
15 | File | `/goform/GetNewDir` | High
16 | File | `/goform/telnet` | High
17 | File | `/goform/WanParameterSetting` | High
18 | File | `/hnap.cgi` | Medium
19 | File | `/HNAP1` | Low
20 | File | `/include/makecvs.php` | High
21 | File | `/includes/common.inc.php` | High
22 | File | `/knomi/analyze` | High
23 | File | `/mgmt/tm/util/bash` | High
24 | File | `/monitoring` | Medium
25 | File | `/out.php` | Medium
26 | File | `/outgoing.php` | High
27 | File | `/scripts/iisadmin/bdir.htr` | High
28 | File | `/tmp` | Low
29 | File | `/tmp/csman/0` | Medium
30 | File | `/ui/cbpc/login` | High
31 | File | `/var/avamar/f_cache.dat` | High
32 | File | `/var/hnap/timestamp` | High
33 | File | `/var/run/storage_account_root` | High
34 | File | `/webmail/` | Medium
35 | File | `/wp-content/plugins/forum-server/feed.php` | High
36 | File | `/{ADMIN-FILE}/` | High
37 | File | `a2billing/customer/iridium_threed.php` | High
38 | File | `address.html` | Medium
39 | File | `adm/systools.asp` | High
40 | File | `admin.php` | Medium
41 | ... | ... | ...

There are 354 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
