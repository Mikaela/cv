---
title: English
excerpt:
  "Everything about everything version of my CV, the tailored version doesn't
  exist in English yet."
layout: default
versionString: 2024.24.0
date: 2024-06-12T22:03:00+03:00
lang: en
locale: en_FI
permalink: /en/index.html
redirect_from: /en/html
robots: nofollow
---

# Aminda Suomalainen

<img src="https://media.githubusercontent.com/media/Mikaela/mikaela.github.io/lfs-media/avatar/250.jpeg" alt="photo of me"/>

<span id="bio">_…is an open-source enthustiastic IT generalist, currently
volunteering as a sysadmin in the Pirate Party of Finland._</span>

<p style="text-align: center;">&#x1F3F3;&#xFE0F;&#x200D;&#x26A7;&#xFE0F;&#x200D;&#65038;&#x1F3F3;&#xFE0F;&#x200D;&#x1F308;</p>

<ul class="linklist">
  <li>Helsinki, Finland</li>
  <li><a href="https://aminda.eu">Aminda.eu</a> <a href="https://keyoxide.org/aspe:keyoxide.org:LGWNUB7QG4M326FXXBH5Z6PLVY">Keyoxide</a>  <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}">LinkedIn</a></li>
  <li><a href="https://github.com/{{ site.github_username }}">GitHub</a> <a href="https://gitlab.com/Mikaela">GitLab.com</a> <a href="https://www.openhub.net/accounts/Mikaela">OpenHub</a></li>
  <li><a href="mailto:{{ site.email }}">Email</a></li>
</ul>

<p style="text-align: center;">&#x1F3F3;&#xFE0F;&#x200D;&#x1F308;&#x1F3F3;&#xFE0F;&#x200D;&#x26A7;&#xFE0F;&#x200D;&#65038;</p>

## Table of Contents

<!-- editorconfig-checker-disable -->
<!-- prettier-ignore-start -->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Volunteering, positions of trust](#volunteering-positions-of-trust)
- [IT Skills](#it-skills)
- [Language skills](#language-skills)
- [Work Experience](#work-experience)
- [Education](#education)
- [Courses and Additional Training](#courses-and-additional-training)
- [Hobbies](#hobbies)
- [Societal and Political Activity](#societal-and-political-activity)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!-- prettier-ignore-end -->
<!-- editorconfig-checker-enable -->

## Volunteering, positions of trust

- 10.2015-- _[Pirate Party of Finland](https://piraattipuolue.fi/en/)_
  - **Web Services and Instant Messaging Maintenance**
    <!-- The instant messaging team was officially founded on 27.03.2018, the web services survey on 06.08.2019, and the IT team has been in place since 11.12.2019 -->
  - _Reference: [Utu Hopiavuori](https://www.hopiavuori.net/)_
  - Unified the management of the Pirate Party's IRC channels under the
    `Atheme` `GroupServ`, centralizing access control instead of using
    individual lists for dozens of different channels.
  - Unified messaging of the party's communication channels regardless of
    where messages are originally sent from. Initially I only did `IRC` to
    `Slack` using `Slack`'s `IRC-gateway` while it was supported. I was also
    `Slack` workspace admin.
  - Set up `TeleIRC` and `Discord-IRC` to bridge communication between `IRC`,
    `Discord`, and `Telegram` for the Pirate Party.
  - Assist the PirateIRC oper team in maintaining the network, communicating
    with operators from the Pirate Parties of Australia and Sweden, and
    assisting our users (e.g., Pirate Party of the Netherlands, Pirate Party
    of Massachusetts).
  - Acted as the contact person for PirateIRC with the Matrix bridge
    maintained by the Indian Pirates, assisting with the PirateIRC end
    configurations to set up the bridge.
  - Transitioned from `TeleIRC` and `Discord-IRC` to `Matterbridge` as a
    better solution, removing `IRC` as an intermediary.
  - Maintain a `Limnoria` instance that tracks `certificate transparency`
    feeds, monitors `Git-webhooks`, and fetches titles of linked sites to aid
    users of various `IRC` and `Matrix` clients that do not fetch link titles
    for users.
  - Set up role-based access control on the Pirate Party's `Discord` server to
    ensure that not all channels are visible to everyone, providing a more
    peaceful workspace for those channels which need it.
  - Assist in the maintenance of the Pirate Party's web services, including
    updating (Debian and Ubuntu) operating systems, writing `systemd` units,
    and updating software.
  - Assist with email forwarding and mailing list creation and updates using
    `CPanel`.
  - Assist in maintaining the Pirate Party's `Nextcloud` instance, creating
    user accounts for party activists as needed.
  - Created `Matrix` rooms and spaces for the Pirate Party to allow
    participation in party instant messaging with (similar as Discord)
    restricted access to rooms requiring working peace.
  - Communicated with the Austrian Pirate Party, as the Finnish Pirate Party
    used their `Matrix` server for `matterbridge`, and I still maintain a
    relay on international Pirate Party discussion channel (Global Pirates) on
    the Austrian `Mattermost` server, `Matrix`, `Telegram`, `Discord`, and
    `PirateIRC`.
  - Assisted PirateIRC in transitioning from four `Charybdis` `IRC` servers
    and `Atheme IRC` services to a more modern `Ergo IRCd` solution that
    integrates both components.
  - Actively communicate with the upstream developers of the software used by
    the party, especially `Charybdis`, `Atheme`, `Ergo`, `Limnoria`, and
    <del>`Gitea`</del> `Forgejo`.
  - Translated the `TLG_JoinCaptchaBot` we use into Finnish.
  - Reolved `Nextcloud` server crashes caused by low memory with out of the
    container thinking by improving the `systemd.unit` and implementing
    `earlyoom`, considering additional memory to be unnecessary.
- 19.03.2020 - 04.01.2022
  _[Federated Networks Association ry (Feneas)](https://feneas.org/)_
  - **Committee Member**
  - Even after the association's dissolution, I assist in maintaining Feneas
    Matrix rooms and engage with the community.
  - Occasionally helped update the `Matrix` server or the `Element` client by
    opening `merge-requests` for `GitLab`'s `Ansible-playbooks`.
  - Act as the Feneas group contact for [LiberaChat] IRC network,
    communicating on both sides if there are issues with [LiberaChat],
    registering Feneas namespace channels on their network, serving as channel
    operator, and requesting `vhosts` for our members to show their connection
    to the association.
- 02.04.2019 - 19.04.2020, 07.10.2021-23.11.2021
  _[Privacy Guides](https://privacyguides.org/)_
  - **Team Member**
  - Participated in discussions on `GitHub`, in the `issues` and `discussions`
    sections, and labeled them to facilitate sorting and finding them in the
    future.
  - Reviewed `pull requests`.
  - Particularly involved in creating the encrypted DNS section, gathering
    information on solutions (`DNS over HTTPS`, `DNS over TLS`, `DNSCrypt`)
    and following their developments with interest.
  - Conducted research on suggested applications and services, assessing
    whether they met the project's criteria.

[LiberaChat]: https://libera.chat/

## IT Skills

- Linux administration since 2008
  - Arch Linux, Debian, (Ubuntu, ) Fedora, SailfishOS
  - systemd (`system/user unit`s (services, timers), networkd, resolved,
    timesyncd…)
  - OpenSSHd, CUPS print server, UFW and firewalld firewalls
  - Chrony time server
- Git
  - At least a decade of experience in all sorts of git magic, including
    managing bare repositories without pretty user interfaces, moving remotes,
    setting upstreams, fetching pull request remotes directly from terminal
    (`git config --add remote.origin.fetch '+refs/pull/*/head:refs/remotes/origin/pr/*'`),
    etc.
    - One of the most active GitHub users in Finland in
      [2013-2014](https://gist.github.com/jaukia/b23b15d2859e6cf5386b),
      [2014-2015](https://gist.github.com/jaukia/1d41a0045ab8e9f411ff),
      [2015-2016](https://gist.github.com/nikcorg/4ebdda1952976b8cc0af#most-active-github-users-gitiotop),
      …and
      [now](https://github.com/gayanvoice/top-github-users/blob/main/markdown/public_contributions/finland.md).
  - Follows best practices _in her opinion_ including `.gitattributes`,
    `pre-commit`, `.editorconfig`, which can be found in most of my
    repositories.
  - GitHub/GitLab/Gitea/Forĝejo organizations, issue tracker, labels
  - GitLab/Gitea/Forĝejo repository mirroring
  - GitHub/GitLab pages
- DNS
  - DNSSEC, zone management, Unbound
  - DNS-over-HTTPS (iOS 14 and Windows 11 clients) and DNS-over-TLS (Android,
    systemd, Unbound clients)
- IPv6
  - SixXS, Tunnelbroker, radvd, radvdump, Yggdrasil
- Windows Server
  - Active Directory, Group Policy…
- IRC
  - Charybdis+Atheme, Ergo services and servers
  - KiwiIRC, Gamja browser-based clients
- WordPress troubleshooting
- `bash` scripting and `Python` basics, see
  [Mikaela/Scripts](https://gitea.blesmrt.net/mikaela/scripts)
- MySQL-basics
- $\LaTeX$ -basics, see.
  [LaTeX directory of Mikaela/gist](https://gitea.blesmrt.net/mikaela/gist/src/branch/master/LaTeX)
- Centralized management of web browsers through policies
  - I have written two blog posts on the subject,
    [part one on enforcing HTTPS-only mode](https://aminda.eu/blog/english/2024/05/17/https-everywhere.html)
    and
    [part two on installing and managing Privacy Badger and uBlock Origin](https://aminda.eu/blog/english/2024/05/22/policy-contentblocker.html).

## Language skills

- Finnish `🌟🌟🌟🌟🌟🌟` (native)
- English `⭐⭐⭐⭐⭐⚫` (CEFRL: C1)
- Esperanto `⭐⚫⚫⚫⚫⚫` (CEFRL: A1)

## Work Experience

- 13.09.2021-28.11.2021 _Digitalents Academy_
  - **[On the job training]**
  - Created a GitHub Pages-based CV (cv.aminda.eu).
  - Got acquainted with the basics of `Python` and `JavaScript`.
  - Briefly explored the `Flask` web framework.
  - Assisted other trainees with using `git`.
- 03.2020 - 09.2020 _[Unicus Finland](https://unicus.com/fi/)_
  - **[On the job training]**
  - Prepared for the _ISTQB Foundation Level_ exam.
  - Briefly explored programming with `Python 3`, `Ruby`, and `Go`.
  - Familiarized myself with `Firefox` Developer Tools, especially for
    accessibility testing.
  - Learned about the _Web Content Accessibility Guidelines_ and accessibility
    testing, and understood how accessibility benefits me personally.
- 28.10.2019 - 19.12.2019 _Robuntu Osk_
  - **[On the job training]**
  - Performed various tasks in support of the cooperative's operations.
  - Assisted in marketing the cooperative's services by exploring mass
    communication with `Thunderbird` extensions and `Facebook Marketplace`.

[On the job training]:
  https://toimistot.te-palvelut.fi/en/work-try-out-practices-and-provisions

## Education

- 14.03.2024 - 11.10.2024 _Taitotalo (Helsinki)_
  - **Partial Degree in Information and Communication Technology: Maintenance
    of Cybersecurity**
- 08.08.2012 - 29.05.2015 _Etelä-Kymenlaakson Vocational College (Hamina)_
  - **Vocational Qualification in Information and Communication Technology:
    User Support Training Program**

## Courses and Additional Training

<!-- * 25.05.2015 - TIEKE: Computer User's A Certificate -->

- 25.05.2015 - TIEKE: Computer User's AB Certificate
- 16.09.2014 - CCNA Discovery: Working at a Small-to-Medium Business or ISP
- 28.04.2014 - CCNA Discovery: Networking for Home and Small Businesses

## Hobbies

- Cybersecurity: I constantly follow industry news and online communities
  (IRC, Matrix).
- "Software Testing": I often find issues or missing features in the software
  I use and, if a clear reporting channel exists, I report them.
  - Requires a user account to view the list of my
    [issues in other people's GitHub repositories](https://github.com/issues?q=is%3Aissue+author%3AMikaela+-user%3AMikaela),
    [GitLab.com](https://gitlab.com/dashboard/issues/?scope=all&state=all&author_username=Mikaela).
- Political Activity: I am active in the Pirate Party and assist with
  campaigns in Helsinki, including discussing with people, distributing
  flyers, making coffee, or helping to set up slideshow presentations at the
  campaign booth.
- Languages
- 11.07.2014-- Maintaining my personal websites Mikaela.info, 114077943.xyz,
  and Aminda.eu, and writing a blog
  - **Webmaster**
  - I registered my domains with `Gandi` and have since used services from
    `Cloudflare`, `EasyDNS`, and `PorkBun`, especially after Gandi was sold.
    Currently, all three of my domains are managed by Cloudflare (though only
    `mikaela.info` is registered through them).
  - I maintain multiple sites on `GitHub Pages`. I originally wrote my main
    site (aminda.eu) in `HTML+CSS`, later transitioning to the `Jekyll` `CMS`,
    which generates static pages. However, it doesn't do everything for me, so
    I occasionally work with `HTML` and `CSS`, especially when I need more
    advanced tools than markdown.
  - I write blog posts on various topics, including my life and more technical
    subjects like `IRC` and `Matrix` protocols, as well as previously
    mentioned browser policies.
  - I often ponder what improvements I could make, what I could blog about,
    and frequently outline what I want to write in the site's `issue tracker`.
- Reading
- Localization
  - I maintain the Finnish translations for `FluffyChat` (since 19.11.2021)
    and `Nheko` (since 04.04.2022) `Matrix` clients using the `Weblate`
    translation tool. Outside of Matrix, I have translated
    `TLG_JoinCaptchaBot` (since 11.04.2022), which combats spam in Telegram
    groups.
  - I discuss the meaning of original messages with other translators, how
    they have been translated into other languages, or what special meanings
    they may have.
  - I follow discussions and feedback on translations in Matrix Finland.
  - I also support users of these applications in their respective support
    channels.

## Societal and Political Activity

- Pirate Party Council
  - Deputy Member 26.09.2020-25.02.2021, Full Member 25.02.2021-18.06.2022
    <!-- The same term from 26.09.2020 onwards, two full members left, hence the "update" -->
- Young Pirates Finland Board
  - Member 2017-06.06.2018, Deputy Member 2018-2019-01-11,
    19.01.2020-18.12.2021
- Pirate Party Helsinki District Association, Deputy Board Member
  - 2017-2018, 2019-2021, 13.07.2022--
- Finnish Association for Autism, Deputy Board Member
  - 14.04.2018 - 12.04.2019
- Pirate Party Municipal Election Candidate in Helsinki 2017

<!-- ## Recommenders

To be added when they exist

-->

---

| Version                  | Date            |
| ------------------------ | --------------- |
| {{ page.versionString }} | {{ page.date }} |
