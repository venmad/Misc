In Linux Centos 7, by feault the openjdk packages will install. When we want to work with Oracle JDK, install the oracle jdk at the official website in Downloads section and install via rpm.

# Below are the steps to switch between different java version in Linux.

1. Enter the below command to see which java versions are installed and configured as alternatives.
   
   ```alternatives --config java```
   
2. Enter the Selection to set as default java.

3. Now, check the java version which reflects the above selected version.

4. In this way, we can easily switch between different jdk versions.

#### References:

1. [configuring-different-jdks-with-alternatives](https://blogs.igalia.com/dpino/2011/10/13/configuring-different-jdks-with-alternatives/
)
