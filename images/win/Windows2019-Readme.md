# Microsoft Windows Server 2019 Datacenter
- OS Version: 10.0.17763 Build 3406
- Image Version: 20220925.1

## Enabled windows optional features
- Windows Subsystem for Linux [WSLv1]

## Installed Software
### Language and Runtime
- Bash 5.1.16(1)-release
- Go 1.17.13
- Julia 1.8.1
- Kotlin 1.7.10
- LLVM 14.0.6
- Node 16.17.1
- Perl 5.32.1
- PHP 8.1.10
- Python 3.7.9
- Ruby 2.5.9p229

### Package Management
- Chocolatey 1.1.0
- Composer 2.4.2
- Helm 3.9.4
- Miniconda 4.12.0 (pre-installed on the image but not added to PATH)
- NPM 8.15.0
- NuGet 6.3.0.131
- pip 22.2.2 (python 3.7)
- Pipx 1.1.0
- RubyGems 2.7.6.3
- Vcpkg (build from master \<57d3194e7>)
- Yarn 1.22.19

#### Environment variables
| Name                    | Value        |
| ----------------------- | ------------ |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg     |
| VCPKG_ROOT              | C:\vcpkg     |
| CONDA                   | C:\Miniconda |

### Project Management
- Ant 1.10.12
- Gradle 7.5
- Maven 3.8.6
- sbt 1.7.1

### Tools
- 7zip 22.01
- aria2 1.36.0
- azcopy 10.16.0
- Bazel 5.3.1
- Bazelisk 1.13.2
- Bicep 0.10.61
- Cabal 3.8.1.0
- CMake 3.24.2
- CodeQL Action Bundle 2.10.5
- Docker Compose v1 1.29.2
- Docker Compose v2 2.11.1
- Docker master-dockerproject-2022-03-26
- Docker-wincred 0.7.0
- ghc 9.4.2
- Git 2.37.3.windows.1
- Git LFS 3.2.0
- Google Cloud SDK 403.0.0
- ImageMagick 7.1.0-49
- InnoSetup 6.2.1
- jq 1.6
- Kind 0.16.0
- Kubectl 1.25.2
- Mercurial 5.0
- Mingw-w64 8.1.0
- Newman 5.3.2
- NSIS v3.08
- OpenSSL 1.1.1
- Packer 1.8.2
- Parcel 2.7.0
- Pulumi v3.40.1
- R 4.2.1
- Service Fabric SDK 9.0.1028.9590
- Stack 2.9.1
- Subversion (SVN) 1.14.2
- Swig 4.0.2
- VSWhere 3.0.3
- WinAppDriver 1.2.2009.02003
- WiX Toolset v3.11.2.4516
- yamllint 1.28.0
- zstd 1.5.2

### CLI Tools
- Alibaba Cloud CLI 3.0.127
- AWS CLI 2.7.35
- AWS SAM CLI 1.57.0
- AWS Session Manager CLI 1.2.339.0
- Azure CLI 2.40.0
- Azure DevOps CLI extension 0.25.0
- Cloud Foundry CLI 6.53.0
- GitHub CLI 2.16.0
- Hub CLI 2.14.2

### Rust Tools
- Cargo 1.64.0
- Rust 1.64.0
- Rustdoc 1.64.0
- Rustup 1.25.1

#### Packages
- bindgen 0.60.1
- cargo-audit 0.17.0
- cargo-outdated 0.11.1
- cbindgen 0.24.3
- Clippy 0.1.64
- Rustfmt 1.5.1

### Browsers and webdrivers
- Google Chrome 105.0.5195.127
- Chrome Driver 105.0.5195.52
- Microsoft Edge 105.0.1343.50
- Microsoft Edge Driver 105.0.1343.50
- Mozilla Firefox 105.0.1
- Gecko Driver 0.31.0
- IE Driver 3.150.1.1
- Selenium server 4.4.0

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |
| GECKOWEBDRIVER    | C:\SeleniumWebDrivers\GeckoDriver  |
| SELENIUM_JAR_PATH | C:\selenium\selenium-server.jar    |

### Java
| Version             | Vendor          | Environment Variable |
| ------------------- | --------------- | -------------------- |
| 8.0.345+1 (default) | Eclipse Temurin | JAVA_HOME_8_X64      |
| 11.0.16+101         | Eclipse Temurin | JAVA_HOME_11_X64     |
| 13.0.2+8.1          | Adopt OpenJDK   | JAVA_HOME_13_X64     |
| 17.0.4+101          | Eclipse Temurin | JAVA_HOME_17_X64     |

### Shells
| Name          | Target                            |
| ------------- | --------------------------------- |
| gitbash.exe   | C:\Program Files\Git\bin\bash.exe |
| msys2bash.cmd | C:\msys64\usr\bin\bash.exe        |
| wslbash.exe   | C:\Windows\System32\bash.exe      |

### MSYS2
- Pacman 6.0.1

##### Notes:
```
Location: C:\msys64

Note: MSYS2 is pre-installed on image but not added to PATH.
```

### BizTalk Server
- BizTalk Server Project Build Component 3.13.832.0

### Cached Tools
#### Go
| Version | Architecture | Environment Variable |
| ------- | ------------ | -------------------- |
| 1.17.13 (Default) | x64          | GOROOT_1_17_X64      |
| 1.18.6  | x64          | GOROOT_1_18_X64      |
| 1.19.1  | x64          | GOROOT_1_19_X64      |

#### Node
| Version | Architecture |
| ------- | ------------ |
| 12.22.12 | x64          |
| 14.20.1 | x64          |
| 16.17.1 | x64          |

#### Python
| Version | Architecture |
| ------- | ------------ |
| 2.7.18  | x64, x86     |
| 3.6.8   | x64, x86     |
| 3.7.9 (Default) | x64, x86     |
| 3.8.10  | x64, x86     |
| 3.9.13  | x64, x86     |
| 3.10.7  | x64, x86     |

#### Ruby
| Version | Architecture |
| ------- | ------------ |
| 2.4.10  | x64          |
| 2.5.9 (Default) | x64          |
| 2.6.10  | x64          |
| 2.7.6   | x64          |
| 3.0.4   | x64          |
| 3.1.2   | x64          |

#### PyPy
| Python Version | PyPy Version |
| -------------- | ------------ |
| 2.7.18         | PyPy 7.3.9 with MSC v.1929 64 bit (AMD64) |
| 3.6.12         | PyPy 7.3.3 with MSC v.1927 32 bit |
| 3.7.13         | PyPy 7.3.9 with MSC v.1929 64 bit (AMD64) |
| 3.8.12         | PyPy 7.3.9 with MSC v.1929 64 bit (AMD64) |
| 3.9.10         | PyPy 7.3.9 with MSC v.1929 64 bit (AMD64) |

### Databases
#### PostgreSQL
| Property             | Value                                                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| ServiceName          | postgresql-x64-14                                                                                                                    |
| Version              | 14.5                                                                                                                                 |
| ServiceStatus        | Stopped                                                                                                                              |
| ServiceStartType     | Disabled                                                                                                                             |
| EnvironmentVariables | PGBIN=C:\Program Files\PostgreSQL\14\bin <br> PGDATA=C:\Program Files\PostgreSQL\14\data <br> PGROOT=C:\Program Files\PostgreSQL\14  |
| Path                 | C:\Program Files\PostgreSQL\14                                                                                                       |
| UserName             | postgres                                                                                                                             |
| Password             | root                                                                                                                                 |

#### MongoDB
| Version  | ServiceName | ServiceStatus | ServiceStartType |
| -------- | ----------- | ------------- | ---------------- |
| 5.0.12.0 | MongoDB     | Stopped       | Disabled         |

### Database tools
- Azure CosmosDb Emulator 2.14.9.0
- DacFx 16.0.6296.0
- MySQL 5.7.39.0
- SQL OLEDB Driver 18.6.3.0
- SQLPS 1.0

### Web Servers
| Name   | Version | ConfigFile                            | ServiceName | ServiceStatus | ListenPort |
| ------ | ------- | ------------------------------------- | ----------- | ------------- | ---------- |
| Apache | 2.4.54  | C:\tools\Apache24\conf\httpd.conf     | Apache      | Stopped       | 80         |
| Nginx  | 1.23.1  | C:\tools\nginx-1.23.1\conf\nginx.conf | nginx       | Stopped       | 80         |

### Visual Studio Enterprise 2019
| Name                          | Version        | Path                                                           |
| ----------------------------- | -------------- | -------------------------------------------------------------- |
| Visual Studio Enterprise 2019 | 16.11.32901.82 | C:\Program Files (x86)\Microsoft Visual Studio\2019\Enterprise |

#### Workloads, components and extensions:
| Package                                                                   | Version         |
| ------------------------------------------------------------------------- | --------------- |
| Component.Android.NDK.R16B                                                | 16.11.32830.301 |
| Component.Android.SDK25.Private                                           | 16.0.28625.61   |
| Component.Android.SDK30                                                   | 16.10.31205.252 |
| Component.Ant                                                             | 1.9.3.8         |
| Component.Dotfuscator                                                     | 16.10.31205.252 |
| Component.Linux.CMake                                                     | 16.2.29003.222  |
| Component.MDD.Android                                                     | 16.0.28517.75   |
| Component.MDD.Linux                                                       | 16.5.29515.121  |
| Component.MDD.Linux.GCC.arm                                               | 16.5.29515.121  |
| Component.Microsoft.VisualStudio.LiveShare                                | 1.0.4440        |
| Component.Microsoft.VisualStudio.RazorExtension                           | 16.10.31205.252 |
| Component.Microsoft.VisualStudio.Tools.Applications                       | 16.0.31110.1    |
| Component.Microsoft.VisualStudio.Web.AzureFunctions                       | 16.10.31205.252 |
| Component.Microsoft.Web.LibraryManager                                    | 16.10.31205.180 |
| Component.Microsoft.WebTools.BrowserLink.WebLivePreview                   | 0.7.22.39845    |
| Component.Microsoft.Windows.DriverKit                                     | 10.0.21381.0    |
| Component.OpenJDK                                                         | 16.11.31827.77  |
| Component.UnityEngine.x64                                                 | 16.10.31205.252 |
| Component.Unreal                                                          | 16.1.28810.153  |
| Component.Unreal.Android                                                  | 16.1.28810.153  |
| Component.VSInstallerProjects                                             | 1.0.2           |
| Component.WixToolset.VisualStudioExtension.Dev16                          | 1.0.0.18        |
| Component.WixToolset.VisualStudioExtension.Schemas3                       | 1.0.0.18        |
| Component.WixToolset.VisualStudioExtension.Schemas4                       | 1.0.0.18        |
| Component.Xamarin                                                         | 16.10.31205.252 |
| Component.Xamarin.RemotedSimulator                                        | 16.11.32629.160 |
| Microsoft.Component.Azure.DataLake.Tools                                  | 16.10.31205.252 |
| Microsoft.Component.ClickOnce                                             | 16.11.31603.221 |
| Microsoft.Component.MSBuild                                               | 16.5.29515.121  |
| Microsoft.Component.NetFX.Native                                          | 16.5.29515.121  |
| Microsoft.Component.PythonTools                                           | 16.11.31314.313 |
| Microsoft.Component.PythonTools.Miniconda                                 | 16.11.31314.313 |
| Microsoft.Component.PythonTools.Web                                       | 16.10.31205.252 |
| Microsoft.Component.VC.Runtime.UCRTSDK                                    | 16.0.28625.61   |
| Microsoft.ComponentGroup.Blend                                            | 16.0.28315.86   |
| Microsoft.ComponentGroup.ClickOnce.Publish                                | 16.11.31603.221 |
| Microsoft.Net.Component.3.5.DeveloperTools                                | 16.0.28517.75   |
| Microsoft.Net.Component.4.5.1.TargetingPack                               | 16.11.31605.320 |
| Microsoft.Net.Component.4.5.2.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.5.TargetingPack                                 | 16.11.31605.320 |
| Microsoft.Net.Component.4.6.1.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.6.2.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.6.TargetingPack                                 | 16.0.28517.75   |
| Microsoft.Net.Component.4.7.1.TargetingPack                               | 16.10.31205.252 |
| Microsoft.Net.Component.4.7.2.SDK                                         | 16.4.29409.204  |
| Microsoft.Net.Component.4.7.2.TargetingPack                               | 16.10.31205.252 |
| Microsoft.Net.Component.4.7.TargetingPack                                 | 16.10.31205.252 |
| Microsoft.Net.Component.4.8.SDK                                           | 16.4.29313.120  |
| Microsoft.Net.Component.4.TargetingPack                                   | 16.11.31605.320 |
| Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools                         | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools                         | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.4.7.DeveloperTools                           | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.DevelopmentPrerequisites                     | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.TargetingPacks.Common                        | 16.0.28516.191  |
| Microsoft.NetCore.Component.DevelopmentTools                              | 16.10.31303.231 |
| Microsoft.NetCore.Component.Runtime.3.1                                   | 16.11.32901.82  |
| Microsoft.NetCore.Component.Runtime.6.0                                   | 16.11.32901.82  |
| Microsoft.NetCore.Component.SDK                                           | 16.11.32901.82  |
| Microsoft.NetCore.Component.Web                                           | 16.10.31303.231 |
| Microsoft.VisualStudio.Component.AppInsights.Tools                        | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.AspNet45                                 | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.AuthoringTools                     | 16.11.31827.77  |
| Microsoft.VisualStudio.Component.Azure.ClientLibs                         | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.Azure.Compute.Emulator                   | 16.11.31827.77  |
| Microsoft.VisualStudio.Component.Azure.Kubernetes.Tools                   | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.Powershell                         | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.Azure.ResourceManager.Tools              | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.Azure.ServiceFabric.Tools                | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.Azure.Storage.AzCopy                     | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Azure.Storage.Emulator                   | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.Azure.Waverton                           | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools                | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.ClassDesigner                            | 16.0.28528.71   |
| Microsoft.VisualStudio.Component.CloudExplorer                            | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.CodeMap                                  | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Common.Azure.Tools                       | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.CoreEditor                               | 16.1.28811.260  |
| Microsoft.VisualStudio.Component.Debugger.JustInTime                      | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Debugger.Snapshot                        | 16.5.29813.82   |
| Microsoft.VisualStudio.Component.Debugger.TimeTravel                      | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DiagnosticTools                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DockerTools                              | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.DotNetModelBuilder                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DslTools                                 | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.EntityFramework                          | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp                                   | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp.Desktop                           | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp.WebTemplates                      | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.GraphDocument                            | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Graphics                                 | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Graphics.Tools                           | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.IISExpress                               | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.IntelliCode                              | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.IntelliTrace.FrontEnd                    | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.JavaScript.Diagnostics                   | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.JavaScript.TypeScript                    | 16.11.31404.150 |
| Microsoft.VisualStudio.Component.LinqToSql                                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.LiveUnitTesting                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.ManagedDesktop.Core                      | 16.4.29318.151  |
| Microsoft.VisualStudio.Component.ManagedDesktop.Prerequisites             | 16.10.31205.180 |
| Microsoft.VisualStudio.Component.Merq                                     | 16.2.29012.281  |
| Microsoft.VisualStudio.Component.MonoDebugger                             | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.MSODBC.SQL                               | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils                         | 16.0.28707.177  |
| Microsoft.VisualStudio.Component.Node.Tools                               | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.NuGet                                    | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.NuGet.BuildTools                         | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.PortableLibrary                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Roslyn.Compiler                          | 16.0.28714.129  |
| Microsoft.VisualStudio.Component.Roslyn.LanguageServices                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Sharepoint.Tools                         | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.SQL.ADAL                                 | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.SQL.CLR                                  | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.SQL.DataSources                          | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.SQL.SSDT                                 | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.TeamOffice                               | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.TestTools.CodedUITest                    | 16.0.28327.66   |
| Microsoft.VisualStudio.Component.TestTools.WebLoadTest                    | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.TextTemplating                           | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.TypeScript.4.3                           | 16.0.31506.151  |
| Microsoft.VisualStudio.Component.Unity                                    | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.UWP.VC.ARM64                             | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.VC.14.25.x86.x64                         | 16.11.32428.96  |
| Microsoft.VisualStudio.Component.VC.140                                   | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.ASAN                                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.ATL                                   | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM                               | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM.Spectre                       | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64                             | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64.Spectre                     | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.ATL.Spectre                           | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.ATLMFC                                | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATLMFC.Spectre                        | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.CLI.Support                           | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.CMake.Project                         | 16.3.29103.31   |
| Microsoft.VisualStudio.Component.VC.CoreIde                               | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.DiagnosticTools                       | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Llvm.Clang                            | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.VC.Llvm.ClangToolset                     | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM                               | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM.Spectre                       | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64                             | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64.Spectre                     | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.Modules.x86.x64                       | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.Redist.14.Latest                      | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Redist.MSM                            | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM.Spectre                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM64.Spectre                | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Runtimes.x86.x64.Spectre              | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.TestAdapterForBoostTest               | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.VC.TestAdapterForGoogleTest              | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.VC.Tools.ARM                             | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64                           | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64EC                         | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Tools.x86.x64                         | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.v141.ARM                              | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.ARM.Spectre                      | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.v141.ARM64                            | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.ARM64.Spectre                    | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.v141.ATL                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM                          | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM.Spectre                  | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64                        | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64.Spectre                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.Spectre                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.ARM.Spectre                  | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.ARM64.Spectre                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.Spectre                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64.Spectre                  | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VSSDK                                    | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.Wcf.Tooling                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Web                                      | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.WebDeploy                                | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Windows10SDK                             | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.Windows10SDK.16299                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.17134                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.17763                       | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Windows10SDK.18362                       | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.Windows10SDK.19041                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.20348                       | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.Windows11SDK.22000                       | 16.11.31727.170 |
| Microsoft.VisualStudio.Component.WinXP                                    | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Workflow                                 | 16.0.28315.86   |
| Microsoft.VisualStudio.ComponentGroup.ArchitectureTools.Native            | 16.0.28621.142  |
| Microsoft.VisualStudio.ComponentGroup.Azure.CloudServices                 | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Azure.Prerequisites                 | 16.10.31303.231 |
| Microsoft.VisualStudio.ComponentGroup.Azure.ResourceManager.Tools         | 16.0.28528.71   |
| Microsoft.VisualStudio.ComponentGroup.AzureFunctions                      | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.MSIX.Packaging                      | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core                  | 16.2.29012.281  |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Llvm.Clang            | 16.11.31603.221 |
| Microsoft.VisualStudio.ComponentGroup.UWP.NetCoreAndStandard              | 16.3.29102.218  |
| Microsoft.VisualStudio.ComponentGroup.UWP.Support                         | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.UWP.VC                              | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.UWP.VC.v141                         | 16.1.28810.153  |
| Microsoft.VisualStudio.ComponentGroup.UWP.Xamarin                         | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.VisualStudioExtension.Prerequisites | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web                                 | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web.Client                          | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web.CloudTools                      | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions                  | 16.11.32413.511 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.CMake            | 16.11.32413.511 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.TemplateEngine   | 16.11.32413.511 |
| Microsoft.VisualStudio.Workload.Azure                                     | 16.11.31503.43  |
| Microsoft.VisualStudio.Workload.CoreEditor                                | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.Data                                      | 16.0.28720.110  |
| Microsoft.VisualStudio.Workload.DataScience                               | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.ManagedDesktop                            | 16.10.31303.231 |
| Microsoft.VisualStudio.Workload.ManagedGame                               | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NativeCrossPlat                           | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NativeDesktop                             | 16.11.31727.170 |
| Microsoft.VisualStudio.Workload.NativeGame                                | 16.11.31727.170 |
| Microsoft.VisualStudio.Workload.NativeMobile                              | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NetCoreTools                              | 16.10.31303.231 |
| Microsoft.VisualStudio.Workload.NetCrossPlat                              | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NetWeb                                    | 16.10.31303.231 |
| Microsoft.VisualStudio.Workload.Node                                      | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.Office                                    | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.Python                                    | 16.11.32001.129 |
| Microsoft.VisualStudio.Workload.Universal                                 | 16.11.31727.170 |
| Microsoft.VisualStudio.Workload.VisualStudioExtension                     | 16.10.31205.180 |
| ms-biztalk.BizTalk                                                        | 3.13.2.0        |
| ProBITools.MicrosoftAnalysisServicesModelingProjects                      | 2.9.18          |
| ProBITools.MicrosoftReportProjectsforVisualStudio                         | 2.6.11          |
| SSIS.SqlServerIntegrationServicesProjects                                 | 4.2             |
| VisualStudioClient.MicrosoftVisualStudio2017InstallerProjects             | 1.0.2           |
| Windows Driver Kit                                                        | 10.1.22000.1    |
| Windows Driver Kit Visual Studio Extension                                | 10.0.21381.0    |
| Windows Software Development Kit                                          | 10.1.22621.1    |
| WixToolset.WixToolsetVisualStudio2019Extension                            | 1.0.0.18        |

#### Microsoft Visual C++:
| Name                                         | Architecture | Version     |
| -------------------------------------------- | ------------ | ----------- |
| Microsoft Visual C++ 2010 Redistributable    | x64          | 10.0.40219  |
| Microsoft Visual C++ 2010 Redistributable    | x86          | 10.0.40219  |
| Microsoft Visual C++ 2012 Additional Runtime | x64          | 11.0.61030  |
| Microsoft Visual C++ 2012 Minimum Runtime    | x64          | 11.0.61030  |
| Microsoft Visual C++ 2013 Additional Runtime | x64          | 12.0.40660  |
| Microsoft Visual C++ 2013 Minimum Runtime    | x64          | 12.0.40660  |
| Microsoft Visual C++ 2013 Additional Runtime | x86          | 12.0.21005  |
| Microsoft Visual C++ 2013 Minimum Runtime    | x86          | 12.0.21005  |
| Microsoft Visual C++ 2019 Debug Runtime      | x64          | 14.29.30139 |
| Microsoft Visual C++ 2019 Debug Runtime      | x86          | 14.29.30139 |
| Microsoft Visual C++ 2022 Additional Runtime | x64          | 14.32.31332 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x64          | 14.32.31332 |
| Microsoft Visual C++ 2022 Additional Runtime | x86          | 14.32.31332 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x86          | 14.32.31332 |

#### Installed Windows SDKs
`Location C:\Program Files (x86)\Windows Kits\10\Extension SDKs\WindowsDesktop`
- 10.0.14393.0
- 10.0.16299.0
- 10.0.17134.0
- 10.0.17763.0
- 10.0.18362.0
- 10.0.19041.0
- 10.0.20348.0
- 10.0.22000.0
- 10.0.22621.0

### .NET Core SDK
`Location C:\Program Files\dotnet\sdk`
- 3.1.120 3.1.202 3.1.302 3.1.423 5.0.104 5.0.214 5.0.303 5.0.408 5.0.412

### .NET Core Runtime
`Location: C:\Program Files\dotnet\shared\Microsoft.AspNetCore.App`
- 3.1.4 3.1.6 3.1.20 3.1.29 5.0.4 5.0.9 5.0.17 6.0.9

`Location: C:\Program Files\dotnet\shared\Microsoft.NETCore.App`
- 3.1.4 3.1.6 3.1.20 3.1.29 5.0.4 5.0.9 5.0.17 6.0.9

`Location: C:\Program Files\dotnet\shared\Microsoft.WindowsDesktop.App`
- 3.1.4 3.1.6 3.1.20 3.1.29 5.0.4 5.0.9 5.0.17 6.0.9

### .NET Framework
`Type: Developer Pack`
`Location: C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX <version> Tools`
- 4.7.2
- 4.8

### .NET tools
- nbgv 3.5.113+a908c6d9d2

### PowerShell Tools
- PowerShell 7.2.6

#### Azure Powershell Modules
| Module  | Version                                                                                                                                                                        | Path                           |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------ |
| Az      | 1.0.0.zip<br>1.6.0.zip<br>2.3.2.zip<br>2.6.0.zip<br>3.1.0.zip<br>3.5.0.zip<br>3.8.0.zip<br>4.3.0.zip<br>4.4.0.zip<br>4.7.0.zip<br>5.5.0.zip<br>5.9.0.zip<br>6.6.0.zip<br>7.5.0 | C:\Modules\az_\<version\>      |
| Azure   | 2.1.0 [Installed]<br>3.8.0.zip<br>4.2.1.zip<br>5.1.1.zip<br>5.3.0                                                                                                              | C:\Modules\azure_\<version\>   |
| AzureRM | 2.1.0 [Installed]<br>3.8.0.zip<br>4.2.1.zip<br>5.1.1.zip<br>6.7.0.zip<br>6.13.1                                                                                                | C:\Modules\azurerm_\<version\> |
```
Azure PowerShell module 2.1.0 and AzureRM PowerShell module 2.1.0 are installed
and are available via 'Get-Module -ListAvailable'.
All other versions are saved but not installed.
```

#### Powershell Modules
| Module             | Version          |
| ------------------ | ---------------- |
| AWSPowerShell      | 4.1.175          |
| DockerMsftProvider | 1.0.0.8          |
| MarkdownPS         | 1.9              |
| Microsoft.Graph    | 1.11.1           |
| Pester             | 3.4.0<br>5.3.3   |
| PowerShellGet      | 1.0.0.1<br>2.2.5 |
| PSScriptAnalyzer   | 1.20.0           |
| PSWindowsUpdate    | 2.2.0.3          |
| SqlServer          | 21.1.18256       |
| VSSetup            | 2.2.16           |

### Android
| Package Name               | Version                                                                                                                                                                                                                                                                                                                                |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 7.0                                                                                                                                                                                                                                                                                                                                    |
| Android SDK Build-tools    | 33.0.0<br>32.0.0<br>31.0.0<br>30.0.0 30.0.1 30.0.2 30.0.3<br>29.0.0 29.0.1 29.0.2 29.0.3<br>28.0.0 28.0.1 28.0.2 28.0.3<br>27.0.0 27.0.1 27.0.2 27.0.3<br>26.0.0 26.0.1 26.0.2 26.0.3<br>25.0.0 25.0.1 25.0.2 25.0.3<br>24.0.0 24.0.1 24.0.2 24.0.3<br>23.0.1 23.0.2 23.0.3<br>22.0.1<br>21.1.2<br>20.0.0<br>19.1.0                    |
| Android SDK Platforms      | android-33 (rev 2)<br>android-32 (rev 1)<br>android-31 (rev 1)<br>android-30 (rev 3)<br>android-29 (rev 5)<br>android-28 (rev 6)<br>android-27 (rev 3)<br>android-26 (rev 2)<br>android-25 (rev 3)<br>android-24 (rev 2)<br>android-23 (rev 3)<br>android-22 (rev 2)<br>android-21 (rev 2)<br>android-20 (rev 2)<br>android-19 (rev 4) |
| Android SDK Platform-Tools | 33.0.3                                                                                                                                                                                                                                                                                                                                 |
| Android SDK Tools          | 26.1.1                                                                                                                                                                                                                                                                                                                                 |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                                                                                                                                 |
| CMake                      | 3.10.2<br>3.18.1<br>3.22.1                                                                                                                                                                                                                                                                                                             |
| Google APIs                | addon-google_apis-google-21<br>addon-google_apis-google-22<br>addon-google_apis-google-23<br>addon-google_apis-google-24                                                                                                                                                                                                               |
| Google Play services       | 49                                                                                                                                                                                                                                                                                                                                     |
| Google Repository          | 58                                                                                                                                                                                                                                                                                                                                     |
| NDK                        | 23.2.8568313<br>24.0.8215888<br>25.1.8937393                                                                                                                                                                                                                                                                                           |
| SDK Patch Applier v4       | 1                                                                                                                                                                                                                                                                                                                                      |

#### Environment variables
| Name                    | Value                                   |
| ----------------------- | --------------------------------------- |
| ANDROID_HOME            | C:\Android\android-sdk                  |
| ANDROID_NDK             | C:\Android\android-sdk\ndk\25.1.8937393 |
| ANDROID_NDK_HOME        | C:\Android\android-sdk\ndk\25.1.8937393 |
| ANDROID_NDK_LATEST_HOME | C:\Android\android-sdk\ndk\25.1.8937393 |
| ANDROID_NDK_ROOT        | C:\Android\android-sdk\ndk\25.1.8937393 |
| ANDROID_SDK_ROOT        | C:\Android\android-sdk                  |

### Cached Docker images
| Repository:Tag                                                            | Digest                                                                   | Created    |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------- |
| mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2019  | sha256:7501f0b0b539d4a4d2da522e9981fd72bda1fa420cd95e69e1da7f9f8e407219  | 2022-09-13 |
| mcr.microsoft.com/dotnet/framework/runtime:4.8-windowsservercore-ltsc2019 | sha256:18d9698bb0b80472d8993fc1fbd08e102982934ba80b19eef4a869537b83251d  | 2022-09-13 |
| mcr.microsoft.com/dotnet/framework/sdk:4.8-windowsservercore-ltsc2019     | sha256:9d1fde4186c74ad261923c583ddb6102e940cbb3929ce1d1bc0d245e745d61a3  | 2022-09-13 |
| mcr.microsoft.com/windows/nanoserver:1809                                 | sha256:92455b285ba046b1aecfd9ab598023c31bbea59149fcb7c02e4427abcbf44d37  | 2022-09-09 |
| mcr.microsoft.com/windows/servercore:ltsc2019                             | sha256:7450aeee8739b486e1493c44014e9c211cea8391aae7ec25416584b8f4301938  | 2022-09-09 |

