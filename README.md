# GTK
compile flags: gcc $(pkg-config --cflags gtk4) -o binaryName sourceName.c $(pkg-config -libs gtk4)
