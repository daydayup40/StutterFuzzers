# StutterFuzzers

## Description

These codes and scripts are used to prove deficiencies in libFuzzer, AFL, klee, QSYM tools. Please modify the build_test_ * script to use it in your environment.
None of them could construct a use case that could trigger a NULL pointer access. Although the programmer can find the location of the NULL pointer access vulnerability at a glance.
## Relationship
|  | AFL | liFuzzer | klee | QSYM |
|--|--|--|--|--|
| stutter_AFL.c | Yes |  |  |  |
| stutter_libFuzzer_and_AFL.c | Yes | Yes |  |  |
| stutter_All_for_klee.c |  |  | Yes |  |
| stutter_All_for_QSYM_libFuzzer_AFL.c | Yes | Yes |  | Yes |
