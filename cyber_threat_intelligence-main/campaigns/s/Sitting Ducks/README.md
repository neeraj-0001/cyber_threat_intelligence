# Sitting Ducks - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Sitting Ducks_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sitting Ducks:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 20 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Sitting Ducks or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Russian Nexus](https://vuldb.com/?actor.russian_nexus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sitting Ducks.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.136.49.35](https://vuldb.com/?ip.45.136.49.35) | - | [Russian Nexus](https://vuldb.com/?actor.russian_nexus) | High
2 | [81.19.135.241](https://vuldb.com/?ip.81.19.135.241) | undefined.hostname.localhost | [Russian Nexus](https://vuldb.com/?actor.russian_nexus) | High
3 | [178.250.243.30](https://vuldb.com/?ip.178.250.243.30) | hosted-by.majordomo.ru | [Russian Nexus](https://vuldb.com/?actor.russian_nexus) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Sitting Ducks. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Sitting Ducks. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/.pomerium` | Medium
4 | File | `/Account/login.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=bike` | High
7 | File | `/admin/?page=musics/manage_music` | High
8 | File | `/admin/ajax.php?action=delete_user` | High
9 | File | `/Admin/changepassword.php` | High
10 | File | `/admin/emp-profile-avatar.php` | High
11 | File | `/admin/general-setting` | High
12 | File | `/admin/inquiries/view_inquiry.php` | High
13 | File | `/admin/order.php` | High
14 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
15 | File | `/admin/service` | High
16 | File | `/adminapi/system/crud` | High
17 | File | `/adminapi/system/file/openfile` | High
18 | File | `/admin_route/dec_service_credits.php` | High
19 | File | `/api/v1/custom_component` | High
20 | File | `/api/v4/teams//channels/deleted` | High
21 | File | `/api/wechat/app_auth` | High
22 | File | `/b2b-supermarket/shopping-cart` | High
23 | File | `/cancel.php` | Medium
24 | File | `/category.php` | High
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/nas_sharing.cgi` | High
27 | File | `/change-language/de_DE` | High
28 | File | `/classes/Master.php` | High
29 | File | `/classes/Master.php?f=delete_category` | High
30 | File | `/classes/Master.php?f=save_medicine` | High
31 | File | `/classes/SystemSettings.php?f=update_settings` | High
32 | File | `/classes/Users.php?f=delete` | High
33 | File | `/control/register_case.php` | High
34 | File | `/debug/pprof` | Medium
35 | File | `/devinfo` | Medium
36 | File | `/dist/index.js` | High
37 | File | `/download` | Medium
38 | File | `/downloadFile.php` | High
39 | File | `/DXR.axd` | Medium
40 | File | `/endpoint/add-folder.php` | High
41 | File | `/etc/shadow` | Medium
42 | File | `/file_manager/login.php` | High
43 | File | `/film-rating.php` | High
44 | File | `/foms/routers/place-order.php` | High
45 | File | `/forum/away.php` | High
46 | File | `/goform/formSysCmd` | High
47 | File | `/goform/SetIpMacBind` | High
48 | File | `/goform/WifiExtraSet` | High
49 | File | `/guestbook` | Medium
50 | File | `/hosts/firewall/ip` | High
51 | File | `/index.jsp#settings` | High
52 | File | `/index.php` | Medium
53 | File | `/index.php/ccm/system/file/upload` | High
54 | File | `/js/player/dmplayer/dmku/?ac=edit` | High
55 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
56 | ... | ... | ...

There are 491 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.infoblox.com/threat-intelligence/who-knew-domain-hijacking-is-so-easy/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
