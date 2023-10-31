
![Logo](https://raw.githubusercontent.com/LavaGang/MelonLoader.Installer/master/Resources/ML_Icon.png)


## Authors

- [@xmoderlive(aka NightSky)](https://www.github.com/xmoderlive)

- [NightSky000](https://github.com/Nightsky000)


## About This Project

This is the base template for Melon Mod Development. This is a base template you can use it to create mods. Follow the steps below to start making Melons

## Steps

    1.Open the .sln Project in visual studio
    2.Set debug to release
    3.Add the following project references
        I.UnityEngine.dll(Found at Gamefolder/GameName_Data/Managed/UnityEngine.dll)
        II.UnityEngine.CoreModule.dll(Found at Gamefolder/GameName_Data/Managed/UnityEngine.CoreModule.dll)
        III.UnityEngine.InputLegacyModule.dll(Found at Gamefolder/GameName_Data/Managed/UnityEngine.InputLegacyModule.dll)
        VI.Assembly-CSharp.dll(Found at Gamefolder/GameName_Data/Managed/Assembly-CSharp.dll)
        V.MelonLoader.dll(Found at Gamefolder/MelonLoader/MelonLoader.dll)
        VI.0Harmony.dll(Found at Gamefolder/MelonLoader/0Harmony.dll)
    4.Open "OkCheaterMain.cs"
    5.In "public override void OnUpdate()" you will write your code
[See](https://melonwiki.xyz/#/modders/quickstart?id=melon-callbacks) This for more info

