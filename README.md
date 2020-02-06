# CIdemo
CI example project
To publish app to the AppCenter use following command from project root directory:
appcenter distribute release -f app/build/outputs/apk/debug/app-debug.apk -r "Release from CLI" --group Collaborators
# Configure appcenter CLI
npm install appcenter-cli
appcenter login
appcenter distribute release -f <path to apk file> -r "My CLI Release" --group <group name>
