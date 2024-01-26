# jvm-default-cli-flags
Quick detection of JVM's default command-line flags.


[Oracle JDK 8u202](https://mirrors.huaweicloud.com/java/jdk/8u202-b08/jdk-8u202-linux-x64.tar.gz)
-XX:InitialHeapSize=129924672 -XX:MaxHeapSize=2078794752 -XX:+UseCompressedClassPointers -XX:+UseCompressedOops -XX:+UseParallelGC

[Eclipse Temurin™ 8u402-b06](https://github.com/adoptium/temurin8-binaries/releases/download/jdk8u402-b06/OpenJDK8U-jdk_x64_linux_hotspot_8u402b06.tar.gz)
-XX:InitialHeapSize=129924672 -XX:MaxHeapSize=2078794752 -XX:+UseCompressedClassPointers -XX:+UseCompressedOops -XX:+UseParallelGC

[Eclipse Temurin™ 11.0.22+7](https://github.com/adoptium/temurin11-binaries/releases/download/jdk-11.0.22%2B7/OpenJDK11U-jdk_x64_linux_hotspot_11.0.22_7.tar.gz)
-XX:G1ConcRefinementThreads=2 -XX:GCDrainStackTargetSize=64 -XX:InitialHeapSize=129924672 -XX:MaxHeapSize=2078794752  -XX:ReservedCodeCacheSize=251658240 -XX:+SegmentedCodeCache -XX:+UseCompressedClassPointers -XX:+UseCompressedOops -XX:+UseG1GC

[Microsoft 17.0.9]()
-XX:ConcGCThreads=1 -XX:G1ConcRefinementThreads=2 -XX:GCDrainStackTargetSize=64 -XX:InitialHeapSize=129924672 -XX:MarkStackSize=4194304 -XX:MaxHeapSize=2078794752 -XX:MinHeapSize=6815736 -XX:ReservedCodeCacheSize=251658240 -XX:+SegmentedCodeCache -XX:+UseCompressedClassPointers -XX:+UseCompressedOops -XX:+UseG1GC

[Microsoft 21.0.1]()
-XX:ConcGCThreads=1 -XX:G1ConcRefinementThreads=2 -XX:GCDrainStackTargetSize=64 -XX:InitialHeapSize=129924672 -XX:MarkStackSize=4194304 -XX:MaxHeapSize=2078794752 -XX:MinHeapSize=6815736 -XX:ReservedCodeCacheSize=251658240 -XX:+SegmentedCodeCache -XX:+UseCompressedOops -XX:+UseG1GC