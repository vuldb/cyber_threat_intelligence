# Pegasus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Pegasus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pegasus:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Pegasus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [LULU](https://vuldb.com/?actor.lulu) | High
2 | [NSO Group](https://vuldb.com/?actor.nso_group) | High
3 | [Sarwent](https://vuldb.com/?actor.sarwent) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pegasus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.13.132.96](https://vuldb.com/?ip.3.13.132.96) | ec2-3-13-132-96.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
2 | [3.16.75.157](https://vuldb.com/?ip.3.16.75.157) | ec2-3-16-75-157.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
3 | [13.58.85.100](https://vuldb.com/?ip.13.58.85.100) | ec2-13-58-85-100.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
4 | [13.59.79.240](https://vuldb.com/?ip.13.59.79.240) | ec2-13-59-79-240.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
5 | [18.191.63.125](https://vuldb.com/?ip.18.191.63.125) | ec2-18-191-63-125.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
6 | [18.217.13.50](https://vuldb.com/?ip.18.217.13.50) | ec2-18-217-13-50.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
7 | [18.225.12.72](https://vuldb.com/?ip.18.225.12.72) | ec2-18-225-12-72.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
8 | [23.239.16.143](https://vuldb.com/?ip.23.239.16.143) | li685-143.members.linode.com | [NSO Group](https://vuldb.com/?actor.nso_group) | High
9 | [45.32.105.249](https://vuldb.com/?ip.45.32.105.249) | 45.32.105.249.vultrusercontent.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
10 | [45.79.190.38](https://vuldb.com/?ip.45.79.190.38) | srv01.benlinden.com | [NSO Group](https://vuldb.com/?actor.nso_group) | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Pegasus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Pegasus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.ssh/authorized_keys` | High
2 | File | `/Actions.php` | Medium
3 | File | `/activity/newActivityedit.php?DontCheckLogin=1&id=null&ret=mod1` | High
4 | File | `/admin#themes` | High
5 | File | `/admin-page.php` | High
6 | File | `/admin/#maintenance_sysTask/edit` | High
7 | File | `/admin/?/snippet/edit/3` | High
8 | File | `/admin/?page=establishment` | High
9 | File | `/admin/action/add_con.php` | High
10 | File | `/admin/action/new-feed.php` | High
11 | File | `/admin/add-directory.php` | High
12 | File | `/admin/add_query_account.php` | High
13 | File | `/admin/admin_running.php` | High
14 | File | `/admin/ajax.php?action=delete_application` | High
15 | File | `/admin/ajax.php?action=login` | High
16 | File | `/admin/app` | Medium
17 | File | `/admin/category.php` | High
18 | File | `/admin/cmsWebFile/doUpload` | High
19 | File | `/admin/Create_category.php` | High
20 | File | `/admin/delete-session.php` | High
21 | File | `/admin/domain_management.php?id=0&list=whitelist&remove=pligg.com` | High
22 | File | `/admin/edit-card-detail.php` | High
23 | File | `/admin/edit-class.php` | High
24 | File | `/admin/edit-equipmentform.php` | High
25 | File | `/admin/edit_room.php` | High
26 | File | `/admin/edit_student.php` | High
27 | File | `/admin/edit_user.php` | High
28 | File | `/admin/login.php` | High
29 | File | `/admin/manage-art-medium.php` | High
30 | File | `/admin/manage-users.php` | High
31 | File | `/admin/post/list` | High
32 | File | `/admin/publishnews.php` | High
33 | File | `/admin/subscriber-csv.php` | High
34 | File | `/admin/tag.php` | High
35 | File | `/admin/template/update` | High
36 | File | `/admin/unreadenq.php` | High
37 | File | `/admin/upload/upimage.html` | High
38 | File | `/admin/user-payment.php` | High
39 | File | `/admin/user.php` | High
40 | File | `/admin/user/list` | High
41 | File | `/admin/userlist.php` | High
42 | File | `/admin/userSys_deal.php?mudi=infoSet` | High
43 | File | `/admin/view-enquiry.php` | High
44 | File | `/adminapi/export/product_list` | High
45 | File | `/adminLogin.php` | High
46 | File | `/ajax.php?action=delete_position` | High
47 | File | `/api` | Low
48 | File | `/api/monitors/import` | High
49 | File | `/api/sys/login` | High
50 | File | `/app/api/controller/Store.php` | High
51 | File | `/application/index/controller/Unity.php` | High
52 | File | `/apprain/developer/addons/update/hysontable` | High
53 | File | `/apprain/developer/addons/update/rich_text_editor` | High
54 | File | `/apps/meteor/app/irc/server/servers/RFC2813/parseMessage.js` | High
55 | File | `/auth/soup-auth-digest.c` | High
56 | ... | ... | ...

There are 493 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2021/09/fakeantipegasusamnesty.html
* https://citizenlab.ca/2021/08/bahrain-hacks-activists-with-nso-group-zero-click-iphone-exploits/
* https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
* https://www.amnesty.org/en/latest/research/2021/07/forensic-methodology-report-how-to-catch-nso-groups-pegasus/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
