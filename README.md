# Sync and build Discovery

### Sync Discovery

1. Create a folder for your project

   e.g. ``` mkdir discovery ```

2. Enter into the folder you created

   e.g. ``` cd discovery ```

3. Init the repo into your project's folder

   ``` 
   repo init -u https://github.com/DiscoveryTeam/platform_manifest -b 8.1 
   ```
   
4. Sync your project 

   ```
   repo sync 
   ```
   
### Clone your device sources

You have to clone manually all the needed repositories to build for your device. Like device tree, kernel and vendor.

### Build Discovery

   ```
   source build/envsetup.sh
   ```
   
   Replace "devicename" with the codename of your device e.g. ```breakfast discovery_dumpling```
   
   ```
   breakfast discovery_devicename
   
   brunch discovery_devicename
   ```
