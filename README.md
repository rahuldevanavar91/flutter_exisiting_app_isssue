# flutter_exisiting_app_isssue
Add Setting.gradle 
include ':app'

setBinding(new Binding([gradle: this]))
evaluate(new File(
        '/$path/flutter_example/.android/include_flutter.groovy'
))

replace $path wtih flutter module code path
