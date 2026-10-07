<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="C++ LOGIN EXERCISE — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="learning / English and Persian documentation" />

</div>

# C++ LOGIN EXERCISE

A forked C++ exercise that experiments with username input and file persistence. It is preserved as a learning snapshot with upstream attribution.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/exam) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [Static artwork](assets/readme/hero.png)

> This repository is a fork. Source attribution belongs to the upstream authors; the previous README is preserved in docs/UPSTREAM_README.md.


Upstream source: [Soroush26/exam](https://github.com/Soroush26/exam).

## Features

- Console submit/login prompt
- Username file comparison
- Early file-persistence experiment

## Stack

| Tool | Version / source |
|---|---|
| C++ | `standard library` |

## Getting started

A C++ compiler such as GCC, Clang or MSVC. The commands below use g++.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/exam.git
cd exam

g++ project26.cpp -o login-exercise
```

## Configuration

No standard environment template is defined. Standalone exercises need no external configuration; inspect any service constants or paths in the source before running.

## Usage

Read project26.cpp before compiling; configure the hardcoded drive paths if you want to explore the exercise.

## Project structure

| Path | Role |
|---|---|
| [`assets/`](assets/) | Brand/media/README assets |
| [`project26.cpp`](project26.cpp) | Project entry/configuration file |

## Commands and checks

No automated test command is declared in a manifest. Verify behavior through a local example run.

## Deployment

This is a local learning exercise, not a public service. Browser exercises can use static hosting.

## Limitations

The login path is incomplete, loop conditions are problematic and credentials are stored as plain text. Do not use it for authentication.

## Troubleshooting

- Compiler unavailable: install GCC/Clang/MSVC and adapt the example command.
- Missing output: inspect hardcoded paths, drive permissions and input values.

## Contributing

Create a focused branch, verify the affected behavior and explain the change clearly. Keep private data, build outputs and local databases out of commits.

## License

No repository-level license file is included in this snapshot. Public visibility alone does not grant reuse rights; contact the repository owner for terms.

---

Part of **PIMX** · Documentation in English and Persian.
