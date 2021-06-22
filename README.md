# Amplify Live Streaming #

Based on [AWS Amplify Video Livestreaming and Video on Demand](https://www.youtube.com/watch?v=vM_YoZbLQQ0)

## Project Setup ##

`npm install -g @amplify/cli`

```bash
# Troubleshooting Amplify CLI issues

# See which plugins are missing
amplify plugin scan
amplify plugin list

# Manually add them
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-provider-awscloudformation
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-analytics
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-api
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-auth
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-function
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-hosting
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-interactions
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-notifications
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-predictions
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-storage
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-category-xr
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-codegen
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-console-hosting
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-container-hosting
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-frontend-javascript
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-frontend-flutter
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-frontend-android
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-frontend-ios
amplify plugin add /C/Users/<USER>/AppData/Local/Yarn/Data/global/node_modules/amplify-util-mock

# Configure new user if desired (alternatively use already set up aws profile)
amplify configure
```

The project was created by running:

```bash
mkdir amplify-live-streaming
cd amplify-live-streaming
amplify init
```

To open Amplify Console: `amplify console` (select `Console`, not `Admin UI`)
