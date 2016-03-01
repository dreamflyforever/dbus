dbus: dbus-example.c
	gcc -o dbus dbus-example.c `pkg-config --libs --cflags dbus-1 dbus-glib-1 glib-2.0`
	#g++ -o dbus `pkg-config --cflags --libs dbus-1` dbus-example.c

clean:
	rm dbus
