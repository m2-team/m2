## m2 - intergreted build environment for front-end develop
m2 is a pun of "i'm tool" & "i'm to do sth" :))

m2 is a infrustructure for front-end develop with featurs:

* init a project easily
* auto-refresh while saving

### features

1. init a project/module set up the skeleton
   * project/module name;
   * develop-server and test-server info;
   * project info: git path, domain name, port info;
2. launch the local develop server
3. sync to the test-server
4. extensible config file
   * add the sync role - from vm path to the java source path.
5. unified develop environment management: include the java source into project path as a submodule for git.
6. local git hook: eslint and doc generate.
7. online page checking -- for no dead links and check the script errors.

### command lines

* m2 init
* m2 install
* m2 package
* m2 sync
* m2 deploy
* m2 check
* m2 analyze - analyze the online code.


### develop planing

* init project and test main features:
    use `npm install -g m2` to install the tool
    use m2 init to request for infos:
        project name
        project path(in git)
        domain name - default-value for <project name>.jd.com
            - the domain-suffix are stored as m2's global value

### design
    *global settings:
        - domain name - default value is "jd.com"
        - dev server - default value is username@test.smart.jd.com


