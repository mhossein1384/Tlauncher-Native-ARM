
# Tlauncher-Native-M1
Let's make Tlauncher to run in aarch64(Linux-macOS(-Windows coming soon)).

Tlauncher is a russian minecraft launcher: https://tlauncher.org/en/

*_The launcher is not mine and I don't accept any responsibilities in terms of safety or..._ *

# 1. Download Java For ARM
Linux:https://cdn.azul.com/zulu-embedded/bin/zulu8.58.0.13-ca-jdk8.0.312-linux_aarch64.tar.gz

macOS:https://cdn.azul.com/zulu/bin/zulu8.58.0.53-ca-fx-jdk8.0.312-macosx_aarch64.tar.gz
# 2. Find Tlauncher Library location
Linux: ~/.local/share/tlauncher (If It's wrong ,fix it)

macOS: ~/Library/Application Support/tlauncher
# 3. Extract Java
With an unarchivever app or with $ tar -xf [The file name] command.
# 4. Put Extracted JAVA To Tlauncher
Linux: Go to ~/.local/share/tlauncher/jvms/ and open the one and only folder there and delete everything on that folder and replace it with files and folders inside .jdk (from the downloaded java) folder

macOS: Open ~/Library/Application Support/tlauncher/jvms/jdk1.8.0_202.jdk/ and delete contents folder and replace it with the one in the downloaded java folder.

Now Open tlauncher.jar and enjoy the performance
<img width="1049" alt="Screen Shot 2021-12-05 at 6 28 53 PM" src="https://user-images.githubusercontent.com/95017233/144751925-d17500f6-c999-457d-bbf8-94c1e0759798.png">

# NOTES AND ISSUES
•This is only tested on macOS with M1 chip

•Minecraft Itself cannot be run in native arm(macos)...

•The launcher needs serious Updates in terms of running java for minecraft to run it natively on ARM...

•(In Mac) The launcher thinks ARM java is 32bits so When I replace it with the main java It downloads the x86 java again...

•In Linux download Java 17 ARM from Oracle Site and replace it with the one at minecraft/runtime/java-runtime-alpha(or beta)/  It might work.

•Windows ARM Version Is unavailable because There is no JDK ARM v1.8.0

•Still The best way to get minecraft to run in native ARM is MultiMC(macOS)

