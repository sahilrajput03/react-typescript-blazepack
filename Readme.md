# Early access to `react-typescript-app` template for blazepack

This is a proposal of using `react-typescript-app` with `blazepack`(an over the air bundler).

## How to use

Execute below commands:

```bash
$ git clone https://github.com/sahilrajput03/react-typescript-blazepack react-typescript-app
$ cd react-typescript-app
$ ./by add @types/react @types/react-dom
$ blazepack #To run the typescript app.
```

We are only installing required types i.e., @types/react`and`@types/react-dom via `by`(`blazepackyarn` ) bash script.

#### Optional: Other desirable type definition packages installation and removal:

```bash
#Install other desirable type definitions via -
./by add @types/react-query @types/lodash @types/date-fns

#Remove a type definition package via -
./by remove @types/date-fns
```
