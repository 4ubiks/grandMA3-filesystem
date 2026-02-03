# MA3 File System
This is a tree visual of the grandMA3 file system.

```
Root
│
├──>MessageCenter 
│   ├─>Undefined
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │   └──>Errors
│   │   └──>Alerts
│   ├─>System
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │  	└──>Errors
│   │   └──>Alerts
│   ├─>Cmdline
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │  	└──>Errors
│   │   └──>Alerts
│   ├─>Power
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │  	└──>Errors
│   │   └──>Alerts
│   ├─>Manet
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │  	└──>Errors
│   │   └──>Alerts
│   ├─>USB
│   │   └──>Undefined
│   │   └──>Spam
│   │   └──>Warnings
│   │  	└──>Errors
│   │   └──>Alerts
│   └──>Chat
│       └──>Undefined
│       └──>Spam
│       └──>Warnings
│      	└──>Errors
│       └──>Alerts
├──>StationSettings
│   ├──>TimeConfig
│   ├──>LocalSettings
│   ├──>DefaultDisplayPositionsCollect
│   │   ├──>Conventional
│   │   │   └──>DefaultDisplayPosition (7)
│   │	└──>Web
│   │       └──>DefaultDisplayPosition (7)
│   ├──>DeskLightsCollect // contains information on light configuration in Settings->Desk Lights and Color Theme
│   │   ├──>DeskLights
│   │   ├──>Screens
│   │   ├──>LedMaster
│   │   ├──>LedBackground
│   │   ├──>LedFeedback
│   │   └──>MibFeedback
│   └──>DisplaySurfaces
├──>Interfaces // Information on interfaces - will vary on config. basic onPC has lo1 and en0/eth0.
│   ├──>lo0
│   └──>en0
├──>KeyRegistry
│   └──>Default // registry key for product? i don't actually know what this is
├──>MAnetSocket
│   ├──>Sessions
│   │   └──> my_session_local@Local // will vary based on how many sessions your config sees/uses
│   └──>HostTypes
│       ├──>Undefined       
│       ├──>Console
│       ├──>onPC
│       │   └──>JACK_SESSION Undefined 127.0.0.1 my_session_local Local plugins IdleMaster // etc. all info for sessions
│       ├──>PU
│       ├──>NetworkNode
│       ├──>InternalWing
│       ├──>Switch
│       ├──>Plugin
│       ├──>PluginSmall
│       ├──>Extension
│       └──>UpdateMode
├──>Cloud
├──>NDI
├──>UsbNotifier // any information on devices plugged into USB ports 
│   ├──>TouchScreen
│   ├──>MA3Modules
│   ├──>StorageDevice
│   ├──>Mouse
│   ├──>Keyboard
│   ├──>Dongle
│   └──>UnknownDevice
├──>WebServer
├──>VirtualKeys // information on all physical keys the console utilizes
│   ├──>VirtualKey 1 MA1
│   │   └──>Name Status Hold Modifier Execution // etc. info exists for every button.
│   ├──>VirtualKey 2 MA2
│   ├──>VirtualKey 3 PREV
│   ├──>VirtualKey 4 PREV_X
│   ├──>VirtualKey 5 PREV_Y
│   ├──>VirtualKey 6 PREV_Z
│   ├──>VirtualKey 7 PREV_STEP
│   ├──>VirtualKey 8 NEXT
│   ├──>VirtualKey 9 NEXT_X
│   ├──>VirtualKey 10 NEXT_Y
│   ├──>VirtualKey 11 NEXT_Z
│   ├──>VirtualKey 12 NEXT_STEP
│   ├──>VirtualKey 13 SET
│   ├──>VirtualKey 14 TOGGLE_STEP
│   ├──>VirtualKey 15 TOGGLE_MATRICKS
│   ├──>VirtualKey 16 RESET_MATRICKS
│   ├──>VirtualKey 17 UP
│   ├──>VirtualKey 18 SELFIX
│   ├──>VirtualKey 19 DOWN
│   ├──>VirtualKey 20 MENU
│   ├──>VirtualKey 21 HIGHLIGHT
│   ├──>VirtualKey 22 SOLO 
│   ├──>VirtualKey 23 FREEZE
│   ├──>VirtualKey 24 PREVIEW
│   ├──>VirtualKey 25 BLIND
│   ├──>VirtualKey 26 PAGE_UP
│   ├──>VirtualKey 27 PAGE_DOWN
│   ├──>VirtualKey 28 LIST
│   ├──>VirtualKey 29 X1
│   ├──>VirtualKey 30 CLONE
│   ├──>VirtualKey 31 X2
│   ├──>VirtualKey 32 X3
│   ├──>VirtualKey 33 GRID
│   ├──>VirtualKey 34 X4 
│   ├──>VirtualKey 35 LAYOUT
│   ├──>VirtualKey 36 X5
│   ├──>VirtualKey 37 STEP
│   ├──>VirtualKey 38 X6
│   ├──>VirtualKey 39 TIMECODE
│   ├──>VirtualKey 40 X7
│   ├──>VirtualKey 41 VIEW
│   ├──>VirtualKey 42 X8
│   ├──>VirtualKey 43 DMX
│   ├──>VirtualKey 44 X9
│   ├──>VirtualKey 45 X10
│   ├──>VirtualKey 46 X11
│   ├──>VirtualKey 47 X12
│   ├──>VirtualKey 48 X13
│   ├──>VirtualKey 49 PHASER
│   ├──>VirtualKey 50 X14
│   ├──>VirtualKey 51 MACRO
│   ├──>VirtualKey 52 X15
│   ├──>VirtualKey 53 PAGE
│   ├──>VirtualKey 54 X16
│   ├──>VirtualKey 55 EXECUTOR
│   ├──>VirtualKey 56 EXEC
│   ├──>VirtualKey 57 FADER
│   ├──>VirtualKey 58 DEF_GO
│   ├──>VirtualKey 59 DEF_PAUSE
│   ├──>VirtualKey 60 DEF_GOBACK 
│   ├──>VirtualKey 61 PAUSE
│   ├──>VirtualKey 62 FIX
│   ├──>VirtualKey 63 GOBACK
│   ├──>VirtualKey 64 GO
│   ├──>VirtualKey 65 LEARN 
│   ├──>VirtualKey 66 GOBACKFAST
│   ├──>VirtualKey 67 GOFAST
│   ├──>VirtualKey 68 ON
│   ├──>VirtualKey 69 OFF
│   ├──>VirtualKey 70 MOVE 
│   ├──>VirtualKey 71 COPY
│   ├──>VirtualKey 72 DELETE
│   ├──>VirtualKey 73 ALIGN
│   ├──>VirtualKey 74 STOMP 
│   ├──>VirtualKey 75 HELP
│   ├──>VirtualKey 76 SELECT
│   ├──>VirtualKey 77 GOTO
│   ├──>VirtualKey 78 FIXTURE
│   ├──>VirtualKey 79 CHANNEL
│   ├──>VirtualKey 80 GROUP
│   ├──>VirtualKey 81 SEQUENCE
│   ├──>VirtualKey 82 CUE
│   ├──>VirtualKey 83 PRESET 
│   ├──>VirtualKey 84 EDIT 
│   ├──>VirtualKey 85 ASSIGN 
│   ├──>VirtualKey 86 TIME 
│   ├──>VirtualKey 87 UPDATE
│   ├──>VirtualKey 88 STORE
│   ├──>VirtualKey 89 NUM0
│   ├──>VirtualKey 90 NUM1
│   ├──>VirtualKey 91 NUM2 
│   ├──>VirtualKey 92 NUM3
│   ├──>VirtualKey 93 NUM4
│   ├──>VirtualKey 94 NUM5
│   ├──>VirtualKey 95 NUM6
│   ├──>VirtualKey 96 NUM7
│   ├──>VirtualKey 97 NUM8
│   ├──>VirtualKey 98 NUM9
│   ├──>VirtualKey 99 PLUS
│   ├──>VirtualKey 100 THRU
│   ├──>VirtualKey 101 MINUS
│   ├──>VirtualKey 102 DOT
│   ├──>VirtualKey 103 IF
│   ├──>VirtualKey 104 AT
│   ├──>VirtualKey 105 SLASH 
│   ├──>VirtualKey 106 ASTERISK
│   ├──>VirtualKey 107 PLEASE 
│   ├──>VirtualKey 108 FULL 
│   ├──>VirtualKey 109 OOPS
│   ├──>VirtualKey 110 CLEAR
│   ├──>VirtualKey 111 ESC
│   ├──>VirtualKey 112 ENCODER_INSIDE1
│   ├──>VirtualKey 113 ENCODER_OUTSIDE1
│   ├──>VirtualKey 114 ENCODER_INSIDE2
│   ├──>VirtualKey 115 ENCODER_OUTSIDE2
│   ├──>VirtualKey 116 ENCODER_INSIDE3
│   ├──>VirtualKey 117 ENCODER_OUTSIDE3
│   ├──>VirtualKey 118 ENCODER_INSIDE4
│   ├──>VirtualKey 119 ENCODER_OUTSIDE4
│   ├──>VirtualKey 120 ENCODER_INSIDE5
│   ├──>VirtualKey 121 ENCODER_OUTSIDE5
│   ├──>VirtualKey 122 USER1
│   ├──>VirtualKey 123 USER2
│   ├──>VirtualKey 124 XKEYS
│   ├──>VirtualKey 125 FLASH
│   ├──>VirtualKey 126 BLACK
│   ├──>VirtualKey 127 KILL 
│   ├──>VirtualKey 128 RATE1
│   ├──>VirtualKey 129 TEMP
│   ├──>VirtualKey 130 TOGGLE 
│   ├──>VirtualKey 131 TOP
│   ├──>VirtualKey 132 LOAD
│   ├──>VirtualKey 133 LOWLIGHT
│   ├──>VirtualKey 134 GOSTEP
│   ├──>VirtualKey 135 SWAP
│   ├──>VirtualKey 136 HALF_SPEED
│   ├──>VirtualKey 137 DOUBLE_SPEED 
│   ├──>VirtualKey 138 RECORD
│   ├──>VirtualKey 139 FLIP
│   ├──>VirtualKey 140 ONPC_SCREEN2
│   ├──>VirtualKey 141 ONPC_SCREEN3
│   ├──>VirtualKey 142 ONPC_SCREEN4
│   ├──>VirtualKey 143 ONPC_SCREEN5
│   ├──>VirtualKey 144 ONPC_SCREEN6
│   └──>VirtualKey 145 ONPC_SCREEN7
├──>HardwareConfigurations
│   ├──>MasterModule (MM) // each subfolder holds hundreds of definitions, similar to the VirtualKeys directory
│   │   ├──>Hardkeys (256) 
│   │   ├──>LedDefinitions (105)
│   │   ├──>EncoderDefinitions (44)
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>FaderModuleEncoder (MFE)
│   │   ├──>Hardkeys (310) 
│   │   ├──>LedDefinitions (118)
│   │   ├──>EncoderDefinitions (50)
│   │   ├──>FaderDefinitions (15)
│   │   └──>HardwareIoConnectors
│   ├──>FaderModuleCrossFader (MFX)
│   │   ├──>Hardkeys (256) 
│   │   ├──>LedDefinitions (117)
│   │   ├──>EncoderDefinitions (44)
│   │   ├──>FaderDefinitions (17)
│   │   └──>HardwareIoConnectors
│   ├──>onPC Command Wing
│   │   ├──>Hardkeys (449) 
│   │   ├──>LedDefinitions (158)
│   │   ├──>EncoderDefinitions (77)
│   │   ├──>FaderDefinitions (12)
│   │   └──>HardwareIoConnectors
│   ├──>compact
│   │   ├──>Hardkeys (449)
│   │   ├──>LedDefinitions (169)
│   │   ├──>EncoderDefinitions (77)
│   │   ├──>FaderDefinitions (12)
│   │   └──>HardwareIoConnectors
│   ├──>compact XT
│   │   ├──>Hardkeys (500) 
│   │   ├──>LedDefinitions (204)
│   │   ├──>EncoderDefinitions (88)
│   │   ├──>FaderDefinitions (17)
│   │   └──>HardwareIoConnectors
│   ├──>DMX Board (GM3-X)
│   │   ├──>Hardkeys  
│   │   ├──>LedDefinitions (1) 
│   │   ├──>EncoderDefinitions
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>Processing unit DMX Board (GM3P-X)
│   │   ├──>Hardkeys  
│   │   ├──>LedDefinitions 
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>Node 4Port Board (GM3N-4P)
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (1)
│   │   ├──>EncoderDefinitions (1) 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>Din-Rail Node
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (1)
│   │   ├──>EncoderDefinitions (1) 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>IO Node
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (1)
│   │   ├──>EncoderDefinitions (1) 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>Din-Rail IO Node
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (1)
│   │   ├──>EncoderDefinitions (1) 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>MA-key
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (3)
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>viz-key
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (3)
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>MAker-key
│   │   ├──>Hardkeys (1) 
│   │   ├──>LedDefinitions (3)
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>grandMA3 onPC Fader Wing
│   │   ├──>Hardkeys (194) 
│   │   ├──>LedDefinitions (71)
│   │   ├──>EncoderDefinitions (33)
│   │   ├──>FaderDefinitions (10)
│   │   └──>HardwareIoConnectors
│   ├──>MF-10
│   │   ├──>Hardkeys (194) 
│   │   ├──>LedDefinitions (71)
│   │   ├──>EncoderDefinitions (33)
│   │   ├──>FaderDefinitions (10)
│   │   └──>HardwareIoConnectors
│   ├──>onPC Rack Unit
│   │   ├──>Hardkeys  
│   │   ├──>LedDefinitions 
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   ├──>onPC DMX-key
│   │   ├──>Hardkeys (1)
│   │   ├──>LedDefinitions 
│   │   ├──>EncoderDefinitions 
│   │   ├──>FaderDefinitions
│   │   └──>HardwareIoConnectors
│   └──>onPC DMX-key starter
│       ├──>Hardkeys (1)
│       ├──>LedDefinitions 
│       ├──>EncoderDefinitions 
│       ├──>FaderDefinitions
│       └──>HardwareIoConnectors
├──>KeyboardLayouts
│   ├──>German (55)
│   │   └──>KeyboardKey Keycode Value KeyIsModifier ... // each keyboard has 55 of these subobjects with key information
│   ├──>English (55)
│   ├──>Russian (55)
│   ├──>Danish (55)
│   ├──>Portuguese (55)
│   └──>Spanish (55)
├──>ShowData // likely the biggest folder
│   ├──>ShowSettings (10)
│   │   ├──>DefaultPlaybackSettings  // content may vary by showfile 
│   │   ├──>GlobalSettings
│   │   ├──>MidiSettings
│   │   ├──>SoundSettings
│   │   ├──>TimecodeStatuses
│   │   ├──>GlobalVariables
│   │   ├──>AddonVariables
│   │   ├──>ShowMetaData
│   │   ├──>ShowDeletedData
│   │   └──>ScreenEncoder
│   │       ├──>ScreenX
│   │       └──>ScreenY
│   ├──>MediaPools (6) // all contents loaded onto ma system, so will vary by system. this is on a generic onPC MA3
│   │   ├──>Gobos (1000) // based on your patch. every gobo that exists on the fixtures currently in your patch
│   │   ├──>Symbols (1000) // all symbols currently in your patch
│   │   ├──>Images
│   │   ├──>MeshImagePool (7)
│   │   ├──>Videos (1)
│   │   └──>Sounds
│   ├──>Scribbles (1)
│   │   └──>Scribble 1
│   ├──>Appearances (1000) // I'll list out the 15 appearances in an arbitrary MA3 showfile
│   │   ├──>Macro
│   │   ├──>Plugin
│   │   ├──>Group
│   │   ├──>World
│   │   ├──>Sequence
│   │   ├──>Master
│   │   ├──>Sound
│   │   ├──>Subfixture
│   │   ├──>Fixture
│   │   ├──>View
│   │   ├──>Menu
│   │   ├──>User
│   │   ├──>ScreenConfig
│   │   ├──>Transparent
│   │   └──>MATricks
│   ├──>Tags
│   ├──>GelPools (12) // gels that exist in your showfile
│   │   ├──>MA 'MA Lighting'
│   │   ├──>Apollo 'Apollo Design'
│   │   ├──>CalCol 'Rosco CalColor'
│   │   ├──>Cinegel 'Rosco Cinegel'
│   │   ├──>Supergel 'Rosci Supergel'
│   │   ├──>GamColor 'GamColor'
│   │   ├──>Lee 'Lee'
│   │   ├──>PolyCol 'Poly Color'
│   │   ├──>Storaro 'Storaro Selection'
│   │   ├──>Zircom 'Lee Zircom'
│   │   ├──>Custom 'Custom'
│   │   └──>GelPool '12'
│   ├──>Meshes // all meshes for existing 3D models of patched fixtures. I'll list locked meshes that are included.
│   │   ├──>cube_3ds `cube.3ds`
│   │   ├──>sphere_3ds `sphere.3ds`
│   │   ├──>cylinder_3ds `cylinder.3ds`
│   │   ├──>base_3ds `base.3ds`
│   │   ├──>yoke_3ds `yoke.3ds`
│   │   ├──>head_3ds `head.3ds`
│   │   ├──>scanner_3ds `scanner.3ds`
│   │   ├──>conventional_3ds `conventional.3ds`
│   │   └──>pigtail_3ds `pigtail.3ds`
│   ├──>RDMData
│   │   ├──>RDMFixtureTypes
│   │   └──>RDMPorts
│   ├──>LivePatch
│   │   ├──>DmxCurves (1)
│   │   │   └──>DmxCurve1   CurveMode  MinX  MinY  MaxX  MaxY  UseForVisualization
│   │   ├──>AttributeDefinitions (4) // These values should be dependent on fixtures in the patch. 
│   │   │   ├──>DeactivationGroups (2)
│   │   │   │   ├──>Position
│   │   │   │   └──>Color
│   │   │   ├──>ActivationGroups (20) // only listing 2 for example
│   │   │   │   ├──>PanTilt  AttributeCount  DeactivationGroup
│   │   │   │   └──>ColorRGB  AttributeCount  DeactivationGroup
│   │   │   ├──>FeatureGroups (9)
│   │   │   │   ├──>Dimmer
│   │   │   │   ├──>Position
│   │   │   │   ├──>Gobo
│   │   │   │   ├──>Color
│   │   │   │   ├──>Beam
│   │   │   │   ├──>Focus
│   │   │   │   ├──>Control
│   │   │   │   ├──>Shapers
│   │   │   │   └──>Video
│   │   │   └──>Attributes (479) // every single attribbute in your patch. I list 5 for example.
│   │   │       ├──>Gobo1SelectSpin  Pretty  MainAttribute  ActivationGroup  Feature   
│   │   │       ├──>ColorRBG_RY  Amber  NoEntry  ColorRGB  Color.RGB
│   │   │       ├──>Blade1B  Blade 1B  NoEntry  Shaper  Shapers.Shapers
│   │   │       ├──>ZondaSize  Zonda Size  NoEntry  Gobo2  Gobo.Media
│   │   │       └──>PixelMaskNone  PixelMaskNone  GoboSelectSpin  NoEntry  Gobo.GOBOMISC
│   │   ├──>Layers (1)
│   │   │   └──>FixtureLayer 1
│   │   ├──>Classes (1)
│   │   │   └──>Class 1
│   │   ├──>PsrExtraData (2)
│   │   │   ├──>Gobos
│   │   │   └──>Meshes
│   │   ├──>FixtureTypes (9)
│   │   │   ├──>Universal (8) // each 8 subobjects exist for every fixture. only listed once for simplicity.
│   │   │   │   ├──>AttributeDefinitions (4)
│   │   │   │   ├──>Wheels
│   │   │   │   ├──>PhysicalDescriptions (7) 
│   │   │   │   │   ├──>Emitters
│   │   │   │   │   ├──>CRIs
│   │   │   │   │   ├──>FTFilters
│   │   │   │   │   ├──>Connectors
│   │   │   │   │   ├──>PhysicalProperties
│   │   │   │   │   │   └──>PhysicalPropertiesData  TempLow  TempHigh  Weight  LegHeight
│   │   │   │   │   ├──>ColorSpaceCollect
│   │   │   │   │   └──>GamutCollect
│   │   │   │   ├──>Models (4)
│   │   │   │   │   ├──>Base
│   │   │   │   │   ├──>Yoke
│   │   │   │   │   ├──>Head
│   │   │   │   │   └──>Beam
│   │   │   │   ├──>Geometries (1)
│   │   │   │   ├──>DMXModes (1)
│   │   │   │   ├──>Revisions (1)
│   │   │   │   └──>Protocols (1)
│   │   │   ├──>Ghibli (8)
│   │   │   ├──>Nando 502 (8)
│   │   │   ├──>Mac 101 (8)
│   │   │   ├──>Robin Spikie (8)
│   │   │   ├──>Veloce Profile (8)
│   │   │   ├──>Zonda 9FX (8)
│   │   │   ├──>MagicPanel 602 (8)
│   │   │   └──>Maverick MK3 Wash (8)
│   │   ├──>Stages (2) // all stages that exist in your showfile. mine has 2
│   │   │   ├──>Stage 1 (2)
│   │   │   │   ├──>Spaces (1)
│   │   │   │   │   └──>Stage  Scribble  Appearance  Note  Tags  MinX  MaxX  MinY  MaxY  MinZ  MaxZ
│   │   │   │   └──>Fixtures (45) // will display data for every existing FixID in a stage
│   │   │   │       ├──>NO  OFFSETPAN  OFFSETTILT  Name  FixtureType  Mode  ModeDirect  Fid  IdType  Patch
│   │   │   │       └──>22  None  None  Mac 101 1  ShowData.LivePatch.FixtureTypes.Mac101  3 RGB  3.DMXModes.RGB  22  Fixture  2.013
│   │   │   └──>FixtureTest (2)
│   │   │       ├──>Spaces (1)
│   │   │       └──>Fixtures (12)
│   │   ├──>UIChannels (3076) // every channel currently patched into your show. this gets big fast. 
│   │   │   ├──>NO  Name  Type  Subattribute  Master
│   │   │   └──>3076 Pixel127#2 Maverick MK3 Wash ColorRGB_W None 
│   │   ├──>RTChannels (3092)
│   │   │   ├──>NO  Name  FID  IDType  CID  ChannelName  Default   Highlight  Lowlight  Coarse  Fine  DmxCurve
│   │   │   └──>3091 Pixel127#2 401 1 None RGBW Pixel#2_ColorRGB_W 0 0 11.485 11.486 NoEntry
│   │   ├──>IDTypes (12)
│   │   │   ├──>Fixture (407) // holds fixture data for all patched fixtures. quantity is max FID. 
│   │   │   │   ├──>101 'Mac101 1' ShowData.LivePatch.FixtureTypes.Mac101 '3 RGB'
│   │   │   │   ├──>301 (36) 'MP602 1' ShowData.LivePatch.FixtureTypes.MagicPanel602 '2 Extended'
│   │   │   │   └──>401 (27) 'Mk3 1' ShowData.LivePatch.FixtureTypes.MaverickMK3Wash '1 Dual-Advanced movement-Advanced pixels'
│   │   │   ├──>Channel (1)
│   │   │   ├──>Universal (2)
│   │   │   ├──>Houselights (1)
│   │   │   ├──>NonDim (1)
│   │   │   ├──>Media (1)
│   │   │   ├──>Fog (1)
│   │   │   ├──>Effect (1)
│   │   │   ├──>Pyro (1)
│   │   │   ├──>MArker (1)
│   │   │   ├──>Multipatch (1)
│   │   │   └──>PSR (1)
│   │   ├──>DmxUniverses (1024) // info on all 1,024 universes. I will outline an entry for a populated universe
│   │   │   ├──>NO  Name  MergeMode  Request  Granted  CoarseParams  Used
│   │   │   └──>3 (512) DmxUniverse3 Prio Auto No 304 16
│   │   ├──>DmxAddresses (524288)
│   │   │   ├──>1 DMXAddress1
│   │   │   ├──>2 DMXAddress2
│   │   │   ├──>3 DMXAddress3
│   │   │   ├──>X DMXAddressX
│   │   │   └──>524288 DMXAddress 524288
│   │   ├──>FixtureTypesOverview (9)
│   │   │   ├──>Universal (8)
│   │   │   ├──>Ghibli (8)
│   │   │   ├──>Mac 101 (8)
│   │   │   ├──>Robin Spikie (8)
│   │   │   ├──>Veloce Profile (8)
│   │   │   ├──>Nando 502 (8)
│   │   │   ├──>MagicPanel 602 (8)
│   │   │   ├──>Zonda 9 FX (8)
│   │   │   └──>Maverick MK3 Wash (8)
│   │   └──>PatchFilter
│   ├──>Patch // contains the same data as 'LivePatch'
│   │   ├──>DmxCurves (1)
│   │   │   └──>DmxCurve1   CurveMode  MinX  MinY  MaxX  MaxY  UseForVisualization
│   │   ├──>AttributeDefinitions (4) // These values should be dependent on fixtures in the patch. 
│   │   │   ├──>DeactivationGroups (2)
│   │   │   │   ├──>Position
│   │   │   │   └──>Color
│   │   │   ├──>ActivationGroups (20) // only listing 2 for example
│   │   │   │   ├──>PanTilt  AttributeCount  DeactivationGroup
│   │   │   │   └──>ColorRGB  AttributeCount  DeactivationGroup
│   │   │   ├──>FeatureGroups (9)
│   │   │   │   ├──>Dimmer
│   │   │   │   ├──>Position
│   │   │   │   ├──>Gobo
│   │   │   │   ├──>Color
│   │   │   │   ├──>Beam
│   │   │   │   ├──>Focus
│   │   │   │   ├──>Control
│   │   │   │   ├──>Shapers
│   │   │   │   └──>Video
│   │   │   └──>Attributes (479) // every single attribbute in your patch. I list 5 for example.
│   │   │       ├──>Gobo1SelectSpin  Pretty  MainAttribute  ActivationGroup  Feature   
│   │   │       ├──>ColorRBG_RY  Amber  NoEntry  ColorRGB  Color.RGB
│   │   │       ├──>Blade1B  Blade 1B  NoEntry  Shaper  Shapers.Shapers
│   │   │       ├──>ZondaSize  Zonda Size  NoEntry  Gobo2  Gobo.Media
│   │   │       └──>PixelMaskNone  PixelMaskNone  GoboSelectSpin  NoEntry  Gobo.GOBOMISC
│   │   ├──>Layers (1)
│   │   │   └──>FixtureLayer 1
│   │   ├──>Classes (1)
│   │   │   └──>Class 1
│   │   ├──>PsrExtraData (2)
│   │   │   ├──>Gobos
│   │   │   └──>Meshes
│   │   ├──>FixtureTypes (9)
│   │   │   ├──>Universal (8) // each 8 subobjects exist for every fixture. only listed once for simplicity.
│   │   │   │   ├──>AttributeDefinitions (4)
│   │   │   │   ├──>Wheels
│   │   │   │   ├──>PhysicalDescriptions (7) 
│   │   │   │   │   ├──>Emitters
│   │   │   │   │   ├──>CRIs
│   │   │   │   │   ├──>FTFilters
│   │   │   │   │   ├──>Connectors
│   │   │   │   │   ├──>PhysicalProperties
│   │   │   │   │   │   └──>PhysicalPropertiesData  TempLow  TempHigh  Weight  LegHeight
│   │   │   │   │   ├──>ColorSpaceCollect
│   │   │   │   │   └──>GamutCollect
│   │   │   │   ├──>Models (4)
│   │   │   │   │   ├──>Base
│   │   │   │   │   ├──>Yoke
│   │   │   │   │   ├──>Head
│   │   │   │   │   └──>Beam
│   │   │   │   ├──>Geometries (1)
│   │   │   │   ├──>DMXModes (1)
│   │   │   │   ├──>Revisions (1)
│   │   │   │   └──>Protocols (1)
│   │   │   ├──>Ghibli (8)
│   │   │   ├──>Nando 502 (8)
│   │   │   ├──>Mac 101 (8)
│   │   │   ├──>Robin Spikie (8)
│   │   │   ├──>Veloce Profile (8)
│   │   │   ├──>Zonda 9FX (8)
│   │   │   ├──>MagicPanel 602 (8)
│   │   │   └──>Maverick MK3 Wash (8)
│   │   ├──>Stages (2) // all stages that exist in your showfile. mine has 2
│   │   │   ├──>Stage 1 (2)
│   │   │   │   ├──>Spaces (1)
│   │   │   │   │   └──>Stage  Scribble  Appearance  Note  Tags  MinX  MaxX  MinY  MaxY  MinZ  MaxZ
│   │   │   │   └──>Fixtures (45) // will display data for every existing FixID in a stage
│   │   │   │       ├──>NO  OFFSETPAN  OFFSETTILT  Name  FixtureType  Mode  ModeDirect  Fid  IdType  Patch
│   │   │   │       └──>22  None  None  Mac 101 1  ShowData.LivePatch.FixtureTypes.Mac101  3 RGB  3.DMXModes.RGB  22  Fixture  2.013
│   │   │   └──>FixtureTest (2)
│   │   │       ├──>Spaces (1)
│   │   │       └──>Fixtures (12)
│   │   ├──>UIChannels (3076) // every channel currently patched into your show. this gets big fast. 
│   │   │   ├──>NO  Name  Type  Subattribute  Master
│   │   │   └──>3076 Pixel127#2 Maverick MK3 Wash ColorRGB_W None 
│   │   ├──>RTChannels (3092)
│   │   │   ├──>NO  Name  FID  IDType  CID  ChannelName  Default   Highlight  Lowlight  Coarse  Fine  DmxCurve
│   │   │   └──>3091 Pixel127#2 401 1 None RGBW Pixel#2_ColorRGB_W 0 0 11.485 11.486 NoEntry
│   │   ├──>IDTypes (12)
│   │   │   ├──>Fixture (407) // holds fixture data for all patched fixtures. quantity is max FID. 
│   │   │   │   ├──>101 'Mac101 1' ShowData.LivePatch.FixtureTypes.Mac101 '3 RGB'
│   │   │   │   ├──>301 (36) 'MP602 1' ShowData.LivePatch.FixtureTypes.MagicPanel602 '2 Extended'
│   │   │   │   └──>401 (27) 'Mk3 1' ShowData.LivePatch.FixtureTypes.MaverickMK3Wash '1 Dual-Advanced movement-Advanced pixels'
│   │   │   ├──>Channel (1)
│   │   │   ├──>Universal (2)
│   │   │   ├──>Houselights (1)
│   │   │   ├──>NonDim (1)
│   │   │   ├──>Media (1)
│   │   │   ├──>Fog (1)
│   │   │   ├──>Effect (1)
│   │   │   ├──>Pyro (1)
│   │   │   ├──>MArker (1)
│   │   │   ├──>Multipatch (1)
│   │   │   └──>PSR (1)
│   │   ├──>DmxUniverses (1024) // info on all 1,024 universes. I will outline an entry for a populated universe
│   │   │   ├──>NO  Name  MergeMode  Request  Granted  CoarseParams  Used
│   │   │   └──>3 (512) DmxUniverse3 Prio Auto No 304 16
│   │   ├──>DmxAddresses (524288)
│   │   │   ├──>1 DMXAddress1
│   │   │   ├──>2 DMXAddress2
│   │   │   ├──>3 DMXAddress3
│   │   │   ├──>X DMXAddressX
│   │   │   └──>524288 DMXAddress 524288
│   │   ├──>FixtureTypesOverview (9)
│   │   │   ├──>Universal (8)
│   │   │   ├──>Ghibli (8)
│   │   │   ├──>Mac 101 (8)
│   │   │   ├──>Robin Spikie (8)
│   │   │   ├──>Veloce Profile (8)
│   │   │   ├──>Nando 502 (8)
│   │   │   ├──>MagicPanel 602 (8)
│   │   │   ├──>Zonda 9 FX (8)
│   │   │   └──>Maverick MK3 Wash (8)
│   │   └──>PatchFilter
│   ├──>PsrPatch 
│   ├──>Output
│   ├──>Masters
│   │   ├──>Selected (11)
│   │   │   ├──>Master
│   │   │   ├──>XFade
│   │   │   ├──>XFadeA
│   │   │   ├──>XFadeB
│   │   │   ├──>Temp
│   │   │   ├──>Rate
│   │   │   ├──>Speed
│   │   │   ├──>Highlight
│   │   │   ├──>Lowlight
│   │   │   ├──>Solo
│   │   │   └──>Time
│   │   ├──>Grand (15)
│   │   │   ├──>Master
│   │   │   ├──>World
│   │   │   ├──>Highlight
│   │   │   ├──>Lowlight
│   │   │   ├──>Solo
│   │   │   ├──>Rate
│   │   │   ├──>Reserved
│   │   │   ├──>ProgramTime
│   │   │   ├──>ProgramXFade
│   │   │   ├──>ExecutorTime
│   │   │   ├──>ExecutorXFade
│   │   │   ├──>Blind
│   │   │   ├──>SoundOut
│   │   │   ├──>SoundIn
│   │   │   └──>SoundFade
│   │   ├──>Speed (16)
│   │   │   ├──>Speed1
│   │   │   ├──>Speed2
│   │   │   ├──>Speed3
│   │   │   ├──>Speed4
│   │   │   ├──>Speed5
│   │   │   ├──>Speed6
│   │   │   ├──>Speed7
│   │   │   ├──>Speed8
│   │   │   ├──>Speed9
│   │   │   ├──>Speed10
│   │   │   ├──>Speed11
│   │   │   ├──>Speed12
│   │   │   ├──>Speed13
│   │   │   ├──>Speed14
│   │   │   ├──>Speed15
│   │   │   └──>BPM
│   │   ├──>Playback (50)
│   │   │   ├──>Playback1
│   │   │   ├──>Playback2
│   │   │   ├──>Playback3
│   │   │   ├──>Playback4
│   │   │   ├──>Playback5
│   │   │   ├──>Playback6
│   │   │   ├──>Playback7
│   │   │   ├──>Playback8
│   │   │   ├──>Playback9
│   │   │   ├──>Playback10
│   │   │   ├──>Playback11
│   │   │   ├──>Playback12
│   │   │   ├──>Playback13
│   │   │   ├──>Playback14
│   │   │   ├──>Playback15
│   │   │   ├──>Playback16
│   │   │   ├──>Playback17
│   │   │   ├──>Playback18
│   │   │   ├──>Playback19
│   │   │   ├──>Playback20
│   │   │   ├──>Playback21
│   │   │   ├──>Playback22
│   │   │   ├──>Playback23
│   │   │   ├──>Playback24
│   │   │   ├──>Playback25
│   │   │   ├──>Playback26
│   │   │   ├──>Playback27
│   │   │   ├──>Playback28
│   │   │   ├──>Playback29
│   │   │   ├──>Playback30
│   │   │   ├──>Playback31
│   │   │   ├──>Playback32
│   │   │   ├──>Playback33
│   │   │   ├──>Playback34
│   │   │   ├──>Playback35
│   │   │   ├──>Playback36
│   │   │   ├──>Playback37
│   │   │   ├──>Playback38
│   │   │   ├──>Playback39
│   │   │   ├──>Playback40
│   │   │   ├──>Playback41
│   │   │   ├──>Playback42
│   │   │   ├──>Playback43
│   │   │   ├──>Playback44
│   │   │   ├──>Playback45
│   │   │   ├──>Playback46
│   │   │   ├──>Playback47
│   │   │   ├──>Playback48
│   │   │   ├──>Playback49
│   │   │   └──>Playback50
│   │   └──>Timing (50)
│   │       ├──>Timing1
│   │       ├──>Timing2
│   │       ├──>Timing3
│   │       ├──>Timing4
│   │       ├──>Timing5
│   │       ├──>Timing6
│   │       ├──>Timing7
│   │       ├──>Timing8
│   │       ├──>Timing9
│   │       ├──>Timing10
│   │       ├──>Timing11
│   │       ├──>Timing12
│   │       ├──>Timing13
│   │       ├──>Timing14
│   │       ├──>Timing15
│   │       ├──>Timing16
│   │       ├──>Timing17
│   │       ├──>Timing18
│   │       ├──>Timing19
│   │       ├──>Timing20
│   │       ├──>Timing21
│   │       ├──>Timing22
│   │       ├──>Timing23
│   │       ├──>Timing24
│   │       ├──>Timing25
│   │       ├──>Timing26
│   │       ├──>Timing27
│   │       ├──>Timing28
│   │       ├──>Timing29
│   │       ├──>Timing30
│   │       ├──>Timing31
│   │       ├──>Timing32
│   │       ├──>Timing33
│   │       ├──>Timing34
│   │       ├──>Timing35
│   │       ├──>Timing36
│   │       ├──>Timing37
│   │       ├──>Timing38
│   │       ├──>Timing39
│   │       ├──>Timing40
│   │       ├──>Timing41
│   │       ├──>Timing42
│   │       ├──>Timing43
│   │       ├──>Timing44
│   │       ├──>Timing45
│   │       ├──>Timing46
│   │       ├──>Timing47
│   │       ├──>Timing48
│   │       ├──>Timing49
│   │       └──>Timing50
│   ├──>DataPools (2)
│   │   ├──>Default (15)
│   │   │   ├──>Worlds (1)
│   │   │   │   └──>All AppendX All Normal
│   │   │   ├──>Filters (1000)
│   │   │   │   ├──>All
│   │   │   │   ├──>Only Dimmer
│   │   │   │   ├──>Only Position
│   │   │   │   ├──>Only Color
│   │   │   │   ├──>Prog Only
│   │   │   │   ├──>Selection Only
│   │   │   │   └──>Parked Only
│   │   │   ├──>GeneratorTypes (2)
│   │   │   │   ├──>Bitmaps (1000)
│   │   │   │   │   └──>Bitmap 1 ShowData.MediaPools.Videos.[ring_webm] // followed by other video information
│   │   │   │   └──>Generators
│   │   │   ├──>PresetPools (25)
│   │   │   │       ├──>Dimmer
│   │   │   │       ├──>Position
│   │   │   │       ├──>Gobo
│   │   │   │       ├──>Color
│   │   │   │       ├──>Beam
│   │   │   │       ├──>Focus
│   │   │   │       ├──>Control
│   │   │   │       ├──>Shapers
│   │   │   │       ├──>Video
│   │   │   │       ├──>All 1
│   │   │   │       ├──>All 2
│   │   │   │       ├──>All 3
│   │   │   │       ├──>All 4
│   │   │   │       └──>All 5
│   │   │   ├──>Groups (1000)
│   │   │   │   ├──>1 Ghiblis
│   │   │   │   ├──>2 101s
│   │   │   │   ├──>3 Spikies
│   │   │   │   └──>4 Veloces
│   │   │   ├──>Sequences (1000) // contains almost every attribute found in sequence settings
│   │   │   │   ├──>Sequence 1
│   │   │   │   ├──>Sequence 2
│   │   │   │   ├──>Sequence 3
│   │   │   │   └──>Sequence 4
│   │   │   ├──>Plugins (1000) // Name Scribble Appearance Note 
│   │   │   │   ├──>Plugin 1 NA NA Plugin to do stuff
│   │   │   │   ├──>Plugin 2 NA NA Plugin to do other thing
│   │   │   │   ├──>Plugin 3 NA NA Third feature
│   │   │   │   ├──>Plugin 4 NA NA Prints 'hello world'
│   │   │   ├──>Macros (1000) // Name Scribble Appearance Note Tags CLI
│   │   │   │   ├──>ClearAll
│   │   │   │   ├──>PATCH
│   │   │   │   ├──>SAVE
│   │   │   │   ├──>NETWORK
│   │   │   │   ├──>ClearOne
│   │   │   │   ├──>STOMP
│   │   │   │   ├──>ReloadPlugins
│   │   │   │   └──>Import Predefined Phaser
│   │   │   ├──>QuickKeys
│   │   │   ├──>MAtricks
│   │   │   ├──>Configurations (14)
│   │   │   │   ├──>Default Sequence
│   │   │   │   ├──>Default Macro
│   │   │   │   ├──>Default View 
│   │   │   │   ├──>Default World
│   │   │   │   ├──>Default Group
│   │   │   │   ├──>Default Preset
│   │   │   │   ├──>Default Plugin
│   │   │   │   ├──>Default User
│   │   │   │   ├──>Default Sound
│   │   │   │   ├──>Default ScreenConfig
│   │   │   │   ├──>Default Timer 
│   │   │   │   ├──>Default Master
│   │   │   │   ├──>Default SpeedMaster
│   │   │   │   └──>Default PlaybackMaster
│   │   │   ├──>Pages (1)
│   │   │   │   └──>Page 1
│   │   │   ├──>Layouts (1000) // Name PositionX PositionY DimensionW DimensionH UsedX UsedY UsedW UsedH
│   │   │   │   └──>Default
│   │   │   ├──>Timecodes
│   │   │   └──>Timers (1)
│   │   │       └──>Stopwatch
│   │   └──>Pool 2 (15)
│   │       ├──>Worlds (1)
│   │       │   └──>All AppendX All Normal
│   │       ├──>Filters (1000)
│   │       │   ├──>All
│   │       │   ├──>Only Dimmer
│   │       │   ├──>Only Position
│   │       │   ├──>Only Color
│   │       │   ├──>Prog Only
│   │       │   ├──>Selection Only
│   │       │   └──>Parked Only
│   │       ├──>GeneratorTypes (2)
│   │       │   ├──>Bitmaps (1000)
│   │       │   │   └──>Bitmap 1 ShowData.MediaPools.Videos.[ring_webm] // followed by other video information
│   │       │   └──>Generators
│   │       ├──>PresetPools (25)
│   │       │       ├──>Dimmer
│   │       │       ├──>Position
│   │       │       ├──>Gobo
│   │       │       ├──>Color
│   │       │       ├──>Beam
│   │       │       ├──>Focus
│   │       │       ├──>Control
│   │       │       ├──>Shapers
│   │       │       ├──>Video
│   │       │       ├──>All 1
│   │       │       ├──>All 2
│   │       │       ├──>All 3
│   │       │       ├──>All 4
│   │       │       └──>All 5
│   │       ├──>Groups (1000)
│   │       │   ├──>1 Ghiblis
│   │       │   ├──>2 101s
│   │       │   ├──>3 Spikies
│   │       │   └──>4 Veloces
│   │       ├──>Sequences (1000) // contains almost every attribute found in sequence settings
│   │       │   ├──>Sequence 1
│   │       │   ├──>Sequence 2
│   │       │   ├──>Sequence 3
│   │       │   └──>Sequence 4
│   │       ├──>Plugins (1000) // Name Scribble Appearance Note 
│   │       │   ├──>Plugin 1 NA NA Plugin to do stuff
│   │       │   ├──>Plugin 2 NA NA Plugin to do other thing
│   │       │   ├──>Plugin 3 NA NA Third feature
│   │       │   ├──>Plugin 4 NA NA Prints 'hello world'
│   │       ├──>Macros (1000) // Name Scribble Appearance Note Tags CLI
│   │       │   ├──>ClearAll
│   │       │   ├──>PATCH
│   │       │   ├──>SAVE
│   │       │   ├──>NETWORK
│   │       │   ├──>ClearOne
│   │       │   ├──>STOMP
│   │       │   ├──>ReloadPlugins
│   │       │   └──>Import Predefined Phaser
│   │       ├──>QuickKeys
│   │       ├──>MAtricks
│   │       ├──>Configurations (14)
│   │       │   ├──>Default Sequence
│   │       │   ├──>Default Macro
│   │       │   ├──>Default View 
│   │       │   ├──>Default World
│   │       │   ├──>Default Group
│   │       │   ├──>Default Preset
│   │       │   ├──>Default Plugin
│   │       │   ├──>Default User
│   │       │   ├──>Default Sound
│   │       │   ├──>Default ScreenConfig
│   │       │   ├──>Default Timer 
│   │       │   ├──>Default Master
│   │       │   ├──>Default SpeedMaster
│   │       │   └──>Default PlaybackMaster
│   │       ├──>Pages (1)
│   │       │   └──>Page 1
│   │       ├──>Layouts (1000) // Name PositionX PositionY DimensionW DimensionH UsedX UsedY UsedW UsedH
│   │       │   └──>Default
│   │       ├──>Timecodes
│   │       └──>Timers (1)
│   │           └──>Stopwatch
│   ├──>DMXRoot
│   ├──>Agendas // Name Mode StartDate StartTime EndDate EndTime DaylightOffset ValidDuration Enabled
│   │   └──>AgendaEvent1
│   ├──>Remotes
│   │   ├──>DCRemotes
│   │   ├──>MIDIRemotes
│   │   └──>DmxRemotes
│   ├──>OSCBase // Name DestinationIP Mode Port DataPool Page Fader ExecutorKnob Key FaderRange Receive Send
│   │   ├──>OSCData1 127.255.255.255
│   │   └──>OSCData2 192.168.255.255
│   ├──>UserProfiles
│   │   ├──>Default (21)
│   │   │   ├──>Environments (2)
│   │   │   │   ├──>UserEnvironment1 1   
│   │   │   │   └──>UserEnvironment1 2
│   │   │   ├──>EncoderBarPool (1)
│   │   │   │   └──>EncoderBar1
│   │   │   ├──>Cameras (1000)
│   │   │   │   ├──>Auto
│   │   │   │   ├──>Front
│   │   │   │   ├──>Front/Left
│   │   │   │   ├──>Left
│   │   │   │   ├──>Back/Left
│   │   │   │   ├──>Back
│   │   │   │   ├──>Back/Right
│   │   │   │   ├──>Right
│   │   │   │   ├──>Front/Right
│   │   │   │   ├──>Top
│   │   │   │   ├──>2D Front
│   │   │   │   ├──>2D Left
│   │   │   │   ├──>2D Back
│   │   │   │   ├──>2D Right
│   │   │   │   └──>2D Top
│   │   │   ├──>WindowTypes (82) // every window popup that exists in a basic MA3 system!
│   │   │   │   ├──>Window3D
│   │   │   │   ├──>WindowAlignBar
│   │   │   │   ├──>WindowAppearancePool
│   │   │   │   ├──>WindowAtFilter
│   │   │   │   ├──>WindowCameraPool
│   │   │   │   ├──>WindowRenderQualityPool
│   │   │   │   ├──>WindowClock
│   │   │   │   ├──>WindowSpecialDialog
│   │   │   │   ├──>WindowCommandLine
│   │   │   │   ├──>WindowDataPool
│   │   │   │   ├──>WindowDmxSheet
│   │   │   │   ├──>WindowConfigurationPool
│   │   │   │   ├──>WindowFilterPool
│   │   │   │   ├──>WindowFixtureSheet
│   │   │   │   ├──>WindowSymbolPool
│   │   │   │   ├──>WindowTagPool
│   │   │   │   ├──>WindowGelPool
│   │   │   │   ├──>WindowGoboPool
│   │   │   │   ├──>WindowGroupPool
│   │   │   │   ├──>WindowHelpViewer
│   │   │   │   ├──>WindowImagePool
│   │   │   │   ├──>WindowInfo
│   │   │   │   ├──>WindowLayoutPool
│   │   │   │   ├──>WindowLayoutView
│   │   │   │   ├──>WindowMacroPool
│   │   │   │   ├──>WindowQuickeyPool
│   │   │   │   ├──>WindowMatricks
│   │   │   │   ├──>WindowMatricksPool
│   │   │   │   ├──>WindowMeshPool
│   │   │   │   ├──>WindowMessageCenter
│   │   │   │   ├──>WindowPagePool
│   │   │   │   ├──>WindowPhaserEditor
│   │   │   │   ├──>WindowPlaybacks
│   │   │   │   ├──>WindowPluginPool
│   │   │   │   ├──>WindowRecipeEditor
│   │   │   │   ├──>WindowRunningPlaybacks
│   │   │   │   ├──>WindowRDM
│   │   │   │   ├──>WindowScribblePool
│   │   │   │   ├──>WindowSelectionBar
│   │   │   │   ├──>WindowSelectionView
│   │   │   │   ├──>WindowSequencePool
│   │   │   │   ├──>WindowSequenceSheet
│   │   │   │   ├──>WindowSmartView
│   │   │   │   ├──>WindowSound
│   │   │   │   ├──>WindowSoundPool
│   │   │   │   ├──>WindowStepBar
│   │   │   │   ├──>WindowSystemInfo
│   │   │   │   ├──>WindowSystemMonitor
│   │   │   │   ├──>WindowTimecodePool
│   │   │   │   ├──>WindowTimecodeSlotPool
│   │   │   │   ├──>WindowTimecode
│   │   │   │   ├──>WindowUniversePool
│   │   │   │   ├──>WindowUserPool
│   │   │   │   ├──>WindowEncoderBarPool
│   │   │   │   ├──>WindowVideoPool
│   │   │   │   ├──>WindowViewPool
│   │   │   │   ├──>WindowWorldPool
│   │   │   │   ├──>WindowGeneratorRandomPool
│   │   │   │   ├──>WindowGeneratorBitmapPool
│   │   │   │   ├──>WindowAgenda
│   │   │   │   ├──>WindowXKeys
│   │   │   │   ├──>WindowTrackpad
│   │   │   │   ├──>WindowCustomMasterSection
│   │   │   │   ├──>WindowEncoderBar
│   │   │   │   ├──>WindowCommandWingBar
│   │   │   │   ├──>WindowContentSheet
│   │   │   │   ├──>WindowTimerPool
│   │   │   │   ├──>WindowPresetPool 
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   │   ├──>WindowPresetPool
│   │   │   ├──>Views (1000) // each stored layout on your showfile. each layout contains info from the 'WindowTypes' class
│   │   │   │   ├──>main (10) // Name Display X Y W H MinW MinH MaxW MaxH PresetPoolType
│   │   │   │   │   ├──>WindowPluginPool
│   │   │   │   │   ├──>WindowMacroPool
│   │   │   │   │   ├──>WindowCommandLine
│   │   │   │   │   ├──>WindowSystemMonitor
│   │   │   │   │   ├──>WindowSystemInfo
│   │   │   │   │   ├──>WindowGroupPool
│   │   │   │   │   ├──>WindowCustomMasterSection
│   │   │   │   │   ├──>Window3d
│   │   │   │   │   ├──>WindowPlaybacks
│   │   │   │   │   └──>WindowClock
│   │   │   │   ├──>Preset (4)
│   │   │   │   ├──>Sequence Sheet (7)
│   │   │   │   ├──>Phaser (4)
│   │   │   │   ├──>3D (2)
│   │   │   │   ├──>Help (1)
│   │   │   │   ├──>Special Dialog (1)
│   │   │   │   ├──>Trackpad (1)
│   │   │   │   ├──>MATricks s6 (1)
│   │   │   │   ├──>SpecialDialog s6 (1)
│   │   │   │   ├──>Trackpad s6 (1)
│   │   │   │   ├──>AtFilter s6 (2)
│   │   │   │   ├──>envTest (5)
│   │   │   │   ├──>cmd (8)
│   │   │   │   ├──>cmd (2)
│   │   │   │   ├──>selGrid (3)
│   │   │   │   ├──>magicpanel main (8)
│   │   │   │   ├──>fixtureSheet (4)
│   │   │   │   ├──>users (1)
│   │   │   │   ├──>playbacks (1)
│   │   │   │   └──>dmx (1)
│   │   │   ├──>StorePreferences (8)
│   │   │   │   ├──>Preset
│   │   │   │   ├──>Sequence
│   │   │   │   ├──>Executor
│   │   │   │   ├──>Views (57)
│   │   │   │   │   ├──>FixtureSheet
│   │   │   │   │   ├──>DMXSheet
│   │   │   │   │   ├──>SequenceSheet
│   │   │   │   │   ├──>ContentSheet
│   │   │   │   │   ├──>Window3D
│   │   │   │   │   ├──>MessageGrid
│   │   │   │   │   ├──>RunningPlaybacks
│   │   │   │   │   ├──>ClockWindow
│   │   │   │   │   ├──>SmartView
│   │   │   │   │   ├──>GenericPool
│   │   │   │   │   ├──>PresetPool
│   │   │   │   │   ├──>CommandlineWindow
│   │   │   │   │   ├──>HelpViewerWindow
│   │   │   │   │   ├──>SelectionView
│   │   │   │   │   ├──>SysteminfoWindow
│   │   │   │   │   ├──>SysmonWindow
│   │   │   │   │   ├──>Window
│   │   │   │   │   ├──>GelPool
│   │   │   │   │   ├──>TimecodeWindow
│   │   │   │   │   ├──>WindowAgenda
│   │   │   │   │   ├──>WindowPhaserEditor
│   │   │   │   │   ├──>ColorPicker
│   │   │   │   │   ├──>RdmWindow
│   │   │   │   │   ├──>SpecialWindow
│   │   │   │   │   ├──>EncoderBarWindow
│   │   │   │   │   ├──>LayoutView
│   │   │   │   │   ├──>WindowInfo
│   │   │   │   │   ├──>PlaybackWindow
│   │   │   │   │   ├──>BitmapPool
│   │   │   │   │   ├──>ExecConfigPool
│   │   │   │   │   ├──>FilterPool
│   │   │   │   │   ├──>GeneratorPool
│   │   │   │   │   ├──>GroupPool
│   │   │   │   │   ├──>LayoutPool
│   │   │   │   │   ├──>MacroPool
│   │   │   │   │   ├──>MatricksPool
│   │   │   │   │   ├──>PagePool
│   │   │   │   │   ├──>PluginPool
│   │   │   │   │   ├──>QuickeyPool
│   │   │   │   │   ├──>SequencePool
│   │   │   │   │   ├──>TimecodePool
│   │   │   │   │   ├──>TimerPool
│   │   │   │   │   ├──>WorldPool
│   │   │   │   │   ├──>PresetDynamicPool
│   │   │   │   │   ├──>PresetAllPool
│   │   │   │   │   ├──>PresetDimmerPool
│   │   │   │   │   ├──>PresetPositionPool
│   │   │   │   │   ├──>PresetGoboPool
│   │   │   │   │   ├──>PresetColorPool
│   │   │   │   │   ├──>PresetBeamPool
│   │   │   │   │   ├──>PresetFocusPool
│   │   │   │   │   ├──>PresetControlPool
│   │   │   │   │   ├──>PresetShapersPool
│   │   │   │   │   ├──>PresetVideoPool
│   │   │   │   │   ├──>SoundPool
│   │   │   │   │   ├──>TimecodeSlotPool
│   │   │   │   │   └──>VideoPool
│   │   │   │   ├──>Timecode
│   │   │   │   ├──>AutoCreateSettings
│   │   │   │   ├──>Timer
│   │   │   │   └──>Group
│   │   │   ├──>ExecutorFixation
│   │   │   ├──>SequenceSelection
│   │   │   ├──>SpecialExecutorPages (6)
│   │   │   │   ├──>SpecialExecutor1 (390) // 'Name' 'Key' 
│   │   │   │   │   ├──>Master 
│   │   │   │   │   ├──>XFade
│   │   │   │   │   ├──>Highlight Toggle
│   │   │   │   │   ├──>Solo Toggle
│   │   │   │   │   ├──>Master Black
│   │   │   │   │   ├──>Speed1 Speed1
│   │   │   │   │   ├──>Speed2 Speed1
│   │   │   │   │   ├──>Speed1 LearnSpeed
│   │   │   │   │   ├──>Speed2 LearnSpeed
│   │   │   │   │   ├──>ExecutorTime
│   │   │   │   │   ├──>ExecutorTime Off
│   │   │   │   │   ├──>ExecutorTime Toggle
│   │   │   │   │   ├──>ExecutorTime On
│   │   │   │   │   ├──>ProgramTime
│   │   │   │   │   ├──>ProgramTime Off
│   │   │   │   │   ├──>ProgramTime Toggle
│   │   │   │   │   └──>ProgramTime On
│   │   │   │   ├──>SpecialExecutor2 (390)   
│   │   │   │   │   ├──>Master 
│   │   │   │   │   ├──>XFade
│   │   │   │   │   ├──>Highlight Toggle
│   │   │   │   │   ├──>Solo Toggle
│   │   │   │   │   ├──>Master Black
│   │   │   │   │   ├──>Speed1 Speed1
│   │   │   │   │   ├──>Speed2 Speed1
│   │   │   │   │   ├──>Speed1 LearnSpeed
│   │   │   │   │   ├──>Speed2 LearnSpeed
│   │   │   │   │   ├──>ExecutorTime
│   │   │   │   │   ├──>ExecutorTime Off
│   │   │   │   │   ├──>ExecutorTime Toggle
│   │   │   │   │   ├──>ExecutorTime On
│   │   │   │   │   ├──>ProgramTime
│   │   │   │   │   ├──>ProgramTime Off
│   │   │   │   │   ├──>ProgramTime Toggle
│   │   │   │   │   └──>ProgramTime On
│   │   │   │   ├──>SpecialExecutor3 (390) 
│   │   │   │   │   ├──>Master 
│   │   │   │   │   ├──>XFade
│   │   │   │   │   ├──>Highlight Toggle
│   │   │   │   │   ├──>Solo Toggle
│   │   │   │   │   ├──>Master Black
│   │   │   │   │   ├──>Speed1 Speed1
│   │   │   │   │   ├──>Speed2 Speed1
│   │   │   │   │   ├──>Speed1 LearnSpeed
│   │   │   │   │   ├──>Speed2 LearnSpeed
│   │   │   │   │   ├──>ExecutorTime
│   │   │   │   │   ├──>ExecutorTime Off
│   │   │   │   │   ├──>ExecutorTime Toggle
│   │   │   │   │   ├──>ExecutorTime On
│   │   │   │   │   ├──>ProgramTime
│   │   │   │   │   ├──>ProgramTime Off
│   │   │   │   │   ├──>ProgramTime Toggle
│   │   │   │   │   └──>ProgramTime On
│   │   │   │   ├──>SpecialExecutor4 (390) 
│   │   │   │   │   ├──>Master 
│   │   │   │   │   ├──>XFade
│   │   │   │   │   ├──>Highlight Toggle
│   │   │   │   │   ├──>Solo Toggle
│   │   │   │   │   ├──>Master Black
│   │   │   │   │   ├──>Speed1 Speed1
│   │   │   │   │   ├──>Speed2 Speed1
│   │   │   │   │   ├──>Speed1 LearnSpeed
│   │   │   │   │   ├──>Speed2 LearnSpeed
│   │   │   │   │   ├──>ExecutorTime
│   │   │   │   │   ├──>ExecutorTime Off
│   │   │   │   │   ├──>ExecutorTime Toggle
│   │   │   │   │   ├──>ExecutorTime On
│   │   │   │   │   ├──>ProgramTime
│   │   │   │   │   ├──>ProgramTime Off
│   │   │   │   │   ├──>ProgramTime Toggle
│   │   │   │   │   └──>ProgramTime On
│   │   │   │   ├──>SpecialExecutor5 (390) 
│   │   │   │   │   ├──>Master 
│   │   │   │   │   ├──>XFade
│   │   │   │   │   ├──>Highlight Toggle
│   │   │   │   │   ├──>Solo Toggle
│   │   │   │   │   ├──>Master Black
│   │   │   │   │   ├──>Speed1 Speed1
│   │   │   │   │   ├──>Speed2 Speed1
│   │   │   │   │   ├──>Speed1 LearnSpeed
│   │   │   │   │   ├──>Speed2 LearnSpeed
│   │   │   │   │   ├──>ExecutorTime
│   │   │   │   │   ├──>ExecutorTime Off
│   │   │   │   │   ├──>ExecutorTime Toggle
│   │   │   │   │   ├──>ExecutorTime On
│   │   │   │   │   ├──>ProgramTime
│   │   │   │   │   ├──>ProgramTime Off
│   │   │   │   │   ├──>ProgramTime Toggle
│   │   │   │   │   └──>ProgramTime On
│   │   │   │   └──>SpecialExecutor6 (390) 
│   │   │   │       ├──>Master 
│   │   │   │       ├──>XFade
│   │   │   │       ├──>Highlight Toggle
│   │   │   │       ├──>Solo Toggle
│   │   │   │       ├──>Master Black
│   │   │   │       ├──>Speed1 Speed1
│   │   │   │       ├──>Speed2 Speed1
│   │   │   │       ├──>Speed1 LearnSpeed
│   │   │   │       ├──>Speed2 LearnSpeed
│   │   │   │       ├──>ExecutorTime
│   │   │   │       ├──>ExecutorTime Off
│   │   │   │       ├──>ExecutorTime Toggle
│   │   │   │       ├──>ExecutorTime On
│   │   │   │       ├──>ProgramTime
│   │   │   │       ├──>ProgramTime Off
│   │   │   │       ├──>ProgramTime Toggle
│   │   │   │       └──>ProgramTime On
│   │   │   ├──>TemporaryWindowSettings (25)
│   │   │   │   ├──>SequenceSheetSettings (6)
│   │   │   │   │   ├──>Column Filters (1)
│   │   │   │   │   │   └──>SequenceSheetColumnFilter1
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>SequenceSheetRowFilter (1)
│   │   │   │   │   │   └──>GridObjectContentFilterItem
│   │   │   │   │   ├──>GridColumnConfigurationCollect (4)
│   │   │   │   │   │   ├──>Set 1
│   │   │   │   │   │   ├──>Track
│   │   │   │   │   │   ├──>MIB
│   │   │   │   │   │   └──>Timing
│   │   │   │   │   ├──>FilteredSheetSettingsFilterCollect (16)
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 0 
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 1
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 2
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 3
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 4
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 5
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 6
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 7
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 8
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 9
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 10
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 11
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 12
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 13
│   │   │   │   │   │   ├──>FakeFilteredSheetSettingsFilter 14
│   │   │   │   │   │   └──>FakeFilteredSheetSettingsFilter 15
│   │   │   │   │   └──>RecipeSheetSettings (4)
│   │   │   │   │       ├──>Column Filters
│   │   │   │   │       ├──>Set
│   │   │   │   │       ├──>GridContentFilter
│   │   │   │   │       └──>GridColumnConfigurationCollect
│   │   │   │   ├──>TimecodeWindowSettings (6)
│   │   │   │   │   ├──>Column Filters
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>GridContentsFilter
│   │   │   │   │   ├──>GridColumnConfigurationCollect
│   │   │   │   │   ├──>GridSettings
│   │   │   │   │   └──>TimecodeWindowSharedContainer
│   │   │   │   ├──>PatchEditorSettings (4)
│   │   │   │   │   ├──>Column Filters (2)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter (9)
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>PatchLiveSettings (4)
│   │   │   │   │   ├──>Column Filters (2)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter (1)
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>MatricksWindowSettings
│   │   │   │   ├──>PresetEditorSettings (4)
│   │   │   │   │   ├──>Column Filters (1)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter 
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>WindowPhaserEditorSettings (4)
│   │   │   │   │   ├──>Column Filters (1)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter 
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>FixtureEditorSettings (4)
│   │   │   │   │   ├──>Column Filters (2)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter 
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>ExecEditorSettings
│   │   │   │   ├──>View3DSettings (1)
│   │   │   │   │   └──>Front
│   │   │   │   ├──>RenderQuality
│   │   │   │   ├──>WindowInfoSettings
│   │   │   │   ├──>SelectionViewSettings
│   │   │   │   ├──>CloningWindowSettings
│   │   │   │   ├──>SequencePoolSettings
│   │   │   │   ├──>GroupPoolSettings
│   │   │   │   ├──>PresetPoolSettings
│   │   │   │   ├──>PagePoolSettings
│   │   │   │   ├──>MacroPoolSettings
│   │   │   │   ├──>PoolSettings
│   │   │   │   ├──>RunningPlaybacksSettings (1)
│   │   │   │   │   └──>RunningPlaybacksSheetSettings1 (4)
│   │   │   │   │       ├──>Column Filters (7)
│   │   │   │   │       ├──>Set
│   │   │   │   │       ├──>PatchRowFilter 
│   │   │   │   │       └──>GridColumnConfigurationCollect (1)
│   │   │   │   ├──>PlaybackWindowSettings
│   │   │   │   ├──>AtFilterSettings
│   │   │   │   ├──>DMXAddressSettings (4)
│   │   │   │   │   ├──>Column Filters (1)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter 
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   │   └──>DMXSheetSettings (4)
│   │   │   │   │   ├──>Column Filters (1)
│   │   │   │   │   ├──>Set
│   │   │   │   │   ├──>PatchRowFilter 
│   │   │   │   │   └──>GridColumnConfigurationCollect (1)
│   │   │   ├──>SmartViewPool (1)
│   │   │   ├──>Variables
│   │   │   ├──>ScreenConfigurations (3)
│   │   │   │   ├──>Default (4)
│   │   │   │   │   ├──>ScreenContents (7)
│   │   │   │   │   │   ├──>ScreenContent 1 (2)
│   │   │   │   │   │   │   ├──>WindowCommandLine (3)
│   │   │   │   │   │   │   │   ├──>CommandlineWindowSettings 
│   │   │   │   │   │   │   │   ├──>WindowAppearance
│   │   │   │   │   │   │   │   └──>WindowScrollPositions
│   │   │   │   │   │   │   └──>WindowSystemMonitor (3)
│   │   │   │   │   │   │       ├──>SysmonWindowSettings
│   │   │   │   │   │   │       ├──>WindowAppearance
│   │   │   │   │   │   │       └──>WindowScrollPositions
│   │   │   │   │   │   ├──>ScreenContent 2
│   │   │   │   │   │   ├──>ScreenContent 3
│   │   │   │   │   │   ├──>ScreenContent 4
│   │   │   │   │   │   ├──>ScreenContent 5
│   │   │   │   │   │   ├──>ScreenContent 6
│   │   │   │   │   │   └──>ScreenContent 7
│   │   │   │   │   ├──>ViewButtonScreens2 (7)
│   │   │   │   │   │   ├──>ViewButtonScreen 1 (14)
│   │   │   │   │   │   │   ├──>main 
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   ├──>Help
│   │   │   │   │   │   │   ├──>envTest
│   │   │   │   │   │   │   ├──>fixtureSheet
│   │   │   │   │   │   │   ├──>magicpanel main
│   │   │   │   │   │   │   ├──>selGrid
│   │   │   │   │   │   │   ├──>selGrid
│   │   │   │   │   │   │   ├──>users
│   │   │   │   │   │   │   ├──>dmx
│   │   │   │   │   │   │   └──>cmd
│   │   │   │   │   │   ├──>ViewButtonScreen 2 (7)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   ├──>Help
│   │   │   │   │   │   │   └──>playbacks
│   │   │   │   │   │   ├──>ViewButtonScreen 3 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 4 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 5 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 6 (4)
│   │   │   │   │   │   │   ├──>MAtricks s6
│   │   │   │   │   │   │   ├──>Special Dialog s6
│   │   │   │   │   │   │   ├──>Trackpad s6
│   │   │   │   │   │   │   └──>AtFilter s6
│   │   │   │   │   │   └──>ViewButtonScreen 7 (2)
│   │   │   │   │   │       ├──>Special Dialog
│   │   │   │   │   │       └──>Trackpad
│   │   │   │   │   ├──>PluginPreferencesCollect (18)
│   │   │   │   │   │   ├──>GenericEdit
│   │   │   │   │   │   ├──>MacroEdit
│   │   │   │   │   │   ├──>PresetBar
│   │   │   │   │   │   ├──>ExecutorEditor
│   │   │   │   │   │   ├──>CommandControl
│   │   │   │   │   │   ├──>RunningPlaybacksOverlay
│   │   │   │   │   │   ├──>SequenceEdit
│   │   │   │   │   │   ├──>sMAke
│   │   │   │   │   │   ├──>WindowFixtureSheet
│   │   │   │   │   │   ├──>GeneratorBitmapEdit
│   │   │   │   │   │   ├──>OopsOverlay
│   │   │   │   │   │   ├──>UpdateOverlay
│   │   │   │   │   │   ├──>KeyboardShortcutEditor
│   │   │   │   │   │   ├──>EncoderBarControl
│   │   │   │   │   │   ├──>PlaybackControl
│   │   │   │   │   │   ├──>DMXTester
│   │   │   │   │   │   ├──>AtFilterOverlay
│   │   │   │   │   │   └──>MessageCenter
│   │   │   │   │   └──>PoolSettings
│   │   │   │   ├──>3D (4)
│   │   │   │   │   ├──>ScreenContents (7)
│   │   │   │   │   │   ├──>ScreenContent 1 (1)
│   │   │   │   │   │   │   └──>WindowUserPool (3)
│   │   │   │   │   │   │       ├──>PoolSettings 
│   │   │   │   │   │   │       ├──>WindowAppearance
│   │   │   │   │   │   │       └──>WindowScrollPositions
│   │   │   │   │   │   ├──>ScreenContent 2
│   │   │   │   │   │   ├──>ScreenContent 3
│   │   │   │   │   │   ├──>ScreenContent 4
│   │   │   │   │   │   ├──>ScreenContent 5
│   │   │   │   │   │   ├──>ScreenContent 6
│   │   │   │   │   │   └──>ScreenContent 7
│   │   │   │   │   ├──>ViewButtonsScreens2 (7)
│   │   │   │   │   │   ├──>ViewButtonScreen 1 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 2 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 3 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 4 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 5 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 6 (4)
│   │   │   │   │   │   │   ├──>MAtricks s6
│   │   │   │   │   │   │   ├──>Special Dialog s6
│   │   │   │   │   │   │   ├──>Trackpad s6
│   │   │   │   │   │   │   └──>AtFilter s6
│   │   │   │   │   │   └──>ViewButtonScreen 7 (2)
│   │   │   │   │   │       ├──>Special Dialog
│   │   │   │   │   │       └──>Trackpad
│   │   │   │   │   ├──>PluginPreferencesCollect3
│   │   │   │   │   └──>PoolSettings
│   │   │   │   └──>Remote (4)
│   │   │   │   │   ├──>ScreenContents (7)
│   │   │   │   │   │   ├──>ScreenContent 1 (1)
│   │   │   │   │   │   │   └──>WindowUserPool (3)
│   │   │   │   │   │   │       ├──>PoolSettings 
│   │   │   │   │   │   │       ├──>WindowAppearance
│   │   │   │   │   │   │       └──>WindowScrollPositions
│   │   │   │   │   │   ├──>ScreenContent 2
│   │   │   │   │   │   ├──>ScreenContent 3
│   │   │   │   │   │   ├──>ScreenContent 4
│   │   │   │   │   │   ├──>ScreenContent 5
│   │   │   │   │   │   ├──>ScreenContent 6
│   │   │   │   │   │   └──>ScreenContent 7
│   │   │   │   │   ├──>ViewButtonsScreens2 (7)
│   │   │   │   │   │   ├──>ViewButtonScreen 1 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 2 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 3 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 4 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 5 (6)
│   │   │   │   │   │   │   ├──>main
│   │   │   │   │   │   │   ├──>Preset
│   │   │   │   │   │   │   ├──>Sequence Sheet
│   │   │   │   │   │   │   ├──>Phaser
│   │   │   │   │   │   │   ├──>3D
│   │   │   │   │   │   │   └──>Help
│   │   │   │   │   │   ├──>ViewButtonScreen 6 (4)
│   │   │   │   │   │   │   ├──>MAtricks s6
│   │   │   │   │   │   │   ├──>Special Dialog s6
│   │   │   │   │   │   │   ├──>Trackpad s6
│   │   │   │   │   │   │   └──>AtFilter s6
│   │   │   │   │   │   └──>ViewButtonScreen 7 (2)
│   │   │   │   │   │       ├──>Special Dialog
│   │   │   │   │   │       └──>Trackpad
│   │   │   │   │   ├──>PluginPreferencesCollect3
│   │   │   │   │   └──>PoolSettings
│   │   │   ├──>LayoutElementDefaultsCollect (15)
│   │   │   ├──>KeyboardShortcuts (157)
│   │   │   ├──>UserAttributePreferences (479)
│   │   │   ├──>RenderQualities (1000)
│   │   │   ├──>SequenceSelection
│   │   │   ├──>Collection
│   │   │   ├──>GridColumnRegistry (46)
│   │   │   └──>StatusCenter (20)
│   │   ├──>UserProfile2 (21)
│   │   └──>new (21)
│   ├──>Users
│   ├──>PlaybackTable 
│   ├──>PSNProtocol
│   ├──>Materials
│   └──>MVRxchange
├──>
├──>
├──>
├──>
├──>
├──>
├──>
├──>
├──>
├──>
```
