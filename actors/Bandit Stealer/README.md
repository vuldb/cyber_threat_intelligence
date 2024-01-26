# Bandit Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandit Stealer](https://vuldb.com/?actor.bandit_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandit_stealer](https://vuldb.com/?actor.bandit_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandit Stealer:

* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bandit Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.92.209.204](https://vuldb.com/?ip.3.92.209.204) | ec2-3-92-209-204.compute-1.amazonaws.com | - | Medium
2 | [20.102.80.176](https://vuldb.com/?ip.20.102.80.176) | - | - | High
3 | [20.150.218.195](https://vuldb.com/?ip.20.150.218.195) | - | - | High
4 | [24.199.107.85](https://vuldb.com/?ip.24.199.107.85) | - | - | High
5 | [41.216.183.23](https://vuldb.com/?ip.41.216.183.23) | - | - | High
6 | [41.216.183.94](https://vuldb.com/?ip.41.216.183.94) | - | - | High
7 | [45.42.45.10](https://vuldb.com/?ip.45.42.45.10) | web9-redirect.me | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bandit Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.vscode/cody.json` | High
2 | File | `/?r=email/api/mark&op=delFromSend` | High
3 | File | `/accounts/login` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/admin.php` | Medium
6 | File | `/admin/` | Low
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/book_add.php` | High
9 | File | `/admin/courses/view_course.php` | High
10 | File | `/admin/database/backup` | High
11 | File | `/admin/index.php?act=reset_admin_psw` | High
12 | File | `/admin/list_onlineuser.php` | High
13 | File | `/admin/sales/view_details.php` | High
14 | File | `/admin/students/view_details.php` | High
15 | File | `/admin/sys_sql_query.php` | High
16 | File | `/ajax/ajax_login.ashx` | High
17 | File | `/api/download/updateFile` | High
18 | File | `/api/email/update` | High
19 | File | `/Attachment/fromImageUrl` | High
20 | File | `/b2b-supermarket/shopping-cart` | High
21 | File | `/bin/boa` | Medium
22 | File | `/blog` | Low
23 | File | `/catalog/compare` | High
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
26 | File | `/cgi-bin/wlogin.cgi` | High
27 | File | `/classes/Master.php? f=save_medicine` | High
28 | File | `/classes/Users.php?f=save` | High
29 | File | `/clinic/disease_symptoms_view.php` | High
30 | File | `/collection/all` | High
31 | File | `/common/log/list` | High
32 | File | `/content/list.do` | High
33 | File | `/dataset/new` | Medium
34 | File | `/edit_branch.php` | High
35 | File | `/endpoint/add-user.php` | High
36 | File | `/fcgi/scrut_fcgi.fcgi` | High
37 | File | `/file` | Low
38 | File | `/forum/away.php` | High
39 | File | `/goform/SetNetControlList` | High
40 | File | `/goform/SetOnlineDevName` | High
41 | File | `/login` | Low
42 | File | `/login.php?do=login` | High
43 | File | `/log_proxy` | Medium
44 | File | `/MailAdmin_dll.htm` | High
45 | File | `/main/inc/ajax/work.ajax.php` | High
46 | File | `/me` | Low
47 | File | `/mhds/clinic/view_details.php` | High
48 | File | `/mobileredir/openApp.jsp` | High
49 | File | `/modals/class_form.php` | High
50 | File | `/modules/projects/summary.inc.php` | High
51 | ... | ... | ...

There are 439 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/41.216.183.23
* https://search.censys.io/hosts/41.216.183.94
* https://search.censys.io/hosts/45.42.45.10
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
