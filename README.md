<!-- markdownlint-configure-file {
  "MD013": {
    "code_blocks": false,
    "tables": false
  },
  "MD033": false,
  "MD041": false
} -->

# [Electron.js](https://electronjs.org/) Alternatives [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="electron-logo.svg" align="right" width="100">](https://electronjs.org)

> A curated list of awesome [Electron](https://electronjs.org) alternatives.

[Electron](https://electronjs.org/) is an open-source framework for creating desktop apps using web technologies as JavaScript, HTML and CSS. It combines the [Chromium](https://www.chromium.org) rendering engine and the [Node.js](https://nodejs.org) runtime.

There are a number of good reasons to avoid Electron or consider something other than Electron:
* Large size
* Resource (RAM) hogging
* [Source code protection](https://www.contextis.com/en/blog/basic-electron-framework-exploitation)
* We would already have a web component in the system that can be used.
* Electron apps cannot be submitted to the [Apple store](https://news.ycombinator.com/item?id=21437255)
* Minimal resources

<br>

## Alternatives to the [electron](https://electronjs.org)

### C#(.Net)
* [Orleans](https://github.com/dotnet/Orleans): Cloud Native application framework for .NET
* [Avalonia](https://avaloniaui.net): Avalonia UI creates pixel-perfect, native, create Multi-Platform Apps with .NET
* [Uno](https://platform.uno): Pixel-Perfect Multi-Platform Applications with C# and WinUI
* [Chromely](https://github.com/chromelyapps/Chromely): Build HTML Desktop Apps on .NET/.NET Core/.NET 5 using native GUI, HTML5, JavaScript, CSS
* [SpiderEye](https://github.com/JBildstein/SpiderEye): Cross platform .Net Core applications with a webview UI
* [Photino.NET](https://github.com/tryphotino/photino.NET): Photino uses the OSs built-in WebKit-based browser control for Windows, macOS and Linux. Photino is the lightest cross-platform framework. Compared to Electron, a Photino app is up to 110 times smaller! And it uses far less system memory too!
* [foton](https://github.com/integrativesoft/foton): Prototype for an Electron alternative written in C# by Integrative Software LLC and contributors

### C/C++
* [Qt](https://www.qt.io)
* [wxWidgets](https://wxwidgets.org): wxWidgets is a C++ library that lets developers create applications for Windows, macOS, Linux and other platforms with a single code base. It has popular language bindings for Python, Ruby, Lua, Perl and several other languages
* [sciter](https://sciter.com): Embeddable HTML/CSS/JavaScript engine for modern UI development
* [Ultralight](https://ultralig.ht): Ultra-fast, ultra-light, standards-compliant HTML renderer for applications and games. Based on WebKit— supports most modern HTML5, CSS, and JavaScript features while still remaining light and configurable.
* [Webview](https://github.com/webview/webview): Tiny cross-platform webview library which uses Cocoa/WebKit on macOS, gtk-webkit2 on Linux and Edge on Windows 10

### Crystal
* [Crystal Webview](https://github.com/naqvis/webview): Crystal language bindings for [webview](https://github.com/webview/webview), a tiny cross-platform webview library which uses Cocoa/WebKit on macOS, gtk-webkit2 on Linux and Edge on Windows 10)

### Dart
* [flutter](https://flutter.dev): Flutter is an open source framework by Google for building beautiful, natively compiled, multi-platform applications from a single codebase.

### Go
* [lorca](https://github.com/zserge/lorca): Build cross-platform modern desktop apps in Go + HTML5
* [wails](https://github.com/wailsapp/wails): Create beautiful applications using Go
* [muon](https://github.com/ImVexed/muon): Lightweight alternative to Electron written in Golang in about ~300 LoC, using Ultralight instead of Chromium.

### Guile
* [guile-pstk](https://github.com/KikyTokamuro/guile-pstk): [PS/TK version](http://mirror.informatimago.com/scheme/www.t3x.org/pstk/index.html) fixed to work fine on modern GNU Guile
* [guile-webview](https://github.com/KikyTokamuro/guile-webview): Wrapper for using libwebview from GNU Guile

### Java
* [Swing](https://en.wikipedia.org/wiki/Swing_(Java)): Swing is a GUI widget toolkit for Java.[1] It is part of Oracle's Java Foundation Classes (JFC) – an API for providing a graphical user interface (GUI) for Java programs.
* [OpenJFX or JavaFX](https://openjfx.io/): JavaFX is an open source, next generation client application platform for desktop, mobile and embedded systems built on Java. It is a collaborative effort by many individuals and companies with the goal of producing a modern, efficient, and fully featured toolkit for developing rich client applications.

### JS
* [NW.js](https://nwjs.io): Similar to electron, [provides Source code protection](https://nwjs.io/blog/js-src-protect-perf/))
* [DeskGap](https://deskgap.com): bundles a Node.js runtime and leaves the HTML rendering to the operating system‘s webview)
* [Neutralinojs](https://neutralino.js.org): chromium module is replaced with either user’s web browser or built-in browser component. Node run-time is replaced with a lightweight web server which exposes native OS functionality)
* [Proton Native](https://proton-native.js.org): does the same to desktop that React Native did to mobile, based on [libui-node](https://github.com/parro-it/libui-node)
* [React Native Desktop](https://github.com/status-im/react-native-desktop) Cross-platform React Native Desktop port based on Qt framework
* [Vuido](https://github.com/mimecorg/vuido): Creating native desktop applications based on Vue.js, based on [libui-node](https://github.com/parro-it/libui-node)
* [NodeGui](https://github.com/nodegui/nodegui): Powered by Qt5, [NodeGui-React](https://github.com/nodegui/react-nodegui), [Vue NodeGui](https://github.com/nodegui/vue-nodegui), [Svelte-NodeGui](https://github.com/nodegui/svelte-nodegui)
* [quasar](https://quasar.dev): Vue.js based framework, which lets web developer to quickly create responsive websites/apps
* [nidium](https://www.nidium.com): A powerful rendering engine for modern mobile applications. Unlike many solution, nidium doesn't rely on webviews or native OS widgets. Instead, it uses its own high-performance rendering engine to draw custom widgets.
* [electrino](https://github.com/pojala/electrino): Desktop runtime for apps built on web technologies, using the system's own web browser engine
* [graffiti](https://github.com/cztomsik/graffiti): HTML/CSS engine for node.js and deno.
* [Tauri](https://github.com/tauri-apps/tauri)
* [Sciter.JS](https://github.com/c-smile/sciter-js-sdk): Is a 5MB HTML/CSS/JS (ES6) runtime aimed as a direct Electron replacement
* [Avernakis](https://github.com/qber-soft/Ave-Nodejs) Nodejs addon for Avernakis SDK, use TypeScript to develop modern desktop app with powerful UI kits.
* [Gluon](https://github.com/gluon-framework/gluon) Uses normal system installed browsers (not webviews) and NodeJS, also supports Firefox

### Kotlin
* [Compose Multiplatform](https://www.jetbrains.com/lp/compose-mpp)

### Perl
* [Gtk](https://metacpan.org/pod/Gtk3)
* [Prima](https://metacpan.org/pod/Prima)
* [Tk](https://metacpan.org/dist/Tk)
* [Tkx](https://metacpan.org/pod/Tkx)
* [Wx](https://metacpan.org/pod/Wx)

### Python
* [fbs](https://build-system.fman.io): Python and Qt are great for writing lightweight desktop apps. But packaging, installers, code signing and automatic updates are a pain. fbs solves these problems and saves you months of development.
* [PyQt](https://en.wikipedia.org/wiki/PyQt)
* [Kivy](https://kivy.org/#home)
* [PyGUI](http://www.cosc.canterbury.ac.nz/greg.ewing/python_gui)
* [wxPython](https://wxpython.org/)
* [Tkinter](https://docs.python.org/2/library/tkinter.html)
* [pywebview](https://github.com/r0x0r/pywebview)

### Ruby
* [Glimmer](https://github.com/AndyObtiva/glimmer): A Domain-Specific Language & metaframework for building GUI apps using Ruby, with bindings for various GUI libraries and also Web
* [qtbindings](https://github.com/ryanmelt/qtbindings): Ruby bindings for Qt
* [tk](https://github.com/ruby/tk): Ruby bindings for Tcl/Tk
* [ruby-gnome](https://github.com/ruby-gnome/ruby-gnome): Ruby bindings from GNOME/GTK3
* [JRubyFX](https://github.com/jruby/jrubyfx): JRuby wrapper on JavaFX
* [traveling-ruby](https://github.com/phusion/traveling-ruby): Runtime to bundle Ruby applications into executables

### Rust
* [gtk-rs](https://github.com/gtk-rs): Rust bindings for GTK
* [tauri](https://github.com/tauri-apps/tauri)

### Others
* [tiny](https://github.com/Rafi993/tiny): This is a tiny alternative to electron
* [Livecode](https://livecode.com): Lightweight language with [native GUI], integrated IDE, and visual interface builder
* [Qt](https://www.qt.io)
* [jscherer92/Quark](https://github.com/jscherer92/Quark): Create Applications with browser technologies using the native engine in your OS.
* [Xojo](https://www.xojo.com)
* [LambdaNative](http://www.lambdanative.org)
* [REVERY](https://www.outrunlabs.com/revery)
* [8th](https://8th-dev.com/index.html)
* [CEF](https://bitbucket.org/%7Bdc443723-7652-4c63-b340-033e522146db%7D/)
* [yue/yue](https://github.com/yue/yue): A library for creating native cross-platform GUI apps
* [Godot](https://godotengine.org/): Godot Engine – Multi-platform 2D and 3D game engine
* [Red](https://www.red-lang.org/p/about.html): Full-stack lightweight language with [native GUI](https://github.com/red/docs/blob/master/en/view.adoc), [layout](https://github.com/red/docs/blob/master/en/vid.adoc) and [drawing](https://github.com/red/docs/blob/master/en/draw.adoc) DSLs
* [HaxeUI](http://haxeui.org/) [Haxe](https://haxe.org) based cross platform (desktop, mobile, web) UI framework

# Notes
See this: [Blazor](https://visualstudiomagazine.com/articles/2019/09/26/blazor-future.aspx), [ElectronCGI](https://www.npmjs.com/package/electron-cgi)

Consider **Progressive Web Apps** [PWA](https://developers.google.com/web/progressive-web-apps/desktop), if your app doesn't require any platform interactions. 

> "Progressive Web Apps might not be able to replace every kind of native application, but they can be viable replacements for some apps written with the Electron web wrapper technology". For more info:
https://www.androidpolice.com/2020/05/27/google-chats-desktop-application-is-now-a-progressive-web-app/

## Contributions
electron-alternatives is open to contributions, but I recommend creating an issue or replying in a comment to let me know what you are working on first that way we don't overwrite each other.

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on this project. If you have any questions, feel free to open an issue. And feel free to improve this list by contributing! 


## License
* Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.
* Electron-alternatives is licensed with MIT by sudhakar3697 and contributors

## Contributors
<a href="https://github.com/sudhakar3697/electron-alternatives/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=sudhakar3697/electron-alternatives"/>
</a>
