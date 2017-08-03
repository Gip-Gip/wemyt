# weM/yt

The Lo**w** R**e**source **M**emory/S**y**stem In**t**erface

## Source Documentation

weM/yt's source code may be a bit difficult to browse due to the fact there is
little standard for assembly language source. In order to mitigate this, Gip-Gip
attempts to sort the source code very simularly to his C code in that every call
has it's own designated file and the call files are grouped into well-suited
directories. The directories include

 * **data/** - assembler files that contain little-to-no code but lots of
   important data

 * **graphics/** - assembler files that contain basic graphical calls

 * **init/** - assembler files that contain all the initialization code

 * **io/** - assembler files that contain basic io calls

 * **memory/** - assembler files that contain memory i/o calls

 * **scc/** - assembler files for the simulated CPU core
