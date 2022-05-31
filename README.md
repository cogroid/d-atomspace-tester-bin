[![cogroid.com](https://github.com/cogroid/resources/raw/main/images/banner/cogroid-48.png)](https://cogroid.com)

# Binaries of dAtomSpace Tester

## dAtomSpace Tester with Atomize 0.3

### Features

The app runs test cases in [Tester.java](https://github.com/cogroid/d-atomspace-tester-bin/raw/main/0.3/Tester.java)

```
com.cogroid.atomspace.Tester tester = new com.cogroid.atomspace.Tester("/storage/emulated/0/Download/datomspace-test.txt");
tester.testAll();
```

The app also execute [Tests.js](https://github.com/cogroid/d-atomspace-tester-bin/raw/main/0.3/samples/Tests.js)

```
int timeout = 60000;
String jsFile = "/storage/emulated/0/Download/jsb/Tests.js";
String inputFile = "/storage/emulated/0/Download/jsb/input.json";
String outputFile = "/storage/emulated/0/Download/jsb/output.json";

com.cogroid.atomize.ASBRun asbRun = new com.cogroid.atomize.ASBRun();
asbRun.exec(jsFile, timeout, inputFile, outputFile);
```

### Install & Run

1. Download [datomspace-tester.apk](https://github.com/cogroid/d-atomize-bin/releases/download/atomize-0.2/datomspace-tester.apk)

2. Install datomspace-tester.apk (Do not run!)

3. Go to Settings -> Apps -> dAtomSpace Tester. Set Storage permission.

4. Run dAtomSpace Tester

5. View results in datomspace-test.txt file in Download folder


---
[Head icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/head)
