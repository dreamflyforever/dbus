all: server client

server: server.cpp
	g++ -o server server.cpp `pkg-config --libs --cflags dbus-1 dbus-glib-1 glib-2.0`


client: client.cpp
	g++ -o client client.cpp `pkg-config --libs --cflags dbus-1 dbus-glib-1 glib-2.0`

clean:
	rm client server
