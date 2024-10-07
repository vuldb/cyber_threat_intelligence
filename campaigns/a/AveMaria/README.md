# AveMaria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AveMaria_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AveMaria:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [BR](https://vuldb.com/?country.br)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AveMaria or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/?actor.fin7) | High
2 | [AveMaria](https://vuldb.com/?actor.avemaria) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AveMaria.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.56.56.88](https://vuldb.com/?ip.2.56.56.88) | nutir.top | [AveMaria](https://vuldb.com/?actor.avemaria) | High
2 | [2.56.57.85](https://vuldb.com/?ip.2.56.57.85) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
3 | [5.2.68.67](https://vuldb.com/?ip.5.2.68.67) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
4 | [20.7.14.99](https://vuldb.com/?ip.20.7.14.99) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
5 | [31.210.20.231](https://vuldb.com/?ip.31.210.20.231) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
6 | [37.0.14.204](https://vuldb.com/?ip.37.0.14.204) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AveMaria. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AveMaria. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/etc/splunk-launch.conf` | High
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/account/details.php` | High
4 | File | `/admin/academic/studenview_left.php` | High
5 | File | `/admin/admin.php?module=admin_group_edit&agID` | High
6 | File | `/admin/contenttemp` | High
7 | File | `/Admin/login.php` | High
8 | File | `/admin/payment.php` | High
9 | File | `/admin/syslog` | High
10 | File | `/admin/user/manage_user.php` | High
11 | File | `/advance_push/public/login` | High
12 | File | `/anony/mjpg.cgi` | High
13 | File | `/app/uploading/upload-mp3.php` | High
14 | File | `/application/index/controller/Databasesource.php` | High
15 | File | `/application/index/controller/File.php` | High
16 | File | `/application/plugins/controller/Upload.php` | High
17 | File | `/assets/components/gallery/connector.php` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/master.php?f=delete_order` | High
21 | File | `/course/filterRecords/` | High
22 | File | `/ctcprotocol/Protocol` | High
23 | File | `/device/device=140/tab=wifi/view` | High
24 | File | `/download/image` | High
25 | File | `/endpoint/update-bookmark.php` | High
26 | File | `/etc/sudoers` | Medium
27 | File | `/ext/collect/find_text.do` | High
28 | File | `/Forms/` | Low
29 | File | `/forum/away.php` | High
30 | File | `/framework/modules/users/models/user.php` | High
31 | File | `/ghost/preview` | High
32 | File | `/HNAP1/SetAccessPointMode` | High
33 | File | `/index.php` | Medium
34 | File | `/mcategory.php` | High
35 | File | `/member/picture/album` | High
36 | File | `/mysql/api/diags.php` | High
37 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
38 | File | `/ndmComponents.js` | High
39 | File | `/oauth/idp/.well-known/openid-configuration` | High
40 | File | `/out.php` | Medium
41 | File | `/phpcollab/users/edituser.php` | High
42 | File | `/plain` | Low
43 | File | `/products/details.asp` | High
44 | File | `/product_list.php` | High
45 | File | `/public/login.htm` | High
46 | File | `/replication` | Medium
47 | File | `/secserver` | Medium
48 | File | `/service/upload` | High
49 | File | `/services/details.asp` | High
50 | File | `/showfile.php` | High
51 | File | `/spip.php` | Medium
52 | File | `/trx_addons/v2/get/sc_layout` | High
53 | File | `/uncpath/` | Medium
54 | ... | ... | ...

There are 472 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/34102/
* https://asec.ahnlab.com/en/34624/
* https://asec.ahnlab.com/en/34785/
* https://asec.ahnlab.com/en/35190/
* https://asec.ahnlab.com/en/36629/
* https://blog.morphisec.com/threat-alert-ave-maria-infostealer-on-the-rise-with-new-stealthier-delivery
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-10-11%20AveMaria%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-01-28%20AveMaria_Warzone%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-04-19%20AveMaria_Warzone%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-06-24%20AveMaria_Warzone%20RAT%20IOCs
* https://securelist.com/fin7-5-the-infamous-cybercrime-rig-fin7-continues-its-activities/90703/
* https://www.zscaler.com/blogs/security-research/dynamic-approaches-seen-avemarias-distribution-strategy

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
