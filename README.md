# nat
A bash utility that helps automate Ant build targets and build.xmls.

Add the folder containing this script to the PATH environment variable.

Run "nat" from within a project folder where build.xmls should be or already are.

If there isn't a build.xml in the current folder, it will ask permission to create one for you.

If there is a build.xml in the folder already, it will verify any .java test files are in the build.xml, if not, it will ask premission to append it.

Note: It presumes the Ant targets will be named the same as the test case .java file with camelCase.
