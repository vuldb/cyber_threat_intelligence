# APT29 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT29](https://vuldb.com/?actor.apt29). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt29](https://vuldb.com/?actor.apt29)

## Campaigns

The following _campaigns_ are known and can be associated with APT29:

* Cobalt Strike
* COVID-19
* PowerDuke
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT29:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT29.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.64.163.50](https://vuldb.com/?ip.3.64.163.50) | ec2-3-64-163-50.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.45.66.134](https://vuldb.com/?ip.5.45.66.134) | - | - | High
3 | [5.199.174.164](https://vuldb.com/?ip.5.199.174.164) | - | - | High
4 | [13.248.169.48](https://vuldb.com/?ip.13.248.169.48) | a904c694c05102f30.awsglobalaccelerator.com | - | High
5 | [23.29.115.180](https://vuldb.com/?ip.23.29.115.180) | 23-29-115-180.static.hvvc.us | StellarParticle | High
6 | [23.82.128.144](https://vuldb.com/?ip.23.82.128.144) | - | StellarParticle | High
7 | [23.227.38.32](https://vuldb.com/?ip.23.227.38.32) | myshopify.com | - | High
8 | [27.102.130.115](https://vuldb.com/?ip.27.102.130.115) | - | - | High
9 | [31.7.63.141](https://vuldb.com/?ip.31.7.63.141) | game.bignamegamereviewz.com | - | High
10 | [31.31.74.79](https://vuldb.com/?ip.31.31.74.79) | - | Cobalt Strike | High
11 | [31.170.107.186](https://vuldb.com/?ip.31.170.107.186) | ohra.supplrald.com | - | High
12 | [35.205.61.67](https://vuldb.com/?ip.35.205.61.67) | 67.61.205.35.bc.googleusercontent.com | - | Medium
13 | [45.120.156.69](https://vuldb.com/?ip.45.120.156.69) | - | - | High
14 | [45.123.190.167](https://vuldb.com/?ip.45.123.190.167) | - | COVID-19 | High
15 | [45.123.190.168](https://vuldb.com/?ip.45.123.190.168) | - | - | High
16 | [45.129.229.48](https://vuldb.com/?ip.45.129.229.48) | - | COVID-19 | High
17 | [45.152.84.57](https://vuldb.com/?ip.45.152.84.57) | - | - | High
18 | [46.19.143.69](https://vuldb.com/?ip.46.19.143.69) | - | - | High
19 | [46.246.120.178](https://vuldb.com/?ip.46.246.120.178) | - | - | High
20 | [50.7.192.146](https://vuldb.com/?ip.50.7.192.146) | - | - | High
21 | [64.18.143.66](https://vuldb.com/?ip.64.18.143.66) | - | - | High
22 | [64.91.249.20](https://vuldb.com/?ip.64.91.249.20) | tiger.parklogic.com | - | High
23 | [65.15.88.243](https://vuldb.com/?ip.65.15.88.243) | adsl-065-015-088-243.sip.asm.bellsouth.net | PowerDuke | High
24 | ... | ... | ... | ...

There are 92 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT29_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT29. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/alphaware/summary.php` | High
9 | File | `/api/` | Low
10 | File | `/api/admin/store/product/list` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/stl/actions/search` | High
13 | File | `/api/sys/login` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/api/v2/cli/commands` | High
16 | File | `/attachments` | Medium
17 | File | `/bin/ate` | Medium
18 | File | `/boat/login.php` | High
19 | File | `/book-services.php` | High
20 | File | `/booking/show_bookings/` | High
21 | File | `/bsms_ci/index.php/book` | High
22 | File | `/cgi-bin` | Medium
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/changePassword` | High
25 | File | `/Content/Template/root/reverse-shell.aspx` | High
26 | File | `/context/%2e/WEB-INF/web.xml` | High
27 | File | `/dashboard/add-blog.php` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/DXR.axd` | Medium
30 | File | `/ecshop/admin/template.php` | High
31 | File | `/en/blog-comment-4` | High
32 | File | `/env` | Low
33 | File | `/etc/hosts` | Medium
34 | File | `/forum/away.php` | High
35 | File | `/group1/uploa` | High
36 | File | `/h/` | Low
37 | File | `/medicines/profile.php` | High
38 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
39 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
40 | File | `/owa/auth/logon.aspx` | High
41 | File | `/php-sms/admin/?page=user/manage_user` | High
42 | File | `/project/PROJECTNAME/reports/` | High
43 | File | `/proxy` | Low
44 | ... | ... | ...

There are 382 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog-assets.f-secure.com/wp-content/uploads/2020/03/18122307/F-Secure_Dukes_Whitepaper.pdf
* https://circleid.com/posts/20231114-apt29-goes-from-targeted-attacks-to-phishing-via-nobelium-a-dns-deep-dive
* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/Russia/Advisory-APT29-targets-COVID-19-vaccine-development.pdf
* https://unit42.paloaltonetworks.com/cloaked-ursa-online-storage-services-campaigns/
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar20-198c
* https://www.crowdstrike.com/blog/observations-from-the-stellarparticle-campaign/
* https://www.microsoft.com/security/blog/2018/12/03/analysis-of-cyberattack-on-u-s-think-tanks-non-profits-public-sector-by-unidentified-attackers/
* https://www.ncsc.gov.uk/files/Advisory-APT29-targets-COVID-19-vaccine-development-V1-1.pdf
* https://www.volexity.com/blog/2016/11/09/powerduke-post-election-spear-phishing-campaigns-targeting-think-tanks-and-ngos/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
