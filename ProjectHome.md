The project is a multimedia player on WM5 & WM6. It use TCPMP 0.72RC1 for reference, but written in C++, and more understandable than TCPMP itself.

1. The most valuable module of this project, is the architecture of a multimedia player on embedded system. It's well designed, portable, and flexible to any type of filters (readers, audio/video decoders, renderers).

2. The core of this player is named "popcore", It uses an adapator layer to separate the multimedia logic from the operating system, so the "popcore" can be easily port to other embedded OS.

3. The audio and video decoders are using some other open project, such as libmad, then I wrap their interface to the player.

4. readers and renderers are plaform relatived.

5. This project includes some commerial libs, decoding wmv, wma, rmvb. In these filters, I can only publish the binary file, but not the source code.
