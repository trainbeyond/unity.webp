# Linux WebP native dependency

`libwebp.so` links to the `libsharpyuv.so.0` SONAME. Unity must preload the
bundled `libsharpyuv.so` plugin so editor imports do not depend on a matching
system package being installed.
