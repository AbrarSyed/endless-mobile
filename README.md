# Endless Mobile

This is a fork of [endless-sky](https://endless-sky.github.io/) that will attempt to add android support, as well as touchscreen and user interface updates that should make it useful for other platforms as well. 

The android branch will be the main branch that developement takes place against, and the master branch will be the lastest endless-sky branch that the master branch is based on. 

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="80">](https://f-droid.org/packages/com.github.thewierdnut.endless_mobile/)

# CI builds
If you are feeling particularly brave, you can try out one of the [debug apks generated by the CI build](https://github.com/thewierdnut/endless-mobile/releases)

# Build Instructions
## Desktop build
Most development is done on using the [SCons](https://scons.org/) build tool to compile the project. For those wishing to use an IDE, project files are provided for [XCode](https://developer.apple.com/xcode/) and [Code::Blocks](https://www.codeblocks.org/) to simplify the project setup. It is possible to use other IDEs or build systems to compile the game, but support is not provided.  
For full installation instructions, consult the [Build Instructions](https://github.com/thewierdnut/endless-mobile/blob/master/readme-developer.md) readme.
## Android build
Android builds are self contained within the android/ folder. See the [Build Instructions](https://github.com/thewierdnut/endless-mobile/blob/android/android/build_instructions.md) there for more details.
