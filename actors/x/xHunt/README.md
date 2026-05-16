# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [PW](https://vuldb.com/?country.pw)
* [DE](https://vuldb.com/?country.de)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/actuator` | Medium
2 | File | `/addProduct.php` | High
3 | File | `/admin/` | Low
4 | File | `/admin/activity.php` | High
5 | File | `/admin/add-subadmins.php` | High
6 | File | `/Admin/additems.php` | High
7 | File | `/admin/add_area.php` | High
8 | File | `/admin/add_payroll.php` | High
9 | File | `/Admin/delete-fee.php` | High
10 | File | `/admin/delete_activity.php` | High
11 | File | `/admin/editsite.php` | High
12 | File | `/admin/edit_activity_query.php` | High
13 | File | `/admin/expenses.php` | High
14 | File | `/admin/login.php` | High
15 | File | `/admin/modules/lesson/index.php` | High
16 | File | `/admin/quesadd.php` | High
17 | File | `/admin/system/variableList.do` | High
18 | File | `/admin/system/variableSave.do` | High
19 | File | `/admin/user-search.php` | High
20 | File | `/Administrator/PHP/AdminAddUser.php` | High
21 | File | `/Administrator/PHP/AdminViewSongs.php` | High
22 | File | `/admin_delete.php` | High
23 | File | `/api/jobs` | Medium
24 | File | `/app/checkout/delete.php` | High
25 | File | `/app/checkout/update.php` | High
26 | File | `/app/complaint.php` | High
27 | File | `/app/Jobs/Util/Import.php` | High
28 | File | `/app/register.php?action=reg` | High
29 | File | `/base/safe_setting/` | High
30 | File | `/blog/bContent/save` | High
31 | File | `/boafrm/formParentControl` | High
32 | File | `/boafrm/formWsc` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/imode_alldata.php` | High
35 | File | `/contact_us.php` | High
36 | File | `/controller/api/hotelList.php` | High
37 | File | `/controller/api/Room.php` | High
38 | File | `/customer_details.php` | High
39 | File | `/data/pbootcms.db` | High
40 | File | `/dayrui/Fcms/Init.php` | High
41 | File | `/dev-api/common/upload` | High
42 | File | `/dws/api/` | Medium
43 | File | `/edtlbls.php` | Medium
44 | File | `/enroll.php` | Medium
45 | File | `/form137.php` | Medium
46 | File | `/fort/login/edit_pwd_mall` | High
47 | File | `/fort/trust/version/common/common.jsp` | High
48 | ... | ... | ...

There are 417 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
