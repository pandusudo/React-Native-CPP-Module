# What i think about React native C++ Module
This repo is just for testing the React native C++ Module. I think react native C++ module is very useful to hide your api key.
It will be useless if you want to hide your backend ip address, because the http traffic can be seen by sniffing method.

Hackers still can get your api key actually, they will use reverse engineering method to get your api key.
To avoid reverse engineering, you can use ProGuard by google, by editing the build.gradle file.
But it's not completely safe. Some hackers somehow still can get your api key even you have turned the ProGuard on.

Decompile java is really easy, that's why you need to use c++ to hide your api key.
It will be harder to decompile if you hide it in c++ native module.
But i think in the future, hackers will somehow able to decompile c++ easily, because you know, NO SYSTEM IS SAFE
