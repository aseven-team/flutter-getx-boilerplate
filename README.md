# Flutter GetX Boilerplate

This is a boilerplate project for Flutter using the GetX state management.

## Features
- GetX for state management
- .env File

## Usage

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/aseven-team/flutter_getx_boilerplate.git
```

**2. Install the dependencies**

```bash
flutter pub get
```

**3. Configure the project**

- **Change package name**

```
dart run change_app_package_name:main id.co.aseven.flutter_boilerplate
```

Above command will change the package name and application id to `id.co.aseven.flutter_boilerplate`.


- **Create environment file**

Copy the `.env.example` file to `*.env` and change the values.

- **Change launcher icon**

To change the launcher icon, replace the `assets/launcher_icon.png` file with your icon and run the following command:

```bash
dart run flutter_launcher_icons
```

Take a look at the [Flutter Launcher Icons](https://pub.dev/packages/flutter_launcher_icons) package for more information.

### Build

**Android**

To build the project for Android, follow the instructions in the Flutter documentation: [https://docs.flutter.dev/deployment/android](https://docs.flutter.dev/deployment/android)

> Because we are using .env file defining some configurations, don't forget to add `--dart-define-from-file=.env` to the build command.

Example:

```bash
flutter build apk --dart-define-from-file=.env
```

**iOS**

@todo

## Packages

- [GetX](https://pub.dev/packages/get)
- [change_app_package_name](https://pub.dev/packages/change_app_package_name)
- [flutter_env_native](https://pub.dev/packages/flutter_env_native)
- [Flutter Launcher Icons](https://pub.dev/packages/flutter_launcher_icons)