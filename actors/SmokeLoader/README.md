# SmokeLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SmokeLoader](https://vuldb.com/?actor.smokeloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.smokeloader](https://vuldb.com/?actor.smokeloader)

## Campaigns

The following _campaigns_ are known and can be associated with SmokeLoader:

* Tsunami

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmokeLoader:

* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmokeLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | Tsunami | High
2 | [5.196.8.173](https://vuldb.com/?ip.5.196.8.173) | vps-b5645e9a.vps.ovh.net | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
5 | [31.13.65.36](https://vuldb.com/?ip.31.13.65.36) | edge-star-mini-shv-01-atl3.facebook.com | - | High
6 | [31.210.170.195](https://vuldb.com/?ip.31.210.170.195) | vps16632.hosted-by.eurohoster.online | - | High
7 | [51.254.25.115](https://vuldb.com/?ip.51.254.25.115) | ip115.ip-51-254-25.eu | Tsunami | High
8 | [51.255.48.78](https://vuldb.com/?ip.51.255.48.78) | vps-ede152ed.vps.ovh.net | Tsunami | High
9 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SmokeLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

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
23 | File | `/opt/pia/ruby/64/ruby` | High
24 | File | `/out.php` | Medium
25 | File | `/outgoing.php` | High
26 | File | `/scripts/iisadmin/bdir.htr` | High
27 | File | `/tmp` | Low
28 | File | `/tmp/csman/0` | Medium
29 | File | `/ui/cbpc/login` | High
30 | File | `/uncpath/` | Medium
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
41 | File | `admin/index.php` | High
42 | File | `administrador.asp` | High
43 | File | `AdminQuickAccessesController.php` | High
44 | ... | ... | ...

There are 384 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://research.checkpoint.com/2019/2019-resurgence-of-smokeloader/
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
