# Inception - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Inception_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Inception:

* [AR](https://vuldb.com/?country.ar)
* [IT](https://vuldb.com/?country.it)
* [SV](https://vuldb.com/?country.sv)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Inception or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Inception](https://vuldb.com/?actor.inception) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Inception.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [51.255.139.194](https://vuldb.com/?ip.51.255.139.194) | ip194.ip-51-255-139.eu | [Inception](https://vuldb.com/?actor.inception) | High
2 | [82.221.100.55](https://vuldb.com/?ip.82.221.100.55) | web.a1yola.com | [Inception](https://vuldb.com/?actor.inception) | High
3 | [82.221.100.60](https://vuldb.com/?ip.82.221.100.60) | - | [Inception](https://vuldb.com/?actor.inception) | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/changestock.php` | High
2 | File | `/admin/client_edit.php` | High
3 | File | `/admin/comment/list` | High
4 | File | `/admin/header.inc.php` | High
5 | File | `/admin/index.PHP` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/modify.php` | High
8 | File | `/admin/plugins/NP_Referrer.php` | High
9 | File | `/admin/products/controller.php?action=add` | High
10 | File | `/admin/profile.php` | High
11 | File | `/admin/search.php` | High
12 | File | `/admin/select.php` | High
13 | File | `/admin/sendmailto.php?tomail=&groupid=` | High
14 | File | `/admin/site/list` | High
15 | File | `/api/` | Low
16 | File | `/api/v2/labels/` | High
17 | File | `/asan/asan_interceptors_memintrinsics.cpp` | High
18 | File | `/cgi-bin/ExportSettings.sh` | High
19 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
20 | File | `/claire_blake` | High
21 | File | `/classes/Master.php?f=delete_student` | High
22 | File | `/common/bbox.cpp` | High
23 | File | `/etc/origin/master/master-config.yaml` | High
24 | File | `/etc/shadow.sample` | High
25 | File | `/footer.inc.php` | High
26 | File | `/framework/core/models/expConfig.php` | High
27 | File | `/framework/modules/core/controllers/expHTMLEditorController.php` | High
28 | File | `/fw.login.php` | High
29 | File | `/gasmark/assets/myimages/oneWord.php` | High
30 | File | `/goform/formWifiBasicSet` | High
31 | File | `/goform/NatStaticSetting` | High
32 | File | `/goform/saveParentControlInfo` | High
33 | File | `/home/www/cgi-bin/login.cgi` | High
34 | File | `/htdocs/utils/Files.php` | High
35 | File | `/include/notify.inc.php` | High
36 | File | `/ip/admin/` | Medium
37 | File | `/issue` | Low
38 | File | `/leave_system/classes/Master.php?f=delete_application` | High
39 | File | `/master/index.php` | High
40 | File | `/mdiy/model/delete` | High
41 | File | `/net-banking/customer_transactions.php` | High
42 | File | `/net/nfc/netlink.c` | High
43 | File | `/pages/permit/permit.php` | High
44 | File | `/patient/settings.php` | High
45 | File | `/ptipupgrade.cgi` | High
46 | ... | ... | ...

There are 398 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/interception
* https://securelist.com/recent-cloud-atlas-activity/92016/
* https://unit42.paloaltonetworks.com/unit42-inception-attackers-target-europe-year-old-office-vulnerability/
* https://www.threatminer.org/report.php?q=bcs_wp_InceptionReport_EN_v12914.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
