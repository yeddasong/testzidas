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
