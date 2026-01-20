# Skuld - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Skuld](https://vuldb.com/?actor.skuld). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.skuld](https://vuldb.com/?actor.skuld)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Skuld:

* [IR](https://vuldb.com/?country.ir)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Skuld.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.128.248.46](https://vuldb.com/?ip.23.128.248.46) | - | - | High
2 | [34.83.46.130](https://vuldb.com/?ip.34.83.46.130) | 130.46.83.34.bc.googleusercontent.com | - | Medium
3 | [34.85.253.170](https://vuldb.com/?ip.34.85.253.170) | 170.253.85.34.bc.googleusercontent.com | - | Medium
4 | [34.105.0.27](https://vuldb.com/?ip.34.105.0.27) | 27.0.105.34.bc.googleusercontent.com | - | Medium
5 | [34.105.183.68](https://vuldb.com/?ip.34.105.183.68) | 68.183.105.34.bc.googleusercontent.com | - | Medium
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Skuld_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-29, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-266, CWE-269, CWE-272, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Skuld. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/account/delivery` | High
2 | File | `/ad-list` | Medium
3 | File | `/admin.php` | Medium
4 | File | `/admin/admin.php` | High
5 | File | `/admin/admin_user.php` | High
6 | File | `/admin/ajax.php?action=save_settings` | High
7 | File | `/admin/form/save` | High
8 | File | `/admin/makehtml_freelist_action.php` | High
9 | File | `/admin/modal_add_product.php` | High
10 | File | `/admin/nav/save` | High
11 | File | `/admin/slide/update` | High
12 | File | `/alumni/admin/ajax.php?action=save_settings` | High
13 | File | `/ample/app/action/edit_product.php` | High
14 | File | `/api/controllers/merchant/app/ComboController.php` | High
15 | File | `/api/dashboard/activity` | High
16 | File | `/api/system/sessions` | High
17 | File | `/appliance/users?action=edit` | High
18 | File | `/apply.cgi` | Medium
19 | File | `/arp_sys.asp` | Medium
20 | File | `/blog` | Low
21 | File | `/boafrm/formParentControl` | High
22 | File | `/boafrm/formWlSiteSurvey` | High
23 | File | `/browse` | Low
24 | File | `/bypass/config` | High
25 | File | `/catalog/compare` | High
26 | File | `/cgi-bin/cstecgi.cgi` | High
27 | File | `/classes/Master.php?f=delete_img` | High
28 | File | `/classes/Master.php?f=delete_service` | High
29 | File | `/classes/Master.php?f=save_category` | High
30 | File | `/common/show_image.php` | High
31 | File | `/contact-us.php` | High
32 | File | `/control/player?center&eventlist&pda&dummy_for_reload=1736177631&p_evt` | High
33 | File | `/cupseasylive/grnprint.php` | High
34 | File | `/cupseasylive/stock.php` | High
35 | File | `/cupseasylive/stockissuancedisplay.php` | High
36 | File | `/cupseasylive/taxstructurelist.php` | High
37 | File | `/ddns.asp?opt=add` | High
38 | File | `/dev/audio` | Medium
39 | File | `/DiscoveryProcess/Service/Admin.svc/getGridColumnStructure` | High
40 | File | `/endpoint/delete-account.php` | High
41 | File | `/etc/hosts.deny` | High
42 | File | `/etc_ro/smb.conf` | High
43 | File | `/formLoginAuth.htm` | High
44 | File | `/goform/AdvSetWrlsafeset` | High
45 | File | `/goform/formAdvanceSetup` | High
46 | ... | ... | ...

There are 396 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trellix.com/about/newsroom/stories/research/skuld-the-infostealer-that-speaks-golang/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
