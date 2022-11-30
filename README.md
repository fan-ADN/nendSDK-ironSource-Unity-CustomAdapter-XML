# nendSDK-ironSource-Unity-CustomAdapter-XML

## About this XML file
This is the custom adapter XML for adding the nend Custom Adapter to the [ironSource Unity plugin](https://developers.is.com/ironsource-mobile/unity/unity-plugin/).


## Add nend custom adapter
Download ISnendCustomAdapterDependencies.xml from this repository and Follow the [EDM4U manual](https://github.com/googlesamples/unity-jar-resolver#android-resolver-usage) to add the XML file to your Unity project.  
The XML file just needs to be under an Editor directory. For example, `Unity/Assets/Editor/ISnendCustomAdapterDependencies.xml`.
For more information, please refer to [here](https://developers.is.com/ironsource-mobile/unity/custom-adapter-integration-unity/#step-1).


## Adding SKAdNetwork ID
In iOS, follow the steps in [Adding SKAdNetwork IDs Manually](https://developers.is.com/ironsource-mobile/unity/ios-14-network-support/) to add nend's SKAdNetworkIdentifier.  
nend's SKAdNetwork ID is `eh6m2bh4zr.skadnetwork`.

```xml
<key>SKAdNetworkItems</key>
<array>
    <dict>
        <key>SKAdNetworkIdentifier</key>
        <string>eh6m2bh4zr.skadnetwork</string>
    </dict>
</array>
```

## License
Copyright (C) FAN Communications, Inc.