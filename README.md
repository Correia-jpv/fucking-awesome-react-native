<br/>

<p align="center">
    <img alt="awesome react native" src="arn.svg" width="480" />
</p>

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img src="https://awesome.re/badge.svg" alt="Awesome" /></a>
</p>

Awesome React Native is a curated list of the best libraries, tools, and learning resources for building React Native apps today. Every entry is checked for maintenance and relevance — if it's here, it works with modern React Native. PRs are welcome, see [contributing](CONTRIBUTING.md).

## Contents

- [Getting Started](#getting-started)
- [AI-Assisted Development](#ai-assisted-development)
  - [Agents & Skills](#agents--skills)
  - [MCP Servers](#mcp-servers)
  - [On-Device AI](#on-device-ai)
  - [AI App Builders](#ai-app-builders)
- [Components](#components)
  - [UI](#ui)
  - [Lists](#lists)
  - [Navigation](#navigation)
  - [Sheets, Menus & Toasts](#sheets-menus--toasts)
  - [Forms & Keyboard](#forms--keyboard)
  - [Text & Rich Content](#text--rich-content)
  - [Image & Camera](#image--camera)
  - [Video & Audio](#video--audio)
  - [Maps & Location](#maps--location)
  - [Charts](#charts)
  - [Animation & Gestures](#animation--gestures)
  - [Styling & Design Systems](#styling--design-systems)
  - [Internationalization](#internationalization)
  - [System & Device](#system--device)
  - [Notifications](#notifications)
  - [Web & WebViews](#web--webviews)
  - [Other Platforms](#other-platforms)
- [Data](#data)
  - [State Management](#state-management)
  - [Storage & Databases](#storage--databases)
  - [Networking](#networking)
- [Services & Integrations](#services--integrations)
- [Payments & Monetization](#payments--monetization)
- [Development Tools](#development-tools)
  - [Tooling & IDE](#tooling--ide)
  - [Debugging](#debugging)
  - [Testing](#testing)
  - [Builds, Deployment & OTA Updates](#builds-deployment--ota-updates)
  - [Building Libraries](#building-libraries)
- [Starters & Boilerplates](#starters--boilerplates)
- [Open Source Apps](#open-source-apps)
- [Learning](#learning)
- [Staying Up to Date](#staying-up-to-date)

## Getting Started

- 🌎 [React Native](reactnative.dev) - Official documentation, including environment setup, guides, and API reference.
- 🌎 [Expo](expo.dev) - The recommended framework for building React Native apps: file-based routing, native modules, builds, and updates out of the box.
- 🌎 [React Native Directory](reactnative.directory) - Searchable, filterable directory of React Native libraries with maintenance and New Architecture compatibility signals.
- <b><code>&nbsp;&nbsp;4066⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Upgrade Helper](https://github.com/react-native-community/upgrade-helper)) - Web tool that shows the exact diff between two React Native versions for painless upgrades.
- <b><code>&nbsp;&nbsp;1316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge)) - The raw version-to-version diffs powering Upgrade Helper.
- <b><code>&nbsp;&nbsp;3721⭐</code></b> <b><code>&nbsp;&nbsp;1098🍴</code></b> [Expo Examples](https://github.com/expo/examples)) - Example projects demonstrating Expo APIs and integrations.

## AI-Assisted Development

Tools for building React Native apps with AI agents, and for putting AI inside your apps.

### Agents & Skills

- 🌎 [Expo AI Agents Guide](docs.expo.dev/agents/) - Expo's official documentation for AI-native development: agent setup, llms.txt, and best practices.
- 🌎 [Claude Code + Expo](docs.expo.dev/agents/claude/) - Official guide for building, debugging, and deploying Expo apps with Claude Code.
- <b><code>&nbsp;&nbsp;2496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Expo Skills](https://github.com/expo/skills)) - Agent skills that give coding agents Expo-specific knowledge and best practices.
- <b><code>173676⭐</code></b> <b><code>&nbsp;20607🍴</code></b> [Agent Skills](https://github.com/anthropics/skills)) - Anthropic's public repository of agent skills, usable with Claude Code and other agents.

### MCP Servers

- 🌎 [Expo MCP](docs.expo.dev/mcp/) - Expo-hosted MCP server: EAS logs, documentation search, and deployment workflows from any MCP-capable agent.
- <b><code>&nbsp;&nbsp;6328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [mobile-mcp](https://github.com/mobile-next/mobile-mcp)) - MCP server for mobile automation on iOS, Android, emulators, simulators, and real devices.
- <b><code>&nbsp;&nbsp;2160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp)) - MCP server for driving the iOS simulator: interact with UI, take screenshots, inspect the view hierarchy.
- 🌎 [Maestro](maestro.dev) - E2E testing framework with a built-in MCP server, letting agents run flows and control devices.

### On-Device AI

- <b><code>&nbsp;&nbsp;1710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [react-native-executorch](https://github.com/software-mansion/react-native-executorch)) - Declarative on-device AI inference powered by ExecuTorch, from Software Mansion.
- <b><code>&nbsp;&nbsp;1033⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [llama.rn](https://github.com/mybigday/llama.rn)) - React Native binding of llama.cpp for running LLMs on device.
- <b><code>&nbsp;&nbsp;1233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [react-native-fast-tflite](https://github.com/mrousavy/react-native-fast-tflite)) - High-performance TensorFlow Lite inference with GPU acceleration.
- <b><code>&nbsp;26568⭐</code></b> <b><code>&nbsp;&nbsp;5072🍴</code></b> [AI SDK](https://github.com/vercel/ai)) - The AI toolkit for TypeScript; works in Expo and React Native apps for chat, streaming, and tool use.

### AI App Builders

- 🌎 [a0.dev](a0.dev) - Generates complete React Native apps from a prompt and ships them to the app stores.
- 🌎 [Rork](rork.com) - AI app builder that generates Expo/React Native projects compiling to native iOS, Android, and web.

## Components

### UI

- <b><code>&nbsp;14454⭐</code></b> <b><code>&nbsp;&nbsp;2241🍴</code></b> [react-native-paper](https://github.com/callstack/react-native-paper)) - Material Design components for Android and iOS.
- <b><code>&nbsp;25859⭐</code></b> <b><code>&nbsp;&nbsp;4674🍴</code></b> [React Native Elements](https://github.com/react-native-elements/react-native-elements)) - Cross-platform UI toolkit with themed, composable components.
- <b><code>&nbsp;14175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;613🍴</code></b> [Tamagui](https://github.com/tamagui/tamagui)) - Universal UI kit and style system with an optimizing compiler, 100% parity between React Native and web.
- <b><code>&nbsp;&nbsp;5283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [gluestack-ui](https://github.com/gluestack/gluestack-ui)) - Copy-paste components and patterns built on Tailwind-style utility classes.
- <b><code>&nbsp;10670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;963🍴</code></b> [react-native-ui-kitten](https://github.com/akveo/react-native-ui-kitten)) - UI library based on the Eva Design System with theming support.
- <b><code>&nbsp;20380⭐</code></b> <b><code>&nbsp;&nbsp;2390🍴</code></b> [NativeBase](https://github.com/GeekyAnts/NativeBase)) - Mobile-first, accessible component library for React Native and web.
- <b><code>&nbsp;&nbsp;4979⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Shoutem UI](https://github.com/shoutem/ui)) - Customizable set of styled components for React Native.
- <b><code>&nbsp;17915⭐</code></b> <b><code>&nbsp;&nbsp;2105🍴</code></b> [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)) - Customizable icon sets with support for styling and image sources.
- <b><code>&nbsp;17210⭐</code></b> <b><code>&nbsp;&nbsp;1800🍴</code></b> [lottie-react-native](https://github.com/lottie-react-native/lottie-react-native)) - Render After Effects animations natively.
- <b><code>&nbsp;&nbsp;8002⭐</code></b> <b><code>&nbsp;&nbsp;1200🍴</code></b> [react-native-svg](https://github.com/software-mansion/react-native-svg)) - SVG rendering for React Native and web.
- <b><code>&nbsp;&nbsp;1736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [react-native-svg-transformer](https://github.com/kristerkari/react-native-svg-transformer)) - Import SVG files as components, like on the web.
- <b><code>&nbsp;&nbsp;5654⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;657🍴</code></b> [react-native-modal](https://github.com/react-native-modal/react-native-modal)) - Enhanced, animated, customizable modal.
- <b><code>&nbsp;&nbsp;3882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;563🍴</code></b> [react-native-blur](https://github.com/margelo/react-native-blur)) - Native blur view component.
- <b><code>&nbsp;&nbsp;2239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [react-native-blurhash](https://github.com/mrousavy/react-native-blurhash)) - Colorful blurry placeholders while content loads.
- <b><code>&nbsp;10310⭐</code></b> <b><code>&nbsp;&nbsp;3064🍴</code></b> [react-native-calendars](https://github.com/wix/react-native-calendars)) - Feature-rich calendar components.
- <b><code>&nbsp;&nbsp;2506⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [react-native-date-picker](https://github.com/henninghall/react-native-date-picker)) - Native date and time picker for Android and iOS.
- <b><code>&nbsp;&nbsp;3431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;352🍴</code></b> [react-native-reanimated-carousel](https://github.com/dohooo/react-native-reanimated-carousel)) - Swiper/carousel built entirely on Reanimated, the successor to snap-carousel.
- <b><code>&nbsp;&nbsp;3356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;475🍴</code></b> [react-native-pager-view](https://github.com/callstack/react-native-pager-view)) - Native ViewPager and UIPageViewController wrapper.
- <b><code>&nbsp;&nbsp;2437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;429🍴</code></b> [react-native-copilot](https://github.com/mohebifar/react-native-copilot)) - Step-by-step walkthrough tooltips for onboarding.
- <b><code>&nbsp;&nbsp;1482⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [react-native-super-grid](https://github.com/saleel/react-native-super-grid)) - Responsive grid view.
- <b><code>&nbsp;&nbsp;2249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [react-native-circular-progress](https://github.com/bartgryszko/react-native-circular-progress)) - Animated circular progress indicators.
- <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [react-native-progress-steps](https://github.com/colbymillerdev/react-native-progress-steps)) - Customizable progress stepper.
- <b><code>&nbsp;&nbsp;1229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [react-native-confirmation-code-field](https://github.com/retyui/react-native-confirmation-code-field)) - OTP/confirmation code input for iOS, Android, and web.
- <b><code>&nbsp;&nbsp;1173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [react-native-qrcode-svg](https://github.com/Expensify/react-native-qrcode-svg)) - QR code generator based on react-native-svg.
- <b><code>&nbsp;&nbsp;1112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;833🍴</code></b> [react-native-country-picker-modal](https://github.com/xcarpentier/react-native-country-picker-modal)) - Country picker with flags, search, and localization.
- <b><code>&nbsp;&nbsp;&nbsp;446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [react-native-hole-view](https://github.com/ibitcy/react-native-hole-view)) - Cut touch-through holes anywhere, perfect for onboarding highlights.

### Lists

- <b><code>&nbsp;&nbsp;7195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;390🍴</code></b> [FlashList](https://github.com/Shopify/flash-list)) - Shopify's fast and performant list, a drop-in replacement for FlatList.
- <b><code>&nbsp;&nbsp;3340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Legend List](https://github.com/LegendApp/legend-list)) - High-performance list in pure JS, built for the New Architecture.
- <b><code>&nbsp;&nbsp;5433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;438🍴</code></b> [recyclerlistview](https://github.com/Flipkart/recyclerlistview)) - The recycling listview that pioneered high-performance lists in React Native.

### Navigation

- <b><code>&nbsp;24505⭐</code></b> <b><code>&nbsp;&nbsp;5131🍴</code></b> [React Navigation](https://github.com/react-navigation/react-navigation)) - The standard routing and navigation library for React Native.
- 🌎 [Expo Router](docs.expo.dev/router/introduction/) - File-based routing for universal React Native apps, built on React Navigation.
- <b><code>&nbsp;13176⭐</code></b> <b><code>&nbsp;&nbsp;2629🍴</code></b> [react-native-navigation](https://github.com/wix/react-native-navigation)) - Wix's fully native navigation solution.
- <b><code>&nbsp;&nbsp;3726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;701🍴</code></b> [react-native-screens](https://github.com/software-mansion/react-native-screens)) - Native navigation primitives that back React Navigation's native stack.
- <b><code>&nbsp;&nbsp;1449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [react-native-bottom-tabs](https://github.com/callstack/react-native-bottom-tabs)) - Truly native bottom tab bars (SwiftUI and Material) for React Native.

### Sheets, Menus & Toasts

- <b><code>&nbsp;&nbsp;9084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;963🍴</code></b> [react-native-bottom-sheet](https://github.com/gorhom/react-native-bottom-sheet)) - Performant, interactive bottom sheet with configurable gestures.
- <b><code>&nbsp;&nbsp;2050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [react-native-true-sheet](https://github.com/lodev09/react-native-true-sheet)) - The true native bottom sheet experience.
- <b><code>&nbsp;&nbsp;2177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [react-native-actions-sheet](https://github.com/ammarahm-ed/react-native-actions-sheet)) - Cross-platform ActionSheet with a flexible API.
- <b><code>&nbsp;&nbsp;2253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Zeego](https://github.com/nandorojo/zeego)) - Menus for React Native done right — truly native dropdown and context menus.
- <b><code>&nbsp;&nbsp;1562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Burnt](https://github.com/nandorojo/burnt)) - Native toasts and alerts for iOS and Android.
- <b><code>&nbsp;&nbsp;2136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;393🍴</code></b> [react-native-root-toast](https://github.com/magicismight/react-native-root-toast)) - Pure JavaScript toast solution.
- <b><code>&nbsp;&nbsp;1530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [react-native-flash-message](https://github.com/lucasferreira/react-native-flash-message)) - Flashbar and top-notification alerts.
- <b><code>&nbsp;&nbsp;1438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [react-native-notifier](https://github.com/seniv/react-native-notifier)) - Fast and simple in-app notifications.
- <b><code>&nbsp;&nbsp;1557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [react-native-popup-menu](https://github.com/instea/react-native-popup-menu)) - Extensible popup menu component.

### Forms & Keyboard

- <b><code>&nbsp;44847⭐</code></b> <b><code>&nbsp;&nbsp;2469🍴</code></b> [React Hook Form](https://github.com/react-hook-form/react-hook-form)) - Performant form state management and validation for React and React Native.
- <b><code>&nbsp;34328⭐</code></b> <b><code>&nbsp;&nbsp;2779🍴</code></b> [Formik](https://github.com/jaredpalmer/formik)) - Build forms without the tears.
- <b><code>&nbsp;&nbsp;3710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [react-native-keyboard-controller](https://github.com/kirillzyusko/react-native-keyboard-controller)) - Keyboard manager that works identically on iOS and Android.
- <b><code>&nbsp;&nbsp;1846⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;499🍴</code></b> [react-native-picker-select](https://github.com/lawnstarter/react-native-picker-select)) - Picker emulating the native select interface.
- <b><code>&nbsp;&nbsp;&nbsp;871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [react-native-autocomplete-input](https://github.com/byteburgers/react-native-autocomplete-input)) - Pure JavaScript autocomplete input.
- <b><code>&nbsp;&nbsp;1607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [react-native-masked-text](https://github.com/bhrott/react-native-masked-text)) - Masked text and input components.
- <b><code>&nbsp;&nbsp;1508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;708🍴</code></b> [react-native-credit-card-input](https://github.com/sbycrosz/react-native-credit-card-input)) - Cross-platform credit card input.
- <b><code>&nbsp;&nbsp;&nbsp;589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [react-native-multiple-select](https://github.com/toystars/react-native-multiple-select)) - Simple multi-select component.

### Text & Rich Content

- <b><code>&nbsp;&nbsp;1337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [react-native-live-markdown](https://github.com/Expensify/react-native-live-markdown)) - Drop-in TextInput replacement with live Markdown formatting, by Expensify.
- <b><code>&nbsp;&nbsp;&nbsp;792⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [react-native-markdown-display](https://github.com/iamacup/react-native-markdown-display)) - 100% CommonMark-compatible Markdown renderer.
- <b><code>&nbsp;&nbsp;&nbsp;812⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [react-native-hyperlink](https://github.com/obipawan/react-native-hyperlink)) - Make URLs, emails, and fuzzy links clickable.
- <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [react-native-html-to-pdf](https://github.com/christopherdro/react-native-html-to-pdf)) - Convert HTML strings to PDF documents.
- <b><code>&nbsp;&nbsp;&nbsp;740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [react-native-responsive-fontsize](https://github.com/heyman333/react-native-responsive-fontsize)) - Responsive font sizes based on device screen size.

### Image & Camera

- <b><code>&nbsp;&nbsp;9609⭐</code></b> <b><code>&nbsp;&nbsp;1388🍴</code></b> [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera)) - Powerful, high-performance camera library with frame processors.
- 🌎 [expo-image](docs.expo.dev/versions/latest/sdk/image/) - Fast, modern image component with caching and blurhash support.
- <b><code>&nbsp;&nbsp;8634⭐</code></b> <b><code>&nbsp;&nbsp;2078🍴</code></b> [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker)) - Native UI for selecting photos and videos.
- <b><code>&nbsp;&nbsp;6350⭐</code></b> <b><code>&nbsp;&nbsp;1608🍴</code></b> [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker)) - Image picker with camera, cropping, and compression.
- <b><code>&nbsp;&nbsp;2705⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;632🍴</code></b> [react-native-camera-kit](https://github.com/teslamotors/react-native-camera-kit)) - High-performance camera library with barcode scanning, by Tesla.
- <b><code>&nbsp;&nbsp;1661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;362🍴</code></b> [react-native-image-resizer](https://github.com/bamlab/react-native-image-resizer)) - Resize local images natively.

### Video & Audio

- <b><code>&nbsp;&nbsp;7716⭐</code></b> <b><code>&nbsp;&nbsp;3027🍴</code></b> [react-native-video](https://github.com/TheWidlarzGroup/react-native-video)) - The Video component for React Native.
- 🌎 [expo-video](docs.expo.dev/versions/latest/sdk/video/) - Modern video playback built for Expo and the New Architecture.
- <b><code>&nbsp;&nbsp;3707⭐</code></b> <b><code>&nbsp;&nbsp;1198🍴</code></b> [react-native-track-player](https://github.com/doublesymmetry/react-native-track-player)) - Full-featured audio player: background playback, Android Auto, CarPlay, lock-screen controls.
- <b><code>&nbsp;&nbsp;&nbsp;836⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [react-native-audio-api](https://github.com/software-mansion/react-native-audio-api)) - High-performance audio engine implementing the Web Audio API.
- <b><code>&nbsp;&nbsp;2918⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;783🍴</code></b> [react-native-sound](https://github.com/zmxv/react-native-sound)) - Play sound clips natively.
- <b><code>&nbsp;&nbsp;4992⭐</code></b> <b><code>&nbsp;&nbsp;1328🍴</code></b> [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc)) - WebRTC for React Native.

### Maps & Location

- <b><code>&nbsp;15994⭐</code></b> <b><code>&nbsp;&nbsp;4959🍴</code></b> [react-native-maps](https://github.com/react-native-maps/react-native-maps)) - MapView components for iOS and Android.
- <b><code>&nbsp;&nbsp;2909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;946🍴</code></b> [rnmapbox/maps](https://github.com/rnmapbox/maps)) - Mapbox maps for custom map experiences.
- <b><code>&nbsp;&nbsp;2921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [react-native-background-geolocation](https://github.com/transistorsoft/react-native-background-geolocation)) - Battery-conscious background location with motion detection.
- <b><code>&nbsp;&nbsp;&nbsp;821⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [react-native-map-link](https://github.com/tschoffelen/react-native-map-link)) - Open the user's preferred maps app.
- <b><code>&nbsp;&nbsp;2071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;872🍴</code></b> [react-native-google-places-autocomplete](https://github.com/FaridSafi/react-native-google-places-autocomplete)) - Customizable Google Places autocomplete.

### Charts

- <b><code>&nbsp;&nbsp;1219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [victory-native-xl](https://github.com/FormidableLabs/victory-native-xl)) - Charting built on Skia and Reanimated with a focus on performance.
- <b><code>&nbsp;&nbsp;2613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [react-native-graph](https://github.com/margelo/react-native-graph)) - Beautiful, high-performance line graphs built with Skia.
- <b><code>&nbsp;&nbsp;1363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [react-native-gifted-charts](https://github.com/Abhinandan-Kushwaha/react-native-gifted-charts)) - Bar, line, area, pie, donut, and stacked charts.

### Animation & Gestures

- <b><code>&nbsp;10975⭐</code></b> <b><code>&nbsp;&nbsp;1506🍴</code></b> [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated)) - The standard for performant animations, running on the UI thread.
- <b><code>&nbsp;&nbsp;6783⭐</code></b> <b><code>&nbsp;&nbsp;1068🍴</code></b> [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler)) - Declarative, native-driven gesture system.
- <b><code>&nbsp;&nbsp;8540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;639🍴</code></b> [react-native-skia](https://github.com/Shopify/react-native-skia)) - High-performance 2D graphics with the Skia rendering engine.
- <b><code>&nbsp;&nbsp;4549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Moti](https://github.com/nandorojo/moti)) - Universal animation library powered by Reanimated, with a Framer Motion-like API.
- <b><code>&nbsp;&nbsp;9934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;694🍴</code></b> [react-native-animatable](https://github.com/oblador/react-native-animatable)) - Declarative transitions and standard animations.
- <b><code>&nbsp;&nbsp;3162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [TypeGPU](https://github.com/software-mansion/TypeGPU)) - Type-safe WebGPU toolkit for advanced GPU work.

### Styling & Design Systems

- <b><code>&nbsp;&nbsp;8078⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;402🍴</code></b> [NativeWind](https://github.com/nativewind/nativewind)) - Tailwind CSS for React Native.
- <b><code>&nbsp;&nbsp;2939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Unistyles](https://github.com/jpudysz/react-native-unistyles)) - C++-powered StyleSheet superset with themes and breakpoints, built for the New Architecture.
- <b><code>&nbsp;41124⭐</code></b> <b><code>&nbsp;&nbsp;2688🍴</code></b> [styled-components](https://github.com/styled-components/styled-components)) - CSS-in-JS styling that also targets React Native.
- <b><code>&nbsp;18021⭐</code></b> <b><code>&nbsp;&nbsp;1141🍴</code></b> [Emotion](https://github.com/emotion-js/emotion)) - High-performance CSS-in-JS style composition.
- <b><code>&nbsp;&nbsp;3558⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [react-native-typography](https://github.com/hectahertz/react-native-typography)) - Pixel-perfect, native-looking typographic styles.
- <b><code>&nbsp;&nbsp;1028⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Stacks](https://github.com/grapp-dev/stacks)) - Layout primitives for building consistent UIs.
- <b><code>&nbsp;&nbsp;1036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [react-native-edge-to-edge](https://github.com/zoontek/react-native-edge-to-edge)) - Effortless edge-to-edge display on Android.
- <b><code>&nbsp;&nbsp;2756⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [react-native-safe-area-context](https://github.com/AppAndFlow/react-native-safe-area-context)) - Flexible safe area inset handling.

### Internationalization

- <b><code>&nbsp;&nbsp;2442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [react-native-localize](https://github.com/zoontek/react-native-localize)) - Toolbox for app localization: locales, timezones, currencies.

### System & Device

- <b><code>&nbsp;&nbsp;6680⭐</code></b> <b><code>&nbsp;&nbsp;1460🍴</code></b> [react-native-device-info](https://github.com/react-native-device-info/react-native-device-info)) - Device information for iOS and Android.
- <b><code>&nbsp;&nbsp;4379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;846🍴</code></b> [react-native-permissions](https://github.com/zoontek/react-native-permissions)) - Unified permissions API.
- <b><code>&nbsp;&nbsp;3475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;540🍴</code></b> [react-native-keychain](https://github.com/oblador/react-native-keychain)) - Secure keychain and keystore access.
- <b><code>&nbsp;&nbsp;4956⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;658🍴</code></b> [react-native-config](https://github.com/react-native-config/react-native-config)) - Expose environment config to your JS and native code.
- <b><code>&nbsp;&nbsp;1704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;593🍴</code></b> [react-native-contacts](https://github.com/morenoh149/react-native-contacts)) - Native contacts access.
- <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [react-native-calendar-events](https://github.com/wmcmahan/react-native-calendar-events)) - Calendar event access for iOS and Android.
- <b><code>&nbsp;&nbsp;3894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;976🍴</code></b> [react-native-share](https://github.com/react-native-share/react-native-share)) - Native share sheet and social sharing.
- <b><code>&nbsp;&nbsp;&nbsp;978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [react-native-haptic-feedback](https://github.com/mkuczera/react-native-haptic-feedback)) - Haptics that feel right, including Core Haptics patterns.
- <b><code>&nbsp;&nbsp;&nbsp;934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [react-native-sensors](https://github.com/react-native-sensors/react-native-sensors)) - Developer-friendly access to device sensors.
- <b><code>&nbsp;&nbsp;1609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [react-native-background-fetch](https://github.com/transistorsoft/react-native-background-fetch)) - Periodic background callbacks on iOS and Android.
- <b><code>&nbsp;&nbsp;&nbsp;215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [react-native-background-downloader](https://github.com/kesha-antonov/react-native-background-downloader)) - Download and upload large files, even when the app is backgrounded.
- <b><code>&nbsp;&nbsp;1516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;465🍴</code></b> [document-picker](https://github.com/react-native-documents/document-picker)) - Document picker and viewer.
- <b><code>&nbsp;&nbsp;&nbsp;656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [expo-quick-actions](https://github.com/EvanBacon/expo-quick-actions)) - Home screen quick actions and custom app icons.
- <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [react-native-ssl-pinning](https://github.com/MaxToyberman/react-native-ssl-pinning)) - SSL pinning and cookie handling.

### Notifications

- 🌎 [Expo Notifications](docs.expo.dev/versions/latest/sdk/notifications/) - Push and local notifications for Expo apps.
- <b><code>&nbsp;12301⭐</code></b> <b><code>&nbsp;&nbsp;2330🍴</code></b> [react-native-firebase](https://github.com/invertase/react-native-firebase)) - Includes FCM messaging alongside the full Firebase suite.
- <b><code>&nbsp;&nbsp;3341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;757🍴</code></b> [react-native-notifications](https://github.com/wix/react-native-notifications)) - Wix's notification handling library.
- <b><code>&nbsp;&nbsp;1592⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [react-native-onesignal](https://github.com/OneSignal/react-native-onesignal)) - OneSignal push notification SDK.

### Web & WebViews

- <b><code>&nbsp;&nbsp;7191⭐</code></b> <b><code>&nbsp;&nbsp;3176🍴</code></b> [react-native-webview](https://github.com/react-native-webview/react-native-webview)) - The community WebView component.
- <b><code>&nbsp;&nbsp;1416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [react-native-inappbrowser](https://github.com/proyecto26/react-native-inappbrowser)) - In-app browser using Chrome Custom Tabs and SFSafariViewController.
- <b><code>&nbsp;22141⭐</code></b> <b><code>&nbsp;&nbsp;1822🍴</code></b> [react-native-web](https://github.com/necolas/react-native-web)) - Run React Native components and APIs on the web.
- <b><code>&nbsp;&nbsp;4091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Solito](https://github.com/nandorojo/solito)) - React Native + Next.js, unified navigation for universal apps.

### Other Platforms

- <b><code>&nbsp;17339⭐</code></b> <b><code>&nbsp;&nbsp;1202🍴</code></b> [react-native-windows](https://github.com/microsoft/react-native-windows)) - Build native Windows apps with React.
- <b><code>&nbsp;&nbsp;4384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [react-native-macos](https://github.com/microsoft/react-native-macos)) - Build native macOS apps with React.

## Data

### State Management

- <b><code>&nbsp;58640⭐</code></b> <b><code>&nbsp;&nbsp;2188🍴</code></b> [Zustand](https://github.com/pmndrs/zustand)) - Bear necessities for state management.
- <b><code>&nbsp;21250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;726🍴</code></b> [Jotai](https://github.com/pmndrs/jotai)) - Primitive and flexible atomic state.
- <b><code>&nbsp;11223⭐</code></b> <b><code>&nbsp;&nbsp;1293🍴</code></b> [Redux Toolkit](https://github.com/reduxjs/redux-toolkit)) - The official, batteries-included Redux toolset.
- <b><code>&nbsp;&nbsp;4193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [Legend State](https://github.com/LegendApp/legend-state)) - Super fast state with fine-grained reactivity and built-in sync.

### Storage & Databases

- <b><code>&nbsp;&nbsp;8493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;339🍴</code></b> [react-native-mmkv](https://github.com/mrousavy/react-native-mmkv)) - The fastest key/value storage for React Native, ~30x faster than AsyncStorage.
- <b><code>&nbsp;&nbsp;5071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;482🍴</code></b> [AsyncStorage](https://github.com/react-native-async-storage/async-storage)) - Simple, asynchronous, persistent key-value storage.
- <b><code>&nbsp;&nbsp;1032⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [op-sqlite](https://github.com/OP-Engineering/op-sqlite)) - The fastest SQLite library for React Native.
- 🌎 [expo-sqlite](docs.expo.dev/versions/latest/sdk/sqlite/) - SQLite database access in Expo, with support for Drizzle ORM.
- <b><code>&nbsp;35674⭐</code></b> <b><code>&nbsp;&nbsp;1578🍴</code></b> [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)) - TypeScript ORM with first-class Expo/React Native SQLite support.
- <b><code>&nbsp;11780⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;656🍴</code></b> [WatermelonDB](https://github.com/Nozbe/WatermelonDB)) - Reactive and asynchronous database for powerful apps that scale.
- <b><code>&nbsp;23372⭐</code></b> <b><code>&nbsp;&nbsp;1174🍴</code></b> [RxDB](https://github.com/pubkey/rxdb)) - Local-first, reactive database that replicates with your backend.
- <b><code>&nbsp;&nbsp;6004⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [Realm](https://github.com/realm/realm-js)) - Mobile object database, an alternative to SQLite.

### Networking

- <b><code>&nbsp;50259⭐</code></b> <b><code>&nbsp;&nbsp;4228🍴</code></b> [TanStack Query](https://github.com/TanStack/query)) - Powerful async state management and data fetching.
- <b><code>&nbsp;&nbsp;2886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [apisauce](https://github.com/infinitered/apisauce)) - Axios with standardized errors and request/response transforms.
- <b><code>&nbsp;&nbsp;2180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [react-native-netinfo](https://github.com/react-native-netinfo/react-native-netinfo)) - Network state and connectivity info.
- <b><code>&nbsp;&nbsp;&nbsp;687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [react-native-network-logger](https://github.com/alexbrazier/react-native-network-logger)) - In-app HTTP request monitor.
- <b><code>&nbsp;&nbsp;1067⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [react-native-quick-crypto](https://github.com/margelo/react-native-quick-crypto)) - Fast native implementation of Node's crypto module.

## Services & Integrations

- <b><code>&nbsp;12301⭐</code></b> <b><code>&nbsp;&nbsp;2330🍴</code></b> [react-native-firebase](https://github.com/invertase/react-native-firebase)) - Well-tested, feature-rich modular Firebase implementation.
- <b><code>&nbsp;&nbsp;1820⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;366🍴</code></b> [sentry-react-native](https://github.com/getsentry/sentry-react-native)) - Official Sentry SDK for crash reporting and performance monitoring.
- <b><code>&nbsp;&nbsp;2256⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;474🍴</code></b> [react-native-app-auth](https://github.com/FormidableLabs/react-native-app-auth)) - PKCE-compliant OAuth2 client based on AppAuth.
- <b><code>&nbsp;&nbsp;3553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;893🍴</code></b> [google-signin](https://github.com/react-native-google-signin/google-signin)) - Google Sign-In for React Native.

## Payments & Monetization

- <b><code>&nbsp;&nbsp;1429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;325🍴</code></b> [stripe-react-native](https://github.com/stripe/stripe-react-native)) - Official Stripe SDK for payments in React Native.
- <b><code>&nbsp;&nbsp;1204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [react-native-purchases](https://github.com/RevenueCat/react-native-purchases)) - RevenueCat SDK for in-app purchases and subscriptions.

## Development Tools

### Tooling & IDE

- <b><code>&nbsp;&nbsp;1717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Radon IDE](https://github.com/software-mansion/radon-ide)) - VSCode/Cursor extension that turns your editor into a full-featured React Native IDE with an embedded simulator.
- <b><code>&nbsp;&nbsp;1350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [EAS CLI](https://github.com/expo/eas-cli)) - Build, submit, and update iOS and Android apps from the command line.
- <b><code>&nbsp;&nbsp;2777⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [react-native-rename](https://github.com/junedomingo/react-native-rename)) - Rename a React Native app with one command.
- <b><code>&nbsp;&nbsp;1630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [react-native-bundle-visualizer](https://github.com/callstack/react-native-bundle-visualizer)) - See which packages inflate your bundle size.
- <b><code>&nbsp;&nbsp;1933⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [Re.Pack](https://github.com/callstack/repack)) - Webpack/Rspack-based toolkit with code splitting and Module Federation for React Native.

### Debugging

- <b><code>&nbsp;15589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;975🍴</code></b> [Reactotron](https://github.com/infinitered/reactotron)) - Desktop app for inspecting React Native apps: state, API requests, performance.
- <b><code>&nbsp;&nbsp;&nbsp;691⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Buoy](https://github.com/Buoy-gg/buoy)) - Devtools that live in your app — and answer to your AI agent.

### Testing

- <b><code>&nbsp;15501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;940🍴</code></b> [Maestro](https://github.com/mobile-dev-inc/Maestro)) - Painless declarative E2E automation for mobile.
- <b><code>&nbsp;12022⭐</code></b> <b><code>&nbsp;&nbsp;1913🍴</code></b> [Detox](https://github.com/wix/Detox)) - Gray-box end-to-end testing and automation framework.
- <b><code>&nbsp;&nbsp;3417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [React Native Testing Library](https://github.com/callstack/react-native-testing-library)) - Testing utilities that encourage good practices.
- <b><code>&nbsp;&nbsp;1909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;182🍴</code></b> [Loki](https://github.com/oblador/loki)) - Visual regression testing for Storybook.

### Builds, Deployment & OTA Updates

- 🌎 [EAS](expo.dev/eas) - Expo Application Services: cloud builds, app store submission, and OTA updates.
- <b><code>&nbsp;&nbsp;1695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [hot-updater](https://github.com/gronxb/hot-updater)) - Self-hostable OTA update solution, a CodePush alternative.
- 🌎 [Fastlane](fastlane.tools) - Automate building, screenshots, and releasing for iOS and Android.

### Building Libraries

- <b><code>&nbsp;&nbsp;3226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [create-react-native-library](https://github.com/callstack/react-native-builder-bob)) - Scaffold and build React Native libraries for distribution.
- <b><code>&nbsp;&nbsp;1925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Nitro Modules](https://github.com/mrousavy/nitro)) - Insanely fast native C++, Swift, or Kotlin modules with statically compiled bindings.

## Starters & Boilerplates

- <b><code>&nbsp;19939⭐</code></b> <b><code>&nbsp;&nbsp;1538🍴</code></b> [Ignite](https://github.com/infinitered/ignite)) - Infinite Red's battle-tested boilerplate with CLI and generators.
- <b><code>&nbsp;&nbsp;5563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;939🍴</code></b> [react-native-boilerplate](https://github.com/thecodingmachine/react-native-boilerplate)) - TheCodingMachine's template for solid, scalable applications.
- 🌎 [Expo Templates](docs.expo.dev/more/create-expo/) - Official Expo templates, from blank to tabs to full navigation setups.

## Open Source Apps

Production apps you can learn from.

- <b><code>&nbsp;18263⭐</code></b> <b><code>&nbsp;&nbsp;2828🍴</code></b> [Bluesky](https://github.com/bluesky-social/social-app)) - The Bluesky social app for web, iOS, and Android.
- <b><code>&nbsp;&nbsp;5016⭐</code></b> <b><code>&nbsp;&nbsp;4003🍴</code></b> [Expensify](https://github.com/Expensify/App)) - New Expensify: financial collaboration, chat-centered.
- <b><code>&nbsp;56232⭐</code></b> <b><code>&nbsp;&nbsp;6260🍴</code></b> [Joplin](https://github.com/laurent22/joplin)) - Privacy-focused note-taking app with sync, on every platform.
- <b><code>&nbsp;&nbsp;2714⭐</code></b> <b><code>&nbsp;&nbsp;1655🍴</code></b> [Mattermost](https://github.com/mattermost/mattermost-mobile)) - Mattermost's mobile apps.
- <b><code>&nbsp;&nbsp;2413⭐</code></b> <b><code>&nbsp;&nbsp;1466🍴</code></b> [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat.ReactNative)) - Rocket.Chat's mobile client.
- <b><code>&nbsp;&nbsp;3773⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;592🍴</code></b> [Artsy](https://github.com/artsy/eigen)) - The art world in your pocket.
- <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [YouTrack Mobile](https://github.com/JetBrains/youtrack-mobile)) - JetBrains' YouTrack client for iOS and Android.

## Learning

- 🌎 [React Native Docs](reactnative.dev/docs/getting-started) - The official guides, always the right place to start.
- 🌎 [Expo Tutorial](docs.expo.dev/tutorial/introduction/) - Official hands-on tutorial building a universal app.
- 🌎 [React Native Express](www.reactnative.express) - Guided walkthrough of the React Native ecosystem.
- 🌎 [Start React Native](start-react-native.dev) - William Candillon's in-depth course on gestures and animations.
- 🌎 [Can it be done in React Native?](www.youtube.com/@wcandillon) - William Candillon's YouTube series rebuilding famous UIs.

## Staying Up to Date

- 🌎 [This Week In React](thisweekinreact.com) - Weekly newsletter covering React and React Native.
- 🌎 [React Native Newsletter](reactnativenewsletter.com) - Occasional newsletter of React Native news and articles.
- 🌎 [React Native Radio](reactnativeradio.com) - The long-running React Native podcast, by Infinite Red.
- 🌎 [Chain React](chainreactconf.com) - The US React Native conference, Portland, OR.
- 🌎 [App.js Conf](appjs.co) - Expo and React Native conference, Kraków, Poland.
- 🌎 [React Universe Conf](www.reactuniverseconf.com) - Callstack's conference (formerly React Native EU), Wrocław, Poland.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first: entries should be actively maintained, work with current React Native, and be genuinely useful to most developers.

Many thanks to everyone on the [contributor list](https://github.com/correia-jpv/fucking-awesome-react-native/graphs/contributors) :)

## Source
<b><code>&nbsp;35694⭐</code></b> <b><code>&nbsp;&nbsp;4035🍴</code></b> [jondot/awesome-react-native](https://github.com/jondot/awesome-react-native))