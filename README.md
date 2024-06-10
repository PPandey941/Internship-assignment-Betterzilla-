The project contained some aws information so I need to zip it before pushing. 
The server was not running since,
My system support 64bit so the bcrypt was node compatible with my node js so I uninstalled the bcrypt and installed bcryptjs
By using the following code.

**npm uninstall bcrypt
npm install bcryptjs**

The client side was not working so I used the following code to make it run 
# Navigate to the client directory
cd C:\Users\Lenovo\Desktop\GE-CoPilot\client

# Remove node_modules and package-lock.json
Remove-Item -Recurse -Force .\node_modules
Remove-Item -Force package-lock.json

# Reinstall dependencies
npm install

# (Optional) Use yarn instead of npm
# npm install --global yarn
# yarn install

# If problems persist, use esbuild-wasm
# npm install esbuild-wasm


**You can add these code to Chatgpt to find how to reverse the changes I did**
