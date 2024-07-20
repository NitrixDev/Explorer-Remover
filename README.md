# Explorer-Remover

This simple batch script will get rid of the annoying TJprojMain malware, also known as fake explorer.exe/svchost.exe, which infects all your exe files to spread and disguises itself as common system files.

The virus drops the fake system files at Windows\Resources and Windows\Resources\Themes folders.
All we need to do is enter a loop of ending the task and then deleting the files immediately,
before they manage to open again or be restored by their "friends".
When we make sure the files are not in the system anymore, the program finishes.
Works for C:, D: and E: windows drive letters.

Fyi, if you have an infected file you need to recover, you can easily get the original file with a help of a tool called byte_stinker. (https://github.com/jack51706/byte_stinker) byte stinker binary: https://github.com/skidaim/byte_stinker/releases/download/1.0/byte_stinker.exe
