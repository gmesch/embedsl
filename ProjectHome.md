The Embedsl library allows language level integration of WebGL shaders and Javascript. A builder API is used to define shader programs as expression trees in the Javascript application, and the library creates the glsl source code from that javascript expression.

When used with the closure compiler, this gives shader language level type safety to the glsl program.