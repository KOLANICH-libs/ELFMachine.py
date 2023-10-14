ELFMachine.py
=============
~~[wheel (GHA via nightly.link)](https://nightly.link/KOLANICH-libs/ELFMachine.py/workflows/CI/master/ELFMachine-0.CI-py3-none-any.whl)~~
~~[wheel (GitLab)](https://gitlab.com/KOLANICH/ELFMachine.py/-/jobs/artifacts/master/raw/dist/ELFMachine-0.CI-py3-none-any.whl?job=build)~~
[![PyPi Status](https://img.shields.io/pypi/v/ELFMachine.svg)](https://pypi.python.org/pypi/ELFMachine)
~~[![GitLab Build Status](https://gitlab.com/KOLANICH/ELFMachine.py/badges/master/pipeline.svg)](https://gitlab.com/KOLANICH/ELFMachine.py/pipelines/master/latest)~~
~~[![GitHub Actions CI](https://github.com/KOLANICH-libs/ELFMachine.py/workflows/CI/badge.svg)](https://github.com/KOLANICH-libs/ELFMachine.py/actions/)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH-libs/ELFMachine.py.svg)](https://libraries.io/github/KOLANICH/ELFMachine.py)
![N∅ install dependencies](https://shields.io/badge/-N%E2%88%85_deps!-0F0)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-libs/ELFMachine.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success and wide adoption of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

Just a enum of values for `e_machine` field of ELF header.

`setup.py` is just a script downloading headers from different projects under permissive licenses, parsing them, merging the enum into a single enum and then composing a python file.
