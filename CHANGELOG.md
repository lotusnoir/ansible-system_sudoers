# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.0](https://github.com/lotusnoir/ansible-system_sudoers/compare/2.1.0...2.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`410f891`](https://github.com/lotusnoir/ansible-system_sudoers/commit/410f891cbf66332ed4e47b103ad9e7bc40754722)
- update main to include success flag at the end to be able to monitor last playbook run [`5c18fcc`](https://github.com/lotusnoir/ansible-system_sudoers/commit/5c18fcc077343af86dbb6624ac5e6b36c212befc)

## [2.1.0](https://github.com/lotusnoir/ansible-system_sudoers/compare/2.0.0...2.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`fb939a3`](https://github.com/lotusnoir/ansible-system_sudoers/commit/fb939a34535f59014955814676c71b0c209b9f2c)
- add oraclelinux10 support + lint and core fixes [`a5b7ce9`](https://github.com/lotusnoir/ansible-system_sudoers/commit/a5b7ce9f9420df369e1b890b7e0678db1887af37)

## [2.0.0](https://github.com/lotusnoir/ansible-system_sudoers/compare/1.0.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`0215e60`](https://github.com/lotusnoir/ansible-system_sudoers/commit/0215e60969f384e2245a64699cd3371363120f9c)
- update core, molecule + gitlab-ci [`bfad341`](https://github.com/lotusnoir/ansible-system_sudoers/commit/bfad34161c2dabc9bdd95cad7e523b7c1e24b2fe)
- fix lint [`4664209`](https://github.com/lotusnoir/ansible-system_sudoers/commit/4664209a517cc302ea88333f18573ef00be7a20d)
- fix molecule paralelism and little updates [`cf0fef0`](https://github.com/lotusnoir/ansible-system_sudoers/commit/cf0fef05e77260fa96e60707b59562a7c1b7d719)
- add support for ubuntu24 [`29f09c3`](https://github.com/lotusnoir/ansible-system_sudoers/commit/29f09c33ab0b98bd446bdd0a07a5ba5812beb9b0)
- add version on molecule play image to maintain support on old release [`c3c63b7`](https://github.com/lotusnoir/ansible-system_sudoers/commit/c3c63b796a39689afe6ddb3f6f33d412f1ad5ca3)
- update molecule [`5db5056`](https://github.com/lotusnoir/ansible-system_sudoers/commit/5db50564d95a63bef5055d4c2de6d54efe39e905)
- add redhat 9 to default supported distrib [`9f7f0c7`](https://github.com/lotusnoir/ansible-system_sudoers/commit/9f7f0c7f78dd09b9a7d837eae798b8d26bd385ad)
- add redhat 8 to default supported distrib [`c38549f`](https://github.com/lotusnoir/ansible-system_sudoers/commit/c38549fa91169d9edfc206dc58f6d8004b84864a)
- sort testing distrib to avoid random changes [`f0a928b`](https://github.com/lotusnoir/ansible-system_sudoers/commit/f0a928bd9eac2079dd93725cabdd2a8e0bb3a3db)

## [1.0.0](https://github.com/lotusnoir/ansible-system_sudoers/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`80dbed7`](https://github.com/lotusnoir/ansible-system_sudoers/commit/80dbed709e623d164c8033a168ba958d827eff05)
- update readme + precommit + include vars [`3d95d7e`](https://github.com/lotusnoir/ansible-system_sudoers/commit/3d95d7e309720bccaeed10dffad25c2bdb52b75b)
- change import tasks to include in order to support facts on name [`dcdf228`](https://github.com/lotusnoir/ansible-system_sudoers/commit/dcdf2280dd2821247827266188e3388cf391e0f1)

## [0.2.0](https://github.com/lotusnoir/ansible-system_sudoers/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`5f14f5a`](https://github.com/lotusnoir/ansible-system_sudoers/commit/5f14f5a6b6decd2ed120a42d1263b2cfacc931e0)
- add galaxy id [`89385ef`](https://github.com/lotusnoir/ansible-system_sudoers/commit/89385ef15831d9d00d70af535c4fbe59779f684e)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`a2f33ea`](https://github.com/lotusnoir/ansible-system_sudoers/commit/a2f33ea918f08381b2643c164d339939ed61e2e9)
- add precommit for lint [`dbe3838`](https://github.com/lotusnoir/ansible-system_sudoers/commit/dbe38388afc7e025e6737ee6b68a89667eb16856)
- fix checks [`804248a`](https://github.com/lotusnoir/ansible-system_sudoers/commit/804248a33d9475a8641ae78effbac0397c5aeaec)
- add new molecule all scenario [`4f84261`](https://github.com/lotusnoir/ansible-system_sudoers/commit/4f84261773ed2c375461214f81dbf14b785212e9)
- split distro for molecule tests on ci [`f492f04`](https://github.com/lotusnoir/ansible-system_sudoers/commit/f492f045e4b0c4fe8aaefb858b15a144f787430f)
- update checks and Readme [`0d99ef1`](https://github.com/lotusnoir/ansible-system_sudoers/commit/0d99ef1cbce2e371e6b5402943a141056301e164)
- fix template for debian11 and ubuntu22 [`4cbb434`](https://github.com/lotusnoir/ansible-system_sudoers/commit/4cbb434437038fef7c06d0938d3138f689eb4271)
- initial commit [`9721693`](https://github.com/lotusnoir/ansible-system_sudoers/commit/972169350e7cb01ea8f460ea5f3ea72a4d1772a4)
