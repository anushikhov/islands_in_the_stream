# JDK BUILD  

* toolchain  
* build tools  
* external libs  
* boot JDK  

### Toolchain  (Native compiler) requirements
Large portions of JDK consist of native code that needs to be compiled to be able to run on the target platform.  
In theory, toolchain and operating system should be independent factors, but in practice there's more or less a one-to-one correlation between target operating system and toolchain.
