# Amazon AWS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Amazon AWS_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Amazon AWS:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [DE](https://vuldb.com/?country.de)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Amazon AWS or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Amazon AWS.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.58.150.54](https://vuldb.com/?ip.2.58.150.54) | mta-15054.mail.members.Y3GJIj6l6jdzv.com | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [3.87.88.196](https://vuldb.com/?ip.3.87.88.196) | ec2-3-87-88-196.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
3 | [3.92.161.20](https://vuldb.com/?ip.3.92.161.20) | ec2-3-92-161-20.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
4 | [3.120.207.231](https://vuldb.com/?ip.3.120.207.231) | ec2-3-120-207-231.eu-central-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
5 | [3.134.110.223](https://vuldb.com/?ip.3.134.110.223) | ec2-3-134-110-223.us-east-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
6 | [3.143.228.87](https://vuldb.com/?ip.3.143.228.87) | ec2-3-143-228-87.us-east-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
7 | [3.230.173.139](https://vuldb.com/?ip.3.230.173.139) | ec2-3-230-173-139.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
8 | [3.238.100.27](https://vuldb.com/?ip.3.238.100.27) | ec2-3-238-100-27.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
9 | [13.56.247.108](https://vuldb.com/?ip.13.56.247.108) | ec2-13-56-247-108.us-west-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
10 | [18.144.86.242](https://vuldb.com/?ip.18.144.86.242) | ec2-18-144-86-242.us-west-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
11 | [18.159.195.197](https://vuldb.com/?ip.18.159.195.197) | ec2-18-159-195-197.eu-central-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
12 | [18.207.250.11](https://vuldb.com/?ip.18.207.250.11) | ec2-18-207-250-11.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
13 | [20.18.34.148](https://vuldb.com/?ip.20.18.34.148) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
14 | [20.97.113.197](https://vuldb.com/?ip.20.97.113.197) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
15 | [20.163.67.84](https://vuldb.com/?ip.20.163.67.84) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Amazon AWS. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Amazon AWS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.jsp` | Low
2 | File | `//proc/kcore` | Medium
3 | File | `/?ajax-request=jnews` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/add_new_invoice.php` | High
6 | File | `/admin.php?p=/Area/index#tab=t2` | High
7 | File | `/admin/action/delete-vaccine.php` | High
8 | File | `/Admin/akun_edit.php` | High
9 | File | `/admin/apply.php` | High
10 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
11 | File | `/admin/create-package.php` | High
12 | File | `/admin/div_data/delete?divId=9` | High
13 | File | `/admin/doAdminAction.php?act=addCate` | High
14 | File | `/admin/edit-brand.php` | High
15 | File | `/admin/edit-post.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/index2.html` | High
18 | File | `/Admin/Proses_Edit_Akun.php` | High
19 | File | `/admin/robot.php` | High
20 | File | `/admin/search-invoices.php` | High
21 | File | `/admin/view_order.php` | High
22 | File | `/api/cron/settings/setJob/` | High
23 | File | `/api/objects/recipes` | High
24 | File | `/api/sys/set_passwd` | High
25 | File | `/app/index/controller/Common.php` | High
26 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
27 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
28 | File | `/applications/nexus/modules/front/store/store.php` | High
29 | File | `/backend/doc/his_doc_update-account.php` | High
30 | File | `/bitrix/admin/ldap_server_edit.php` | High
31 | File | `/boaform/wlan_basic_set.cgi` | High
32 | File | `/cgi-bin/apkg_mgr.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/cgi-bin/wlogin.cgi` | High
37 | File | `/classes/Master.php` | High
38 | File | `/classes/Master.php?f=delete_record` | High
39 | File | `/classes/Master.php?f=save_category` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/classes/Users.php?f=save` | High
42 | File | `/customnode/install` | High
43 | File | `/cwp_{SESSION_HASH}/admin/loader_ajax.php` | High
44 | File | `/dashboard/system/basics/name` | High
45 | File | `/deal/{note_id}/note` | High
46 | File | `/debug/pprof` | Medium
47 | File | `/detailed.php` | High
48 | File | `/dtale/chart-data/1` | High
49 | ... | ... | ...

There are 427 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securitylabs.datadoghq.com/articles/following-attackers-trail-in-aws-methodology-findings-in-the-wild/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
