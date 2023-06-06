# RMS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RMS](https://vuldb.com/?actor.rms). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rms](https://vuldb.com/?actor.rms)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RMS:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RMS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.133.65.53](https://vuldb.com/?ip.5.133.65.53) | - | - | High
2 | [37.58.60.5](https://vuldb.com/?ip.37.58.60.5) | hosted-by.zenex5.com | - | High
3 | [45.144.30.30](https://vuldb.com/?ip.45.144.30.30) | polzovatel.com | - | High
4 | [50.240.232.117](https://vuldb.com/?ip.50.240.232.117) | 50-240-232-117-static.hfc.comcastbusiness.net | - | High
5 | [51.83.171.223](https://vuldb.com/?ip.51.83.171.223) | hosted.by.majorcore.com | - | High
6 | [52.208.217.243](https://vuldb.com/?ip.52.208.217.243) | ec2-52-208-217-243.eu-west-1.compute.amazonaws.com | - | Medium
7 | [66.23.226.254](https://vuldb.com/?ip.66.23.226.254) | - | - | High
8 | [66.208.244.253](https://vuldb.com/?ip.66.208.244.253) | sbs.heraldtech.net | - | High
9 | [77.223.124.211](https://vuldb.com/?ip.77.223.124.211) | - | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RMS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RMS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/addusers` | High
2 | File | `/api/v11/users/sessions` | High
3 | File | `/apply.cgi` | Medium
4 | File | `/category.php` | High
5 | File | `/cgi-bin/diagnostics` | High
6 | File | `/cgi-bin/pass` | High
7 | File | `/cmf/process/<process_id>/logs` | High
8 | File | `/config.cgi?webmin` | High
9 | File | `/connectors/index.php` | High
10 | File | `/data/wps.setup.json` | High
11 | File | `/index.php` | Medium
12 | File | `/mcategory.php` | High
13 | File | `/movie.php` | Medium
14 | File | `/multi-vendor-shopping-script/product-list.php` | High
15 | File | `/news-portal-script/information.php` | High
16 | File | `/page.php` | Medium
17 | File | `/public/login.htm` | High
18 | File | `/public/plugins/` | High
19 | File | `/real-estate-script/search_property.php` | High
20 | File | `/recordings/index.php` | High
21 | File | `/searchJob.php` | High
22 | File | `/uncpath/` | Medium
23 | File | `/user/loader.php?api=1` | High
24 | File | `/var/miniupnpd.conf` | High
25 | File | `/wp-admin/options-general.php` | High
26 | File | `/wp-content/plugins/updraftplus/admin.php` | High
27 | File | `addrtoname.c` | Medium
28 | File | `admin/languages.php` | High
29 | File | `admin/src/containers/InputModalStepperProvider/index.js` | High
30 | File | `adm_program/modules/dates/dates_function.php` | High
31 | ... | ... | ...

There are 264 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
