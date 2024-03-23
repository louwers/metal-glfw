# GLFW + Metal + Bazel

`glfw-metal-example.m` from https://gist.github.com/gcatlin/987be74e2d58da96093a7598f3fbfb27

```
brew install bazelisk glfw3
```

```
bazel run //:glfw-metal-example --linkopt=-L/opt/homebrew/lib
```

