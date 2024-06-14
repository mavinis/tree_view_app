# Starting a new Flutter project




19. Update ".gitignore" file with the following content:

     ```gitignore
     # IntelliJ
     *.iml
     *.ipr
     *.iws
     .idea/*
     !.idea/codeStyles
     !.idea/runConfigurations
     !.idea/spelling
    
     # VS Code
     .vscode/*
     !.vscode/launch.json
     !.vscode/settings.json
     
     # IntelliJ Crashlytics plugin
     com_crashlytics_export_strings.xml
     crashlytics.properties
     crashlytics-build.properties
     fabric.properties
    
     # FVM
     .fvm/
    
     # Generated files
     lib/**/*.g.dart
     lib/**/*.gr.dart
     lib/**/*.gen.dart
     lib/**/*.freezed.dart
     lib/**/*.config.dart
     lib/assets/
    
     # Firebase Hosting
     /.firebase/**.cache
    
     # Google Play upload keystore
     /android/key.properties
     ```

20. Configure Version Control:
    * Initialize git with the prod branch `git init -b prod`
    * Connect to remote repository `git remote add origin https://github.com/mavinis/tree_view_app.git`
    * Add and commit the initial project `git add .` `git commit -m "initial project"`
    * Create branch stg from prod `git checkout -b stg prod`
    * Push dev to remote `git push -u origin stg`
    * Create branch dev from prod `git checkout -b dev prod`
    * Push dev to remote `git push -u origin dev`
