# Mod-Resources
A place to access public artifacts from all Kyubion Studios mod projects



Maven `gradle` Dependency Script
```
repositories {
    maven {
        name = 'Kyubion Mod Resources'
        url "https://raw.githubusercontent.com/Kyubion-Studios/Mod-Resources/main/maven/"
    }
}

dependencies {
    modApi "<group>.<modId>:<mod_id>-<mod_loader>:<mod_version>"
}
```