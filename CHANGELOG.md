# Change Log

## [1.2.5](https://github.com/tubemogul/puppet-redis/tree/1.2.5) (2017-04-13)
[Full Changelog](https://github.com/tubemogul/puppet-redis/compare/1.2.4...1.2.5)

**Fixed issues:**

- Parameters not valid for older Redis in config [\#111](https://github.com/arioch/puppet-redis/issues/111)
- Ownership problem with Ubuntu redis-server [\#150](https://github.com/arioch/puppet-redis/issues/150)

## [1.2.4](https://github.com/arioch/puppet-redis/tree/1.2.4) (2016-12-05)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.2.3...1.2.4)

**Closed issues:**

- Wrong redis.conf after c45049986a7fcb1c9a0591de123c6bf97c761355 [\#142](https://github.com/arioch/puppet-redis/issues/142)
- Speed up Travis [\#118](https://github.com/arioch/puppet-redis/issues/118)
- Forge Release [\#110](https://github.com/arioch/puppet-redis/issues/110)
- git submodule issue? [\#104](https://github.com/arioch/puppet-redis/issues/104)
- powerstack.org - No longer hosted [\#103](https://github.com/arioch/puppet-redis/issues/103)
- Add support to custom repos with RedHat [\#91](https://github.com/arioch/puppet-redis/issues/91)
- redis.conf under /etc/redis.conf [\#81](https://github.com/arioch/puppet-redis/issues/81)
- Add socket option [\#79](https://github.com/arioch/puppet-redis/issues/79)
- Can't run multiple instances [\#78](https://github.com/arioch/puppet-redis/issues/78)
- preinstall.pp fails on CEntOS 6.5 and Puppet Enterprise 2.7. [\#72](https://github.com/arioch/puppet-redis/issues/72)
- How do I change from powerstack.org repo if I need to? Should I just edit manifests/preinstall.pp?  [\#68](https://github.com/arioch/puppet-redis/issues/68)
- puppet-redis || every time when puppet runs, the service restarts [\#59](https://github.com/arioch/puppet-redis/issues/59)
- 'manage\_repo =\> true' causes run to fail because add-apt-repository command isn't available [\#49](https://github.com/arioch/puppet-redis/issues/49)

**Merged pull requests:**

- For folks that do not use redis to cache to disk [\#144](https://github.com/arioch/puppet-redis/pull/144) ([petems](https://github.com/petems))
- Revert "Changes templates to use scope" [\#143](https://github.com/arioch/puppet-redis/pull/143) ([petems](https://github.com/petems))
- Update sentinel.pp [\#141](https://github.com/arioch/puppet-redis/pull/141) ([denis-sorokin](https://github.com/denis-sorokin))
- Manage workdir and permissions [\#138](https://github.com/arioch/puppet-redis/pull/138) ([petems](https://github.com/petems))
- Adds minimum versions parameters [\#137](https://github.com/arioch/puppet-redis/pull/137) ([petems](https://github.com/petems))
- Adds redis-server version fact [\#136](https://github.com/arioch/puppet-redis/pull/136) ([petems](https://github.com/petems))
- adding /var/run/redis for Debian based hosts [\#135](https://github.com/arioch/puppet-redis/pull/135) ([petems](https://github.com/petems))
- Refactor unit tests [\#134](https://github.com/arioch/puppet-redis/pull/134) ([petems](https://github.com/petems))
- Update acceptance tests [\#133](https://github.com/arioch/puppet-redis/pull/133) ([petems](https://github.com/petems))
- Move Repo for RHEL systems to EPEL [\#127](https://github.com/arioch/puppet-redis/pull/127) ([petems](https://github.com/petems))
- Fix beaker [\#126](https://github.com/arioch/puppet-redis/pull/126) ([petems](https://github.com/petems))
- Speed up Travis even more [\#125](https://github.com/arioch/puppet-redis/pull/125) ([petems](https://github.com/petems))
- Add fast finish to Travis [\#124](https://github.com/arioch/puppet-redis/pull/124) ([petems](https://github.com/petems))
- Changes package installation [\#123](https://github.com/arioch/puppet-redis/pull/123) ([petems](https://github.com/petems))
- Fix Beaker settings [\#122](https://github.com/arioch/puppet-redis/pull/122) ([petems](https://github.com/petems))
- Fixes gpg key for DotDeb [\#121](https://github.com/arioch/puppet-redis/pull/121) ([petems](https://github.com/petems))
- Sent bind address rebase [\#120](https://github.com/arioch/puppet-redis/pull/120) ([petems](https://github.com/petems))
- Changes templates to use scope [\#119](https://github.com/arioch/puppet-redis/pull/119) ([petems](https://github.com/petems))
- Add save interval squash [\#117](https://github.com/arioch/puppet-redis/pull/117) ([petems](https://github.com/petems))
- FreeBSD fixes [\#116](https://github.com/arioch/puppet-redis/pull/116) ([petems](https://github.com/petems))
- Consolidate travis and testing [\#115](https://github.com/arioch/puppet-redis/pull/115) ([petems](https://github.com/petems))
- Fix specs [\#114](https://github.com/arioch/puppet-redis/pull/114) ([Phil-Friderici](https://github.com/Phil-Friderici))
- Changed default service\_hasstatus variable from false to true for Debian params. [\#106](https://github.com/arioch/puppet-redis/pull/106) ([mlipiec](https://github.com/mlipiec))
- Remove single quotes around variable [\#101](https://github.com/arioch/puppet-redis/pull/101) ([rorybrowne](https://github.com/rorybrowne))

## [1.2.3](https://github.com/arioch/puppet-redis/tree/1.2.3) (2016-09-19)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.2.2...1.2.3)

**Closed issues:**

- Could not find declared class redis [\#96](https://github.com/arioch/puppet-redis/issues/96)

**Merged pull requests:**

- Adds spec for unixsocket and perms [\#99](https://github.com/arioch/puppet-redis/pull/99) ([petems](https://github.com/petems))
- Added the ability to configure Unix socket binding [\#97](https://github.com/arioch/puppet-redis/pull/97) ([gcelestine](https://github.com/gcelestine))
- Lint and English cleanup in the redis.conf [\#93](https://github.com/arioch/puppet-redis/pull/93) ([ryayon](https://github.com/ryayon))
- Added more configuration options to redis.conf [\#90](https://github.com/arioch/puppet-redis/pull/90) ([hanej](https://github.com/hanej))
- Make notification of service optional [\#89](https://github.com/arioch/puppet-redis/pull/89) ([michaeltchapman](https://github.com/michaeltchapman))

## [1.2.2](https://github.com/arioch/puppet-redis/tree/1.2.2) (2016-03-17)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.2.1...1.2.2)

**Closed issues:**

- tcp-keepalive not supported in EPEL redis [\#87](https://github.com/arioch/puppet-redis/issues/87)
- Error 400 on SERVER: Puppet::Parser::AST::Resource failed with error ArgumentError: Invalid resource type redis [\#86](https://github.com/arioch/puppet-redis/issues/86)
- Potential bug: `64min` should read `64mb` [\#73](https://github.com/arioch/puppet-redis/issues/73)
- Typo on sentinel.pp on if defined [\#69](https://github.com/arioch/puppet-redis/issues/69)
- Does't configure EPEL repository on CentOS 7 [\#61](https://github.com/arioch/puppet-redis/issues/61)

## [1.2.1](https://github.com/arioch/puppet-redis/tree/1.2.1) (2015-12-09)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.2.0...1.2.1)

**Merged pull requests:**

- Fix puppet-redis for Redis \< 3 [\#77](https://github.com/arioch/puppet-redis/pull/77) ([EmilienM](https://github.com/EmilienM))

## [1.2.0](https://github.com/arioch/puppet-redis/tree/1.2.0) (2015-12-03)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.1.3...1.2.0)

**Closed issues:**

- $daemonize is defaulted to 'false' on Redhat OS, which causes service command to hang [\#64](https://github.com/arioch/puppet-redis/issues/64)
- Redis service start fail on Debian stable \(Wheezy 7.0\) [\#52](https://github.com/arioch/puppet-redis/issues/52)

**Merged pull requests:**

- Redis Cluster 3.0 Feature [\#71](https://github.com/arioch/puppet-redis/pull/71) ([claudio-walser](https://github.com/claudio-walser))
- Fix Support for EL7 and Puppet 4 [\#66](https://github.com/arioch/puppet-redis/pull/66) ([trlinkin](https://github.com/trlinkin))
- Add a option to override the service provider [\#63](https://github.com/arioch/puppet-redis/pull/63) ([nerzhul](https://github.com/nerzhul))
- add support for hz option [\#50](https://github.com/arioch/puppet-redis/pull/50) ([nerzhul](https://github.com/nerzhul))

## [1.1.3](https://github.com/arioch/puppet-redis/tree/1.1.3) (2015-08-19)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.1.2...1.1.3)

**Closed issues:**

- Unable to bring in as a dependency [\#47](https://github.com/arioch/puppet-redis/issues/47)

**Merged pull requests:**

- Bump puppetlabs-stdlib version spec [\#48](https://github.com/arioch/puppet-redis/pull/48) ([gblair](https://github.com/gblair))

## [1.1.2](https://github.com/arioch/puppet-redis/tree/1.1.2) (2015-08-06)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.1.1...1.1.2)

**Closed issues:**

- Error on CentOS 7 when manage\_repo: true [\#44](https://github.com/arioch/puppet-redis/issues/44)

## [1.1.1](https://github.com/arioch/puppet-redis/tree/1.1.1) (2015-08-04)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.1.0...1.1.1)

**Closed issues:**

- Commit edd7cb55931fe0336bfee475c738ac4b91308f98 seems to be pasting undef params into redis.conf [\#41](https://github.com/arioch/puppet-redis/issues/41)

**Merged pull requests:**

- Save db to disk [\#46](https://github.com/arioch/puppet-redis/pull/46) ([adrian-balcan-ygt](https://github.com/adrian-balcan-ygt))
- Use puppetlabs\_spec\_helper for testing [\#45](https://github.com/arioch/puppet-redis/pull/45) ([jlyheden](https://github.com/jlyheden))
- copy variables used in template to local scope [\#42](https://github.com/arioch/puppet-redis/pull/42) ([eoly](https://github.com/eoly))

## [1.1.0](https://github.com/arioch/puppet-redis/tree/1.1.0) (2015-06-22)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.7...1.1.0)

**Merged pull requests:**

- access out-of-scope variables via the scope.lookupvar method [\#40](https://github.com/arioch/puppet-redis/pull/40) ([eoly](https://github.com/eoly))

## [1.0.7](https://github.com/arioch/puppet-redis/tree/1.0.7) (2015-06-02)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.6...1.0.7)

**Fixed bugs:**

- Sentinel init/upstart file doesn't exist [\#18](https://github.com/arioch/puppet-redis/issues/18)

**Closed issues:**

- Default config\_owner of redis [\#39](https://github.com/arioch/puppet-redis/issues/39)
- Duplicate decleration Package\[redis\] when both include redis and redis::sentinel [\#36](https://github.com/arioch/puppet-redis/issues/36)
- Does not work with Debian 7.8 with redis version 2.4.14-1 [\#24](https://github.com/arioch/puppet-redis/issues/24)

**Merged pull requests:**

- Fixed duplicate declaration of package [\#38](https://github.com/arioch/puppet-redis/pull/38) ([raiblue](https://github.com/raiblue))
- fix issue with params.pp with strict\_variables enabled [\#35](https://github.com/arioch/puppet-redis/pull/35) ([eoly](https://github.com/eoly))
- Enable to not manage the Redis service [\#34](https://github.com/arioch/puppet-redis/pull/34) ([Spredzy](https://github.com/Spredzy))
- Suse conf file fix [\#33](https://github.com/arioch/puppet-redis/pull/33) ([christofhaerens](https://github.com/christofhaerens))
- added Suse osfamily [\#32](https://github.com/arioch/puppet-redis/pull/32) ([christofhaerens](https://github.com/christofhaerens))

## [1.0.6](https://github.com/arioch/puppet-redis/tree/1.0.6) (2015-05-05)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.5...1.0.6)

## [1.0.5](https://github.com/arioch/puppet-redis/tree/1.0.5) (2015-03-30)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.4...1.0.5)

**Merged pull requests:**

- adding anchors to make the ensure\_resource behaive [\#30](https://github.com/arioch/puppet-redis/pull/30) ([shawn-sterling](https://github.com/shawn-sterling))
- Sentinel auth pass [\#29](https://github.com/arioch/puppet-redis/pull/29) ([Vincent--](https://github.com/Vincent--))
- More specific include and class chaining. [\#27](https://github.com/arioch/puppet-redis/pull/27) ([systemsathomesdotcom](https://github.com/systemsathomesdotcom))
- Support notification script [\#26](https://github.com/arioch/puppet-redis/pull/26) ([Spredzy](https://github.com/Spredzy))
- Add basic FreeBSD support [\#25](https://github.com/arioch/puppet-redis/pull/25) ([arioch](https://github.com/arioch))

## [1.0.4](https://github.com/arioch/puppet-redis/tree/1.0.4) (2015-01-19)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.3...1.0.4)

**Merged pull requests:**

- Add an initscript for sentinel on apt-based systems [\#23](https://github.com/arioch/puppet-redis/pull/23) ([cdent](https://github.com/cdent))
- fix trailing comma in metadata.json [\#22](https://github.com/arioch/puppet-redis/pull/22) ([fivetanley](https://github.com/fivetanley))
- metadata: add stdlib as a requirement [\#21](https://github.com/arioch/puppet-redis/pull/21) ([EmilienM](https://github.com/EmilienM))
- Avoid resource dependency when having both Redis Server & Sentinel [\#20](https://github.com/arioch/puppet-redis/pull/20) ([EmilienM](https://github.com/EmilienM))
- Make config file owner dependency on redis package explicit [\#17](https://github.com/arioch/puppet-redis/pull/17) ([cdent](https://github.com/cdent))
- Make sentinel maninfest ensure the redis package [\#16](https://github.com/arioch/puppet-redis/pull/16) ([cdent](https://github.com/cdent))
- Ensure the permissions of a new redis-sentinel.conf [\#15](https://github.com/arioch/puppet-redis/pull/15) ([cdent](https://github.com/cdent))

## [1.0.3](https://github.com/arioch/puppet-redis/tree/1.0.3) (2015-01-05)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.2...1.0.3)

**Implemented enhancements:**

- Feature Request: support for redis-sentinel [\#13](https://github.com/arioch/puppet-redis/issues/13)

## [1.0.2](https://github.com/arioch/puppet-redis/tree/1.0.2) (2014-12-17)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.1...1.0.2)

**Merged pull requests:**

- Sentinel support [\#14](https://github.com/arioch/puppet-redis/pull/14) ([cdent](https://github.com/cdent))

## [1.0.1](https://github.com/arioch/puppet-redis/tree/1.0.1) (2014-10-22)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/arioch/puppet-redis/tree/1.0.0) (2014-10-22)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.10...1.0.0)

## [0.0.10](https://github.com/arioch/puppet-redis/tree/0.0.10) (2014-08-29)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.9...0.0.10)

## [0.0.9](https://github.com/arioch/puppet-redis/tree/0.0.9) (2014-08-29)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.8...0.0.9)

**Closed issues:**

- Amazon AMI Installation/Initialization Issue [\#11](https://github.com/arioch/puppet-redis/issues/11)

**Merged pull requests:**

- Add Amazon support [\#12](https://github.com/arioch/puppet-redis/pull/12) ([arioch](https://github.com/arioch))
- Notify service [\#10](https://github.com/arioch/puppet-redis/pull/10) ([zebzeb](https://github.com/zebzeb))

## [0.0.8](https://github.com/arioch/puppet-redis/tree/0.0.8) (2014-03-27)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.7...0.0.8)

**Closed issues:**

- Default bind on public interface [\#6](https://github.com/arioch/puppet-redis/issues/6)
- Install a specific version [\#4](https://github.com/arioch/puppet-redis/issues/4)

**Merged pull requests:**

- Syslog [\#9](https://github.com/arioch/puppet-redis/pull/9) ([zebzeb](https://github.com/zebzeb))
- add extra config file parameter [\#8](https://github.com/arioch/puppet-redis/pull/8) ([zebzeb](https://github.com/zebzeb))
- pass conf template as a parameter [\#7](https://github.com/arioch/puppet-redis/pull/7) ([zebzeb](https://github.com/zebzeb))

## [0.0.7](https://github.com/arioch/puppet-redis/tree/0.0.7) (2014-01-13)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.6...0.0.7)

**Merged pull requests:**

- bugfix: Added puppetlabs/apt depedency and missing class include [\#5](https://github.com/arioch/puppet-redis/pull/5) ([n1tr0g](https://github.com/n1tr0g))

## [0.0.6](https://github.com/arioch/puppet-redis/tree/0.0.6) (2013-08-07)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.5...0.0.6)

**Merged pull requests:**

- add ubuntu ppa repo support [\#3](https://github.com/arioch/puppet-redis/pull/3) ([nagas](https://github.com/nagas))

## [0.0.5](https://github.com/arioch/puppet-redis/tree/0.0.5) (2013-07-22)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.4...0.0.5)

**Closed issues:**

- Redis config 2.6 not compatible with EPELs 2.4 on Centos6 [\#2](https://github.com/arioch/puppet-redis/issues/2)

## [0.0.4](https://github.com/arioch/puppet-redis/tree/0.0.4) (2013-07-17)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.3...0.0.4)

**Closed issues:**

- Default config path wrong for RedHat [\#1](https://github.com/arioch/puppet-redis/issues/1)

## [0.0.3](https://github.com/arioch/puppet-redis/tree/0.0.3) (2013-07-08)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.2...0.0.3)

## [0.0.2](https://github.com/arioch/puppet-redis/tree/0.0.2) (2013-06-19)
[Full Changelog](https://github.com/arioch/puppet-redis/compare/0.0.1...0.0.2)

## [0.0.1](https://github.com/arioch/puppet-redis/tree/0.0.1) (2013-06-19)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
