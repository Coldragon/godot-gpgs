# GooglePlayGameServices
This is a fork of the Google Play Game Services module for Godot Engine (https://github.com/okamstudio/godot), see it's Readme to find more about it. This fork is just an adaptation to make it ready to use for the new android export template, no modification in the code have been made.

#How to use
- Configure, install  and enable the "Android Custom Template" for your project, just follow the [official documentation](https://docs.godotengine.org/en/latest/getting_started/workflow/export/android_custom_build.html);
- download or clone this repository;
- drop the ```gpgs``` directory (from this repository) inside the ```res://android/``` directory on your Godot project.
- on the Project -> Export -> Android -> Options -> Permissions: check the permissions for _Access Network State_ and _Internet_
- on the Project Settings -> Android -> Modules, add the string:

```
org/godotengine/godot/GodotGooglePlayGameServices
```

## Demo
You can find an example on "demo/GooglePlayGameServices.gd" file.

## License
MIT license
