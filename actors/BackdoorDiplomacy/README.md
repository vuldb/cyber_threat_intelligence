# BackdoorDiplomacy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BackdoorDiplomacy](https://vuldb.com/?actor.backdoordiplomacy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.backdoordiplomacy](https://vuldb.com/?actor.backdoordiplomacy)

## Campaigns

The following _campaigns_ are known and can be associated with BackdoorDiplomacy:

* Middle East

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BackdoorDiplomacy:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BackdoorDiplomacy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.83.224.178](https://vuldb.com/?ip.23.83.224.178) | 23.83.224.178.16clouds.com | - | High
2 | [23.106.140.207](https://vuldb.com/?ip.23.106.140.207) | 23.106.140.207.16clouds.com | - | High
3 | [23.228.203.130](https://vuldb.com/?ip.23.228.203.130) | unassigned.psychz.net | - | High
4 | [23.247.47.252](https://vuldb.com/?ip.23.247.47.252) | - | - | High
5 | [43.225.126.179](https://vuldb.com/?ip.43.225.126.179) | - | - | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BackdoorDiplomacy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BackdoorDiplomacy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin/default.asp` | High
5 | File | `/administrator/components/table_manager/` | High
6 | File | `/ajax/networking/get_netcfg.php` | High
7 | File | `/app/options.py` | High
8 | File | `/assets/ctx` | Medium
9 | File | `/bin/httpd` | Medium
10 | File | `/cgi-bin/wapopen` | High
11 | File | `/ci_spms/admin/category` | High
12 | File | `/ci_spms/admin/search/searching/` | High
13 | File | `/classes/Master.php?f=delete_appointment` | High
14 | File | `/classes/Master.php?f=delete_train` | High
15 | File | `/cms/print.php` | High
16 | File | `/concat?/%2557EB-INF/web.xml` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/ctcprotocol/Protocol` | High
19 | File | `/dashboard/menu-list.php` | High
20 | File | `/data/remove` | Medium
21 | File | `/ffos/classes/Master.php?f=save_category` | High
22 | File | `/goforms/rlminfo` | High
23 | File | `/index.php/newsletter/subscriber/new/` | High
24 | File | `/Items/*/RemoteImages/Download` | High
25 | File | `/login` | Low
26 | File | `/menu.html` | Medium
27 | File | `/mkshop/Men/profile.php` | High
28 | File | `/navigate/navigate_download.php` | High
29 | File | `/ocwbs/admin/?page=user/manage_user` | High
30 | File | `/ofrs/admin/?page=user/manage_user` | High
31 | File | `/out.php` | Medium
32 | File | `/owa/auth/logon.aspx` | High
33 | File | `/password.html` | High
34 | File | `/php_action/fetchSelectedUser.php` | High
35 | File | `/proc/ioports` | High
36 | File | `/property-list/property_view.php` | High
37 | File | `/ptms/classes/Users.php` | High
38 | File | `/rest/api/2/search` | High
39 | File | `/s/` | Low
40 | File | `/scripts/cpan_config` | High
41 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
42 | File | `/services/system/setup.json` | High
43 | File | `/spip.php` | Medium
44 | File | `/tmp` | Low
45 | File | `/uncpath/` | Medium
46 | File | `/vloggers_merch/?p=view_product` | High
47 | File | `/webconsole/APIController` | High
48 | File | `/websocket/exec` | High
49 | File | `/whbs/?page=my_bookings` | High
50 | ... | ... | ...

There are 438 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bitdefender.com/files/News/CaseStudies/study/426/Bitdefender-PR-Whitepaper-BackdoorDiplomacy-creat6507-en-EN.pdf
* https://www.welivesecurity.com/2021/06/10/backdoordiplomacy-upgrading-quarian-turian/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
