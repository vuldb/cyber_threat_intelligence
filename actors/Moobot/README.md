# Moobot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Moobot](https://vuldb.com/?actor.moobot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moobot](https://vuldb.com/?actor.moobot)

## Campaigns

The following _campaigns_ are known and can be associated with Moobot:

* DDoS Ukraine
* UNIX CCTV DVR

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Moobot:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [ES](https://vuldb.com/?country.es)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Moobot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.13.195.56](https://vuldb.com/?ip.31.13.195.56) | - | - | High
2 | [37.49.226.216](https://vuldb.com/?ip.37.49.226.216) | - | - | High
3 | [45.95.168.90](https://vuldb.com/?ip.45.95.168.90) | - | - | High
4 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | UNIX CCTV DVR | High
5 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | UNIX CCTV DVR | High
6 | [89.248.174.198](https://vuldb.com/?ip.89.248.174.198) | - | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Moobot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Moobot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin/cloud.php` | High
3 | File | `/admin/login.php` | High
4 | File | `/api/document/<DocumentID>/attachments` | High
5 | File | `/cgi-bin/uploadWeiXinPic` | High
6 | File | `/core/admin/categories.php` | High
7 | File | `/coreframe/app/order/admin/card.php` | High
8 | File | `/DsaDataTest` | Medium
9 | File | `/eshop/products/json/aouCustomerAdresse` | High
10 | File | `/etc/config/cameo` | High
11 | File | `/etc/environment` | High
12 | File | `/extensionsinstruction` | High
13 | File | `/goform/setWorkmode` | High
14 | File | `/goods/getGoodsListByConditions/` | High
15 | File | `/member/index/login.html` | High
16 | File | `/moddable/xs/sources/xsScript.c` | High
17 | File | `/moddable/xs/sources/xsSymbol.c` | High
18 | File | `/music/ajax.php` | High
19 | File | `/nagioslogserver/configure/create_snapshot` | High
20 | File | `/nova/bin/lcdstat` | High
21 | File | `/orms/` | Low
22 | File | `/rest/api/1.0/issues/{id}/ActionsAndOperations` | High
23 | File | `/rest/api/2/user/picker` | High
24 | File | `/rsms/` | Low
25 | File | `/secure/QueryComponent!Default.jspa` | High
26 | File | `/src/njs_vmcode.c` | High
27 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
28 | File | `/syscmd.asp` | Medium
29 | File | `/system?action=ServiceAdmin` | High
30 | File | `/tmp` | Low
31 | File | `/uncpath/` | Medium
32 | File | `/uploads/dede` | High
33 | File | `/user/add` | Medium
34 | ... | ... | ...

There are 293 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/ddos-botnet-moobot-en/
* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/the-botnet-cluster-on-185-244-25-0-24-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
