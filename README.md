# `.flutter-version`

## Introduction
This is a proposal for a standard in our Flutter pojects: a text-based file that defines the Flutter version that should be used to compile a given Flutter project.

## File name

The file name must always be `.flutter-version`

## File location

The file must be located in the root directory of the project.

## File content

The file content must be a simple string in a text file. The file may or may not end with an empty new line.

### Sample files

```
1.12.13+hotfix.9
```

```
1.17.3
```

It is recommended to only use non-beta releases in an `.flutter-version` file to have fully reproducible builds that you'll be able to run in a few years also (we hope).

# Flutter Version Manager

We suggest using a version manager so you can easily siwtch between flutter versions in your projects.

You can use something like: [FVM](https://github.com/leoafarias/fvm)
