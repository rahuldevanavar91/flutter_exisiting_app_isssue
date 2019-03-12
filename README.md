# Changes required  
change settings.gradle 


include ':app'

setBinding(new Binding([gradle: this]))

evaluate(new File(
        '/$path/flutter_example/.android/include_flutter.groovy'
))

replace $path wtih flutter module code root dir
