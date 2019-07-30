# bitty


[![CircleCI](https://circleci.com/gh/yourgithubhandle/bitty/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/bitty/tree/master)


**Contains the following libraries and executables:**

```
bitty@0.0.0
│
├─test/
│   name:    TestBitty.exe
│   require: bitty/library
│
├─library/
│   library name: bitty/library
│   require:
│
└─executable/
    name:    BittyApp.exe
    require: bitty/library
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x BittyApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
