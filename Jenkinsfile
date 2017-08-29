@Library("mylib")

import com.github.cbuschka.jenkins_scripting_library.Lib

def lib = new Lib()

node {
 stage("step #1") {
  parallel(
    "a": {
         lib.sayHello()
    },
    "b": {
         lib.sayHello()
    }
  )
 }
}
