# Change Log

## [0.18.32](https://github.com/Yelp/paasta/tree/0.18.32) (2016-04-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.31...0.18.32)

**Closed issues:**

- Make haproxy-synapse status url configurable [\#434](https://github.com/Yelp/paasta/issues/434)

**Merged pull requests:**

- Document which config entries invoke a bounce [\#470](https://github.com/Yelp/paasta/pull/470) ([solarkennedy](https://github.com/solarkennedy))
- improve failure message sent by check\_chronos\_jobs [\#468](https://github.com/Yelp/paasta/pull/468) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.18.31](https://github.com/Yelp/paasta/tree/v0.18.31) (2016-04-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.30...v0.18.31)

## [v0.18.30](https://github.com/Yelp/paasta/tree/v0.18.30) (2016-04-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.29...v0.18.30)

## [v0.18.29](https://github.com/Yelp/paasta/tree/v0.18.29) (2016-04-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.28...v0.18.29)

**Merged pull requests:**

- Make synapse port configurable via SystemPaastaConfig [\#454](https://github.com/Yelp/paasta/pull/454) ([EvanKrall](https://github.com/EvanKrall))

## [v0.18.28](https://github.com/Yelp/paasta/tree/v0.18.28) (2016-04-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.27...v0.18.28)

**Merged pull requests:**

- Paasta cluster autoscaling [\#466](https://github.com/Yelp/paasta/pull/466) ([mjksmith](https://github.com/mjksmith))

## [v0.18.27](https://github.com/Yelp/paasta/tree/v0.18.27) (2016-04-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.26...v0.18.27)

**Merged pull requests:**

- Switch from readthedocs.org-\>readthedocs.io [\#467](https://github.com/Yelp/paasta/pull/467) ([nhandler](https://github.com/nhandler))

## [v0.18.26](https://github.com/Yelp/paasta/tree/v0.18.26) (2016-04-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.25...v0.18.26)

**Closed issues:**

- write some documentation on how resource isolation works [\#459](https://github.com/Yelp/paasta/issues/459)
- Create a 'paasta rerun' command [\#216](https://github.com/Yelp/paasta/issues/216)

**Merged pull requests:**

- fix some formatting in docs [\#464](https://github.com/Yelp/paasta/pull/464) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Made autoscale able to scale down below 9 [\#462](https://github.com/Yelp/paasta/pull/462) ([mjksmith](https://github.com/mjksmith))
- add a first pass at some docs explaining isolation. [\#460](https://github.com/Yelp/paasta/pull/460) ([Rob-Johnson](https://github.com/Rob-Johnson))
- improve the documentation on paasta batches [\#458](https://github.com/Yelp/paasta/pull/458) ([Rob-Johnson](https://github.com/Rob-Johnson))
- removed service\_configuration\_lib.DEFAULT\_SOA\_DIR [\#455](https://github.com/Yelp/paasta/pull/455) ([mjksmith](https://github.com/mjksmith))

## [v0.18.25](https://github.com/Yelp/paasta/tree/v0.18.25) (2016-04-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.24...v0.18.25)

**Merged pull requests:**

- made the default metrics provider mesos\_cpu [\#453](https://github.com/Yelp/paasta/pull/453) ([mjksmith](https://github.com/mjksmith))
- interpolate datestrings when using local-run with a chronos job [\#451](https://github.com/Yelp/paasta/pull/451) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.18.24](https://github.com/Yelp/paasta/tree/v0.18.24) (2016-04-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.23...v0.18.24)

**Merged pull requests:**

- Use marathon 1.1.1 in itest and upgrade marathon-python [\#433](https://github.com/Yelp/paasta/pull/433) ([nhandler](https://github.com/nhandler))

## [v0.18.23](https://github.com/Yelp/paasta/tree/v0.18.23) (2016-04-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.22...v0.18.23)

**Merged pull requests:**

- fixed error running paasta metastatus [\#449](https://github.com/Yelp/paasta/pull/449) ([mjksmith](https://github.com/mjksmith))
- fix "paasta rerun" crashes \(PAASTA-4152\) [\#448](https://github.com/Yelp/paasta/pull/448) ([giuliano108](https://github.com/giuliano108))
- Don't alert teams if a service hasn't been deployed yet [\#435](https://github.com/Yelp/paasta/pull/435) ([solarkennedy](https://github.com/solarkennedy))

## [v0.18.22](https://github.com/Yelp/paasta/tree/v0.18.22) (2016-04-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.21...v0.18.22)

**Closed issues:**

- paasta local-run --healthcheck-only exits 0 even when the healthcheck never passes [\#445](https://github.com/Yelp/paasta/issues/445)

**Merged pull requests:**

- made local\_run --healthcheck-only return 1 when healthchecks fail [\#446](https://github.com/Yelp/paasta/pull/446) ([mjksmith](https://github.com/mjksmith))
- Made almost every cli tool take a soa\_dir [\#444](https://github.com/Yelp/paasta/pull/444) ([mjksmith](https://github.com/mjksmith))

## [v0.18.21](https://github.com/Yelp/paasta/tree/v0.18.21) (2016-04-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.20...v0.18.21)

**Closed issues:**

- paasta check for DOCKER\_TAG is too strict [\#439](https://github.com/Yelp/paasta/issues/439)
- Update paasta local run to include memory-swap parameter [\#428](https://github.com/Yelp/paasta/issues/428)
- only require a date to chronos-rerun if there is something to be interpolated [\#420](https://github.com/Yelp/paasta/issues/420)

**Merged pull requests:**

- s/PST/America\/Los\_Angeles/ [\#441](https://github.com/Yelp/paasta/pull/441) ([nhandler](https://github.com/nhandler))
- Make DOCKER\_TAG check less strict [\#440](https://github.com/Yelp/paasta/pull/440) ([EvanKrall](https://github.com/EvanKrall))
- always round --memory-swap param up to closest mb [\#437](https://github.com/Yelp/paasta/pull/437) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Unknown slaves in "paasta status" workaround \(PAASTA-4119\) [\#436](https://github.com/Yelp/paasta/pull/436) ([giuliano108](https://github.com/giuliano108))
- It's dockercfg, not dockerfile. [\#432](https://github.com/Yelp/paasta/pull/432) ([EvanKrall](https://github.com/EvanKrall))
- Local run memory swappiness [\#430](https://github.com/Yelp/paasta/pull/430) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.18.20](https://github.com/Yelp/paasta/tree/v0.18.20) (2016-04-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.19...v0.18.20)

**Merged pull requests:**

- removed portMapping from non-bridge nets [\#431](https://github.com/Yelp/paasta/pull/431) ([mjksmith](https://github.com/mjksmith))

## [v0.18.19](https://github.com/Yelp/paasta/tree/v0.18.19) (2016-04-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.18...v0.18.19)

## [v0.18.18](https://github.com/Yelp/paasta/tree/v0.18.18) (2016-04-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.17...v0.18.18)

**Merged pull requests:**

- made bespoke autoscaling short circuit earlier [\#429](https://github.com/Yelp/paasta/pull/429) ([mjksmith](https://github.com/mjksmith))

## [v0.18.17](https://github.com/Yelp/paasta/tree/v0.18.17) (2016-04-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.16...v0.18.17)

**Merged pull requests:**

- Make the argparser print the full help whenever an argparse issue is encountered [\#422](https://github.com/Yelp/paasta/pull/422) ([solarkennedy](https://github.com/solarkennedy))

## [v0.18.16](https://github.com/Yelp/paasta/tree/v0.18.16) (2016-04-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.15...v0.18.16)

**Closed issues:**

- create a frontend paasta rerun command [\#323](https://github.com/Yelp/paasta/issues/323)

**Merged pull requests:**

- create a frontend paasta rerun command [\#419](https://github.com/Yelp/paasta/pull/419) ([giuliano108](https://github.com/giuliano108))

## [v0.18.15](https://github.com/Yelp/paasta/tree/v0.18.15) (2016-04-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.14...v0.18.15)

**Closed issues:**

- temporary jobs created by chronos-rerun trigger a sensu alert for check\_chronos\_jobs [\#421](https://github.com/Yelp/paasta/issues/421)
- set the "memory-swap" parameter in docker containers. [\#410](https://github.com/Yelp/paasta/issues/410)

**Merged pull requests:**

- Add memory swap param [\#411](https://github.com/Yelp/paasta/pull/411) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Clean up orphaned docker container script [\#352](https://github.com/Yelp/paasta/pull/352) ([nosmo](https://github.com/nosmo))

## [v0.18.14](https://github.com/Yelp/paasta/tree/v0.18.14) (2016-04-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.13...v0.18.14)

**Merged pull requests:**

- ignore temporary jobs when checking chronos jobs [\#425](https://github.com/Yelp/paasta/pull/425) ([Rob-Johnson](https://github.com/Rob-Johnson))
- added healthcheck output to marathon status [\#423](https://github.com/Yelp/paasta/pull/423) ([mjksmith](https://github.com/mjksmith))
- Revert "Merge branch 'dont-require-start-time'" [\#418](https://github.com/Yelp/paasta/pull/418) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Upgrade marathon to 0.15.3-1.0.463.ubuntu1404 in itests [\#415](https://github.com/Yelp/paasta/pull/415) ([nhandler](https://github.com/nhandler))

## [v0.18.13](https://github.com/Yelp/paasta/tree/v0.18.13) (2016-04-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.12...v0.18.13)

**Merged pull requests:**

- fix repo fingerprints [\#417](https://github.com/Yelp/paasta/pull/417) ([ysyoung](https://github.com/ysyoung))
- Bump mesos.interface to 0.28.0 [\#416](https://github.com/Yelp/paasta/pull/416) ([nhandler](https://github.com/nhandler))
- Use json for mesos authentication [\#413](https://github.com/Yelp/paasta/pull/413) ([nhandler](https://github.com/nhandler))
- Removed variable delay and other params from autoscaling [\#394](https://github.com/Yelp/paasta/pull/394) ([mjksmith](https://github.com/mjksmith))
- made local run create a fresh deployments.json [\#368](https://github.com/Yelp/paasta/pull/368) ([mjksmith](https://github.com/mjksmith))

## [v0.18.12](https://github.com/Yelp/paasta/tree/v0.18.12) (2016-04-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.11...v0.18.12)

**Closed issues:**

- Odd formatting in pasta fsm --yelpsoa-config-root [\#396](https://github.com/Yelp/paasta/issues/396)

**Merged pull requests:**

- fixed net host marathon error [\#412](https://github.com/Yelp/paasta/pull/412) ([mjksmith](https://github.com/mjksmith))
- fixed formatting in fsm [\#407](https://github.com/Yelp/paasta/pull/407) ([mjksmith](https://github.com/mjksmith))
- Upgrade tests to use marathon 0.14.2 [\#403](https://github.com/Yelp/paasta/pull/403) ([nhandler](https://github.com/nhandler))

## [v0.18.11](https://github.com/Yelp/paasta/tree/v0.18.11) (2016-04-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.10...v0.18.11)

**Closed issues:**

- chronos jobs require start times [\#383](https://github.com/Yelp/paasta/issues/383)
- Add deploy\_whitelist [\#251](https://github.com/Yelp/paasta/issues/251)
- location of dockercfg file is hardcoded [\#6](https://github.com/Yelp/paasta/issues/6)

**Merged pull requests:**

- Upgrade mesos to 0.28.0-2.0.16.ubuntu1404 in itests [\#408](https://github.com/Yelp/paasta/pull/408) ([nhandler](https://github.com/nhandler))
- added soa\_dir argument to paasta itest [\#406](https://github.com/Yelp/paasta/pull/406) ([mjksmith](https://github.com/mjksmith))
- Upgrade mesos to 0.27.2-2.0.15.ubuntu1404 in the itests [\#405](https://github.com/Yelp/paasta/pull/405) ([nhandler](https://github.com/nhandler))
- added host networking [\#404](https://github.com/Yelp/paasta/pull/404) ([mjksmith](https://github.com/mjksmith))
- Add support for whitelisting. [\#402](https://github.com/Yelp/paasta/pull/402) ([ysyoung](https://github.com/ysyoung))
- Make is\_app\_id\_running tolerate leading slashes [\#401](https://github.com/Yelp/paasta/pull/401) ([solarkennedy](https://github.com/solarkennedy))
- Make the marathon upgrade docs match current practice [\#400](https://github.com/Yelp/paasta/pull/400) ([nhandler](https://github.com/nhandler))
- remove the requirement for a start time in chronos schedules [\#398](https://github.com/Yelp/paasta/pull/398) ([Rob-Johnson](https://github.com/Rob-Johnson))
- make docker config location configurable [\#395](https://github.com/Yelp/paasta/pull/395) ([ysyoung](https://github.com/ysyoung))

## [v0.18.10](https://github.com/Yelp/paasta/tree/v0.18.10) (2016-04-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.9...v0.18.10)

**Closed issues:**

- test\_filter\_expired\_tmp\_jobs is failing on master [\#392](https://github.com/Yelp/paasta/issues/392)
- cleanup\_chronos\_jobs failing on tmp jobs [\#388](https://github.com/Yelp/paasta/issues/388)
- test\_format\_parents\_verbose fails due to hardcoded relative date [\#387](https://github.com/Yelp/paasta/issues/387)
- chronos\_rerun -h blows up [\#385](https://github.com/Yelp/paasta/issues/385)

**Merged pull requests:**

- fix test missing tzinfo [\#393](https://github.com/Yelp/paasta/pull/393) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Upgrade to marathon 0.13.1 in itests [\#375](https://github.com/Yelp/paasta/pull/375) ([nhandler](https://github.com/nhandler))

## [v0.18.9](https://github.com/Yelp/paasta/tree/v0.18.9) (2016-04-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.8...v0.18.9)

**Merged pull requests:**

- fix escaping in chronos\_rerun help string [\#391](https://github.com/Yelp/paasta/pull/391) ([Rob-Johnson](https://github.com/Rob-Johnson))
- fix test dependent on time [\#390](https://github.com/Yelp/paasta/pull/390) ([Rob-Johnson](https://github.com/Rob-Johnson))
- parse the datetime string from lastruntime in chronos jobs [\#389](https://github.com/Yelp/paasta/pull/389) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Autoscaling improvements [\#386](https://github.com/Yelp/paasta/pull/386) ([mjksmith](https://github.com/mjksmith))
- Make the marathon cleanup script resolve all related sensu events. [\#379](https://github.com/Yelp/paasta/pull/379) ([solarkennedy](https://github.com/solarkennedy))

## [v0.18.8](https://github.com/Yelp/paasta/tree/v0.18.8) (2016-04-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.7...v0.18.8)

**Merged pull requests:**

- added a command to autoscale all services [\#382](https://github.com/Yelp/paasta/pull/382) ([mjksmith](https://github.com/mjksmith))

## [v0.18.7](https://github.com/Yelp/paasta/tree/v0.18.7) (2016-04-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.6...v0.18.7)

**Closed issues:**

- make `cleanup\_chronos\_jobs` aware of temporary jobs created by `paasta rerun` [\#324](https://github.com/Yelp/paasta/issues/324)
- create a backend 'paasta rerun' command [\#322](https://github.com/Yelp/paasta/issues/322)

**Merged pull requests:**

- ensure chronos rerun is distributed properly [\#384](https://github.com/Yelp/paasta/pull/384) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.18.6](https://github.com/Yelp/paasta/tree/v0.18.6) (2016-04-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.5...v0.18.6)

**Merged pull requests:**

- Ensure cleanup jobs understands tmp jobs [\#354](https://github.com/Yelp/paasta/pull/354) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Create a ``chronos\_rerun`` script for rerunning past jobs [\#330](https://github.com/Yelp/paasta/pull/330) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.18.5](https://github.com/Yelp/paasta/tree/v0.18.5) (2016-04-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.4...v0.18.5)

**Closed issues:**

- Fix Upgrading Marathon Docs now that we use upstream marathon-python [\#378](https://github.com/Yelp/paasta/issues/378)

**Merged pull requests:**

- Set real disabled value [\#381](https://github.com/Yelp/paasta/pull/381) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Remove docs about adding marathon-python to internal pypi [\#380](https://github.com/Yelp/paasta/pull/380) ([nhandler](https://github.com/nhandler))
- Bump mesos.interface to 0.25.0 [\#377](https://github.com/Yelp/paasta/pull/377) ([nhandler](https://github.com/nhandler))
- Only deploy to pypi on py27 build [\#372](https://github.com/Yelp/paasta/pull/372) ([EvanKrall](https://github.com/EvanKrall))

## [v0.18.4](https://github.com/Yelp/paasta/tree/v0.18.4) (2016-03-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.3...v0.18.4)

**Closed issues:**

- getting started docs are incorrect outside of Yelp [\#82](https://github.com/Yelp/paasta/issues/82)
- wrong version of mesos.interface being installed [\#81](https://github.com/Yelp/paasta/issues/81)

**Merged pull requests:**

- stopped alerting for disabled jobs on chronos [\#361](https://github.com/Yelp/paasta/pull/361) ([mjksmith](https://github.com/mjksmith))
- Added a default autoscaling method [\#303](https://github.com/Yelp/paasta/pull/303) ([mjksmith](https://github.com/mjksmith))

## [v0.18.3](https://github.com/Yelp/paasta/tree/v0.18.3) (2016-03-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.2...v0.18.3)

**Closed issues:**

- Typo in "paasta local-run -h" [\#369](https://github.com/Yelp/paasta/issues/369)
- Switching from branches to tags made it harder to get currently deployed git sha [\#359](https://github.com/Yelp/paasta/issues/359)

**Merged pull requests:**

- Use behave-pytest for pytest-style asserts [\#371](https://github.com/Yelp/paasta/pull/371) ([nhandler](https://github.com/nhandler))
- added a command to get a deploy group's latest deploy sha [\#357](https://github.com/Yelp/paasta/pull/357) ([mjksmith](https://github.com/mjksmith))
- Upgrade to mesos 0.25.0 [\#319](https://github.com/Yelp/paasta/pull/319) ([nhandler](https://github.com/nhandler))

## [v0.18.2](https://github.com/Yelp/paasta/tree/v0.18.2) (2016-03-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.1...v0.18.2)

**Merged pull requests:**

- made args for deep\_merge\_dictionaries more descriptive [\#363](https://github.com/Yelp/paasta/pull/363) ([mjksmith](https://github.com/mjksmith))

## [v0.18.1](https://github.com/Yelp/paasta/tree/v0.18.1) (2016-03-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.18.0...v0.18.1)

**Closed issues:**

- Add Bintray badge to readme [\#364](https://github.com/Yelp/paasta/issues/364)
- Make packages available publicly [\#318](https://github.com/Yelp/paasta/issues/318)

**Merged pull requests:**

- Only have travis build on master \(and pull requests\). [\#366](https://github.com/Yelp/paasta/pull/366) ([EvanKrall](https://github.com/EvanKrall))
- Add Bintray Badge to README [\#365](https://github.com/Yelp/paasta/pull/365) ([nhandler](https://github.com/nhandler))
- Fix bintray upload [\#362](https://github.com/Yelp/paasta/pull/362) ([EvanKrall](https://github.com/EvanKrall))
- fixed a bug where smartstack.yaml was overriding marathon.yaml [\#360](https://github.com/Yelp/paasta/pull/360) ([mjksmith](https://github.com/mjksmith))

## [v0.18.0](https://github.com/Yelp/paasta/tree/v0.18.0) (2016-03-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.20...v0.18.0)

**Closed issues:**

- Marathon doesn't like non-string values in constraints [\#333](https://github.com/Yelp/paasta/issues/333)
- write docs on how to disable a chronos job [\#294](https://github.com/Yelp/paasta/issues/294)

**Merged pull requests:**

- stringify any constraint vals for marathon [\#356](https://github.com/Yelp/paasta/pull/356) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Add mass-deploy-tag.sh to contrib/ [\#347](https://github.com/Yelp/paasta/pull/347) ([nhandler](https://github.com/nhandler))
- Move configuration of replication monitoring to yelpsoa config [\#345](https://github.com/Yelp/paasta/pull/345) ([nosmo](https://github.com/nosmo))
- Public package build [\#337](https://github.com/Yelp/paasta/pull/337) ([EvanKrall](https://github.com/EvanKrall))

## [v0.17.20](https://github.com/Yelp/paasta/tree/v0.17.20) (2016-03-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.19...v0.17.20)

**Closed issues:**

- cleanup\_marathon\_jobs crashing because marathon.yaml doesn't exist [\#350](https://github.com/Yelp/paasta/issues/350)
- metastatus ZeroDivisionError [\#348](https://github.com/Yelp/paasta/issues/348)
- Include schedule\_time\_zone in schema [\#338](https://github.com/Yelp/paasta/issues/338)
- UnboundLocalError when Popen fails [\#60](https://github.com/Yelp/paasta/issues/60)

**Merged pull requests:**

- made cleanup\_marathon\_job not load soa configs for a deleted service [\#351](https://github.com/Yelp/paasta/pull/351) ([mjksmith](https://github.com/mjksmith))
- made metastatus print sane errors if mesos states it has 0 resources [\#349](https://github.com/Yelp/paasta/pull/349) ([mjksmith](https://github.com/mjksmith))
- fixed \_run throwing an error when popen failed with a timeout [\#346](https://github.com/Yelp/paasta/pull/346) ([mjksmith](https://github.com/mjksmith))
- added schedule\_time\_zone to chronos schema [\#344](https://github.com/Yelp/paasta/pull/344) ([mjksmith](https://github.com/mjksmith))
- Make -vv output consistent with -vvv output, humanize figures [\#340](https://github.com/Yelp/paasta/pull/340) ([nosmo](https://github.com/nosmo))
- stopped per-instance configs from nuking global defaults [\#331](https://github.com/Yelp/paasta/pull/331) ([mjksmith](https://github.com/mjksmith))
- Use tags rather than branches for deployments [\#326](https://github.com/Yelp/paasta/pull/326) ([nhandler](https://github.com/nhandler))
- add some docs for paasta start/stop behaviour [\#314](https://github.com/Yelp/paasta/pull/314) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.17.19](https://github.com/Yelp/paasta/tree/v0.17.19) (2016-03-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.18...v0.17.19)

**Closed issues:**

- Broken links in docs [\#336](https://github.com/Yelp/paasta/issues/336)

**Merged pull requests:**

- Fix broken links to drain\_lib / bounce\_lib docs. Fixes \#336 [\#342](https://github.com/Yelp/paasta/pull/342) ([EvanKrall](https://github.com/EvanKrall))
- fixed paasta fsm creating invalid deploy.yaml [\#339](https://github.com/Yelp/paasta/pull/339) ([mjksmith](https://github.com/mjksmith))
- Catch failed responses during http healthcheck [\#332](https://github.com/Yelp/paasta/pull/332) ([koikonom](https://github.com/koikonom))

## [v0.17.18](https://github.com/Yelp/paasta/tree/v0.17.18) (2016-03-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.17...v0.17.18)

## [v0.17.17](https://github.com/Yelp/paasta/tree/v0.17.17) (2016-03-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.16...v0.17.17)

**Closed issues:**

- create alternative backend for logging [\#64](https://github.com/Yelp/paasta/issues/64)

**Merged pull requests:**

- Upgrade mesos.interface to 0.24.1 [\#329](https://github.com/Yelp/paasta/pull/329) ([nhandler](https://github.com/nhandler))
- Allow 'paasta re.start -c' to use a list of clusters [\#328](https://github.com/Yelp/paasta/pull/328) ([nosmo](https://github.com/nosmo))

## [v0.17.16](https://github.com/Yelp/paasta/tree/v0.17.16) (2016-03-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.15...v0.17.16)

**Merged pull requests:**

- Fix `paasta status -vv` [\#325](https://github.com/Yelp/paasta/pull/325) ([giuliano108](https://github.com/giuliano108))
- Display more data when doing the healthcheck during local-run [\#321](https://github.com/Yelp/paasta/pull/321) ([solarkennedy](https://github.com/solarkennedy))

## [v0.17.15](https://github.com/Yelp/paasta/tree/v0.17.15) (2016-03-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.14...v0.17.15)

**Closed issues:**

- setting 'disable: true' in a chronos job is a noop unless you also 'paasta stop' the job [\#283](https://github.com/Yelp/paasta/issues/283)

**Merged pull requests:**

- Mesos 0.24.1 Passes Tests! [\#317](https://github.com/Yelp/paasta/pull/317) ([nhandler](https://github.com/nhandler))
- Use authentication with mesos in itests [\#316](https://github.com/Yelp/paasta/pull/316) ([nhandler](https://github.com/nhandler))
- Print metastatus free resources alongside total resource capacity [\#315](https://github.com/Yelp/paasta/pull/315) ([nosmo](https://github.com/nosmo))
- Make FileLogWriter, which writes json-formatted log lines to a specified file. [\#313](https://github.com/Yelp/paasta/pull/313) ([EvanKrall](https://github.com/EvanKrall))
- Do the mesos upgrade again [\#312](https://github.com/Yelp/paasta/pull/312) ([nhandler](https://github.com/nhandler))
- added clean\_up\_zookeeper\_autoscaling to environment.py [\#310](https://github.com/Yelp/paasta/pull/310) ([mjksmith](https://github.com/mjksmith))
- increased test coverage for marathon\_tools [\#309](https://github.com/Yelp/paasta/pull/309) ([mjksmith](https://github.com/mjksmith))
- fixed the default autoscaling config args [\#308](https://github.com/Yelp/paasta/pull/308) ([mjksmith](https://github.com/mjksmith))
- fixed a log line in generate\_deployments\_for\_service [\#307](https://github.com/Yelp/paasta/pull/307) ([mjksmith](https://github.com/mjksmith))
- ensure disabled flag is considered when computing config hash for chr… [\#306](https://github.com/Yelp/paasta/pull/306) ([Rob-Johnson](https://github.com/Rob-Johnson))
- added an autocomplete to rollback git shas [\#305](https://github.com/Yelp/paasta/pull/305) ([mjksmith](https://github.com/mjksmith))
- Added more explicit start/stop/restart messages [\#302](https://github.com/Yelp/paasta/pull/302) ([solarkennedy](https://github.com/solarkennedy))
- Add stdout/err tail snippet to paasta status -vv \(PAASTA-3268\) [\#301](https://github.com/Yelp/paasta/pull/301) ([giuliano108](https://github.com/giuliano108))
- Order tasks in verbose paasta status [\#295](https://github.com/Yelp/paasta/pull/295) ([drolando](https://github.com/drolando))
- Added an autoscaling\_method field [\#290](https://github.com/Yelp/paasta/pull/290) ([mjksmith](https://github.com/mjksmith))
- Update docs to note Marathon env\_var\_prefix [\#286](https://github.com/Yelp/paasta/pull/286) ([nhandler](https://github.com/nhandler))
- Pluggable log systems [\#281](https://github.com/Yelp/paasta/pull/281) ([EvanKrall](https://github.com/EvanKrall))

## [v0.17.14](https://github.com/Yelp/paasta/tree/v0.17.14) (2016-03-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.13...v0.17.14)

**Closed issues:**

- Can't run paasta itests when using docker http api [\#287](https://github.com/Yelp/paasta/issues/287)
- ``check\_chronos\_job`` alerts when a job is disabled [\#284](https://github.com/Yelp/paasta/issues/284)

**Merged pull requests:**

- Redo mesos.cli upgrade [\#304](https://github.com/Yelp/paasta/pull/304) ([nhandler](https://github.com/nhandler))
- Allow paasta to use docker http api [\#300](https://github.com/Yelp/paasta/pull/300) ([keshavdv](https://github.com/keshavdv))
- refactored create\_complete\_config [\#298](https://github.com/Yelp/paasta/pull/298) ([mjksmith](https://github.com/mjksmith))
- Remove disabled field from chronos soa-configs [\#293](https://github.com/Yelp/paasta/pull/293) ([Rob-Johnson](https://github.com/Rob-Johnson))
- send OK event when a chronos job has been disabled [\#292](https://github.com/Yelp/paasta/pull/292) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.17.13](https://github.com/Yelp/paasta/tree/v0.17.13) (2016-03-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.12...v0.17.13)

**Merged pull requests:**

- Revert "Upgrade mesos.cli for mesos 0.24.1 upgrade" [\#297](https://github.com/Yelp/paasta/pull/297) ([nhandler](https://github.com/nhandler))
- added autoscaling docs [\#296](https://github.com/Yelp/paasta/pull/296) ([mjksmith](https://github.com/mjksmith))
- respect the alert\_after param in check\_chronos\_jobs [\#291](https://github.com/Yelp/paasta/pull/291) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Mesos 0.24.1 [\#289](https://github.com/Yelp/paasta/pull/289) ([nhandler](https://github.com/nhandler))

## [v0.17.12](https://github.com/Yelp/paasta/tree/v0.17.12) (2016-03-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.11...v0.17.12)

**Merged pull requests:**

- Set MARATHON\_PORT env variable in local-run [\#285](https://github.com/Yelp/paasta/pull/285) ([nhandler](https://github.com/nhandler))
- Upgrade mesos in itests to 0.24.1 [\#233](https://github.com/Yelp/paasta/pull/233) ([nhandler](https://github.com/nhandler))

## [v0.17.11](https://github.com/Yelp/paasta/tree/v0.17.11) (2016-03-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.10...v0.17.11)

**Closed issues:**

- paasta metastatus should show units in output [\#277](https://github.com/Yelp/paasta/issues/277)
- paasta fsm generating bad config [\#270](https://github.com/Yelp/paasta/issues/270)
- paasta start/stop/restart should provide helpful hints if it can't talk to git [\#269](https://github.com/Yelp/paasta/issues/269)
- error running metastatus -vv [\#257](https://github.com/Yelp/paasta/issues/257)
- Rename /state.json endpoint in conjunction with mesos 0.24.x to 0.25.x upgrade [\#232](https://github.com/Yelp/paasta/issues/232)

**Merged pull requests:**

- Fix an output bug in paasta check [\#282](https://github.com/Yelp/paasta/pull/282) ([mjksmith](https://github.com/mjksmith))
- add a note about the parents field in yelpsoa-configs [\#280](https://github.com/Yelp/paasta/pull/280) ([Rob-Johnson](https://github.com/Rob-Johnson))
- added docs for deploy groups string interpolation [\#279](https://github.com/Yelp/paasta/pull/279) ([mjksmith](https://github.com/mjksmith))
- fix some dead links in the docs [\#278](https://github.com/Yelp/paasta/pull/278) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Updated /state endpoint for mesos 0.25.x upgrade [\#276](https://github.com/Yelp/paasta/pull/276) ([ameya-pandilwar](https://github.com/ameya-pandilwar))
- Allow marathon instance counts to be read from zookeeper [\#275](https://github.com/Yelp/paasta/pull/275) ([mjksmith](https://github.com/mjksmith))
- Added a more friendly error message when git isn't reachable. [\#274](https://github.com/Yelp/paasta/pull/274) ([solarkennedy](https://github.com/solarkennedy))
- Use returncode instead of sys.exit in the paasta cli [\#273](https://github.com/Yelp/paasta/pull/273) ([solarkennedy](https://github.com/solarkennedy))
- Add extra\_constraints and pool to schemas for paasta validate [\#272](https://github.com/Yelp/paasta/pull/272) ([nhandler](https://github.com/nhandler))
- Added missing pool docs [\#271](https://github.com/Yelp/paasta/pull/271) ([solarkennedy](https://github.com/solarkennedy))
- Fix metastatus -vv [\#262](https://github.com/Yelp/paasta/pull/262) ([nhandler](https://github.com/nhandler))

## [v0.17.10](https://github.com/Yelp/paasta/tree/v0.17.10) (2016-02-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.10n...v0.17.10)

## [v0.17.10n](https://github.com/Yelp/paasta/tree/v0.17.10n) (2016-02-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.9...v0.17.10n)

**Merged pull requests:**

- changed do\_bounce to kill task w/the batch endpoint [\#267](https://github.com/Yelp/paasta/pull/267) ([mjksmith](https://github.com/mjksmith))

## [v0.17.9](https://github.com/Yelp/paasta/tree/v0.17.9) (2016-02-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.9n...v0.17.9)

## [v0.17.9n](https://github.com/Yelp/paasta/tree/v0.17.9n) (2016-02-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.8...v0.17.9n)

**Closed issues:**

- PORT exported by paasta makes it difficult to do dockerfiles according to best practices [\#152](https://github.com/Yelp/paasta/issues/152)

**Merged pull requests:**

- Pass --env\_vars\_prefix to marathon and remove local\_run workaround [\#266](https://github.com/Yelp/paasta/pull/266) ([nhandler](https://github.com/nhandler))

## [v0.17.8](https://github.com/Yelp/paasta/tree/v0.17.8) (2016-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.7...v0.17.8)

## [v0.17.7](https://github.com/Yelp/paasta/tree/v0.17.7) (2016-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.6...v0.17.7)

## [v0.17.6](https://github.com/Yelp/paasta/tree/v0.17.6) (2016-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.5...v0.17.6)

## [v0.17.5](https://github.com/Yelp/paasta/tree/v0.17.5) (2016-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.4...v0.17.5)

## [v0.17.4](https://github.com/Yelp/paasta/tree/v0.17.4) (2016-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.3...v0.17.4)

## [v0.17.3](https://github.com/Yelp/paasta/tree/v0.17.3) (2016-02-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.2...v0.17.3)

## [v0.17.2](https://github.com/Yelp/paasta/tree/v0.17.2) (2016-02-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.1...v0.17.2)

**Merged pull requests:**

- enabled scaling without bounces when editing soa\_configs [\#255](https://github.com/Yelp/paasta/pull/255) ([mjksmith](https://github.com/mjksmith))

## [v0.17.1](https://github.com/Yelp/paasta/tree/v0.17.1) (2016-02-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.17.0...v0.17.1)

**Closed issues:**

- Rename `--deploy\_group` to `--deploy-group` [\#243](https://github.com/Yelp/paasta/issues/243)
- we should validate that a given service.instance parent exists before trying to deploy [\#148](https://github.com/Yelp/paasta/issues/148)
- add validation for chronos job parents [\#97](https://github.com/Yelp/paasta/issues/97)

**Merged pull requests:**

- Renamed --deploy\_group to --deploy-group [\#264](https://github.com/Yelp/paasta/pull/264) ([ameya-pandilwar](https://github.com/ameya-pandilwar))
- made setup\_chronos\_jobs handle non-existant jobs [\#263](https://github.com/Yelp/paasta/pull/263) ([mjksmith](https://github.com/mjksmith))
- added string interpolation to deploy groups [\#259](https://github.com/Yelp/paasta/pull/259) ([mjksmith](https://github.com/mjksmith))
- validate dependent jobs' parents - issue 148 [\#245](https://github.com/Yelp/paasta/pull/245) ([giuliano108](https://github.com/giuliano108))
- re-ordered default deploy order in fsm [\#242](https://github.com/Yelp/paasta/pull/242) ([mjksmith](https://github.com/mjksmith))

## [v0.17.0](https://github.com/Yelp/paasta/tree/v0.17.0) (2016-02-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.34...v0.17.0)

**Closed issues:**

- error in check\_marathon\_services\_replication when a task hasn't started [\#258](https://github.com/Yelp/paasta/issues/258)

**Merged pull requests:**

- marathon tasks with started\_at of None are now unhealthy [\#261](https://github.com/Yelp/paasta/pull/261) ([mjksmith](https://github.com/mjksmith))
- No longer use paasta\_execute\_in\_container for command healthchecks. [\#260](https://github.com/Yelp/paasta/pull/260) ([solarkennedy](https://github.com/solarkennedy))
- made metastatus catch when no dashboard in configured [\#253](https://github.com/Yelp/paasta/pull/253) ([mjksmith](https://github.com/mjksmith))

## [v0.16.34](https://github.com/Yelp/paasta/tree/v0.16.34) (2016-02-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.33...v0.16.34)

**Merged pull requests:**

- Update paasta check sensu\_check and smartstack\_check to pass soa\_dir [\#254](https://github.com/Yelp/paasta/pull/254) ([nhandler](https://github.com/nhandler))
- Revert "Revert "Mark for deployment tags take2"" [\#252](https://github.com/Yelp/paasta/pull/252) ([nhandler](https://github.com/nhandler))

## [v0.16.33](https://github.com/Yelp/paasta/tree/v0.16.33) (2016-02-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.32...v0.16.33)

**Closed issues:**

- Control tags besides start/stop are all interpreted as stop. [\#223](https://github.com/Yelp/paasta/issues/223)

**Merged pull requests:**

- Revert "Mark for deployment tags take2" [\#250](https://github.com/Yelp/paasta/pull/250) ([nhandler](https://github.com/nhandler))
- Added experimental script to kill old marathon deployments [\#249](https://github.com/Yelp/paasta/pull/249) ([solarkennedy](https://github.com/solarkennedy))
- made metastatus read from /etc/paasta to get dashboards [\#248](https://github.com/Yelp/paasta/pull/248) ([mjksmith](https://github.com/mjksmith))
- fix typo in docs [\#247](https://github.com/Yelp/paasta/pull/247) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Fixed typo in docs/source/deploy\_groups.rst [\#246](https://github.com/Yelp/paasta/pull/246) ([drolando](https://github.com/drolando))
- Use verbose flags instead of debug in paasta logs [\#244](https://github.com/Yelp/paasta/pull/244) ([solarkennedy](https://github.com/solarkennedy))
- Added metastatus -vv [\#234](https://github.com/Yelp/paasta/pull/234) ([mjksmith](https://github.com/mjksmith))
- Mark for deployment tags take2 [\#231](https://github.com/Yelp/paasta/pull/231) ([nhandler](https://github.com/nhandler))

## [v0.16.32](https://github.com/Yelp/paasta/tree/v0.16.32) (2016-02-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.31...v0.16.32)

**Merged pull requests:**

- Add support for disk resource isolation [\#241](https://github.com/Yelp/paasta/pull/241) ([nhandler](https://github.com/nhandler))
- removed unnecessary arg from generate\_deployments.get\_desired\_state [\#240](https://github.com/Yelp/paasta/pull/240) ([mjksmith](https://github.com/mjksmith))
- reduced kill\_orphaned\_docker\_containers runtime [\#239](https://github.com/Yelp/paasta/pull/239) ([mjksmith](https://github.com/mjksmith))
- made paasta metastatus display total cpu and mem on critical status [\#237](https://github.com/Yelp/paasta/pull/237) ([mjksmith](https://github.com/mjksmith))
- paasta status - show the value of schedule\_time\_zone \(PAASTA-2389\) [\#235](https://github.com/Yelp/paasta/pull/235) ([giuliano108](https://github.com/giuliano108))

## [v0.16.31](https://github.com/Yelp/paasta/tree/v0.16.31) (2016-02-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.30...v0.16.31)

**Closed issues:**

- update chronos\_schema.json to support dependent jobs [\#217](https://github.com/Yelp/paasta/issues/217)
- If container dies, fail healthcheck \(local-run\) [\#213](https://github.com/Yelp/paasta/issues/213)
- allow a string or array value for the 'parents' key of a dependent job [\#149](https://github.com/Yelp/paasta/issues/149)
- Show the status of a job's parents in paasta status [\#96](https://github.com/Yelp/paasta/issues/96)

**Merged pull requests:**

- Added experimental manual mesos task reconciliation script \(orphan killer\) [\#238](https://github.com/Yelp/paasta/pull/238) ([solarkennedy](https://github.com/solarkennedy))
- Add extra\_constraints, which doesn't override default constraints. [\#236](https://github.com/Yelp/paasta/pull/236) ([EvanKrall](https://github.com/EvanKrall))
- Upgrade mesos.interface to 0.23.1 [\#230](https://github.com/Yelp/paasta/pull/230) ([nhandler](https://github.com/nhandler))
- Fail fast when contained dies in local-run.  Resolves \#213 [\#229](https://github.com/Yelp/paasta/pull/229) ([asottile](https://github.com/asottile))
- Add jsonschema to setup.py [\#228](https://github.com/Yelp/paasta/pull/228) ([asottile](https://github.com/asottile))
- Add a new itest to assert new services have a desired\_state of start [\#227](https://github.com/Yelp/paasta/pull/227) ([nhandler](https://github.com/nhandler))
- Fix typo [\#226](https://github.com/Yelp/paasta/pull/226) ([asottile](https://github.com/asottile))
- Update chronos json schema \#217 [\#224](https://github.com/Yelp/paasta/pull/224) ([giuliano108](https://github.com/giuliano108))
- allow a string or array value for the 'parents' key of a dependent job [\#219](https://github.com/Yelp/paasta/pull/219) ([giuliano108](https://github.com/giuliano108))
- Added documentation for deploy groups [\#218](https://github.com/Yelp/paasta/pull/218) ([mjksmith](https://github.com/mjksmith))
- fsm now generates configs that use deploy groups [\#208](https://github.com/Yelp/paasta/pull/208) ([mjksmith](https://github.com/mjksmith))
- Show details of parents in output of ``paasta status`` [\#200](https://github.com/Yelp/paasta/pull/200) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.16.30](https://github.com/Yelp/paasta/tree/v0.16.30) (2016-02-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.29...v0.16.30)

## [v0.16.29](https://github.com/Yelp/paasta/tree/v0.16.29) (2016-02-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.28...v0.16.29)

**Merged pull requests:**

- Revert "Merge pull request \#190 from Yelp/mark\_for\_deployment-tags" [\#222](https://github.com/Yelp/paasta/pull/222) ([nhandler](https://github.com/nhandler))

## [v0.16.28](https://github.com/Yelp/paasta/tree/v0.16.28) (2016-02-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.27...v0.16.28)

**Merged pull requests:**

- Use json.dumps to get more consistent hash keys [\#221](https://github.com/Yelp/paasta/pull/221) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.27](https://github.com/Yelp/paasta/tree/v0.16.27) (2016-02-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.26...v0.16.27)

**Closed issues:**

- Stop Using Short GPG Key IDs [\#212](https://github.com/Yelp/paasta/issues/212)
- Cannot fetch index base URL http://pypi.yelpcorp.com/ [\#77](https://github.com/Yelp/paasta/issues/77)

**Merged pull requests:**

- Use full GPG fingerprints [\#215](https://github.com/Yelp/paasta/pull/215) ([nhandler](https://github.com/nhandler))
- Upgrade mesos to 0.23.1-0.2.61.ubuntu1404 [\#214](https://github.com/Yelp/paasta/pull/214) ([nhandler](https://github.com/nhandler))
- Catch the race between inspecting a marathon app that isn't running during a bounce. PAASTA-1721 [\#210](https://github.com/Yelp/paasta/pull/210) ([solarkennedy](https://github.com/solarkennedy))
- Gracefully handle killing a marathon task that is already dead. PAASTA-1219 [\#209](https://github.com/Yelp/paasta/pull/209) ([solarkennedy](https://github.com/solarkennedy))
- made paasta start/stop deploy-group aware [\#206](https://github.com/Yelp/paasta/pull/206) ([mjksmith](https://github.com/mjksmith))
- Inject PAASTA\_\* variables into every task [\#196](https://github.com/Yelp/paasta/pull/196) ([solarkennedy](https://github.com/solarkennedy))
- Add healthcheck\_mode to service config [\#194](https://github.com/Yelp/paasta/pull/194) ([fede1024](https://github.com/fede1024))
- Mark for deployment tags [\#190](https://github.com/Yelp/paasta/pull/190) ([nhandler](https://github.com/nhandler))

## [v0.16.26](https://github.com/Yelp/paasta/tree/v0.16.26) (2016-01-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.25...v0.16.26)

**Merged pull requests:**

- Fix regression from https://github.com/Yelp/paasta/pull/179 where we … [\#211](https://github.com/Yelp/paasta/pull/211) ([EvanKrall](https://github.com/EvanKrall))
- added deploy\_group to valid schemas for paasta check [\#207](https://github.com/Yelp/paasta/pull/207) ([mjksmith](https://github.com/mjksmith))

## [v0.16.25](https://github.com/Yelp/paasta/tree/v0.16.25) (2016-01-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.24...v0.16.25)

**Closed issues:**

- Figure out how to launch both a 'scheduled' job and 'dependent' job at the same time [\#147](https://github.com/Yelp/paasta/issues/147)

**Merged pull requests:**

- Have crossover bounce prefer killing unhealthy tasks. [\#179](https://github.com/Yelp/paasta/pull/179) ([EvanKrall](https://github.com/EvanKrall))

## [v0.16.24](https://github.com/Yelp/paasta/tree/v0.16.24) (2016-01-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.23...v0.16.24)

**Merged pull requests:**

- added support for old bugged refs/tags [\#205](https://github.com/Yelp/paasta/pull/205) ([mjksmith](https://github.com/mjksmith))
- make release no longer breaks PEP8 [\#204](https://github.com/Yelp/paasta/pull/204) ([mjksmith](https://github.com/mjksmith))
- Use acutal running tasks for marathon\_services\_running\_here\_works itest [\#203](https://github.com/Yelp/paasta/pull/203) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.23](https://github.com/Yelp/paasta/tree/v0.16.23) (2016-01-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.22...v0.16.23)

**Merged pull requests:**

- metastatus now prints an error when marathon is configured & unreachable [\#202](https://github.com/Yelp/paasta/pull/202) ([mjksmith](https://github.com/mjksmith))
- made cleanup\_chronos\_jobs send OK on sensu [\#191](https://github.com/Yelp/paasta/pull/191) ([mjksmith](https://github.com/mjksmith))
- Enabled deploy\_groups [\#177](https://github.com/Yelp/paasta/pull/177) ([mjksmith](https://github.com/mjksmith))

## [v0.16.22](https://github.com/Yelp/paasta/tree/v0.16.22) (2016-01-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.21...v0.16.22)

**Merged pull requests:**

- made cleanup\_chronos\_jobs remove all non-paasta jobs [\#201](https://github.com/Yelp/paasta/pull/201) ([mjksmith](https://github.com/mjksmith))
- skip dependent jobs if they are created before their parent [\#199](https://github.com/Yelp/paasta/pull/199) ([giuliano108](https://github.com/giuliano108))
- made cleanup\_marathon\_jobs send sensu OK events [\#198](https://github.com/Yelp/paasta/pull/198) ([mjksmith](https://github.com/mjksmith))

## [v0.16.21](https://github.com/Yelp/paasta/tree/v0.16.21) (2016-01-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.20...v0.16.21)

**Merged pull requests:**

- Actually install schemas [\#197](https://github.com/Yelp/paasta/pull/197) ([nhandler](https://github.com/nhandler))

## [v0.16.20](https://github.com/Yelp/paasta/tree/v0.16.20) (2016-01-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.19...v0.16.20)

**Merged pull requests:**

- Converts marathon's `started\_at` to the local tz [\#195](https://github.com/Yelp/paasta/pull/195) ([mjksmith](https://github.com/mjksmith))
- Remove tags chronos jobs [\#193](https://github.com/Yelp/paasta/pull/193) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.16.19](https://github.com/Yelp/paasta/tree/v0.16.19) (2016-01-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.18...v0.16.19)

**Closed issues:**

- Misleading error message with local-run -p [\#192](https://github.com/Yelp/paasta/issues/192)

## [v0.16.18](https://github.com/Yelp/paasta/tree/v0.16.18) (2016-01-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.17...v0.16.18)

**Closed issues:**

- Make 'paasta check' call 'paasta validate' [\#128](https://github.com/Yelp/paasta/issues/128)

**Merged pull requests:**

- Pick a smartstack port randomly, instead of always picking highest existing + 1. [\#189](https://github.com/Yelp/paasta/pull/189) ([EvanKrall](https://github.com/EvanKrall))
- Fixed bugs introduced in the generate deployments rebase [\#188](https://github.com/Yelp/paasta/pull/188) ([mjksmith](https://github.com/mjksmith))
- WIP: Implement 'pool': An attribute & constraint that lets you split a cluster [\#187](https://github.com/Yelp/paasta/pull/187) ([EvanKrall](https://github.com/EvanKrall))
- Make tox faster [\#186](https://github.com/Yelp/paasta/pull/186) ([EvanKrall](https://github.com/EvanKrall))
- added a HOST variable to docker containers [\#185](https://github.com/Yelp/paasta/pull/185) ([mjksmith](https://github.com/mjksmith))
- Make paasta check call validate \(Closes \#128\) [\#161](https://github.com/Yelp/paasta/pull/161) ([nhandler](https://github.com/nhandler))

## [v0.16.17](https://github.com/Yelp/paasta/tree/v0.16.17) (2016-01-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.16...v0.16.17)

**Closed issues:**

- Marathon 'bean is not valid' errors during crossover bounce cause itest failures [\#172](https://github.com/Yelp/paasta/issues/172)
- remove 'versioned' chronos jobs [\#158](https://github.com/Yelp/paasta/issues/158)

**Merged pull requests:**

- Install deps during manpages [\#183](https://github.com/Yelp/paasta/pull/183) ([asottile](https://github.com/asottile))
- chronos now gives sensu the full job id of a failed task [\#181](https://github.com/Yelp/paasta/pull/181) ([mjksmith](https://github.com/mjksmith))
- Catch the 'bean not found' error. Fixes \#172 [\#180](https://github.com/Yelp/paasta/pull/180) ([solarkennedy](https://github.com/solarkennedy))
- Add http://pre-commit.com hooks [\#175](https://github.com/Yelp/paasta/pull/175) ([asottile](https://github.com/asottile))

## [v0.16.16](https://github.com/Yelp/paasta/tree/v0.16.16) (2016-01-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.15...v0.16.16)

**Merged pull requests:**

- Fix the broken link [\#178](https://github.com/Yelp/paasta/pull/178) ([ronin13](https://github.com/ronin13))

## [v0.16.15](https://github.com/Yelp/paasta/tree/v0.16.15) (2016-01-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.14...v0.16.15)

**Closed issues:**

- deploy\_chronos\_services isn't shuffling [\#154](https://github.com/Yelp/paasta/issues/154)
- `paasta check` doesn't consider chronos-\*.yaml for deploy.yaml checks [\#110](https://github.com/Yelp/paasta/issues/110)
- Update paasta help [\#3](https://github.com/Yelp/paasta/issues/3)

**Merged pull requests:**

- Force python2.7 in other tox environments [\#176](https://github.com/Yelp/paasta/pull/176) ([asottile](https://github.com/asottile))
- fixed paasta\_metastatus -vv when there are no mesos slaves [\#174](https://github.com/Yelp/paasta/pull/174) ([mjksmith](https://github.com/mjksmith))
- Fixed formatting for very verbose paasta metastatus [\#173](https://github.com/Yelp/paasta/pull/173) ([mjksmith](https://github.com/mjksmith))
- Remove tags chronos jobs [\#171](https://github.com/Yelp/paasta/pull/171) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Remove PYTHONPATH hax when running tests [\#170](https://github.com/Yelp/paasta/pull/170) ([asottile](https://github.com/asottile))
- Pick an ephemeral port better [\#169](https://github.com/Yelp/paasta/pull/169) ([asottile](https://github.com/asottile))
- made InstanceConfig take service, cluster and instance as args [\#167](https://github.com/Yelp/paasta/pull/167) ([mjksmith](https://github.com/mjksmith))
- Added contrib location and purge\_chronos\_jobs [\#166](https://github.com/Yelp/paasta/pull/166) ([solarkennedy](https://github.com/solarkennedy))
- Add --yelpsoa-config-root argument to 'paasta check' [\#165](https://github.com/Yelp/paasta/pull/165) ([nhandler](https://github.com/nhandler))
- Allow users to set accepted\_resource\_roles in marathon yamls. [\#164](https://github.com/Yelp/paasta/pull/164) ([EvanKrall](https://github.com/EvanKrall))
- add docs for schedule time zone field [\#163](https://github.com/Yelp/paasta/pull/163) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Consider chronos\*.yaml for deploy checks \(Closes: \#110\) [\#162](https://github.com/Yelp/paasta/pull/162) ([nhandler](https://github.com/nhandler))
- Make deploy\_chronos\_services shuffle [\#160](https://github.com/Yelp/paasta/pull/160) ([nhandler](https://github.com/nhandler))
- Fixed a bug where non-smartstack services would fail to send alerts when they start failing [\#145](https://github.com/Yelp/paasta/pull/145) ([mjksmith](https://github.com/mjksmith))
- Added a script to drain and kill a marathon app as gracefully as possible [\#143](https://github.com/Yelp/paasta/pull/143) ([mjksmith](https://github.com/mjksmith))

## [v0.16.14](https://github.com/Yelp/paasta/tree/v0.16.14) (2016-01-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.13...v0.16.14)

**Closed issues:**

- setup\_chronos\_job does not clean up old jobs [\#146](https://github.com/Yelp/paasta/issues/146)
- write integration tests for launching a dependent job [\#141](https://github.com/Yelp/paasta/issues/141)
- lookup the latest full job for a 'service.instance' parent [\#140](https://github.com/Yelp/paasta/issues/140)
- theres a bogus help message in `check\_chronos\_jobs -h` [\#139](https://github.com/Yelp/paasta/issues/139)
- Update 'paasta validate' schemas to be more complete/accurate [\#129](https://github.com/Yelp/paasta/issues/129)
- paasta local-run doesn't handle chronos jobs correctly [\#124](https://github.com/Yelp/paasta/issues/124)

**Merged pull requests:**

- Run command inside sh c local run [\#159](https://github.com/Yelp/paasta/pull/159) ([nhandler](https://github.com/nhandler))
- Update itest to use chronos 2.4.0-0.1.20151007110204.ubuntu1404 [\#157](https://github.com/Yelp/paasta/pull/157) ([nhandler](https://github.com/nhandler))
- Extend schemas [\#156](https://github.com/Yelp/paasta/pull/156) ([nhandler](https://github.com/nhandler))
- remove assumptions from paasta validate tests [\#153](https://github.com/Yelp/paasta/pull/153) ([Rob-Johnson](https://github.com/Rob-Johnson))
- update the description of check\_chronos\_jobs [\#151](https://github.com/Yelp/paasta/pull/151) ([Rob-Johnson](https://github.com/Rob-Johnson))
- First support for creating dependent jobs - Fixes \#140, \#141, \#146 [\#150](https://github.com/Yelp/paasta/pull/150) ([Rob-Johnson](https://github.com/Rob-Johnson))
- fixed a testcase for utils.guess\_instance [\#144](https://github.com/Yelp/paasta/pull/144) ([mjksmith](https://github.com/mjksmith))
- Improve the human readable state of services depending on their type [\#133](https://github.com/Yelp/paasta/pull/133) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.13](https://github.com/Yelp/paasta/tree/v0.16.13) (2016-01-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.12...v0.16.13)

**Closed issues:**

- Make 'paasta validate' validate chronos files [\#127](https://github.com/Yelp/paasta/issues/127)
- Add 'paasta validate' itests [\#126](https://github.com/Yelp/paasta/issues/126)

**Merged pull requests:**

- Consolidate/tighten up filtering of marathon apps so status and bounc… [\#142](https://github.com/Yelp/paasta/pull/142) ([EvanKrall](https://github.com/EvanKrall))
- Fix local-run healthchecks when using custom soadir argument [\#138](https://github.com/Yelp/paasta/pull/138) ([keshavdv](https://github.com/keshavdv))
- Paasta validate itests [\#136](https://github.com/Yelp/paasta/pull/136) ([nhandler](https://github.com/nhandler))
- Validate chronos [\#134](https://github.com/Yelp/paasta/pull/134) ([nhandler](https://github.com/nhandler))

## [v0.16.12](https://github.com/Yelp/paasta/tree/v0.16.12) (2016-01-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.11...v0.16.12)

**Closed issues:**

- support a 'parents' field in Chronos job configuration. [\#94](https://github.com/Yelp/paasta/issues/94)
- If multiple marathon apps exist \(e.g `paasta restart` during a bounce\), crossover bounce might kill your only registered instances [\#20](https://github.com/Yelp/paasta/issues/20)

**Merged pull requests:**

- Added 0 principle [\#137](https://github.com/Yelp/paasta/pull/137) ([solarkennedy](https://github.com/solarkennedy))
- Added a --service argument to paasta check. Closes \#130 [\#132](https://github.com/Yelp/paasta/pull/132) ([solarkennedy](https://github.com/solarkennedy))
- Begin testing against marathon 11 [\#120](https://github.com/Yelp/paasta/pull/120) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.11](https://github.com/Yelp/paasta/tree/v0.16.11) (2015-12-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.10...v0.16.11)

**Closed issues:**

- paasta local-run --pull fails without --interactive [\#131](https://github.com/Yelp/paasta/issues/131)
- paasta check doesn't allow overriding of service name [\#130](https://github.com/Yelp/paasta/issues/130)

**Merged pull requests:**

- Lots of updates to help sections and therefore man pages [\#125](https://github.com/Yelp/paasta/pull/125) ([solarkennedy](https://github.com/solarkennedy))
- Fix some sys.stderr.writes that don't have their newlines [\#123](https://github.com/Yelp/paasta/pull/123) ([asottile](https://github.com/asottile))
- Add 'paasta validate' command [\#107](https://github.com/Yelp/paasta/pull/107) ([nhandler](https://github.com/nhandler))

## [v0.16.10](https://github.com/Yelp/paasta/tree/v0.16.10) (2015-12-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.9...v0.16.10)

**Merged pull requests:**

- Dependent jobs field [\#122](https://github.com/Yelp/paasta/pull/122) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Nix paasta\_cli =\> to just cli [\#121](https://github.com/Yelp/paasta/pull/121) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.9](https://github.com/Yelp/paasta/tree/v0.16.9) (2015-12-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.8...v0.16.9)

**Merged pull requests:**

- Remove extra context from replication check output for performance reasons [\#117](https://github.com/Yelp/paasta/pull/117) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.8](https://github.com/Yelp/paasta/tree/v0.16.8) (2015-12-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.7...v0.16.8)

**Merged pull requests:**

- Fix InvalidJobNameError in marathon\_services\_running\_here [\#119](https://github.com/Yelp/paasta/pull/119) ([EvanKrall](https://github.com/EvanKrall))
- Use https internal pypi [\#118](https://github.com/Yelp/paasta/pull/118) ([asottile](https://github.com/asottile))
- Autodetect the instance in local-run [\#105](https://github.com/Yelp/paasta/pull/105) ([solarkennedy](https://github.com/solarkennedy))
- Make local-run stream the docker-pull with /dev/null as stdin [\#104](https://github.com/Yelp/paasta/pull/104) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.7](https://github.com/Yelp/paasta/tree/v0.16.7) (2015-12-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.6...v0.16.7)

## [v0.16.6](https://github.com/Yelp/paasta/tree/v0.16.6) (2015-12-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.5...v0.16.6)

**Merged pull requests:**

- Bump max\_consecutive\_failures to 30 \(5 minutes\) [\#101](https://github.com/Yelp/paasta/pull/101) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.5](https://github.com/Yelp/paasta/tree/v0.16.5) (2015-12-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.4...v0.16.5)

**Merged pull requests:**

- Make backoff\_seconds work as a function of the instance count. [\#102](https://github.com/Yelp/paasta/pull/102) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.4](https://github.com/Yelp/paasta/tree/v0.16.4) (2015-12-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.3...v0.16.4)

**Closed issues:**

- paasta local-run --interactive default cmd is "b a s h" [\#115](https://github.com/Yelp/paasta/issues/115)
- paasta local-run --help crashes [\#114](https://github.com/Yelp/paasta/issues/114)
- automate builds with pypi [\#35](https://github.com/Yelp/paasta/issues/35)

**Merged pull requests:**

- Added docs explaining the difference between difference service modes [\#113](https://github.com/Yelp/paasta/pull/113) ([solarkennedy](https://github.com/solarkennedy))
- Documented the relationship between instance and nerve\_ns better [\#112](https://github.com/Yelp/paasta/pull/112) ([solarkennedy](https://github.com/solarkennedy))
- Support --version instead of version [\#109](https://github.com/Yelp/paasta/pull/109) ([asottile](https://github.com/asottile))
- Fix --help for local-run and add a test [\#108](https://github.com/Yelp/paasta/pull/108) ([asottile](https://github.com/asottile))

## [v0.16.3](https://github.com/Yelp/paasta/tree/v0.16.3) (2015-12-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.2...v0.16.3)

**Merged pull requests:**

- Setup Travis autodeploy configs [\#103](https://github.com/Yelp/paasta/pull/103) ([tomelm](https://github.com/tomelm))
- Paasta rollback now accepts none, one or a list of instances. [\#99](https://github.com/Yelp/paasta/pull/99) ([zeldinha](https://github.com/zeldinha))
- Enabled local-run to work on docker images on registries instead of building locally [\#88](https://github.com/Yelp/paasta/pull/88) ([solarkennedy](https://github.com/solarkennedy))

## [v0.16.2](https://github.com/Yelp/paasta/tree/v0.16.2) (2015-11-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.1...v0.16.2)

**Closed issues:**

- 0.16.1 Release Broke 'paasta status' [\#91](https://github.com/Yelp/paasta/issues/91)
- http://paasta.readthedocs.org/en/latest/ references y/paasta [\#57](https://github.com/Yelp/paasta/issues/57)

**Merged pull requests:**

- Fix scale condition poistion [\#100](https://github.com/Yelp/paasta/pull/100) ([dichiarafrancesco](https://github.com/dichiarafrancesco))
- remove hardcoded docker registry location [\#93](https://github.com/Yelp/paasta/pull/93) ([Rob-Johnson](https://github.com/Rob-Johnson))
- bump scribereader version in line with aed1812b917daba17a5fd8f1a0fe9b… [\#92](https://github.com/Yelp/paasta/pull/92) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Only allow the itest\_% Makefile target to run at Yelp [\#90](https://github.com/Yelp/paasta/pull/90) ([nhandler](https://github.com/nhandler))
- More smartstack.yaml docs: explanation of the top level, and moving a… [\#89](https://github.com/Yelp/paasta/pull/89) ([EvanKrall](https://github.com/EvanKrall))
- Bump scribereader requirement [\#86](https://github.com/Yelp/paasta/pull/86) ([asottile](https://github.com/asottile))

## [v0.16.1](https://github.com/Yelp/paasta/tree/v0.16.1) (2015-11-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.16.0...v0.16.1)

**Merged pull requests:**

- Minor fixups to setup.py [\#87](https://github.com/Yelp/paasta/pull/87) ([asottile](https://github.com/asottile))
- Added paasta\_rollback command [\#79](https://github.com/Yelp/paasta/pull/79) ([zeldinha](https://github.com/zeldinha))
- Add emergency scale feature [\#74](https://github.com/Yelp/paasta/pull/74) ([dichiarafrancesco](https://github.com/dichiarafrancesco))
- Make local-run default to use bash if set to be interactive [\#73](https://github.com/Yelp/paasta/pull/73) ([solarkennedy](https://github.com/solarkennedy))
- drain\_method\_params affect drain\_method, not bounce\_method. Also fix uwsgi typo. [\#58](https://github.com/Yelp/paasta/pull/58) ([EvanKrall](https://github.com/EvanKrall))
- Flesh out docs for smartstack.yaml [\#47](https://github.com/Yelp/paasta/pull/47) ([EvanKrall](https://github.com/EvanKrall))

## [v0.16.0](https://github.com/Yelp/paasta/tree/v0.16.0) (2015-11-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.9...v0.16.0)

**Merged pull requests:**

- don't use vars\(\) to check for scribereader [\#80](https://github.com/Yelp/paasta/pull/80) ([Rob-Johnson](https://github.com/Rob-Johnson))
- update dh-virtualenv location [\#78](https://github.com/Yelp/paasta/pull/78) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Update Flynn comparison [\#76](https://github.com/Yelp/paasta/pull/76) ([titanous](https://github.com/titanous))
- Added first pass at paasta-contract transplant [\#75](https://github.com/Yelp/paasta/pull/75) ([solarkennedy](https://github.com/solarkennedy))

## [v0.15.9](https://github.com/Yelp/paasta/tree/v0.15.9) (2015-11-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.8...v0.15.9)

**Merged pull requests:**

- Added automatic changelog [\#71](https://github.com/Yelp/paasta/pull/71) ([solarkennedy](https://github.com/solarkennedy))
- Use dulwich for mark for deployment [\#68](https://github.com/Yelp/paasta/pull/68) ([solarkennedy](https://github.com/solarkennedy))

## [v0.15.8](https://github.com/Yelp/paasta/tree/v0.15.8) (2015-11-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.7...v0.15.8)

## [v0.15.7](https://github.com/Yelp/paasta/tree/v0.15.7) (2015-11-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.6...v0.15.7)

**Closed issues:**

- ``paasta logs`` should fail gracefully when scribereader depedency is missing [\#63](https://github.com/Yelp/paasta/issues/63)

**Merged pull requests:**

- active\_only=True doesn't work with chronos. Let's try it with False. [\#70](https://github.com/Yelp/paasta/pull/70) ([mrtyler](https://github.com/mrtyler))
- Mrtyler rejigger status [\#69](https://github.com/Yelp/paasta/pull/69) ([mrtyler](https://github.com/mrtyler))
- execute docker pull before running container [\#67](https://github.com/Yelp/paasta/pull/67) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.15.6](https://github.com/Yelp/paasta/tree/v0.15.6) (2015-11-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/help...v0.15.6)

**Merged pull requests:**

- fail gracefully if you try and run paasta logs without scribe existing [\#66](https://github.com/Yelp/paasta/pull/66) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Some refactoring related to the argument 'clusterinstance' [\#65](https://github.com/Yelp/paasta/pull/65) ([zeldinha](https://github.com/zeldinha))

## [help](https://github.com/Yelp/paasta/tree/help) (2015-11-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.5...help)

## [v0.15.5](https://github.com/Yelp/paasta/tree/v0.15.5) (2015-11-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.4...v0.15.5)

## [v0.15.4](https://github.com/Yelp/paasta/tree/v0.15.4) (2015-11-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.3...v0.15.4)

**Closed issues:**

- Opensource some sort of Mesos -\>SmartStack \(nerve\) bridge [\#13](https://github.com/Yelp/paasta/issues/13)

**Merged pull requests:**

- Mrtyler instance filter [\#53](https://github.com/Yelp/paasta/pull/53) ([mrtyler](https://github.com/mrtyler))

## [v0.15.3](https://github.com/Yelp/paasta/tree/v0.15.3) (2015-11-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.2...v0.15.3)

**Merged pull requests:**

- add missing scribereader dependency when building internally [\#62](https://github.com/Yelp/paasta/pull/62) ([Rob-Johnson](https://github.com/Rob-Johnson))
- reject jobs with an interval more frequent than 60s [\#59](https://github.com/Yelp/paasta/pull/59) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Added reproducible principle [\#56](https://github.com/Yelp/paasta/pull/56) ([solarkennedy](https://github.com/solarkennedy))
- Add coveralls support [\#43](https://github.com/Yelp/paasta/pull/43) ([nhandler](https://github.com/nhandler))

## [v0.15.2](https://github.com/Yelp/paasta/tree/v0.15.2) (2015-11-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.1...v0.15.2)

**Merged pull requests:**

- upgrade marathon and chronos-python [\#55](https://github.com/Yelp/paasta/pull/55) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Fix typo in README [\#52](https://github.com/Yelp/paasta/pull/52) ([chriskuehl](https://github.com/chriskuehl))
- Use the right srvname [\#51](https://github.com/Yelp/paasta/pull/51) ([mrtyler](https://github.com/mrtyler))
- Added paasta principles [\#50](https://github.com/Yelp/paasta/pull/50) ([solarkennedy](https://github.com/solarkennedy))

## [v0.15.1](https://github.com/Yelp/paasta/tree/v0.15.1) (2015-11-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.15.0...v0.15.1)

**Closed issues:**

- comparison table updated against autodesk/ochopod [\#49](https://github.com/Yelp/paasta/issues/49)

**Merged pull requests:**

- fix marathon package naming in requirements.txt [\#48](https://github.com/Yelp/paasta/pull/48) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.15.0](https://github.com/Yelp/paasta/tree/v0.15.0) (2015-11-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.14.1...v0.15.0)

**Merged pull requests:**

- Fixing grammar error [\#46](https://github.com/Yelp/paasta/pull/46) ([nickrobinson](https://github.com/nickrobinson))
- Make setup\_chronos\_job handle the situation where the docker image isn't available [\#44](https://github.com/Yelp/paasta/pull/44) ([solarkennedy](https://github.com/solarkennedy))
- Run itests in travis [\#42](https://github.com/Yelp/paasta/pull/42) ([nhandler](https://github.com/nhandler))
- Bump yelp-clog to 2.2.10 [\#41](https://github.com/Yelp/paasta/pull/41) ([EvanKrall](https://github.com/EvanKrall))
- Fixup make targets [\#40](https://github.com/Yelp/paasta/pull/40) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Install tox in travis [\#39](https://github.com/Yelp/paasta/pull/39) ([nhandler](https://github.com/nhandler))
- Fix some typos in comparison.md [\#38](https://github.com/Yelp/paasta/pull/38) ([nhandler](https://github.com/nhandler))
- Add a note about our IRC channel to the README [\#37](https://github.com/Yelp/paasta/pull/37) ([nhandler](https://github.com/nhandler))
- Add initial .travis.yml [\#36](https://github.com/Yelp/paasta/pull/36) ([nhandler](https://github.com/nhandler))
- Added more words and docker swarm comparison [\#34](https://github.com/Yelp/paasta/pull/34) ([solarkennedy](https://github.com/solarkennedy))
- delete unused wizard-y code [\#33](https://github.com/Yelp/paasta/pull/33) ([mrtyler](https://github.com/mrtyler))
- Remove deps [\#32](https://github.com/Yelp/paasta/pull/32) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Sort jobs so that we really clean up old ones [\#31](https://github.com/Yelp/paasta/pull/31) ([mrtyler](https://github.com/mrtyler))
-  More comparison docs, added flynn [\#29](https://github.com/Yelp/paasta/pull/29) ([solarkennedy](https://github.com/solarkennedy))

## [v0.14.1](https://github.com/Yelp/paasta/tree/v0.14.1) (2015-11-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.11...v0.14.1)

**Closed issues:**

- paasta metastatus should only report "enabled" chronos jobs [\#25](https://github.com/Yelp/paasta/issues/25)

**Merged pull requests:**

- remove pgrp management; it doesn't work properly [\#28](https://github.com/Yelp/paasta/pull/28) ([Rob-Johnson](https://github.com/Rob-Johnson))
- only show enabled jobs in paasta metastatus + cleanup test mocks [\#27](https://github.com/Yelp/paasta/pull/27) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Make paasta code / itests pass on servers with no paasta configuration [\#26](https://github.com/Yelp/paasta/pull/26) ([solarkennedy](https://github.com/solarkennedy))
- refactor lookup\_chronos\_jobs [\#24](https://github.com/Yelp/paasta/pull/24) ([mrtyler](https://github.com/mrtyler))
- remove remove\_tag\_from\_job\_id [\#22](https://github.com/Yelp/paasta/pull/22) ([mrtyler](https://github.com/mrtyler))
- Metastatus verbose mode [\#21](https://github.com/Yelp/paasta/pull/21) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.13.11](https://github.com/Yelp/paasta/tree/v0.13.11) (2015-11-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.10...v0.13.11)

**Merged pull requests:**

- Make tab completions work in zsh [\#19](https://github.com/Yelp/paasta/pull/19) ([nhandler](https://github.com/nhandler))
- Fix more tests to work on a non yelp dev box [\#18](https://github.com/Yelp/paasta/pull/18) ([solarkennedy](https://github.com/solarkennedy))
- Remove references to internal CEP/SCF stuff [\#17](https://github.com/Yelp/paasta/pull/17) ([solarkennedy](https://github.com/solarkennedy))
- Fix chronos bouncing to properly delete chronos jobs [\#16](https://github.com/Yelp/paasta/pull/16) ([solarkennedy](https://github.com/solarkennedy))
- sorting hat [\#15](https://github.com/Yelp/paasta/pull/15) ([mrtyler](https://github.com/mrtyler))
- Consolidate dockerfiles [\#14](https://github.com/Yelp/paasta/pull/14) ([solarkennedy](https://github.com/solarkennedy))

## [v0.13.10](https://github.com/Yelp/paasta/tree/v0.13.10) (2015-11-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.9...v0.13.10)

**Merged pull requests:**

- Added first pass at getting started doc [\#12](https://github.com/Yelp/paasta/pull/12) ([solarkennedy](https://github.com/solarkennedy))
- Use a glob to only read json files out of /etc/paasta/ [\#11](https://github.com/Yelp/paasta/pull/11) ([solarkennedy](https://github.com/solarkennedy))

## [v0.13.9](https://github.com/Yelp/paasta/tree/v0.13.9) (2015-11-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.8...v0.13.9)

**Merged pull requests:**

- Added changes to remove blacklisted locations from the GROUP\_BY value [\#8](https://github.com/Yelp/paasta/pull/8) ([davenonne](https://github.com/davenonne))

## [v0.13.8](https://github.com/Yelp/paasta/tree/v0.13.8) (2015-10-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.7...v0.13.8)

**Merged pull requests:**

- distribute the check\_chronos\_jobs script properly [\#10](https://github.com/Yelp/paasta/pull/10) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Redo the chronos bounce code to be easier to read and actually clean up old jobs [\#7](https://github.com/Yelp/paasta/pull/7) ([solarkennedy](https://github.com/solarkennedy))

## [v0.13.7](https://github.com/Yelp/paasta/tree/v0.13.7) (2015-10-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.6...v0.13.7)

**Merged pull requests:**

- Update chronos\_serviceinit to use LastRunState [\#5](https://github.com/Yelp/paasta/pull/5) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.13.6](https://github.com/Yelp/paasta/tree/v0.13.6) (2015-10-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.5...v0.13.6)

**Merged pull requests:**

- Ensure chronos jobs have docker credentials to pull from the private registry [\#4](https://github.com/Yelp/paasta/pull/4) ([solarkennedy](https://github.com/solarkennedy))

## [v0.13.5](https://github.com/Yelp/paasta/tree/v0.13.5) (2015-10-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.4...v0.13.5)

**Merged pull requests:**

- Catching keyboard interrupt during cook-image build [\#2](https://github.com/Yelp/paasta/pull/2) ([zeldinha](https://github.com/zeldinha))

## [v0.13.4](https://github.com/Yelp/paasta/tree/v0.13.4) (2015-10-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.3...v0.13.4)

## [v0.13.3](https://github.com/Yelp/paasta/tree/v0.13.3) (2015-10-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.2...v0.13.3)

**Merged pull requests:**

- add check\_chronos\_jobs script [\#1](https://github.com/Yelp/paasta/pull/1) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [v0.13.2](https://github.com/Yelp/paasta/tree/v0.13.2) (2015-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.13.1...v0.13.2)

## [v0.13.1](https://github.com/Yelp/paasta/tree/v0.13.1) (2015-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.99...v0.13.1)

## [v0.12.99](https://github.com/Yelp/paasta/tree/v0.12.99) (2015-10-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.98...v0.12.99)

## [v0.12.98](https://github.com/Yelp/paasta/tree/v0.12.98) (2015-10-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.97...v0.12.98)

## [v0.12.97](https://github.com/Yelp/paasta/tree/v0.12.97) (2015-10-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.96...v0.12.97)

## [v0.12.96](https://github.com/Yelp/paasta/tree/v0.12.96) (2015-10-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.95...v0.12.96)

## [v0.12.95](https://github.com/Yelp/paasta/tree/v0.12.95) (2015-10-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.94...v0.12.95)

## [v0.12.94](https://github.com/Yelp/paasta/tree/v0.12.94) (2015-10-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.93...v0.12.94)

## [v0.12.93](https://github.com/Yelp/paasta/tree/v0.12.93) (2015-10-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.92...v0.12.93)

## [v0.12.92](https://github.com/Yelp/paasta/tree/v0.12.92) (2015-10-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.91...v0.12.92)

## [v0.12.91](https://github.com/Yelp/paasta/tree/v0.12.91) (2015-10-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.90...v0.12.91)

## [v0.12.90](https://github.com/Yelp/paasta/tree/v0.12.90) (2015-10-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.89...v0.12.90)

## [v0.12.89](https://github.com/Yelp/paasta/tree/v0.12.89) (2015-10-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.88...v0.12.89)

## [v0.12.88](https://github.com/Yelp/paasta/tree/v0.12.88) (2015-10-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.87...v0.12.88)

## [v0.12.87](https://github.com/Yelp/paasta/tree/v0.12.87) (2015-09-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.86...v0.12.87)

## [v0.12.86](https://github.com/Yelp/paasta/tree/v0.12.86) (2015-09-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.85...v0.12.86)

## [v0.12.85](https://github.com/Yelp/paasta/tree/v0.12.85) (2015-09-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.84...v0.12.85)

## [v0.12.84](https://github.com/Yelp/paasta/tree/v0.12.84) (2015-09-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.82...v0.12.84)

## [v0.12.82](https://github.com/Yelp/paasta/tree/v0.12.82) (2015-09-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.81...v0.12.82)

## [v0.12.81](https://github.com/Yelp/paasta/tree/v0.12.81) (2015-09-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.80...v0.12.81)

## [v0.12.80](https://github.com/Yelp/paasta/tree/v0.12.80) (2015-09-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.79...v0.12.80)

## [v0.12.79](https://github.com/Yelp/paasta/tree/v0.12.79) (2015-09-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.78...v0.12.79)

## [v0.12.78](https://github.com/Yelp/paasta/tree/v0.12.78) (2015-09-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.77...v0.12.78)

## [v0.12.77](https://github.com/Yelp/paasta/tree/v0.12.77) (2015-09-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.76...v0.12.77)

## [v0.12.76](https://github.com/Yelp/paasta/tree/v0.12.76) (2015-09-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.75...v0.12.76)

## [v0.12.75](https://github.com/Yelp/paasta/tree/v0.12.75) (2015-09-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.73...v0.12.75)

## [v0.12.73](https://github.com/Yelp/paasta/tree/v0.12.73) (2015-09-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.72...v0.12.73)

## [v0.12.72](https://github.com/Yelp/paasta/tree/v0.12.72) (2015-09-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.71...v0.12.72)

## [v0.12.71](https://github.com/Yelp/paasta/tree/v0.12.71) (2015-09-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.70...v0.12.71)

## [v0.12.70](https://github.com/Yelp/paasta/tree/v0.12.70) (2015-09-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.69...v0.12.70)

## [v0.12.69](https://github.com/Yelp/paasta/tree/v0.12.69) (2015-09-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.68...v0.12.69)

## [v0.12.68](https://github.com/Yelp/paasta/tree/v0.12.68) (2015-09-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.67...v0.12.68)

## [v0.12.67](https://github.com/Yelp/paasta/tree/v0.12.67) (2015-09-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.66...v0.12.67)

## [v0.12.66](https://github.com/Yelp/paasta/tree/v0.12.66) (2015-09-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.65...v0.12.66)

## [v0.12.65](https://github.com/Yelp/paasta/tree/v0.12.65) (2015-09-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.64...v0.12.65)

## [v0.12.64](https://github.com/Yelp/paasta/tree/v0.12.64) (2015-09-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.63...v0.12.64)

## [v0.12.63](https://github.com/Yelp/paasta/tree/v0.12.63) (2015-09-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.62...v0.12.63)

## [v0.12.62](https://github.com/Yelp/paasta/tree/v0.12.62) (2015-08-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.61...v0.12.62)

## [v0.12.61](https://github.com/Yelp/paasta/tree/v0.12.61) (2015-08-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.60...v0.12.61)

## [v0.12.60](https://github.com/Yelp/paasta/tree/v0.12.60) (2015-08-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.59...v0.12.60)

## [v0.12.59](https://github.com/Yelp/paasta/tree/v0.12.59) (2015-08-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.58...v0.12.59)

## [v0.12.58](https://github.com/Yelp/paasta/tree/v0.12.58) (2015-08-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.57...v0.12.58)

## [v0.12.57](https://github.com/Yelp/paasta/tree/v0.12.57) (2015-08-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.56...v0.12.57)

## [v0.12.56](https://github.com/Yelp/paasta/tree/v0.12.56) (2015-08-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.55...v0.12.56)

## [v0.12.55](https://github.com/Yelp/paasta/tree/v0.12.55) (2015-08-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.54...v0.12.55)

## [v0.12.54](https://github.com/Yelp/paasta/tree/v0.12.54) (2015-08-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.53...v0.12.54)

## [v0.12.53](https://github.com/Yelp/paasta/tree/v0.12.53) (2015-08-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.52...v0.12.53)

## [v0.12.52](https://github.com/Yelp/paasta/tree/v0.12.52) (2015-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.51...v0.12.52)

## [v0.12.51](https://github.com/Yelp/paasta/tree/v0.12.51) (2015-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.50...v0.12.51)

## [v0.12.50](https://github.com/Yelp/paasta/tree/v0.12.50) (2015-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.49...v0.12.50)

## [v0.12.49](https://github.com/Yelp/paasta/tree/v0.12.49) (2015-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.48...v0.12.49)

## [v0.12.48](https://github.com/Yelp/paasta/tree/v0.12.48) (2015-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.47...v0.12.48)

## [v0.12.47](https://github.com/Yelp/paasta/tree/v0.12.47) (2015-08-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.46...v0.12.47)

## [v0.12.46](https://github.com/Yelp/paasta/tree/v0.12.46) (2015-08-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.45...v0.12.46)

## [v0.12.45](https://github.com/Yelp/paasta/tree/v0.12.45) (2015-08-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.44...v0.12.45)

## [v0.12.44](https://github.com/Yelp/paasta/tree/v0.12.44) (2015-08-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.43...v0.12.44)

## [v0.12.43](https://github.com/Yelp/paasta/tree/v0.12.43) (2015-08-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.42...v0.12.43)

## [v0.12.42](https://github.com/Yelp/paasta/tree/v0.12.42) (2015-07-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.41...v0.12.42)

## [v0.12.41](https://github.com/Yelp/paasta/tree/v0.12.41) (2015-07-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.40...v0.12.41)

## [v0.12.40](https://github.com/Yelp/paasta/tree/v0.12.40) (2015-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.39...v0.12.40)

## [v0.12.39](https://github.com/Yelp/paasta/tree/v0.12.39) (2015-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.38...v0.12.39)

## [v0.12.38](https://github.com/Yelp/paasta/tree/v0.12.38) (2015-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.37...v0.12.38)

## [v0.12.37](https://github.com/Yelp/paasta/tree/v0.12.37) (2015-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.36...v0.12.37)

## [v0.12.36](https://github.com/Yelp/paasta/tree/v0.12.36) (2015-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.35...v0.12.36)

## [v0.12.35](https://github.com/Yelp/paasta/tree/v0.12.35) (2015-07-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.34...v0.12.35)

## [v0.12.34](https://github.com/Yelp/paasta/tree/v0.12.34) (2015-07-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.33...v0.12.34)

## [v0.12.33](https://github.com/Yelp/paasta/tree/v0.12.33) (2015-07-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.32...v0.12.33)

## [v0.12.32](https://github.com/Yelp/paasta/tree/v0.12.32) (2015-07-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.31...v0.12.32)

## [v0.12.31](https://github.com/Yelp/paasta/tree/v0.12.31) (2015-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.30...v0.12.31)

## [v0.12.30](https://github.com/Yelp/paasta/tree/v0.12.30) (2015-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.29...v0.12.30)

## [v0.12.29](https://github.com/Yelp/paasta/tree/v0.12.29) (2015-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.28...v0.12.29)

## [v0.12.28](https://github.com/Yelp/paasta/tree/v0.12.28) (2015-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.27...v0.12.28)

## [v0.12.27](https://github.com/Yelp/paasta/tree/v0.12.27) (2015-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.26...v0.12.27)

## [v0.12.26](https://github.com/Yelp/paasta/tree/v0.12.26) (2015-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.25...v0.12.26)

## [v0.12.25](https://github.com/Yelp/paasta/tree/v0.12.25) (2015-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.24...v0.12.25)

## [v0.12.24](https://github.com/Yelp/paasta/tree/v0.12.24) (2015-07-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.23...v0.12.24)

## [v0.12.23](https://github.com/Yelp/paasta/tree/v0.12.23) (2015-07-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.22...v0.12.23)

## [v0.12.22](https://github.com/Yelp/paasta/tree/v0.12.22) (2015-07-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.21...v0.12.22)

## [v0.12.21](https://github.com/Yelp/paasta/tree/v0.12.21) (2015-07-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.20...v0.12.21)

## [v0.12.20](https://github.com/Yelp/paasta/tree/v0.12.20) (2015-07-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.19...v0.12.20)

## [v0.12.19](https://github.com/Yelp/paasta/tree/v0.12.19) (2015-07-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.18...v0.12.19)

## [v0.12.18](https://github.com/Yelp/paasta/tree/v0.12.18) (2015-07-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.17...v0.12.18)

## [v0.12.17](https://github.com/Yelp/paasta/tree/v0.12.17) (2015-07-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.16...v0.12.17)

## [v0.12.16](https://github.com/Yelp/paasta/tree/v0.12.16) (2015-07-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.15...v0.12.16)

## [v0.12.15](https://github.com/Yelp/paasta/tree/v0.12.15) (2015-07-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.14...v0.12.15)

## [v0.12.14](https://github.com/Yelp/paasta/tree/v0.12.14) (2015-07-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.13...v0.12.14)

## [v0.12.13](https://github.com/Yelp/paasta/tree/v0.12.13) (2015-07-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.12...v0.12.13)

## [v0.12.12](https://github.com/Yelp/paasta/tree/v0.12.12) (2015-07-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.11...v0.12.12)

## [v0.12.11](https://github.com/Yelp/paasta/tree/v0.12.11) (2015-07-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.10...v0.12.11)

## [v0.12.10](https://github.com/Yelp/paasta/tree/v0.12.10) (2015-07-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.9...v0.12.10)

## [v0.12.9](https://github.com/Yelp/paasta/tree/v0.12.9) (2015-07-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.8...v0.12.9)

## [v0.12.8](https://github.com/Yelp/paasta/tree/v0.12.8) (2015-07-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.7...v0.12.8)

## [v0.12.7](https://github.com/Yelp/paasta/tree/v0.12.7) (2015-07-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.6...v0.12.7)

## [v0.12.6](https://github.com/Yelp/paasta/tree/v0.12.6) (2015-07-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.5...v0.12.6)

## [v0.12.5](https://github.com/Yelp/paasta/tree/v0.12.5) (2015-06-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.4...v0.12.5)

## [v0.12.4](https://github.com/Yelp/paasta/tree/v0.12.4) (2015-06-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.3...v0.12.4)

## [v0.12.3](https://github.com/Yelp/paasta/tree/v0.12.3) (2015-06-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.2...v0.12.3)

## [v0.12.2](https://github.com/Yelp/paasta/tree/v0.12.2) (2015-06-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.12.1...v0.12.2)

## [v0.12.1](https://github.com/Yelp/paasta/tree/v0.12.1) (2015-06-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.24...v0.12.1)

## [v0.11.24](https://github.com/Yelp/paasta/tree/v0.11.24) (2015-06-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.23...v0.11.24)

## [v0.11.23](https://github.com/Yelp/paasta/tree/v0.11.23) (2015-06-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.22...v0.11.23)

## [v0.11.22](https://github.com/Yelp/paasta/tree/v0.11.22) (2015-06-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.21...v0.11.22)

## [v0.11.21](https://github.com/Yelp/paasta/tree/v0.11.21) (2015-06-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.20...v0.11.21)

## [v0.11.20](https://github.com/Yelp/paasta/tree/v0.11.20) (2015-06-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.19...v0.11.20)

## [v0.11.19](https://github.com/Yelp/paasta/tree/v0.11.19) (2015-06-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.18...v0.11.19)

## [v0.11.18](https://github.com/Yelp/paasta/tree/v0.11.18) (2015-06-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.17...v0.11.18)

## [v0.11.17](https://github.com/Yelp/paasta/tree/v0.11.17) (2015-06-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.16...v0.11.17)

## [v0.11.16](https://github.com/Yelp/paasta/tree/v0.11.16) (2015-06-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.15...v0.11.16)

## [v0.11.15](https://github.com/Yelp/paasta/tree/v0.11.15) (2015-06-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.14...v0.11.15)

## [v0.11.14](https://github.com/Yelp/paasta/tree/v0.11.14) (2015-06-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.13...v0.11.14)

## [v0.11.13](https://github.com/Yelp/paasta/tree/v0.11.13) (2015-06-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.12...v0.11.13)

## [v0.11.12](https://github.com/Yelp/paasta/tree/v0.11.12) (2015-06-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.11...v0.11.12)

## [v0.11.11](https://github.com/Yelp/paasta/tree/v0.11.11) (2015-06-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.10...v0.11.11)

## [v0.11.10](https://github.com/Yelp/paasta/tree/v0.11.10) (2015-06-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.9...v0.11.10)

## [v0.11.9](https://github.com/Yelp/paasta/tree/v0.11.9) (2015-06-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.8...v0.11.9)

## [v0.11.8](https://github.com/Yelp/paasta/tree/v0.11.8) (2015-06-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.7...v0.11.8)

## [v0.11.7](https://github.com/Yelp/paasta/tree/v0.11.7) (2015-06-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.6...v0.11.7)

## [v0.11.6](https://github.com/Yelp/paasta/tree/v0.11.6) (2015-06-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.5...v0.11.6)

## [v0.11.5](https://github.com/Yelp/paasta/tree/v0.11.5) (2015-06-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.4...v0.11.5)

## [v0.11.4](https://github.com/Yelp/paasta/tree/v0.11.4) (2015-06-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.3...v0.11.4)

## [v0.11.3](https://github.com/Yelp/paasta/tree/v0.11.3) (2015-06-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.2...v0.11.3)

## [v0.11.2](https://github.com/Yelp/paasta/tree/v0.11.2) (2015-06-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.1...v0.11.2)

## [v0.11.1](https://github.com/Yelp/paasta/tree/v0.11.1) (2015-05-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.11.0...v0.11.1)

## [v0.11.0](https://github.com/Yelp/paasta/tree/v0.11.0) (2015-05-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.10.4...v0.11.0)

## [v0.10.4](https://github.com/Yelp/paasta/tree/v0.10.4) (2015-05-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.10.3...v0.10.4)

## [v0.10.3](https://github.com/Yelp/paasta/tree/v0.10.3) (2015-05-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.10.2...v0.10.3)

## [v0.10.2](https://github.com/Yelp/paasta/tree/v0.10.2) (2015-05-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.10.1...v0.10.2)

## [v0.10.1](https://github.com/Yelp/paasta/tree/v0.10.1) (2015-05-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.73...v0.10.1)

## [v0.9.73](https://github.com/Yelp/paasta/tree/v0.9.73) (2015-05-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.72...v0.9.73)

## [v0.9.72](https://github.com/Yelp/paasta/tree/v0.9.72) (2015-05-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.71...v0.9.72)

## [v0.9.71](https://github.com/Yelp/paasta/tree/v0.9.71) (2015-05-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.70...v0.9.71)

## [v0.9.70](https://github.com/Yelp/paasta/tree/v0.9.70) (2015-05-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.69...v0.9.70)

## [v0.9.69](https://github.com/Yelp/paasta/tree/v0.9.69) (2015-05-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.68...v0.9.69)

## [v0.9.68](https://github.com/Yelp/paasta/tree/v0.9.68) (2015-05-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.67...v0.9.68)

## [v0.9.67](https://github.com/Yelp/paasta/tree/v0.9.67) (2015-05-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.66...v0.9.67)

## [v0.9.66](https://github.com/Yelp/paasta/tree/v0.9.66) (2015-05-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.65...v0.9.66)

## [v0.9.65](https://github.com/Yelp/paasta/tree/v0.9.65) (2015-05-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.64...v0.9.65)

## [v0.9.64](https://github.com/Yelp/paasta/tree/v0.9.64) (2015-05-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.63...v0.9.64)

## [v0.9.63](https://github.com/Yelp/paasta/tree/v0.9.63) (2015-05-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.62...v0.9.63)

## [v0.9.62](https://github.com/Yelp/paasta/tree/v0.9.62) (2015-05-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.61...v0.9.62)

## [v0.9.61](https://github.com/Yelp/paasta/tree/v0.9.61) (2015-05-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.60...v0.9.61)

## [v0.9.60](https://github.com/Yelp/paasta/tree/v0.9.60) (2015-05-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.59...v0.9.60)

## [v0.9.59](https://github.com/Yelp/paasta/tree/v0.9.59) (2015-05-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.58...v0.9.59)

## [v0.9.58](https://github.com/Yelp/paasta/tree/v0.9.58) (2015-05-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.57...v0.9.58)

## [v0.9.57](https://github.com/Yelp/paasta/tree/v0.9.57) (2015-05-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.56...v0.9.57)

## [v0.9.56](https://github.com/Yelp/paasta/tree/v0.9.56) (2015-05-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.55...v0.9.56)

## [v0.9.55](https://github.com/Yelp/paasta/tree/v0.9.55) (2015-05-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.54...v0.9.55)

## [v0.9.54](https://github.com/Yelp/paasta/tree/v0.9.54) (2015-05-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.53...v0.9.54)

## [v0.9.53](https://github.com/Yelp/paasta/tree/v0.9.53) (2015-04-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.52...v0.9.53)

## [v0.9.52](https://github.com/Yelp/paasta/tree/v0.9.52) (2015-04-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.51...v0.9.52)

## [v0.9.51](https://github.com/Yelp/paasta/tree/v0.9.51) (2015-04-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.50...v0.9.51)

## [v0.9.50](https://github.com/Yelp/paasta/tree/v0.9.50) (2015-04-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.49...v0.9.50)

## [v0.9.49](https://github.com/Yelp/paasta/tree/v0.9.49) (2015-04-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.48...v0.9.49)

## [v0.9.48](https://github.com/Yelp/paasta/tree/v0.9.48) (2015-04-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.47...v0.9.48)

## [v0.9.47](https://github.com/Yelp/paasta/tree/v0.9.47) (2015-04-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.46...v0.9.47)

## [v0.9.46](https://github.com/Yelp/paasta/tree/v0.9.46) (2015-04-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.45...v0.9.46)

## [v0.9.45](https://github.com/Yelp/paasta/tree/v0.9.45) (2015-04-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.44...v0.9.45)

## [v0.9.44](https://github.com/Yelp/paasta/tree/v0.9.44) (2015-04-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.43...v0.9.44)

## [v0.9.43](https://github.com/Yelp/paasta/tree/v0.9.43) (2015-04-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.42...v0.9.43)

## [v0.9.42](https://github.com/Yelp/paasta/tree/v0.9.42) (2015-04-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.41...v0.9.42)

## [v0.9.41](https://github.com/Yelp/paasta/tree/v0.9.41) (2015-03-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.40...v0.9.41)

## [v0.9.40](https://github.com/Yelp/paasta/tree/v0.9.40) (2015-03-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.38...v0.9.40)

## [v0.9.38](https://github.com/Yelp/paasta/tree/v0.9.38) (2015-03-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.37...v0.9.38)

## [v0.9.37](https://github.com/Yelp/paasta/tree/v0.9.37) (2015-03-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.36...v0.9.37)

## [v0.9.36](https://github.com/Yelp/paasta/tree/v0.9.36) (2015-03-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.35...v0.9.36)

## [v0.9.35](https://github.com/Yelp/paasta/tree/v0.9.35) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.34...v0.9.35)

## [v0.9.34](https://github.com/Yelp/paasta/tree/v0.9.34) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.33...v0.9.34)

## [v0.9.33](https://github.com/Yelp/paasta/tree/v0.9.33) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.32...v0.9.33)

## [v0.9.32](https://github.com/Yelp/paasta/tree/v0.9.32) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.31...v0.9.32)

## [v0.9.31](https://github.com/Yelp/paasta/tree/v0.9.31) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.30...v0.9.31)

## [v0.9.30](https://github.com/Yelp/paasta/tree/v0.9.30) (2015-03-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.29...v0.9.30)

## [v0.9.29](https://github.com/Yelp/paasta/tree/v0.9.29) (2015-03-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.28...v0.9.29)

## [v0.9.28](https://github.com/Yelp/paasta/tree/v0.9.28) (2015-03-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.27...v0.9.28)

## [v0.9.27](https://github.com/Yelp/paasta/tree/v0.9.27) (2015-03-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.26...v0.9.27)

## [v0.9.26](https://github.com/Yelp/paasta/tree/v0.9.26) (2015-03-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.24...v0.9.26)

## [v0.9.24](https://github.com/Yelp/paasta/tree/v0.9.24) (2015-03-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.23...v0.9.24)

## [v0.9.23](https://github.com/Yelp/paasta/tree/v0.9.23) (2015-03-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.22...v0.9.23)

## [v0.9.22](https://github.com/Yelp/paasta/tree/v0.9.22) (2015-03-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.21...v0.9.22)

## [v0.9.21](https://github.com/Yelp/paasta/tree/v0.9.21) (2015-03-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.20...v0.9.21)

## [v0.9.20](https://github.com/Yelp/paasta/tree/v0.9.20) (2015-03-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.19...v0.9.20)

## [v0.9.19](https://github.com/Yelp/paasta/tree/v0.9.19) (2015-03-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.18...v0.9.19)

## [v0.9.18](https://github.com/Yelp/paasta/tree/v0.9.18) (2015-03-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.17...v0.9.18)

## [v0.9.17](https://github.com/Yelp/paasta/tree/v0.9.17) (2015-03-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.16...v0.9.17)

## [v0.9.16](https://github.com/Yelp/paasta/tree/v0.9.16) (2015-03-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.15...v0.9.16)

## [v0.9.15](https://github.com/Yelp/paasta/tree/v0.9.15) (2015-03-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.14...v0.9.15)

## [v0.9.14](https://github.com/Yelp/paasta/tree/v0.9.14) (2015-03-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.13...v0.9.14)

## [v0.9.13](https://github.com/Yelp/paasta/tree/v0.9.13) (2015-03-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.12...v0.9.13)

## [v0.9.12](https://github.com/Yelp/paasta/tree/v0.9.12) (2015-03-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.11...v0.9.12)

## [v0.9.11](https://github.com/Yelp/paasta/tree/v0.9.11) (2015-03-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.9...v0.9.11)

## [v0.9.9](https://github.com/Yelp/paasta/tree/v0.9.9) (2015-02-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.8...v0.9.9)

## [v0.9.8](https://github.com/Yelp/paasta/tree/v0.9.8) (2015-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.7...v0.9.8)

## [v0.9.7](https://github.com/Yelp/paasta/tree/v0.9.7) (2015-02-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.6...v0.9.7)

## [v0.9.6](https://github.com/Yelp/paasta/tree/v0.9.6) (2015-02-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.5...v0.9.6)

## [v0.9.5](https://github.com/Yelp/paasta/tree/v0.9.5) (2015-02-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.4...v0.9.5)

## [v0.9.4](https://github.com/Yelp/paasta/tree/v0.9.4) (2015-02-20)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.3...v0.9.4)

## [v0.9.3](https://github.com/Yelp/paasta/tree/v0.9.3) (2015-02-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.2...v0.9.3)

## [v0.9.2](https://github.com/Yelp/paasta/tree/v0.9.2) (2015-02-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.1...v0.9.2)

## [v0.9.1](https://github.com/Yelp/paasta/tree/v0.9.1) (2015-02-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.9.0...v0.9.1)

## [v0.9.0](https://github.com/Yelp/paasta/tree/v0.9.0) (2015-02-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.36...v0.9.0)

## [v0.8.36](https://github.com/Yelp/paasta/tree/v0.8.36) (2015-02-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.35...v0.8.36)

## [v0.8.35](https://github.com/Yelp/paasta/tree/v0.8.35) (2015-02-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.34...v0.8.35)

## [v0.8.34](https://github.com/Yelp/paasta/tree/v0.8.34) (2015-02-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.33...v0.8.34)

## [v0.8.33](https://github.com/Yelp/paasta/tree/v0.8.33) (2015-02-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.32...v0.8.33)

## [v0.8.32](https://github.com/Yelp/paasta/tree/v0.8.32) (2015-02-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.31...v0.8.32)

## [v0.8.31](https://github.com/Yelp/paasta/tree/v0.8.31) (2015-02-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.30...v0.8.31)

## [v0.8.30](https://github.com/Yelp/paasta/tree/v0.8.30) (2015-02-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.29...v0.8.30)

## [v0.8.29](https://github.com/Yelp/paasta/tree/v0.8.29) (2015-02-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.28...v0.8.29)

## [v0.8.28](https://github.com/Yelp/paasta/tree/v0.8.28) (2015-02-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.27...v0.8.28)

## [v0.8.27](https://github.com/Yelp/paasta/tree/v0.8.27) (2015-02-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.26...v0.8.27)

## [v0.8.26](https://github.com/Yelp/paasta/tree/v0.8.26) (2015-02-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.25...v0.8.26)

## [v0.8.25](https://github.com/Yelp/paasta/tree/v0.8.25) (2015-02-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.24...v0.8.25)

## [v0.8.24](https://github.com/Yelp/paasta/tree/v0.8.24) (2015-02-03)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.23...v0.8.24)

## [v0.8.23](https://github.com/Yelp/paasta/tree/v0.8.23) (2015-02-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.22...v0.8.23)

## [v0.8.22](https://github.com/Yelp/paasta/tree/v0.8.22) (2015-01-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.21...v0.8.22)

## [v0.8.21](https://github.com/Yelp/paasta/tree/v0.8.21) (2015-01-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.20...v0.8.21)

## [v0.8.20](https://github.com/Yelp/paasta/tree/v0.8.20) (2015-01-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.19...v0.8.20)

## [v0.8.19](https://github.com/Yelp/paasta/tree/v0.8.19) (2015-01-27)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.18...v0.8.19)

## [v0.8.18](https://github.com/Yelp/paasta/tree/v0.8.18) (2015-01-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.17...v0.8.18)

## [v0.8.17](https://github.com/Yelp/paasta/tree/v0.8.17) (2015-01-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.16...v0.8.17)

## [v0.8.16](https://github.com/Yelp/paasta/tree/v0.8.16) (2015-01-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.15...v0.8.16)

## [v0.8.15](https://github.com/Yelp/paasta/tree/v0.8.15) (2015-01-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.14...v0.8.15)

## [v0.8.14](https://github.com/Yelp/paasta/tree/v0.8.14) (2015-01-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.13...v0.8.14)

## [v0.8.13](https://github.com/Yelp/paasta/tree/v0.8.13) (2015-01-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.12...v0.8.13)

## [v0.8.12](https://github.com/Yelp/paasta/tree/v0.8.12) (2015-01-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.11...v0.8.12)

## [v0.8.11](https://github.com/Yelp/paasta/tree/v0.8.11) (2015-01-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.0.1...v0.8.11)

## [v0.0.1](https://github.com/Yelp/paasta/tree/v0.0.1) (2015-01-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.10...v0.0.1)

## [v0.8.10](https://github.com/Yelp/paasta/tree/v0.8.10) (2015-01-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.9...v0.8.10)

## [v0.8.9](https://github.com/Yelp/paasta/tree/v0.8.9) (2015-01-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.8...v0.8.9)

## [v0.8.8](https://github.com/Yelp/paasta/tree/v0.8.8) (2015-01-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.7...v0.8.8)

## [v0.8.7](https://github.com/Yelp/paasta/tree/v0.8.7) (2015-01-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.6...v0.8.7)

## [v0.8.6](https://github.com/Yelp/paasta/tree/v0.8.6) (2015-01-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.5...v0.8.6)

## [v0.8.5](https://github.com/Yelp/paasta/tree/v0.8.5) (2015-01-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.4...v0.8.5)

## [v0.8.4](https://github.com/Yelp/paasta/tree/v0.8.4) (2015-01-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.3...v0.8.4)

## [v0.8.3](https://github.com/Yelp/paasta/tree/v0.8.3) (2015-01-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.2...v0.8.3)

## [v0.8.2](https://github.com/Yelp/paasta/tree/v0.8.2) (2015-01-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.1...v0.8.2)

## [v0.8.1](https://github.com/Yelp/paasta/tree/v0.8.1) (2015-01-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.8.0...v0.8.1)

## [v0.8.0](https://github.com/Yelp/paasta/tree/v0.8.0) (2015-01-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.40...v0.8.0)

## [v0.7.40](https://github.com/Yelp/paasta/tree/v0.7.40) (2015-01-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.39...v0.7.40)

## [v0.7.39](https://github.com/Yelp/paasta/tree/v0.7.39) (2015-01-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.38...v0.7.39)

## [v0.7.38](https://github.com/Yelp/paasta/tree/v0.7.38) (2015-01-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.37...v0.7.38)

## [v0.7.37](https://github.com/Yelp/paasta/tree/v0.7.37) (2015-01-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.36...v0.7.37)

## [v0.7.36](https://github.com/Yelp/paasta/tree/v0.7.36) (2015-01-06)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.35...v0.7.36)

## [v0.7.35](https://github.com/Yelp/paasta/tree/v0.7.35) (2015-01-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.34...v0.7.35)

## [v0.7.34](https://github.com/Yelp/paasta/tree/v0.7.34) (2014-12-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.33...v0.7.34)

## [v0.7.33](https://github.com/Yelp/paasta/tree/v0.7.33) (2014-12-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.32...v0.7.33)

## [v0.7.32](https://github.com/Yelp/paasta/tree/v0.7.32) (2014-12-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.31...v0.7.32)

## [v0.7.31](https://github.com/Yelp/paasta/tree/v0.7.31) (2014-12-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.30...v0.7.31)

## [v0.7.30](https://github.com/Yelp/paasta/tree/v0.7.30) (2014-12-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.29...v0.7.30)

## [v0.7.29](https://github.com/Yelp/paasta/tree/v0.7.29) (2014-12-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.28...v0.7.29)

## [v0.7.28](https://github.com/Yelp/paasta/tree/v0.7.28) (2014-12-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.27...v0.7.28)

## [v0.7.27](https://github.com/Yelp/paasta/tree/v0.7.27) (2014-12-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.25...v0.7.27)

## [v0.7.25](https://github.com/Yelp/paasta/tree/v0.7.25) (2014-12-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.23...v0.7.25)

## [v0.7.23](https://github.com/Yelp/paasta/tree/v0.7.23) (2014-12-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.22...v0.7.23)

## [v0.7.22](https://github.com/Yelp/paasta/tree/v0.7.22) (2014-12-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.21...v0.7.22)

## [v0.7.21](https://github.com/Yelp/paasta/tree/v0.7.21) (2014-12-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.20...v0.7.21)

## [v0.7.20](https://github.com/Yelp/paasta/tree/v0.7.20) (2014-12-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.19...v0.7.20)

## [v0.7.19](https://github.com/Yelp/paasta/tree/v0.7.19) (2014-12-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.18...v0.7.19)

## [v0.7.18](https://github.com/Yelp/paasta/tree/v0.7.18) (2014-12-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.17...v0.7.18)

## [v0.7.17](https://github.com/Yelp/paasta/tree/v0.7.17) (2014-12-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.16...v0.7.17)

## [v0.7.16](https://github.com/Yelp/paasta/tree/v0.7.16) (2014-12-11)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.15...v0.7.16)

## [v0.7.15](https://github.com/Yelp/paasta/tree/v0.7.15) (2014-12-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.14...v0.7.15)

## [v0.7.14](https://github.com/Yelp/paasta/tree/v0.7.14) (2014-12-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.13...v0.7.14)

## [v0.7.13](https://github.com/Yelp/paasta/tree/v0.7.13) (2014-12-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.11...v0.7.13)

## [v0.7.11](https://github.com/Yelp/paasta/tree/v0.7.11) (2014-12-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.10...v0.7.11)

## [v0.7.10](https://github.com/Yelp/paasta/tree/v0.7.10) (2014-12-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.9...v0.7.10)

## [v0.7.9](https://github.com/Yelp/paasta/tree/v0.7.9) (2014-12-05)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.8...v0.7.9)

## [v0.7.8](https://github.com/Yelp/paasta/tree/v0.7.8) (2014-12-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.7...v0.7.8)

## [v0.7.7](https://github.com/Yelp/paasta/tree/v0.7.7) (2014-12-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.6...v0.7.7)

## [v0.7.6](https://github.com/Yelp/paasta/tree/v0.7.6) (2014-12-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.5...v0.7.6)

## [v0.7.5](https://github.com/Yelp/paasta/tree/v0.7.5) (2014-12-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.4...v0.7.5)

## [v0.7.4](https://github.com/Yelp/paasta/tree/v0.7.4) (2014-12-04)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.3...v0.7.4)

## [v0.7.3](https://github.com/Yelp/paasta/tree/v0.7.3) (2014-12-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.2...v0.7.3)

## [v0.7.2](https://github.com/Yelp/paasta/tree/v0.7.2) (2014-12-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.7.1...v0.7.2)

## [v0.7.1](https://github.com/Yelp/paasta/tree/v0.7.1) (2014-11-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.7...v0.7.1)

## [v0.6.7](https://github.com/Yelp/paasta/tree/v0.6.7) (2014-11-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.6...v0.6.7)

## [v0.6.6](https://github.com/Yelp/paasta/tree/v0.6.6) (2014-11-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.5...v0.6.6)

## [v0.6.5](https://github.com/Yelp/paasta/tree/v0.6.5) (2014-11-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.4...v0.6.5)

## [v0.6.4](https://github.com/Yelp/paasta/tree/v0.6.4) (2014-10-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.3...v0.6.4)

## [v0.6.3](https://github.com/Yelp/paasta/tree/v0.6.3) (2014-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.2...v0.6.3)

## [v0.6.2](https://github.com/Yelp/paasta/tree/v0.6.2) (2014-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.1...v0.6.2)

## [v0.6.1](https://github.com/Yelp/paasta/tree/v0.6.1) (2014-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.6.0...v0.6.1)

## [v0.6.0](https://github.com/Yelp/paasta/tree/v0.6.0) (2014-10-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.5.0...v0.6.0)

## [v0.5.0](https://github.com/Yelp/paasta/tree/v0.5.0) (2014-10-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.9...v0.5.0)

## [v0.4.9](https://github.com/Yelp/paasta/tree/v0.4.9) (2014-10-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.8...v0.4.9)

## [v0.4.8](https://github.com/Yelp/paasta/tree/v0.4.8) (2014-10-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.7...v0.4.8)

## [v0.4.7](https://github.com/Yelp/paasta/tree/v0.4.7) (2014-10-10)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.6...v0.4.7)

## [v0.4.6](https://github.com/Yelp/paasta/tree/v0.4.6) (2014-10-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.5...v0.4.6)

## [v0.4.5](https://github.com/Yelp/paasta/tree/v0.4.5) (2014-10-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.4...v0.4.5)

## [v0.4.4](https://github.com/Yelp/paasta/tree/v0.4.4) (2014-10-07)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.3...v0.4.4)

## [v0.4.3](https://github.com/Yelp/paasta/tree/v0.4.3) (2014-10-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.2...v0.4.3)

## [v0.4.2](https://github.com/Yelp/paasta/tree/v0.4.2) (2014-09-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.1...v0.4.2)

## [v0.4.1](https://github.com/Yelp/paasta/tree/v0.4.1) (2014-09-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.4.0...v0.4.1)

## [v0.4.0](https://github.com/Yelp/paasta/tree/v0.4.0) (2014-08-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.5...v0.4.0)

## [v0.3.5](https://github.com/Yelp/paasta/tree/v0.3.5) (2014-08-26)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.4...v0.3.5)

## [v0.3.4](https://github.com/Yelp/paasta/tree/v0.3.4) (2014-08-19)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.3...v0.3.4)

## [v0.3.3](https://github.com/Yelp/paasta/tree/v0.3.3) (2014-08-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.2...v0.3.3)

## [v0.3.2](https://github.com/Yelp/paasta/tree/v0.3.2) (2014-08-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.1...v0.3.2)

## [v0.3.1](https://github.com/Yelp/paasta/tree/v0.3.1) (2014-08-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.3.0...v0.3.1)

## [v0.3.0](https://github.com/Yelp/paasta/tree/v0.3.0) (2014-08-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.14...v0.3.0)

## [v0.2.14](https://github.com/Yelp/paasta/tree/v0.2.14) (2014-08-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.13...v0.2.14)

## [v0.2.13](https://github.com/Yelp/paasta/tree/v0.2.13) (2014-08-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.12...v0.2.13)

## [v0.2.12](https://github.com/Yelp/paasta/tree/v0.2.12) (2014-08-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.11...v0.2.12)

## [v0.2.11](https://github.com/Yelp/paasta/tree/v0.2.11) (2014-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.10...v0.2.11)

## [v0.2.10](https://github.com/Yelp/paasta/tree/v0.2.10) (2014-08-14)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.8...v0.2.10)

## [v0.2.8](https://github.com/Yelp/paasta/tree/v0.2.8) (2014-08-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.7...v0.2.8)

## [v0.2.7](https://github.com/Yelp/paasta/tree/v0.2.7) (2014-08-13)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.6...v0.2.7)

## [v0.2.6](https://github.com/Yelp/paasta/tree/v0.2.6) (2014-08-12)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.5...v0.2.6)

## [v0.2.5](https://github.com/Yelp/paasta/tree/v0.2.5) (2014-08-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.4...v0.2.5)

## [v0.2.4](https://github.com/Yelp/paasta/tree/v0.2.4) (2014-08-09)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.3...v0.2.4)

## [v0.2.3](https://github.com/Yelp/paasta/tree/v0.2.3) (2014-08-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.2...v0.2.3)

## [v0.2.2](https://github.com/Yelp/paasta/tree/v0.2.2) (2014-08-08)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.1...v0.2.2)

## [v0.2.1](https://github.com/Yelp/paasta/tree/v0.2.1) (2014-08-02)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.2.0...v0.2.1)

## [v0.2.0](https://github.com/Yelp/paasta/tree/v0.2.0) (2014-08-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.31...v0.2.0)

## [v0.1.31](https://github.com/Yelp/paasta/tree/v0.1.31) (2014-08-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.30...v0.1.31)

## [v0.1.30](https://github.com/Yelp/paasta/tree/v0.1.30) (2014-08-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.29...v0.1.30)

## [v0.1.29](https://github.com/Yelp/paasta/tree/v0.1.29) (2014-08-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.28...v0.1.29)

## [v0.1.28](https://github.com/Yelp/paasta/tree/v0.1.28) (2014-08-01)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.27...v0.1.28)

## [v0.1.27](https://github.com/Yelp/paasta/tree/v0.1.27) (2014-07-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.26...v0.1.27)

## [v0.1.26](https://github.com/Yelp/paasta/tree/v0.1.26) (2014-07-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.25...v0.1.26)

## [v0.1.25](https://github.com/Yelp/paasta/tree/v0.1.25) (2014-07-31)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.24...v0.1.25)

## [v0.1.24](https://github.com/Yelp/paasta/tree/v0.1.24) (2014-07-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.23...v0.1.24)

## [v0.1.23](https://github.com/Yelp/paasta/tree/v0.1.23) (2014-07-30)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.22...v0.1.23)

## [v0.1.22](https://github.com/Yelp/paasta/tree/v0.1.22) (2014-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.21...v0.1.22)

## [v0.1.21](https://github.com/Yelp/paasta/tree/v0.1.21) (2014-07-29)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.20...v0.1.21)

## [v0.1.20](https://github.com/Yelp/paasta/tree/v0.1.20) (2014-07-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.19...v0.1.20)

## [v0.1.19](https://github.com/Yelp/paasta/tree/v0.1.19) (2014-07-28)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.18...v0.1.19)

## [v0.1.18](https://github.com/Yelp/paasta/tree/v0.1.18) (2014-07-25)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.17...v0.1.18)

## [v0.1.17](https://github.com/Yelp/paasta/tree/v0.1.17) (2014-07-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.16...v0.1.17)

## [v0.1.16](https://github.com/Yelp/paasta/tree/v0.1.16) (2014-07-24)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.15...v0.1.16)

## [v0.1.15](https://github.com/Yelp/paasta/tree/v0.1.15) (2014-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.14...v0.1.15)

## [v0.1.14](https://github.com/Yelp/paasta/tree/v0.1.14) (2014-07-23)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.13...v0.1.14)

## [v0.1.13](https://github.com/Yelp/paasta/tree/v0.1.13) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.12...v0.1.13)

## [v0.1.12](https://github.com/Yelp/paasta/tree/v0.1.12) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.11...v0.1.12)

## [v0.1.11](https://github.com/Yelp/paasta/tree/v0.1.11) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.10...v0.1.11)

## [v0.1.10](https://github.com/Yelp/paasta/tree/v0.1.10) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.9...v0.1.10)

## [v0.1.9](https://github.com/Yelp/paasta/tree/v0.1.9) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.8...v0.1.9)

## [v0.1.8](https://github.com/Yelp/paasta/tree/v0.1.8) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.7...v0.1.8)

## [v0.1.7](https://github.com/Yelp/paasta/tree/v0.1.7) (2014-07-22)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.6...v0.1.7)

## [v0.1.6](https://github.com/Yelp/paasta/tree/v0.1.6) (2014-07-21)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.5...v0.1.6)

## [v0.1.5](https://github.com/Yelp/paasta/tree/v0.1.5) (2014-07-18)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.4...v0.1.5)

## [v0.1.4](https://github.com/Yelp/paasta/tree/v0.1.4) (2014-07-17)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.3...v0.1.4)

## [v0.1.3](https://github.com/Yelp/paasta/tree/v0.1.3) (2014-07-16)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.2...v0.1.3)

## [v0.1.2](https://github.com/Yelp/paasta/tree/v0.1.2) (2014-07-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.1.1...v0.1.2)

## [v0.1.1](https://github.com/Yelp/paasta/tree/v0.1.1) (2014-07-15)
[Full Changelog](https://github.com/Yelp/paasta/compare/v0.0.2...v0.1.1)

## [v0.0.2](https://github.com/Yelp/paasta/tree/v0.0.2) (2014-07-07)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
