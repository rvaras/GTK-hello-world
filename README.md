# GTK-hello-world
This is just a repo to start learning GTK development

Compile with: 
gcc $(pkg-config --cflags gtk4) -o hello-world-gtk hello-world-gtk.c $(pkg-config --libs gtk4)
