- 👋 Hi, I’m @Osamasemsem
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Osamasemsem/Osamasemsem is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# The largest heading
## The second largest heading
###### The smallest

  Step 1: steal underpants
  Step 2: do the hokey pokey
    | Step 1: put your left foot in
    | Step 2: take your left foot out
    | Step 3: put your left foot in again
    | Step 4: shake it all about
  Step 3: profit!
mentation:
harvester_jt.pl
harvester_jt.pl assembly123.bkm
harvester_jt.pl assembly123.bkm assembly124.bkm assembly125.bkm
harvester_jt.pl AssemblyBookmarks
mentation:
harvester_jt.pl
harvester_jt.pl assembly123.bkm
harvester_jt.pl assembly123.bkm assembly124.bkm assembly125.bkm
harvester_jt.pl AssemblyBookmarks
https://drive.google.com/file/d/1i6B5vTMOzJFMaDN_f3w14aEw3KYXmq1V/view?usp=drivesdk
 
 ​{ 
 ​        ​"version"​: ​"0.1.0"​, 
 ​        ​"configurations"​: ​[ 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Gulp Build"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/node_modules/gulp/bin/gulp.js"​, 
 ​                        ​"stopOnEntry"​: ​true​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"hygiene" 
 ​                        ​] 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"restart"​: ​true​, 
 ​                        ​"name"​: ​"Attach to Extension Host"​, 
 ​                        ​// set to a large number: if there is an issue we're debugging that keeps 
 ​                        ​// the extension host from coming up, or the renderer is paused/crashes 
 ​                        ​// before it happens, developers will get an annoying alert, e.g. #126826. 
 ​                        ​// This can be set to 0 in 1.59. 
 ​                        ​"timeout"​: ​999999999​, 
 ​                        ​"port"​: ​5870​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js"​, 
 ​                                ​"${workspaceFolder}/extensions/*/out/**/*.js" 
 ​                        ​] 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-chrome"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to Shared Process"​, 
 ​                        ​"timeout"​: ​30000​, 
 ​                        ​"port"​: ​9222​, 
 ​                        ​"urlFilter"​: ​"*sharedProcess.html*"​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"hidden"​: ​true 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to Search Process"​, 
 ​                        ​"port"​: ​5876​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​] 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to Pty Host Process"​, 
 ​                        ​"port"​: ​5877​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​] 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to CLI Process"​, 
 ​                        ​"port"​: ​5874​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​] 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to Main Process"​, 
 ​                        ​"timeout"​: ​30000​, 
 ​                        ​"port"​: ​5875​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"hidden"​: ​true​, 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Emmet Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/emmet/test-workspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/emmet"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/emmet/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​6 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Git Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"/tmp/my4g9l"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/git"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/git/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/git/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​6 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Github Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/github/testWorkspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/github"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/github/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/github/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​6 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code API Tests (single folder)"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​// "${workspaceFolder}", // Uncomment for running out of sources. 
 ​                                ​"${workspaceFolder}/extensions/vscode-api-tests/testWorkspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/vscode-api-tests"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/vscode-api-tests/out/singlefolder-tests"​, 
 ​                                ​"--disable-extensions" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​3 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code API Tests (workspace)"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/vscode-api-tests/testworkspace.code-workspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/vscode-api-tests"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/vscode-api-tests/out/workspace-tests" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​4 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Tokenizer Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/vscode-colorize-tests/test"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/vscode-colorize-tests"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/vscode-colorize-tests/out" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​5 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Custom Editor Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/vscode-custom-editor-tests/test-workspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/vscode-custom-editor-tests"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/vscode-custom-editor-tests/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​6 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-chrome"​, 
 ​                        ​"request"​: ​"attach"​, 
 ​                        ​"name"​: ​"Attach to VS Code"​, 
 ​                        ​"browserAttachLocation"​: ​"workspace"​, 
 ​                        ​"port"​: ​9222​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"resolveSourceMapLocations"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"perScriptSourcemaps"​: ​"yes" 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-chrome"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Launch VS Code Internal"​, 
 ​                        ​"windows"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code.bat" 
 ​                        ​}​, 
 ​                        ​"osx"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code.sh" 
 ​                        ​}​, 
 ​                        ​"linux"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code.sh" 
 ​                        ​}​, 
 ​                        ​"port"​: ​9222​, 
 ​                        ​"timeout"​: ​20000​, 
 ​                        ​"env"​: ​{ 
 ​                                ​"VSCODE_EXTHOST_WILL_SEND_SOCKET"​: ​null​, 
 ​                                ​"VSCODE_SKIP_PRELAUNCH"​: ​"1" 
 ​                        ​}​, 
 ​                        ​"cleanUp"​: ​"wholeBrowser"​, 
 ​                        ​"urlFilter"​: ​"*workbench.html*"​, 
 ​                        ​"runtimeArgs"​: ​[ 
 ​                                ​"--inspect=5875"​, 
 ​                                ​"--no-cached-data"​, 
 ​                                ​// for general runtime freezes: https://github.com/microsoft/vscode/issues/127861#issuecomment-904144910 
 ​                                ​"--disable-features=CalculateNativeWinOcclusion"​, 
 ​                        ​]​, 
 ​                        ​"webRoot"​: ​"${workspaceFolder}"​, 
 ​                        ​"cascadeTerminateToConfigurations"​: ​[ 
 ​                                ​"Attach to Extension Host" 
 ​                        ​]​, 
 ​                        ​"userDataDir"​: ​"${workspaceFolder}/.profile-oss"​, 
 ​                        ​"pauseForSourceMap"​: ​false​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"browserLaunchLocation"​: ​"workspace"​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"hidden"​: ​true​, 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"VS Code Server (Web)"​, 
 ​                        ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code-server.sh"​, 
 ​                        ​"windows"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code-server.bat"​, 
 ​                        ​}​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"0_vscode"​, 
 ​                                ​"order"​: ​2 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Main Process"​, 
 ​                        ​"attachSimplePort"​: ​5875​, 
 ​                        ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code.sh"​, 
 ​                        ​"windows"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/scripts/code.bat"​, 
 ​                        ​}​, 
 ​                        ​"runtimeArgs"​: ​[ 
 ​                                ​"--inspect-brk=5875"​, 
 ​                                ​"--no-cached-data"​, 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"1_vscode"​, 
 ​                                ​"order"​: ​1 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-chrome"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"outFiles"​: ​[​]​, 
 ​                        ​"perScriptSourcemaps"​: ​"yes"​, 
 ​                        ​"name"​: ​"VS Code Server (Web, Chrome)"​, 
 ​                        ​"url"​: ​"http://localhost:8080?tkn=dev-token"​, 
 ​                        ​"preLaunchTask"​: ​"Run code server"​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"0_vscode"​, 
 ​                                ​"order"​: ​3 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-msedge"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"outFiles"​: ​[​]​, 
 ​                        ​"perScriptSourcemaps"​: ​"yes"​, 
 ​                        ​"name"​: ​"VS Code Server (Web, Edge)"​, 
 ​                        ​"url"​: ​"http://localhost:8080?tkn=dev-token"​, 
 ​                        ​"pauseForSourceMap"​: ​false​, 
 ​                        ​"preLaunchTask"​: ​"Run code server"​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"0_vscode"​, 
 ​                                ​"order"​: ​3 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Git Unit Tests"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/extensions/git/node_modules/mocha/bin/_mocha"​, 
 ​                        ​"stopOnEntry"​: ​false​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}/extensions/git"​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/git/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​10 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"HTML Server Unit Tests"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/extensions/html-language-features/server/test/index.js"​, 
 ​                        ​"stopOnEntry"​: ​false​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}/extensions/html-language-features/server"​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/html-language-features/server/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​10 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"CSS Server Unit Tests"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/extensions/css-language-features/server/test/index.js"​, 
 ​                        ​"stopOnEntry"​: ​false​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}/extensions/css-language-features/server"​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/css-language-features/server/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​10 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Markdown Extension Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/markdown-language-features/test-workspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/markdown-language-features"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/markdown-language-features/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/markdown-language-features/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​7 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"TypeScript Extension Tests"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/typescript-language-features/test-workspace"​, 
 ​                                ​"--extensionDevelopmentPath=${workspaceFolder}/extensions/typescript-language-features"​, 
 ​                                ​"--extensionTestsPath=${workspaceFolder}/extensions/typescript-language-features/out/test" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/extensions/typescript-language-features/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"5_tests"​, 
 ​                                ​"order"​: ​8 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Run Unit Tests"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/test/unit/electron/index.js"​, 
 ​                        ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/Code - OSS.app/Contents/MacOS/Electron"​, 
 ​                        ​"windows"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/Code - OSS.exe" 
 ​                        ​}​, 
 ​                        ​"linux"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/code-oss" 
 ​                        ​}​, 
 ​                        ​"outputCapture"​: ​"std"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"--remote-debugging-port=9222" 
 ​                        ​]​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}"​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"cascadeTerminateToConfigurations"​: ​[ 
 ​                                ​"Attach to VS Code" 
 ​                        ​]​, 
 ​                        ​"env"​: ​{ 
 ​                                ​"MOCHA_COLORS"​: ​"true" 
 ​                        ​}​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"hidden"​: ​true 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"pwa-node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Run Unit Tests For Current File"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/test/unit/electron/index.js"​, 
 ​                        ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/Code - OSS.app/Contents/MacOS/Electron"​, 
 ​                        ​"windows"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/Code - OSS.exe" 
 ​                        ​}​, 
 ​                        ​"linux"​: ​{ 
 ​                                ​"runtimeExecutable"​: ​"${workspaceFolder}/.build/electron/code-oss" 
 ​                        ​}​, 
 ​                        ​"cascadeTerminateToConfigurations"​: ​[ 
 ​                                ​"Attach to VS Code" 
 ​                        ​]​, 
 ​                        ​"outputCapture"​: ​"std"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"--remote-debugging-port=9222"​, 
 ​                                ​"--run"​, 
 ​                                ​"${relativeFile}" 
 ​                        ​]​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}"​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${workspaceFolder}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"env"​: ​{ 
 ​                                ​"MOCHA_COLORS"​: ​"true" 
 ​                        ​}​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"hidden"​: ​true 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"type"​: ​"node"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"name"​: ​"Launch Smoke Test"​, 
 ​                        ​"program"​: ​"${workspaceFolder}/test/smoke/out/main.js"​, 
 ​                        ​"cwd"​: ​"${workspaceFolder}/test/smoke"​, 
 ​                        ​"timeout"​: ​240000​, 
 ​                        ​"port"​: ​9999​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"-l"​, 
 ​                                ​"${workspaceFolder}/.build/electron/Code - OSS.app/Contents/MacOS/Electron" 
 ​                        ​]​, 
 ​                        ​"outFiles"​: ​[ 
 ​                                ​"${cwd}/out/**/*.js" 
 ​                        ​]​, 
 ​                        ​"env"​: ​{ 
 ​                                ​"NODE_ENV"​: ​"development"​, 
 ​                                ​"VSCODE_DEV"​: ​"1"​, 
 ​                                ​"VSCODE_CLI"​: ​"1" 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Launch Built-in Extension"​, 
 ​                        ​"type"​: ​"extensionHost"​, 
 ​                        ​"request"​: ​"launch"​, 
 ​                        ​"runtimeExecutable"​: ​"${execPath}"​, 
 ​                        ​"args"​: ​[ 
 ​                                ​"--extensionDevelopmentPath=${workspaceRoot}/extensions/debug-auto-launch" 
 ​                        ​] 
 ​                ​} 
 ​        ​]​, 
 ​        ​"compounds"​: ​[ 
 ​                ​{ 
 ​                        ​"name"​: ​"VS Code"​, 
 ​                        ​"stopAll"​: ​true​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Launch VS Code Internal"​, 
 ​                                ​"Attach to Main Process"​, 
 ​                                ​"Attach to Extension Host"​, 
 ​                                ​"Attach to Shared Process"​, 
 ​                        ​]​, 
 ​                        ​"preLaunchTask"​: ​"Ensure Prelaunch Dependencies"​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"0_vscode"​, 
 ​                                ​"order"​: ​1 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Search and Renderer processes"​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Launch VS Code Internal"​, 
 ​                                ​"Attach to Search Process" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"1_vscode"​, 
 ​                                ​"order"​: ​4 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Renderer and Extension Host processes"​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Launch VS Code Internal"​, 
 ​                                ​"Attach to Extension Host" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"1_vscode"​, 
 ​                                ​"order"​: ​3 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Debug Unit Tests"​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Attach to VS Code"​, 
 ​                                ​"Run Unit Tests" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"1_vscode"​, 
 ​                                ​"order"​: ​2 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Debug Unit Tests (Current File)"​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Attach to VS Code"​, 
 ​                                ​"Run Unit Tests For Current File" 
 ​                        ​]​, 
 ​                        ​"presentation"​: ​{ 
 ​                                ​"group"​: ​"1_vscode"​, 
 ​                                ​"order"​: ​2 
 ​                        ​} 
 ​                ​}​, 
 ​                ​{ 
 ​                        ​"name"​: ​"Launch VS Code"​, 
 ​                        ​"stopAll"​: ​true​, 
 ​                        ​"configurations"​: ​[ 
 ​                                ​"Launch VS Code Internal"​, 
 ​                        ​]​, 
 ​                        ​"preLaunchTask"​: ​"Ensure Prelaunch Dependencies" 
 ​                ​}​,
