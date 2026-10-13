# openWorkBenchesCli-spec

The workstation bootstrap, installer, terminal interface, prerequisite checks, and credential recovery engine.

The current installer implementation is in [opensoft/workBenches](https://github.com/opensoft/workBenches). This triad establishes its destination; history-preserving extraction and path integration are the next migration step.

The **spec leg** of the `openworkbenchescli` project: requirements, decisions and
acceptance criteria. The implementation lives in
[`opensoft/openWorkBenchesCli-code`](https://github.com/opensoft/openWorkBenchesCli-code).

**Clone the assembly root, not this repository.** This leg is mounted as a
submodule at `spec/` inside
[`opensoft/openWorkBenchesCli`](https://github.com/opensoft/openWorkBenchesCli), which
is what pins the commit of this repository that the project currently is:

```sh
git clone --recurse-submodules https://github.com/opensoft/openWorkBenchesCli.git
cd openWorkBenchesCli
make bootstrap
```

Working here directly is fine — it is an ordinary repository with an ordinary
branch. What advancing this leg does NOT do is advance the project: that is a
commit in the assembly root moving the gitlink, `contracts/spec-pin.yaml` and
any workflow `@<sha>` reference together.

Being the spec leg confers no authority over specifications. The split is
navigation; authority travels in grants, and a project that keeps spec and
code in one repository is reviewed identically.

Topic: `xf-project-openworkbenchescli`.


## License

Apache-2.0. Copyright 2026 OpenSoft. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
