# testzidas
run("Open...");
run("HeLa Cells (1.3M, 48-bit RGB)");
run("Split Channels");
run("Duplicate...", " ");
setAutoThreshold("Default dark");
//run("Threshold...");
setAutoThreshold("Default dark");
run("Close");
setOption("ScaleConversions", true);
run("8-bit");
run("Analyze Particles...", "display summarize add");
//run("Brightness/Contrast...");
run("Close");
setOption("BlackBackground", true);
run("Make Binary");
run("Analyze Particles...", "display summarize add");
#   java.version: 1.8.0_202
  java.vendor: AdoptOpenJdk
  os.name: Mac OS X
  os.version: 10.13.3
  os.arch: x86_64
  file.separator: /
  path.separator: :
  line.separator: <lf>

  user.name: yshen25
  user.home: /Users/yshen25
  user.dir: /Applications/Fiji.app
  user.country: CN
  file.encoding: UTF-8
  java.home: /Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre
  java.class.path: /Applications/Fiji.app/jars/imagej-launcher-4.0.5.jar
  java.ext.dirs: /Users/yshen25/Library/Java/Extensions:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/ext:/Library/Java/Extensions:/Network/Library/Java/Extensions:/System/Library/Java/Extensions:/usr/lib/java
  java.io.tmpdir: /var/folders/gk/rx7yt9bx5271h0pbkt2c74cm0000gn/T/

  IJ.getVersion: 2.0.0-rc-69/1.52n
  IJ.getFullVersion: 1.52n99
  IJ.javaVersion: 8
  IJ.isLinux: false
  IJ.isMacintosh: true
  IJ.isMacOSX: true
  IJ.isWindows: false
  IJ.is64Bit: true

  IJ.getDir("imagej"): /Applications/Fiji.app/
  IJ.getDir("home"): /Users/yshen25/
  IJ.getDir("plugins"): /Applications/Fiji.app/plugins/
  IJ.getDir("macros"): /Applications/Fiji.app/macros/
  IJ.getDir("luts"): /Applications/Fiji.app/luts/
  IJ.getDir("current"): /Users/yshen25/Desktop/ZIDAS2019/
  IJ.getDir("temp"): /tmp/
  IJ.getDir("default"): /Users/yshen25/Desktop/ZIDAS2019/
  IJ.getDir("image"): null

  Menus.getPlugInsPath: /Applications/Fiji.app/plugins/
  Menus.getMacrosPath: /Applications/Fiji.app/macros/
  Prefs.getImageJDir: /Applications/Fiji.app/
  Prefs.getThreads: 4 (4 cores)
  Prefs.open100Percent: false
  Prefs.blackBackground: true
  Prefs.useJFileChooser: false
  Prefs.weightedColor: false
  Prefs.blackCanvas: false
  Prefs.pointAutoMeasure: false
  Prefs.pointAutoNextSlice: false
  Prefs.requireControlKey: false
  Prefs.useInvertingLut: false
  Prefs.antialiasedTools: true
  Prefs.useInvertingLut: false
  Prefs.intelByteOrder: false
  Prefs.noPointLabels: false
  Prefs.disableUndo: false
  Prefs dir: /Users/yshen25/Library/Preferences
  Current dir: /Users/yshen25/Desktop/ZIDAS2019/
  Sample images dir: http://wsr.imagej.net/images/
  Memory in use: 359MB of 4356MB (8%)
  Screen size: 1440x900
  Max window bounds: x=0,y=23,width=1440,height=877

All Java Properties
  ij.dir: /Applications/Fiji.app
  java.runtime.name: OpenJDK Runtime Environment
  fiji.dir: /Applications/Fiji.app
  imagej.dir: /Applications/Fiji.app
  sun.boot.library.path: /Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib
  java.vm.version: 25.202-b08
  user.country.format: CH
  gopherProxySet: false
  java.vm.vendor: Oracle Corporation
  java.vendor.url: https://adoptopenjdk.net/
  path.separator: :
  java.vm.name: OpenJDK 64-Bit Server VM
  file.encoding.pkg: sun.io
  user.country: CN
  sun.os.patch.level: unknown
  java.vm.specification.name: Java Virtual Machine Specification
  user.dir: /Applications/Fiji.app
  java.runtime.version: 1.8.0_202-b08
  scijava.context.strict: false
  java.awt.graphicsenv: sun.awt.CGraphicsEnvironment
  java.endorsed.dirs: /Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/endorsed
  os.arch: x86_64
  java.io.tmpdir: /var/folders/gk/rx7yt9bx5271h0pbkt2c74cm0000gn/T/
  line.separator: 

  java.vm.specification.vendor: Oracle Corporation
  os.name: Mac OS X
  apple.laf.useScreenMenuBar: true
  sun.jnu.encoding: UTF-8
  java.library.path: /Applications/Fiji.app/lib/macosx:/Applications/Fiji.app/mm/macosx
  sun.awt.enableExtraMouseButtons: true
  java.specification.name: Java Platform API Specification
  java.class.version: 52.0
  sun.management.compiler: HotSpot 64-Bit Tiered Compilers
  os.version: 10.13.3
  apple.awt.fileDialogForDirectories: false
  http.nonProxyHosts: local|*.local|169.254/16|*.169.254/16
  user.home: /Users/yshen25
  user.timezone: Europe/Zurich
  java.awt.printerjob: sun.lwawt.macosx.CPrinterJob
  file.encoding: UTF-8
  java.specification.version: 1.8
  plugins.dir: /Applications/Fiji.app
  java.class.path: /Applications/Fiji.app/jars/imagej-launcher-4.0.5.jar
  user.name: yshen25
  java.vm.specification.version: 1.8
  java.home: /Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre
  sun.arch.data.model: 64
  user.language: zh
  java.specification.vendor: Oracle Corporation
  user.language.format: en
  awt.toolkit: sun.lwawt.macosx.LWCToolkit
  java.vm.info: mixed mode
  java.version: 1.8.0_202
  java.ext.dirs: /Users/yshen25/Library/Java/Extensions:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/ext:/Library/Java/Extensions:/Network/Library/Java/Extensions:/System/Library/Java/Extensions:/usr/lib/java
  sun.boot.class.path: /Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/resources.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/rt.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/sunrsasign.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/jsse.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/jce.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/charsets.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/lib/jfr.jar:/Applications/Fiji.app/java/macosx/adoptopenjdk-8.jdk/jre/Contents/Home/jre/classes
  java.vendor: AdoptOpenJdk
  ij.executable: /Applications/Fiji.app/Contents/MacOS/ImageJ-macosx
  python.cachedir.skip: true
  file.separator: /
  java.vendor.url.bug: https://github.com/AdoptOpenJDK/openjdk-build/issues
  sun.font.fontmanager: sun.font.CFontManager
  sun.io.unicode.encoding: UnicodeBig
  sun.cpu.endian: little
  socksNonProxyHosts: local|*.local|169.254/16|*.169.254/16
  fiji.executable: /Applications/Fiji.app/Contents/MacOS/ImageJ-macosx
  ftp.nonProxyHosts: local|*.local|169.254/16|*.169.254/16
  sun.cpu.isalist: 
