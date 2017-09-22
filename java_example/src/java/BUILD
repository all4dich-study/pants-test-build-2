jvm_binary(name = 'main',
  source = 'org/sunjoo/HelloWorld.java',
  dependencies = [
    ':test-lib'
  ],
  main = 'org.sunjoo.HelloWorld',
  basename = 'sunjoo',
)


java_library(name = 'test-lib', 
    sources=globs('org/testlib/*.java'),
)
