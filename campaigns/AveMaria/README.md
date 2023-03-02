# AveMaria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AveMaria_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AveMaria:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [BR](https://vuldb.com/?country.br)
* ...

There are 19 more country items available. Please use our online service to access the data.

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
4 | [31.210.20.231](https://vuldb.com/?ip.31.210.20.231) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
5 | [37.0.14.204](https://vuldb.com/?ip.37.0.14.204) | - | [AveMaria](https://vuldb.com/?actor.avemaria) | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AveMaria. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AveMaria. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/etc/splunk-launch.conf` | High
2 | File | `.htaccess` | Medium
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/account/details.php` | High
5 | File | `/admin/academic/studenview_left.php` | High
6 | File | `/admin/admin.php?module=admin_group_edit&agID` | High
7 | File | `/admin/contenttemp` | High
8 | File | `/admin/payment.php` | High
9 | File | `/admin/syslog` | High
10 | File | `/advance_push/public/login` | High
11 | File | `/anony/mjpg.cgi` | High
12 | File | `/assets/components/gallery/connector.php` | High
13 | File | `/ctcprotocol/Protocol` | High
14 | File | `/device/device=140/tab=wifi/view` | High
15 | File | `/etc/sudoers` | Medium
16 | File | `/Forms/` | Low
17 | File | `/framework/modules/users/models/user.php` | High
18 | File | `/ghost/preview` | High
19 | File | `/HNAP1/SetAccessPointMode` | High
20 | File | `/index.php` | Medium
21 | File | `/mcategory.php` | High
22 | File | `/member/picture/album` | High
23 | File | `/mysql/api/diags.php` | High
24 | File | `/phpcollab/users/edituser.php` | High
25 | File | `/plain` | Low
26 | File | `/products/details.asp` | High
27 | File | `/product_list.php` | High
28 | File | `/public/login.htm` | High
29 | File | `/replication` | Medium
30 | File | `/service/upload` | High
31 | File | `/services/details.asp` | High
32 | File | `/trx_addons/v2/get/sc_layout` | High
33 | File | `/uncpath/` | Medium
34 | File | `/upload/catalog/controller/account/password.php` | High
35 | File | `/usr/bin/pkexec` | High
36 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
37 | File | `/WebMstr7/servlet/mstrWeb` | High
38 | File | `4.edu.php` | Medium
39 | File | `5.2.9\syscrb.exe` | High
40 | File | `123flashchat.php` | High
41 | File | `add_ons.php` | Medium
42 | File | `add_to_cart.php` | High
43 | File | `admin.php` | Medium
44 | File | `admin/index.php` | High
45 | File | `admin/mod_users/controller.php?action=edit` | High
46 | ... | ... | ...

There are 399 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
