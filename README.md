# personal-intellij-settings
IntelliJ Settings

# custom WebStorm VM options

-server
-Xms2048m
-Xmx4096m
-XX:MaxPermSize=1024M
-XX:ReservedCodeCacheSize=1024M
-XX:+UseCodeCacheFlushing
-XX:+UseCompressedOops
-XX:+UseConcMarkSweepGC
-XX:+UseParNewGC
-XX:ParallelGCThreads=8
-XX:+AggressiveOpts
-XX:+CMSClassUnloadingEnabled
-XX:+CMSIncrementalMode
-XX:+CMSIncrementalPacing
-XX:CMSIncrementalDutyCycleMin=0
-XX:-TraceClassUnloading
-XX:+TieredCompilation
-Dsun.io.useCanonCaches=false
-Djava.net.preferIPv4Stack=true
-Djsse.enableSNIExtension=false
