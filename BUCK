java_library(
  name = 'platform-lib',
  srcs = glob([
    'src/**/*.java',
  ]),
)

java_binary(
  name = 'platform',
  main_class = 'io.njlr.platform.Main',
  deps = [
    ':platform-lib',
  ],
)
