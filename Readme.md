# Early access to `react-typescript-app` template for [blazepack](https://github.com/ameerthehacker/blazepack)

This is a proposal of using `react-typescript-app` with [`blazepack`](https://github.com/ameerthehacker/blazepack)(an over the air bundler).

## How to use

**MUST: If you are a windows user please use `git-bash`/`msys`/`msys2` terminal.**

**MUST: You must have yarn installed in your system.**

Execute below commands:

```bash
$ git clone https://github.com/sahilrajput03/react-typescript-blazepack react-typescript-app
$ cd react-typescript-app
$ ./by
$ blazepack #To run our `react-typescript-app`.
```

We are only installing required types i.e., `@types/react` and `@types/react-dom` using a bash program named`by` (stands for `BlazepackYarn`) to manage/install/remove required types for the IDE to get types for the libraries we are using duiring development. Types are required for supressing error i.e., module definition missing and supporting the autocomplete feature from react, other third-party libraries etc.

#### Optional: Install and remove other desirable type definition packages

```bash
#Install other desirable type definitions via -
./by add @types/react-query @types/lodash @types/date-fns

#Remove a type definition package via -
./by remove @types/date-fns
```
