# Proffy

Proffy is a platform to connect students with teachers.

## Requirements
- Node 16.20.2
- Yarn
- Expo

I recommend creating a virtual environment to avoid conflicts with another version of node and expo. You can use Python's virtualenv. If you don't want to it skip the next step.

If you have a problem on Windows with PowerShell execution policies: [How to resolve it.](https://gist.github.com/MatteusSouza/3dc8812552e0727a717c370bda09b736)

Run in the project root folder: `Python3 -m venv venv` ative a venv `. venv/bin/activate` install nodeenv `pip install nodeenv` install the recommended node version `nodeenv --node=16.20.2 node16` exit venv with `deactivate`.

Activate the virtual environment in the project root folder with `. node16/bin/activate`.
Install yarn `npm install --global yarn` and install expo with `yarn add expo`
To exit the environment: `deactivate_node`

## How to run?

  
For the following commands, you must be in the node16 virtual environment. Then activate it from the project's root folder. `node16/bin/activate`

**Server**:

    cd server
    yarn install
    yarn knex:migrate
    yarn start
   
  **Web**
Esteja com o server rodando em outro terminal e em seguida :

    cd web
    yarn install
    yarn start

**Mobile**
You will need an [emulator](https://developer.android.com/studio) or run directly from your smartphone using the expo client for 

You can run it directly from your smartphone using the Expo client for [Android](https://play.google.com/store/apps/details?id=host.exp.exponent) or [iOS](https://apps.apple.com/us/app/expo-go/id982107779) or with an [emulator](https://developer.android.com/studio).  
###### [How to use Android Studio](https://developer.android.com/studio/run/emulator-launch-separate-window)

	    cd mobile
	    yarn install
	    yarn start

