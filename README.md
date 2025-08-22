You need to have SFML installed to compile. sfml-dev.org/download/sfml/2.5.1.
Run this command: g++ -c main.cpp board.cpp piece.cpp pieceTextures.cpp chessGame.cpp -I <sfml-install-path>\include -mwindows.
g++ main.o board.o piece.o pieceTextures.o chessGame.o -mwindows -L <sfml-install-path>\lib -lsfml-graphics -lsfml-window -lsfml-system.
You need to have sfml-graphics-2.dll , sfml-system-2.dll and sfml-window-2.dll in the same folder as the exe