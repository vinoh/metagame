Meta-Game aims at being a full-featured engine for computer role-playing games, possibly massively multi-player online ones.
Its purpose is also to be an exercise in style and design, making it elegant using modern C++ techniques, and even exploiting features of the forthcoming C++0x standard which already has some parts implemented in some compilers.

It uses a client/server approach with a simple and clearly-specified protocol so that the client and the server can be independent and thus favor competing clients, eventually with different capabilities (text mode, 2D, 3D...).
Development focuses for now on the server which is designed with a hybrid programming approach, combining C++ with Python, since it is to be highly scriptable for rules and items.

You may want to read the [Overview](Overview.md) of what the project aims to provide.

See also our [Coding Guidelines](CodingGuidelines.md).

You are also encouraged to follow and join our MailingList to give your opinion, participate and read up on the development discussions.