# SmokeLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SmokeLoader](https://vuldb.com/?actor.smokeloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.smokeloader](https://vuldb.com/?actor.smokeloader)

## Campaigns

The following _campaigns_ are known and can be associated with SmokeLoader:

* Tsunami

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmokeLoader:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmokeLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.224.217](https://vuldb.com/?ip.5.9.224.217) | static.217.224.9.5.clients.your-server.de | - | High
2 | [5.101.0.32](https://vuldb.com/?ip.5.101.0.32) | - | - | High
3 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | Tsunami | High
4 | [5.196.8.173](https://vuldb.com/?ip.5.196.8.173) | vps-b5645e9a.vps.ovh.net | - | High
5 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
6 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
7 | [23.0.48.75](https://vuldb.com/?ip.23.0.48.75) | a23-0-48-75.deploy.static.akamaitechnologies.com | - | High
8 | [23.0.209.167](https://vuldb.com/?ip.23.0.209.167) | a23-0-209-167.deploy.static.akamaitechnologies.com | - | High
9 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
10 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | - | High
11 | [23.13.211.142](https://vuldb.com/?ip.23.13.211.142) | a23-13-211-142.deploy.static.akamaitechnologies.com | - | High
12 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
13 | [23.66.61.153](https://vuldb.com/?ip.23.66.61.153) | a23-66-61-153.deploy.static.akamaitechnologies.com | - | High
14 | [23.193.177.127](https://vuldb.com/?ip.23.193.177.127) | a23-193-177-127.deploy.static.akamaitechnologies.com | - | High
15 | [23.218.40.161](https://vuldb.com/?ip.23.218.40.161) | a23-218-40-161.deploy.static.akamaitechnologies.com | - | High
16 | [23.221.48.201](https://vuldb.com/?ip.23.221.48.201) | a23-221-48-201.deploy.static.akamaitechnologies.com | - | High
17 | [27.102.67.144](https://vuldb.com/?ip.27.102.67.144) | - | - | High
18 | [31.13.65.36](https://vuldb.com/?ip.31.13.65.36) | edge-star-mini-shv-01-atl3.facebook.com | - | High
19 | [31.210.170.195](https://vuldb.com/?ip.31.210.170.195) | vps16632.hosted-by.eurohoster.online | - | High
20 | ... | ... | ... | ...

There are 74 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SmokeLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.pref.xml` | Medium
2 | File | `/acms/classes/Master.php?f=delete_cargo` | High
3 | File | `/admin.add` | Medium
4 | File | `/admin.php/news/admin/topic/save` | High
5 | File | `/admin/admin_login.php` | High
6 | File | `/admin/comn/service/update.json` | High
7 | File | `/admin/edit-doc.php` | High
8 | File | `/admin/edit_member.php` | High
9 | File | `/admin/edit_review.php` | High
10 | File | `/admin/profile/save_profile` | High
11 | File | `/api/v2/labels/` | High
12 | File | `/aux` | Low
13 | File | `/cgi-bin/koha/acqui/supplier.pl?op=enter` | High
14 | File | `/cgi-bin/luci` | High
15 | File | `/config/getuser` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/dev/shm` | Medium
18 | File | `/dl/dl_print.php` | High
19 | File | `/etc/gsissh/sshd_config` | High
20 | File | `/film-rating.php` | High
21 | File | `/gateway/services/EdgeServiceImpl` | High
22 | File | `/getcfg.php` | Medium
23 | File | `/goform/dir_setWanWifi` | High
24 | File | `/goform/telnet` | High
25 | File | `/goform/WanParameterSetting` | High
26 | File | `/HNAP1` | Low
27 | File | `/include/makecvs.php` | High
28 | File | `/index.php` | Medium
29 | File | `/info.xml` | Medium
30 | File | `/js/app.js` | Medium
31 | File | `/librarian/bookdetails.php` | High
32 | File | `/mgmt/tm/util/bash` | High
33 | File | `/monitoring` | Medium
34 | File | `/ofcms/company-c-47` | High
35 | File | `/opac/Actions.php?a=login` | High
36 | File | `/opt/pia/ruby/64/ruby` | High
37 | File | `/Pwrchute` | Medium
38 | File | `/spip.php` | Medium
39 | File | `/student/bookdetails.php` | High
40 | File | `/tmp/csman/0` | Medium
41 | File | `/ui/cbpc/login` | High
42 | File | `/uncpath/` | Medium
43 | File | `/usr/sbin/httpd` | High
44 | File | `/util/print.c` | High
45 | File | `/var/hnap/timestamp` | High
46 | File | `/vloggers_merch/admin/?page=product/manage_product` | High
47 | File | `/web/MCmsAction.java` | High
48 | File | `/wp-content/plugins/forum-server/feed.php` | High
49 | File | `abc-pcie.c` | Medium
50 | File | `account.asp` | Medium
51 | File | `accounts/payment_history.php` | High
52 | File | `adclick.php` | Medium
53 | File | `addfav.php` | Medium
54 | File | `address.html` | Medium
55 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/0cbee59f9e035659029cc87768c25903a603582a0d247460dcbbf6bf497311c4/
* https://bazaar.abuse.ch/sample/5bbe4ff9dc3e2fb44d356785216d39faa2ea386b1a5227798aea9c2d18b8b3fa/
* https://bazaar.abuse.ch/sample/5e30a88fb1c9a45bd6697990493098ca05e87b2560172ae89e9811ea887ff8b4/#intel
* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://community.blueliv.com/#!/s/6333fa0182df417ed0331a1d
* https://github.com/threatlabz/iocs/blob/main/smokeloader_tradingview_campaign/c2s.txt
* https://isc.sans.edu/forums/diary/Resumethemed+malspam+pushing+Smoke+Loader/23054/
* https://research.checkpoint.com/2019/2019-resurgence-of-smokeloader/
* https://threatfox.abuse.ch
* https://tria.ge/220511-fxrezafgg2
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
