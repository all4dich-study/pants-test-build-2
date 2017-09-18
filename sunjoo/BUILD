jvm_binary(name = 'main',
  source = 'src/main/sunjoo/HelloWorld.java',
  dependencies = [
    ':test-lib'
  ],
  main = 'sunjoo.HelloWorld',
  basename = 'sunjoo',
)


java_library(name = 'test-lib', 
    sources=globs('**/*.java'),
    platform='java7',
)
