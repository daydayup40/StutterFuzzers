# StutterFuzzers

## Description

These codes and scripts are used to prove deficiencies in libFuzzer, AFL, klee, QSYM tools. Please modify the build_test_ * script to use it in your environment.
## Relationship
|  | AFL | liFuzzer | klee | QSYM |
|--|--|--|--|--|
| stutter_AFL.c | Yes |  |  |  |
| stutter_libFuzzer_and_AFL.c | Yes | Yes |  |  |
| stutter_All_for_klee.c |  |  | Yes |  |
| stutter_All_for_QSYM_libFuzzer_AFL.c | Yes | Yes |  | Yes |
