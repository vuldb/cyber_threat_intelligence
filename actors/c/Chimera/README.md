# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/wirelessConnect` | High
2 | File | `/Admin/add-admin.php` | High
3 | File | `/admin/admin_user.php` | High
4 | File | `/admin/api/theme-edit/` | High
5 | File | `/admin/assign/assign.php` | High
6 | File | `/admin/blood/update/B-.php` | High
7 | File | `/admin/case-status` | High
8 | File | `/admin/edit_area.php` | High
9 | File | `/admin/foldernotice/list` | High
10 | File | `/admin/getallarticleinfo` | High
11 | File | `/admin/info_deal.php` | High
12 | File | `/admin/makehtml_freelist_action.php` | High
13 | File | `/admin/overtime_add.php` | High
14 | File | `/admin/reports/index.php` | High
15 | File | `/admin/settings.php` | High
16 | File | `/admin/sign/out` | High
17 | File | `/admin/student.php` | High
18 | File | `/admin/user/user-move-run.php` | High
19 | File | `/admin/vacancy/index.php` | High
20 | File | `/admin_system/api.php` | High
21 | File | `/api/contents` | High
22 | File | `/app/api/controller/default/Sqlite.php` | High
23 | File | `/application/controller/Pengeluaran.php` | High
24 | File | `/application/index/controller/Screen.php` | High
25 | File | `/appLms/ajax.server.php` | High
26 | File | `/backend/register.php` | High
27 | File | `/base/SysEveMenuAuthPointMapper.xml` | High
28 | File | `/boaform/device_reset.cgi` | High
29 | File | `/book-services.php` | High
30 | File | `/busca` | Low
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
33 | File | `/cgi-bin/koha/catalogue/search.pl` | High
34 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/cgi-bin/wapopen` | High
37 | File | `/claire_blake` | High
38 | File | `/com/esafenet/servlet/client/CDGRenewApplicationService.java` | High
39 | File | `/config,admin.jsp` | High
40 | File | `/core/admin/auto-modules/forms/process.php` | High
41 | File | `/cwms/admin/?page=articles/view_article/` | High
42 | File | `/deleteanimal.php` | High
43 | File | `/department_viewmore.php` | High
44 | File | `/ecommerce/admin/settings/setDiscount.php` | High
45 | File | `/editbrand.php` | High
46 | File | `/editorder.php` | High
47 | File | `/endpoint/add-user.php` | High
48 | File | `/etc/shadow.sample` | High
49 | File | `/file-manager/rename.php` | High
50 | File | `/file-manager/upload.php` | High
51 | File | `/file?action=download&file` | High
52 | File | `/filemanager/php/connector.php` | High
53 | File | `/goform/formSetMACFilter` | High
54 | File | `/goform/formSetWizardSelectMode` | High
55 | File | `/goform/formWifiBasicSet` | High
56 | File | `/goform/fromSetIpMacBind` | High
57 | File | `/goform/QuickIndex` | High
58 | File | `/goform/saveParentControlInfo` | High
59 | ... | ... | ...

There are 512 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
