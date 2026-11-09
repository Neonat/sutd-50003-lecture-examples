# SUTD 50.003 — Lecture Examples

Personal reference fork of [sutd50003/examples_in_notes](https://github.com/sutd50003/examples_in_notes), containing code examples for SUTD 50.003 Software Construction and retained local coursework changes. The upstream [MIT licence and attribution](LICENSE) remain in place.

## Example index

| Folder | Contents |
| --- | --- |
| [l1_1_ex](l1_1_ex/) | Browser HTML/CSS/JavaScript, DOM interaction and API-call examples |
| [l1_2_ex](l1_2_ex/) | Node modules, TypeScript, callbacks, promises, file access and events |
| [l2_1_ex](l2_1_ex/) | JavaScript/TypeScript HTTP and Express applications, including MongoDB examples |
| [l2_2_ex](l2_2_ex/) | Express/MySQL message application with EJS forms and AJAX |
| [l3_2_ex](l3_2_ex/) | React/Vite Echo frontend example |
| [l8_2_ex](l8_2_ex/) | Jest unit-testing examples for arithmetic, Fibonacci sequences and string handling |
| [l9_2_ex](l9_2_ex/) | TypeScript Express/MySQL backend and model tests; [conversion instructions](l9_2_ex/my_mysql_app/Instruction1.md) |
| [l10_1_ex](l10_1_ex/) | React frontend with Vitest/component tests; [conversion instructions](l10_1_ex/my_react_app/Instruction1.md) |
| [l11_1_ex](l11_1_ex/) | Simple fuzzer example |
| [l12_2_ex](l12_2_ex/) | Stack/MaxStack implementations and tests; [conversion instructions](l12_2_ex/my_test_app2/Instruction1.md) |

## Using the examples

```bash
git clone https://github.com/Neonat/sutd-50003-lecture-examples.git
cd sutd-50003-lecture-examples
```

For example, the standalone Jest teaching package can be opened with:

```bash
cd l8_2_ex/my_test_app
npm ci
npm test
```

This runs the selected example package's script; it is not a repository-wide
validation command. Inspect its test cases and lecture objective when
interpreting failures.

These folders are separate teaching projects. Open the selected package's `package.json` and any README or instruction file before installing dependencies or running scripts. Some examples need a local database and matching backend/frontend ports; the React example in `l10_1_ex` is paired with the backend in `l9_2_ex`.

Existing TypeScript conversion notes are kept in the relevant `log/` folders. This fork retains local changes; review them before considering any upstream update.

## Context and status

The repository spans browser JavaScript, Node.js, TypeScript, Express, React,
database access and software-testing examples. Each folder demonstrates a
specific lesson; examples may intentionally contain incomplete code or teaching
failures. Some `npm test` scripts are the original package-generator defaults,
so inspect a package before treating its script as a test suite. Runtime and
database behaviour have not been revalidated for this README update.

For personal exercise work, see the companion
[50.003 cohort exercises](https://github.com/Neonat/sutd-50003-cohort-exercises).
Upstream teaching material remains attributed to SUTD 50003 under the linked
MIT licence; retaining local changes does not imply authorship of the upstream
examples.
