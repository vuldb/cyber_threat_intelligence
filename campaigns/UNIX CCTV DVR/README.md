# UNIX CCTV DVR - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _UNIX CCTV DVR_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNIX CCTV DVR:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [ES](https://vuldb.com/?country.es)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with UNIX CCTV DVR or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Moobot](https://vuldb.com/?actor.moobot) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNIX CCTV DVR.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
2 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
3 | [89.248.174.203](https://vuldb.com/?ip.89.248.174.203) | no-reverse-dns-configured.com | [Moobot](https://vuldb.com/?actor.moobot) | High
4 | [92.223.73.54](https://vuldb.com/?ip.92.223.73.54) | james050721.example.com | [Moobot](https://vuldb.com/?actor.moobot) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used within UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer Chroma\SDK\Apps` | High
2 | File | `/admin/cloud.php` | High
3 | File | `/admin/login.php` | High
4 | File | `/api/document/<DocumentID>/attachments` | High
5 | File | `/bin/sh` | Low
6 | File | `/cgi-bin-sdb/` | High
7 | File | `/cgi-bin/` | Medium
8 | File | `/core/admin/categories.php` | High
9 | File | `/coreframe/app/order/admin/card.php` | High
10 | File | `/device/device=345/?tab=ports` | High
11 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
12 | File | `/eshop/products/json/aouCustomerAdresse` | High
13 | File | `/etc/config/cameo` | High
14 | File | `/etc/environment` | High
15 | File | `/extensionsinstruction` | High
16 | File | `/goods/getGoodsListByConditions/` | High
17 | File | `/includes/lib/tree.php` | High
18 | File | `/MagickCore/quantize.c` | High
19 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
20 | File | `/member/index/login.html` | High
21 | File | `/moddable/xs/sources/xsScript.c` | High
22 | File | `/moddable/xs/sources/xsSymbol.c` | High
23 | File | `/multiux/SaveMailbox` | High
24 | File | `/nagioslogserver/configure/create_snapshot` | High
25 | File | `/nova/bin/lcdstat` | High
26 | File | `/PreviewHandler.ashx` | High
27 | File | `/rest/api/1.0/issues/{id}/ActionsAndOperations` | High
28 | File | `/rest/api/2/user/picker` | High
29 | File | `/secure/QueryComponent!Default.jspa` | High
30 | File | `/src/njs_vmcode.c` | High
31 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
32 | File | `/syscmd.asp` | Medium
33 | File | `/system?action=ServiceAdmin` | High
34 | File | `/tmp` | Low
35 | File | `/uncpath/` | Medium
36 | File | `/uploads/dede` | High
37 | File | `/user/add` | Medium
38 | ... | ... | ...

There are 328 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
