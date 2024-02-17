# Clang Format

This repository holds my personal .clang-format file that I use in all my C++ projects and occassionally update.

## Tabs instead of spaces

I use tabs for indentation and spaces for alignment.

I typically size tabs as 8 spaces to discourage nesting.

```
TabWidth: 8
IndentWidth: 8
ContinuationIndentWidth: 8
UseTab: Always
```

## Column limit

I use an 80-column limit to discourage nesting and because I find it easier to read code that flows down rather than along.

```
ColumnLimit: 80
```

## Brace style

I use Allman style for namespaces, classes, and functions, and K&R for everything else.

```
BraceWrapping:
  AfterCaseLabel: false
  AfterClass: true
  AfterControlStatement: Never
  AfterEnum: true
  AfterFunction: true
  AfterNamespace: true
  AfterUnion: true
  BeforeCatch: false
  BeforeElse: false
  IndentBraces: false
  SplitEmptyFunction: false
  SplitEmptyRecord: true
```