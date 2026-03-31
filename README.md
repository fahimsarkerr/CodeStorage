# CodeStorage

## For Navigation
https://developer.android.com/jetpack/androidx/releases/navigation
```
plugins {
  // Kotlin serialization plugin for type safe routes and navigation arguments
  kotlin("plugin.serialization") version "2.0.21"
}

dependencies {
  val nav_version = "2.9.7"

  // Jetpack Compose integration
  implementation("androidx.navigation:navigation-compose:$nav_version")

  // JSON serialization library, works with the Kotlin serialization plugin
  implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.7.3")

----- for Views and Fragments integration -----

  // Views/Fragments integration
  implementation("androidx.navigation:navigation-fragment:$nav_version")
  implementation("androidx.navigation:navigation-ui:$nav_version")
}

import kotlinx.serialization.Serializable
import androidx.navigation.compose.NavHost
import androidx.navigation.compose.composable
import androidx.navigation.compose.rememberNavController
```
## For Preferences DataStore
https://developer.android.com/jetpack/androidx/releases/datastore
```
    dependencies {
        // Preferences DataStore (SharedPreferences like APIs)
        implementation("androidx.datastore:datastore-preferences:1.2.1")
    }
```
