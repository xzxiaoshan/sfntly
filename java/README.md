## sfntly Quick Start Guide

1. Run the ant build
  - go to the java directory and run "ant"
  - this should build all of sfntly and the included samples and tools
2. Run the sfntdump sample
  - go to the java/dist/sample/sfntdump directory
  - run "java -jar sfntdump"
    - the sfntdump.jar is self-contained as are all of the other sample and tool jars
    - you will get the SfntDump sample tool help info
  - run "java -jar sfntdump <font file path>"
    - you will get a very basic dump of the high level contents of the font
  - try adding various options on the SfntDump tool to see more information about the font
3. Try out the rest of the samples and tools
4. Start building your own tools or extending ours
5. Stop by the sfntly discussion list - https://groups.google.com/group/sfntly-users