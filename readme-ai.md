<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>SIMPLE-WEATHER-APP</h1>
<h3>◦ HTTPStatus Exception: 401</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Swift-F05138.svg?style=plastic&logo=Swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=plastic&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=plastic&logo=YAML&logoColor=white" alt="YAML" />
<img src="https://img.shields.io/badge/C-A8B9CC.svg?style=plastic&logo=C&logoColor=black" alt="C" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF.svg?style=plastic&logo=Kotlin&logoColor=white" alt="Kotlin" />

<img src="https://img.shields.io/badge/CMake-064F8C.svg?style=plastic&logo=CMake&logoColor=white" alt="CMake" />
<img src="https://img.shields.io/badge/Gradle-02303A.svg?style=plastic&logo=Gradle&logoColor=white" alt="Gradle" />
<img src="https://img.shields.io/badge/Dart-0175C2.svg?style=plastic&logo=Dart&logoColor=white" alt="Dart" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style=plastic&logo=JSON&logoColor=white" alt="JSON" />
</p>
<img src="https://img.shields.io/github/license/mohdop/simple-weather-app?style=plastic&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/mohdop/simple-weather-app?style=plastic&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/mohdop/simple-weather-app?style=plastic&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/mohdop/simple-weather-app?style=plastic&color=5D6D7E" alt="GitHub top language" />
</div>

---

##  Table of Contents
- [ Table of Contents](#-table-of-contents)
- [ Overview](#-overview)
- [ Features](#-features)
- [ repository Structure](#-repository-structure)
- [ Modules](#modules)
- [ Getting Started](#-getting-started)
    - [ Installation](#-installation)
    - [ Running simple-weather-app](#-running-simple-weather-app)
    - [ Tests](#-tests)
- [ Roadmap](#-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---


##  Overview

HTTPStatus Exception: 401

---

##  Features

HTTPStatus Exception: 401

---


##  Repository Structure

```sh
└── simple-weather-app/
    ├── .metadata
    ├── analysis_options.yaml
    ├── android/
    │   ├── app/
    │   │   ├── build.gradle
    │   │   └── src/
    │   ├── build.gradle
    │   ├── gradle/
    │   │   └── wrapper/
    │   └── settings.gradle
    ├── ios/
    │   ├── Flutter/
    │   │   ├── AppFrameworkInfo.plist
    │   │   ├── Debug.xcconfig
    │   │   └── Release.xcconfig
    │   ├── Runner/
    │   │   ├── AppDelegate.swift
    │   │   ├── Assets.xcassets/
    │   │   ├── Base.lproj/
    │   │   ├── Info.plist
    │   │   └── Runner-Bridging-Header.h
    │   ├── Runner.xcodeproj/
    │   │   ├── project.pbxproj
    │   │   ├── project.xcworkspace/
    │   │   └── xcshareddata/
    │   ├── Runner.xcworkspace/
    │   │   ├── contents.xcworkspacedata
    │   │   └── xcshareddata/
    │   └── RunnerTests/
    │       └── RunnerTests.swift
    ├── lib/
    │   ├── main.dart
    │   ├── model/
    │   │   ├── weather.dart
    │   │   └── weatherr.dart
    │   ├── pages/
    │   │   ├── weather_page.dart
    │   │   ├── weather_pagee.dart
    │   │   └── widgets.dart
    │   └── service/
    │       ├── weatherService.dart
    │       └── weatherServicee.dart
    ├── linux/
    │   ├── CMakeLists.txt
    │   ├── flutter/
    │   │   ├── CMakeLists.txt
    │   │   ├── generated_plugin_registrant.cc
    │   │   ├── generated_plugin_registrant.h
    │   │   └── generated_plugins.cmake
    │   ├── main.cc
    │   ├── my_application.cc
    │   └── my_application.h
    ├── macos/
    │   ├── Flutter/
    │   │   ├── Flutter-Debug.xcconfig
    │   │   ├── Flutter-Release.xcconfig
    │   │   └── GeneratedPluginRegistrant.swift
    │   ├── Runner/
    │   │   ├── AppDelegate.swift
    │   │   ├── Assets.xcassets/
    │   │   ├── Base.lproj/
    │   │   ├── Configs/
    │   │   ├── DebugProfile.entitlements
    │   │   ├── Info.plist
    │   │   ├── MainFlutterWindow.swift
    │   │   └── Release.entitlements
    │   ├── Runner.xcodeproj/
    │   │   ├── project.pbxproj
    │   │   ├── project.xcworkspace/
    │   │   └── xcshareddata/
    │   ├── Runner.xcworkspace/
    │   │   ├── contents.xcworkspacedata
    │   │   └── xcshareddata/
    │   └── RunnerTests/
    │       └── RunnerTests.swift
    ├── pubspec.lock
    ├── pubspec.yaml
    ├── test/
    │   └── widget_test.dart
    ├── web/
    │   ├── icons/
    │   ├── index.html
    │   └── manifest.json
    └── windows/
        ├── CMakeLists.txt
        ├── flutter/
        │   ├── CMakeLists.txt
        │   ├── generated_plugin_registrant.cc
        │   ├── generated_plugin_registrant.h
        │   └── generated_plugins.cmake
        └── runner/
            ├── CMakeLists.txt
            ├── flutter_window.cpp
            ├── flutter_window.h
            ├── main.cpp
            ├── resource.h
            ├── resources/
            ├── runner.exe.manifest
            ├── Runner.rc
            ├── utils.cpp
            ├── utils.h
            ├── win32_window.cpp
            └── win32_window.h

```

---


##  Modules

<details closed><summary>Root</summary>

| File                                                                                                                                                                      | Summary                   |
| ---                                                                                                                                                                       | ---                       |
| [.metadata](https://github.com/mohdop/simple-weather-app/blob/main/.metadata)                                                                                             | HTTPStatus Exception: 401 |
| [analysis_options.yaml](https://github.com/mohdop/simple-weather-app/blob/main/analysis_options.yaml)                                                                     | HTTPStatus Exception: 401 |
| [pubspec.lock](https://github.com/mohdop/simple-weather-app/blob/main/pubspec.lock)                                                                                       | HTTPStatus Exception: 401 |
| [pubspec.yaml](https://github.com/mohdop/simple-weather-app/blob/main/pubspec.yaml)                                                                                       | HTTPStatus Exception: 401 |
| [build.gradle](https://github.com/mohdop/simple-weather-app/blob/main/android\build.gradle)                                                                               | HTTPStatus Exception: 401 |
| [settings.gradle](https://github.com/mohdop/simple-weather-app/blob/main/android\settings.gradle)                                                                         | HTTPStatus Exception: 401 |
| [build.gradle](https://github.com/mohdop/simple-weather-app/blob/main/android\app\build.gradle)                                                                           | HTTPStatus Exception: 401 |
| [MainActivity.kt](https://github.com/mohdop/simple-weather-app/blob/main/android\app\src\main\kotlin\com\example\weather_app\MainActivity.kt)                             | HTTPStatus Exception: 401 |
| [AppFrameworkInfo.plist](https://github.com/mohdop/simple-weather-app/blob/main/ios\Flutter\AppFrameworkInfo.plist)                                                       | HTTPStatus Exception: 401 |
| [Debug.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/ios\Flutter\Debug.xcconfig)                                                                       | HTTPStatus Exception: 401 |
| [Release.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/ios\Flutter\Release.xcconfig)                                                                   | HTTPStatus Exception: 401 |
| [AppDelegate.swift](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\AppDelegate.swift)                                                                  | HTTPStatus Exception: 401 |
| [Info.plist](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Info.plist)                                                                                | HTTPStatus Exception: 401 |
| [Runner-Bridging-Header.h](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Runner-Bridging-Header.h)                                                    | HTTPStatus Exception: 401 |
| [Contents.json](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json)                                       | HTTPStatus Exception: 401 |
| [Contents.json](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json)                                     | HTTPStatus Exception: 401 |
| [LaunchScreen.storyboard](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Base.lproj\LaunchScreen.storyboard)                                           | HTTPStatus Exception: 401 |
| [Main.storyboard](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner\Base.lproj\Main.storyboard)                                                           | HTTPStatus Exception: 401 |
| [project.pbxproj](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcodeproj\project.pbxproj)                                                            | HTTPStatus Exception: 401 |
| [contents.xcworkspacedata](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata)                      | HTTPStatus Exception: 401 |
| [IDEWorkspaceChecks.plist](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist)         | HTTPStatus Exception: 401 |
| [WorkspaceSettings.xcsettings](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings) | HTTPStatus Exception: 401 |
| [Runner.xcscheme](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme)                                     | HTTPStatus Exception: 401 |
| [contents.xcworkspacedata](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcworkspace\contents.xcworkspacedata)                                        | HTTPStatus Exception: 401 |
| [IDEWorkspaceChecks.plist](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist)                           | HTTPStatus Exception: 401 |
| [WorkspaceSettings.xcsettings](https://github.com/mohdop/simple-weather-app/blob/main/ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings)                   | HTTPStatus Exception: 401 |
| [RunnerTests.swift](https://github.com/mohdop/simple-weather-app/blob/main/ios\RunnerTests\RunnerTests.swift)                                                             | HTTPStatus Exception: 401 |
| [main.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\main.dart)                                                                                         | HTTPStatus Exception: 401 |
| [weather.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\model\weather.dart)                                                                             | HTTPStatus Exception: 401 |
| [weatherr.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\model\weatherr.dart)                                                                           | HTTPStatus Exception: 401 |
| [weather_page.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\pages\weather_page.dart)                                                                   | HTTPStatus Exception: 401 |
| [weather_pagee.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\pages\weather_pagee.dart)                                                                 | HTTPStatus Exception: 401 |
| [widgets.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\pages\widgets.dart)                                                                             | HTTPStatus Exception: 401 |
| [weatherService.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\service\weatherService.dart)                                                             | HTTPStatus Exception: 401 |
| [weatherServicee.dart](https://github.com/mohdop/simple-weather-app/blob/main/lib\service\weatherServicee.dart)                                                           | HTTPStatus Exception: 401 |
| [CMakeLists.txt](https://github.com/mohdop/simple-weather-app/blob/main/linux\CMakeLists.txt)                                                                             | HTTPStatus Exception: 401 |
| [main.cc](https://github.com/mohdop/simple-weather-app/blob/main/linux\main.cc)                                                                                           | HTTPStatus Exception: 401 |
| [my_application.cc](https://github.com/mohdop/simple-weather-app/blob/main/linux\my_application.cc)                                                                       | HTTPStatus Exception: 401 |
| [my_application.h](https://github.com/mohdop/simple-weather-app/blob/main/linux\my_application.h)                                                                         | HTTPStatus Exception: 401 |
| [CMakeLists.txt](https://github.com/mohdop/simple-weather-app/blob/main/linux\flutter\CMakeLists.txt)                                                                     | HTTPStatus Exception: 401 |
| [generated_plugins.cmake](https://github.com/mohdop/simple-weather-app/blob/main/linux\flutter\generated_plugins.cmake)                                                   | HTTPStatus Exception: 401 |
| [generated_plugin_registrant.cc](https://github.com/mohdop/simple-weather-app/blob/main/linux\flutter\generated_plugin_registrant.cc)                                     | HTTPStatus Exception: 401 |
| [generated_plugin_registrant.h](https://github.com/mohdop/simple-weather-app/blob/main/linux\flutter\generated_plugin_registrant.h)                                       | HTTPStatus Exception: 401 |
| [Flutter-Debug.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Flutter\Flutter-Debug.xcconfig)                                                     | HTTPStatus Exception: 401 |
| [Flutter-Release.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Flutter\Flutter-Release.xcconfig)                                                 | HTTPStatus Exception: 401 |
| [GeneratedPluginRegistrant.swift](https://github.com/mohdop/simple-weather-app/blob/main/macos\Flutter\GeneratedPluginRegistrant.swift)                                   | HTTPStatus Exception: 401 |
| [AppDelegate.swift](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\AppDelegate.swift)                                                                | HTTPStatus Exception: 401 |
| [DebugProfile.entitlements](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\DebugProfile.entitlements)                                                | HTTPStatus Exception: 401 |
| [Info.plist](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Info.plist)                                                                              | HTTPStatus Exception: 401 |
| [MainFlutterWindow.swift](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\MainFlutterWindow.swift)                                                    | HTTPStatus Exception: 401 |
| [Release.entitlements](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Release.entitlements)                                                          | HTTPStatus Exception: 401 |
| [Contents.json](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json)                                     | HTTPStatus Exception: 401 |
| [MainMenu.xib](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Base.lproj\MainMenu.xib)                                                               | HTTPStatus Exception: 401 |
| [AppInfo.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Configs\AppInfo.xcconfig)                                                          | HTTPStatus Exception: 401 |
| [Debug.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Configs\Debug.xcconfig)                                                              | HTTPStatus Exception: 401 |
| [Release.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Configs\Release.xcconfig)                                                          | HTTPStatus Exception: 401 |
| [Warnings.xcconfig](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner\Configs\Warnings.xcconfig)                                                        | HTTPStatus Exception: 401 |
| [project.pbxproj](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner.xcodeproj\project.pbxproj)                                                          | HTTPStatus Exception: 401 |
| [IDEWorkspaceChecks.plist](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist)       | HTTPStatus Exception: 401 |
| [Runner.xcscheme](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme)                                   | HTTPStatus Exception: 401 |
| [contents.xcworkspacedata](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner.xcworkspace\contents.xcworkspacedata)                                      | HTTPStatus Exception: 401 |
| [IDEWorkspaceChecks.plist](https://github.com/mohdop/simple-weather-app/blob/main/macos\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist)                         | HTTPStatus Exception: 401 |
| [RunnerTests.swift](https://github.com/mohdop/simple-weather-app/blob/main/macos\RunnerTests\RunnerTests.swift)                                                           | HTTPStatus Exception: 401 |
| [widget_test.dart](https://github.com/mohdop/simple-weather-app/blob/main/test\widget_test.dart)                                                                          | HTTPStatus Exception: 401 |
| [index.html](https://github.com/mohdop/simple-weather-app/blob/main/web\index.html)                                                                                       | HTTPStatus Exception: 401 |
| [manifest.json](https://github.com/mohdop/simple-weather-app/blob/main/web\manifest.json)                                                                                 | HTTPStatus Exception: 401 |
| [CMakeLists.txt](https://github.com/mohdop/simple-weather-app/blob/main/windows\CMakeLists.txt)                                                                           | HTTPStatus Exception: 401 |
| [CMakeLists.txt](https://github.com/mohdop/simple-weather-app/blob/main/windows\flutter\CMakeLists.txt)                                                                   | HTTPStatus Exception: 401 |
| [generated_plugins.cmake](https://github.com/mohdop/simple-weather-app/blob/main/windows\flutter\generated_plugins.cmake)                                                 | HTTPStatus Exception: 401 |
| [generated_plugin_registrant.cc](https://github.com/mohdop/simple-weather-app/blob/main/windows\flutter\generated_plugin_registrant.cc)                                   | HTTPStatus Exception: 401 |
| [generated_plugin_registrant.h](https://github.com/mohdop/simple-weather-app/blob/main/windows\flutter\generated_plugin_registrant.h)                                     | HTTPStatus Exception: 401 |
| [CMakeLists.txt](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\CMakeLists.txt)                                                                    | HTTPStatus Exception: 401 |
| [flutter_window.cpp](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\flutter_window.cpp)                                                            | HTTPStatus Exception: 401 |
| [flutter_window.h](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\flutter_window.h)                                                                | HTTPStatus Exception: 401 |
| [main.cpp](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\main.cpp)                                                                                | HTTPStatus Exception: 401 |
| [resource.h](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\resource.h)                                                                            | HTTPStatus Exception: 401 |
| [runner.exe.manifest](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\runner.exe.manifest)                                                          | HTTPStatus Exception: 401 |
| [Runner.rc](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\Runner.rc)                                                                              | HTTPStatus Exception: 401 |
| [utils.cpp](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\utils.cpp)                                                                              | HTTPStatus Exception: 401 |
| [utils.h](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\utils.h)                                                                                  | HTTPStatus Exception: 401 |
| [win32_window.cpp](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\win32_window.cpp)                                                                | HTTPStatus Exception: 401 |
| [win32_window.h](https://github.com/mohdop/simple-weather-app/blob/main/windows\runner\win32_window.h)                                                                    | HTTPStatus Exception: 401 |

</details>

---

##  Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

###  Installation

1. Clone the simple-weather-app repository:
```sh
git clone https://github.com/mohdop/simple-weather-app
```

2. Change to the project directory:
```sh
cd simple-weather-app
```

3. Install the dependencies:
```sh
pub get
```

###  Running simple-weather-app

```sh
dart main.dart
```

###  Tests
```sh
dart test
```

---


##  Project Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/mohdop/simple-weather-app/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/mohdop/simple-weather-app/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/mohdop/simple-weather-app/issues)**: Submit bugs found or log feature requests for MOHDOP.

#### *Contributing Guidelines*

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  License


This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#Top)

---

