# EasingCore [![license](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](https://github.com/setchi/Easings/blob/master/LICENSE)
Core Easing Implementation for Unity.

## API
```csharp
public static EasingFunction Get(Ease type)
```

## Usage
```csharp
var easeOutCubic = Easing.Get(Ease.OutCubic);
var p = easeOutCubic(0.5f);
```

## Installation
### Unity Package Manager
Add a reference to the repository in the [`Packages\manifest.json`](https://docs.unity3d.com/Packages/com.unity.package-manager-ui@1.8/manual/index.html#project-manifests) file in your project directory:

```json
{
  "dependencies": {
    "jp.setchi.easingcore": "https://github.com/setchi/EasingCore.git#upm"
  }
}
```

### Manual
Clone or download this repository into the Assets directory of your project.

## Author
[setchi](https://github.com/setchi)

## License
[MIT](https://github.com/setchi/EasingCore/blob/master/LICENSE)
