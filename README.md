# OffensiveCode

Offensive security experiments and assessment code in C++, C#, and Python, preserved from my previous `sinllaves` account.

This repository contains a mixture of original work, adapted examples, and third-party material. Existing licenses and source attribution apply; inclusion here does not imply sole authorship.

## Repository guide

| Area | Contents |
| --- | --- |
| [OffSec-cpp](OffSec-cpp/) | Windows DLL loading, DLL behavior, file operations, and related experiments |
| [OffSec-cs](OffSec-cs/) | C# offensive security experiments |
| [OffSec-Python](OffSec-Python/) | Port scanners, client/server exercises, and Python assessment experiments |
| [ProcessInjectionEnumerator](ProcessInjectionEnumerator/) | Process-injection enumeration project |
| [ShellCode PreChecker](ShellCode%20PreChecker/) | Shellcode precheck experiments |
| [File-operation privilege escalation](ArbWriteFileOp2SysCMD-almostDone/) | In-progress Windows file-operation and privilege-escalation research |

## Working with the code

Projects are independent experiments, rather than a single application. Inspect each source directory and its project files for build requirements. Windows C++ and C# projects include Visual Studio solution or project files where available.

Historical build outputs are present. Review the source and build your own artifacts in an isolated lab before execution. Compatibility, reliability, and security behavior have not been validated as part of this documentation update.

## Scope

Use only on systems you own or have explicit permission to assess. Record the operating system, privileges, test conditions, observed behavior, and cleanup when reproducing an experiment.

## Attribution and license

Retain existing copyright notices, licenses, and references when reusing code. See [LICENSE](LICENSE) and any project-specific notices.