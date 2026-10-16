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
- <b><code>&nbsp;&nbsp;4072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Upgrade Helper](https://github.com/react-native-community/upgrade-helper)) - Web tool that shows the exact diff between two React Native versions for painless upgrades.
- <b><code>&nbsp;&nbsp;1317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge)) - The raw version-to-version diffs powering Upgrade Helper.
- <b><code>&nbsp;&nbsp;3744⭐</code></b> <b><code>&nbsp;&nbsp;1102🍴</code></b> [Expo Examples](https://github.com/expo/examples)) - Example projects demonstrating Expo APIs and integrations.

## AI-Assisted Development

Tools for building React Native apps with AI agents, and for putting AI inside your apps.

### Agents & Skills

- 🌎 [Expo AI Agents Guide](docs.expo.dev/agents/) - Expo's official documentation for AI-native development: agent setup, llms.txt, and best practices.
- 🌎 [Claude Code + Expo](docs.expo.dev/agents/claude/) - Official guide for building, debugging, and deploying Expo apps with Claude Code.
- <b><code>&nbsp;&nbsp;2868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Expo Skills](https://github.com/expo/skills)) - Agent skills that give coding agents Expo-specific knowledge and best practices.
- <b><code>181409⭐</code></b> <b><code>&nbsp;21482🍴</code></b> [Agent Skills](https://github.com/anthropics/skills)) - Anthropic's public repository of agent skills, usable with Claude Code and other agents.

### MCP Servers

- 🌎 [Expo MCP](docs.expo.dev/mcp/) - Expo-hosted MCP server: EAS logs, documentation search, and deployment workflows from any MCP-capable agent.
- <b><code>&nbsp;&nbsp;9579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;854🍴</code></b> [mobile-mcp](https://github.com/mobile-next/mobile-mcp)) - MCP server for mobile automation on iOS, Android, emulators, simulators, and real devices.
- <b><code>&nbsp;&nbsp;2193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp)) - MCP server for driving the iOS simulator: interact with UI, take screenshots, inspect the view hierarchy.
- 🌎 [Maestro](maestro.dev) - E2E testing framework with a built-in MCP server, letting agents run flows and control devices.

### On-Device AI

- <b><code>&nbsp;&nbsp;1764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [react-native-executorch](https://github.com/software-mansion/react-native-executorch)) - Declarative on-device AI inference powered by ExecuTorch, from Software Mansion.
- <b><code>&nbsp;&nbsp;1059⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [llama.rn](https://github.com/mybigday/llama.rn)) - React Native binding of llama.cpp for running LLMs on device.
- <b><code>&nbsp;&nbsp;1239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [react-native-fast-tflite](https://github.com/mrousavy/react-native-fast-tflite)) - High-performance TensorFlow Lite inference with GPU acceleration.
- <b><code>&nbsp;27338⭐</code></b> <b><code>&nbsp;&nbsp;5353🍴</code></b> [AI SDK](https://github.com/vercel/ai)) - The AI toolkit for TypeScript; works in Expo and React Native apps for chat, streaming, and tool use.

### AI App Builders

- 🌎 [a0.dev](a0.dev) - Generates complete React Native apps from a prompt and ships them to the app stores.
- 🌎 [Rork](rork.com) - AI app builder that generates Expo/React Native projects compiling to native iOS, Android, and web.

## Components

### UI

- <b><code>&nbsp;14469⭐</code></b> <b><code>&nbsp;&nbsp;2249🍴</code></b> [react-native-paper](https://github.com/callstack/react-native-paper)) - Material Design components for Android and iOS.
- <b><code>&nbsp;25875⭐</code></b> <b><code>&nbsp;&nbsp;4665🍴</code></b> [React Native Elements](https://github.com/react-native-elements/react-native-elements)) - Cross-platform UI toolkit with themed, composable components.
- <b><code>&nbsp;14260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [Tamagui](https://github.com/tamagui/tamagui)) - Universal UI kit and style system with an optimizing compiler, 100% parity between React Native and web.
- <b><code>&nbsp;&nbsp;5327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [gluestack-ui](https://github.com/gluestack/gluestack-ui)) - Copy-paste components and patterns built on Tailwind-style utility classes.
- <b><code>&nbsp;10664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;961🍴</code></b> [react-native-ui-kitten](https://github.com/akveo/react-native-ui-kitten)) - UI library based on the Eva Design System with theming support.
- <b><code>&nbsp;20366⭐</code></b> <b><code>&nbsp;&nbsp;2386🍴</code></b> [NativeBase](https://github.com/GeekyAnts/NativeBase)) - Mobile-first, accessible component library for React Native and web.
- <b><code>&nbsp;&nbsp;4983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Shoutem UI](https://github.com/shoutem/ui)) - Customizable set of styled components for React Native.
- <b><code>&nbsp;17916⭐</code></b> <b><code>&nbsp;&nbsp;2100🍴</code></b> [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)) - Customizable icon sets with support for styling and image sources.
- <b><code>&nbsp;17206⭐</code></b> <b><code>&nbsp;&nbsp;1801🍴</code></b> [lottie-react-native](https://github.com/lottie-react-native/lottie-react-native)) - Render After Effects animations natively.
- <b><code>&nbsp;&nbsp;8009⭐</code></b> <b><code>&nbsp;&nbsp;1204🍴</code></b> [react-native-svg](https://github.com/software-mansion/react-native-svg)) - SVG rendering for React Native and web.
- <b><code>&nbsp;&nbsp;1739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [react-native-svg-transformer](https://github.com/kristerkari/react-native-svg-transformer)) - Import SVG files as components, like on the web.
- <b><code>&nbsp;&nbsp;5649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;658🍴</code></b> [react-native-modal](https://github.com/react-native-modal/react-native-modal)) - Enhanced, animated, customizable modal.
- <b><code>&nbsp;&nbsp;3879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;565🍴</code></b> [react-native-blur](https://github.com/margelo/react-native-blur)) - Native blur view component.
- <b><code>&nbsp;&nbsp;2241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [react-native-blurhash](https://github.com/mrousavy/react-native-blurhash)) - Colorful blurry placeholders while content loads.
- <b><code>&nbsp;10327⭐</code></b> <b><code>&nbsp;&nbsp;3053🍴</code></b> [react-native-calendars](https://github.com/wix/react-native-calendars)) - Feature-rich calendar components.
- <b><code>&nbsp;&nbsp;2508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [react-native-date-picker](https://github.com/henninghall/react-native-date-picker)) - Native date and time picker for Android and iOS.
- <b><code>&nbsp;&nbsp;3433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;356🍴</code></b> [react-native-reanimated-carousel](https://github.com/dohooo/react-native-reanimated-carousel)) - Swiper/carousel built entirely on Reanimated, the successor to snap-carousel.
- <b><code>&nbsp;&nbsp;3369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;487🍴</code></b> [react-native-pager-view](https://github.com/callstack/react-native-pager-view)) - Native ViewPager and UIPageViewController wrapper.
- <b><code>&nbsp;&nbsp;2435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;428🍴</code></b> [react-native-copilot](https://github.com/mohebifar/react-native-copilot)) - Step-by-step walkthrough tooltips for onboarding.
- <b><code>&nbsp;&nbsp;1481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [react-native-super-grid](https://github.com/saleel/react-native-super-grid)) - Responsive grid view.
- <b><code>&nbsp;&nbsp;2249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;418🍴</code></b> [react-native-circular-progress](https://github.com/bartgryszko/react-native-circular-progress)) - Animated circular progress indicators.
- <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [react-native-progress-steps](https://github.com/colbymillerdev/react-native-progress-steps)) - Customizable progress stepper.
- <b><code>&nbsp;&nbsp;1229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [react-native-confirmation-code-field](https://github.com/retyui/react-native-confirmation-code-field)) - OTP/confirmation code input for iOS, Android, and web.
- <b><code>&nbsp;&nbsp;1175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [react-native-qrcode-svg](https://github.com/Expensify/react-native-qrcode-svg)) - QR code generator based on react-native-svg.
- <b><code>&nbsp;&nbsp;1113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;830🍴</code></b> [react-native-country-picker-modal](https://github.com/xcarpentier/react-native-country-picker-modal)) - Country picker with flags, search, and localization.
- <b><code>&nbsp;&nbsp;&nbsp;446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [react-native-hole-view](https://github.com/ibitcy/react-native-hole-view)) - Cut touch-through holes anywhere, perfect for onboarding highlights.

### Lists

- <b><code>&nbsp;&nbsp;7243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;401🍴</code></b> [FlashList](https://github.com/Shopify/flash-list)) - Shopify's fast and performant list, a drop-in replacement for FlatList.
- <b><code>&nbsp;&nbsp;3428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [Legend List](https://github.com/LegendApp/legend-list)) - High-performance list in pure JS, built for the New Architecture.
- <b><code>&nbsp;&nbsp;5431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [recyclerlistview](https://github.com/Flipkart/recyclerlistview)) - The recycling listview that pioneered high-performance lists in React Native.

### Navigation

- <b><code>&nbsp;24511⭐</code></b> <b><code>&nbsp;&nbsp;5141🍴</code></b> [React Navigation](https://github.com/react-navigation/react-navigation)) - The standard routing and navigation library for React Native.
- 🌎 [Expo Router](docs.expo.dev/router/introduction/) - File-based routing for universal React Native apps, built on React Navigation.
- <b><code>&nbsp;13173⭐</code></b> <b><code>&nbsp;&nbsp;2623🍴</code></b> [react-native-navigation](https://github.com/wix/react-native-navigation)) - Wix's fully native navigation solution.
- <b><code>&nbsp;&nbsp;3737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;744🍴</code></b> [react-native-screens](https://github.com/software-mansion/react-native-screens)) - Native navigation primitives that back React Navigation's native stack.
- <b><code>&nbsp;&nbsp;1462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [react-native-bottom-tabs](https://github.com/callstack/react-native-bottom-tabs)) - Truly native bottom tab bars (SwiftUI and Material) for React Native.

### Sheets, Menus & Toasts

- <b><code>&nbsp;&nbsp;9106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;962🍴</code></b> [react-native-bottom-sheet](https://github.com/gorhom/react-native-bottom-sheet)) - Performant, interactive bottom sheet with configurable gestures.
- <b><code>&nbsp;&nbsp;2077⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [react-native-true-sheet](https://github.com/lodev09/react-native-true-sheet)) - The true native bottom sheet experience.
- <b><code>&nbsp;&nbsp;2180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [react-native-actions-sheet](https://github.com/ammarahm-ed/react-native-actions-sheet)) - Cross-platform ActionSheet with a flexible API.
- <b><code>&nbsp;&nbsp;2255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Zeego](https://github.com/nandorojo/zeego)) - Menus for React Native done right — truly native dropdown and context menus.
- <b><code>&nbsp;&nbsp;1561⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Burnt](https://github.com/nandorojo/burnt)) - Native toasts and alerts for iOS and Android.
- <b><code>&nbsp;&nbsp;2138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;393🍴</code></b> [react-native-root-toast](https://github.com/magicismight/react-native-root-toast)) - Pure JavaScript toast solution.
- <b><code>&nbsp;&nbsp;1531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [react-native-flash-message](https://github.com/lucasferreira/react-native-flash-message)) - Flashbar and top-notification alerts.
- <b><code>&nbsp;&nbsp;1437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [react-native-notifier](https://github.com/seniv/react-native-notifier)) - Fast and simple in-app notifications.
- <b><code>&nbsp;&nbsp;1557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [react-native-popup-menu](https://github.com/instea/react-native-popup-menu)) - Extensible popup menu component.

### Forms & Keyboard

- <b><code>&nbsp;44860⭐</code></b> <b><code>&nbsp;&nbsp;2495🍴</code></b> [React Hook Form](https://github.com/react-hook-form/react-hook-form)) - Performant form state management and validation for React and React Native.
- <b><code>&nbsp;34305⭐</code></b> <b><code>&nbsp;&nbsp;2777🍴</code></b> [Formik](https://github.com/jaredpalmer/formik)) - Build forms without the tears.
- <b><code>&nbsp;&nbsp;3747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [react-native-keyboard-controller](https://github.com/kirillzyusko/react-native-keyboard-controller)) - Keyboard manager that works identically on iOS and Android.
- <b><code>&nbsp;&nbsp;1844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;498🍴</code></b> [react-native-picker-select](https://github.com/lawnstarter/react-native-picker-select)) - Picker emulating the native select interface.
- <b><code>&nbsp;&nbsp;&nbsp;871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [react-native-autocomplete-input](https://github.com/byteburgers/react-native-autocomplete-input)) - Pure JavaScript autocomplete input.
- <b><code>&nbsp;&nbsp;1607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [react-native-masked-text](https://github.com/bhrott/react-native-masked-text)) - Masked text and input components.
- <b><code>&nbsp;&nbsp;1508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;710🍴</code></b> [react-native-credit-card-input](https://github.com/sbycrosz/react-native-credit-card-input)) - Cross-platform credit card input.
- <b><code>&nbsp;&nbsp;&nbsp;590⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [react-native-multiple-select](https://github.com/toystars/react-native-multiple-select)) - Simple multi-select component.

### Text & Rich Content

- <b><code>&nbsp;&nbsp;1336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [react-native-live-markdown](https://github.com/Expensify/react-native-live-markdown)) - Drop-in TextInput replacement with live Markdown formatting, by Expensify.
- <b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [react-native-markdown-display](https://github.com/iamacup/react-native-markdown-display)) - 100% CommonMark-compatible Markdown renderer.
- <b><code>&nbsp;&nbsp;&nbsp;811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [react-native-hyperlink](https://github.com/obipawan/react-native-hyperlink)) - Make URLs, emails, and fuzzy links clickable.
- <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [react-native-html-to-pdf](https://github.com/christopherdro/react-native-html-to-pdf)) - Convert HTML strings to PDF documents.
- <b><code>&nbsp;&nbsp;&nbsp;739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [react-native-responsive-fontsize](https://github.com/heyman333/react-native-responsive-fontsize)) - Responsive font sizes based on device screen size.

### Image & Camera

- <b><code>&nbsp;&nbsp;9646⭐</code></b> <b><code>&nbsp;&nbsp;1395🍴</code></b> [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera)) - Powerful, high-performance camera library with frame processors.
- 🌎 [expo-image](docs.expo.dev/versions/latest/sdk/image/) - Fast, modern image component with caching and blurhash support.
- <b><code>&nbsp;&nbsp;8633⭐</code></b> <b><code>&nbsp;&nbsp;2069🍴</code></b> [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker)) - Native UI for selecting photos and videos.
- <b><code>&nbsp;&nbsp;6351⭐</code></b> <b><code>&nbsp;&nbsp;1614🍴</code></b> [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker)) - Image picker with camera, cropping, and compression.
- <b><code>&nbsp;&nbsp;2711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;636🍴</code></b> [react-native-camera-kit](https://github.com/teslamotors/react-native-camera-kit)) - High-performance camera library with barcode scanning, by Tesla.
- <b><code>&nbsp;&nbsp;1661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;361🍴</code></b> [react-native-image-resizer](https://github.com/bamlab/react-native-image-resizer)) - Resize local images natively.

### Video & Audio

- <b><code>&nbsp;&nbsp;7720⭐</code></b> <b><code>&nbsp;&nbsp;3023🍴</code></b> [react-native-video](https://github.com/TheWidlarzGroup/react-native-video)) - The Video component for React Native.
- 🌎 [expo-video](docs.expo.dev/versions/latest/sdk/video/) - Modern video playback built for Expo and the New Architecture.
- <b><code>&nbsp;&nbsp;3709⭐</code></b> <b><code>&nbsp;&nbsp;1200🍴</code></b> [react-native-track-player](https://github.com/doublesymmetry/react-native-track-player)) - Full-featured audio player: background playback, Android Auto, CarPlay, lock-screen controls.
- <b><code>&nbsp;&nbsp;&nbsp;848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [react-native-audio-api](https://github.com/software-mansion/react-native-audio-api)) - High-performance audio engine implementing the Web Audio API.
- <b><code>&nbsp;&nbsp;2917⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;781🍴</code></b> [react-native-sound](https://github.com/zmxv/react-native-sound)) - Play sound clips natively.
- <b><code>&nbsp;&nbsp;4995⭐</code></b> <b><code>&nbsp;&nbsp;1332🍴</code></b> [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc)) - WebRTC for React Native.

### Maps & Location

- <b><code>&nbsp;16008⭐</code></b> <b><code>&nbsp;&nbsp;4964🍴</code></b> [react-native-maps](https://github.com/react-native-maps/react-native-maps)) - MapView components for iOS and Android.
- <b><code>&nbsp;&nbsp;2921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;953🍴</code></b> [rnmapbox/maps](https://github.com/rnmapbox/maps)) - Mapbox maps for custom map experiences.
- <b><code>&nbsp;&nbsp;2941⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [react-native-background-geolocation](https://github.com/transistorsoft/react-native-background-geolocation)) - Battery-conscious background location with motion detection.
- <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [react-native-map-link](https://github.com/tschoffelen/react-native-map-link)) - Open the user's preferred maps app.
- <b><code>&nbsp;&nbsp;2071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;869🍴</code></b> [react-native-google-places-autocomplete](https://github.com/FaridSafi/react-native-google-places-autocomplete)) - Customizable Google Places autocomplete.

### Charts

- <b><code>&nbsp;&nbsp;1231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [victory-native-xl](https://github.com/FormidableLabs/victory-native-xl)) - Charting built on Skia and Reanimated with a focus on performance.
- <b><code>&nbsp;&nbsp;2634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [react-native-graph](https://github.com/margelo/react-native-graph)) - Beautiful, high-performance line graphs built with Skia.
- <b><code>&nbsp;&nbsp;1375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [react-native-gifted-charts](https://github.com/Abhinandan-Kushwaha/react-native-gifted-charts)) - Bar, line, area, pie, donut, and stacked charts.

### Animation & Gestures

- <b><code>&nbsp;11026⭐</code></b> <b><code>&nbsp;&nbsp;1532🍴</code></b> [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated)) - The standard for performant animations, running on the UI thread.
- <b><code>&nbsp;&nbsp;6792⭐</code></b> <b><code>&nbsp;&nbsp;1080🍴</code></b> [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler)) - Declarative, native-driven gesture system.
- <b><code>&nbsp;&nbsp;8731⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;671🍴</code></b> [react-native-skia](https://github.com/Shopify/react-native-skia)) - High-performance 2D graphics with the Skia rendering engine.
- <b><code>&nbsp;&nbsp;4556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Moti](https://github.com/nandorojo/moti)) - Universal animation library powered by Reanimated, with a Framer Motion-like API.
- <b><code>&nbsp;&nbsp;9928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;693🍴</code></b> [react-native-animatable](https://github.com/oblador/react-native-animatable)) - Declarative transitions and standard animations.
- <b><code>&nbsp;&nbsp;3275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [TypeGPU](https://github.com/software-mansion/TypeGPU)) - Type-safe WebGPU toolkit for advanced GPU work.

### Styling & Design Systems

- <b><code>&nbsp;&nbsp;8113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;409🍴</code></b> [NativeWind](https://github.com/nativewind/nativewind)) - Tailwind CSS for React Native.
- <b><code>&nbsp;&nbsp;2968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Unistyles](https://github.com/jpudysz/react-native-unistyles)) - C++-powered StyleSheet superset with themes and breakpoints, built for the New Architecture.
- <b><code>&nbsp;41090⭐</code></b> <b><code>&nbsp;&nbsp;2665🍴</code></b> [styled-components](https://github.com/styled-components/styled-components)) - CSS-in-JS styling that also targets React Native.
- <b><code>&nbsp;18015⭐</code></b> <b><code>&nbsp;&nbsp;1136🍴</code></b> [Emotion](https://github.com/emotion-js/emotion)) - High-performance CSS-in-JS style composition.
- <b><code>&nbsp;&nbsp;3559⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [react-native-typography](https://github.com/hectahertz/react-native-typography)) - Pixel-perfect, native-looking typographic styles.
- <b><code>&nbsp;&nbsp;1028⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Stacks](https://github.com/grapp-dev/stacks)) - Layout primitives for building consistent UIs.
- <b><code>&nbsp;&nbsp;1032⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [react-native-edge-to-edge](https://github.com/zoontek/react-native-edge-to-edge)) - Effortless edge-to-edge display on Android.
- <b><code>&nbsp;&nbsp;2768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [react-native-safe-area-context](https://github.com/AppAndFlow/react-native-safe-area-context)) - Flexible safe area inset handling.

### Internationalization

- <b><code>&nbsp;&nbsp;2442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [react-native-localize](https://github.com/zoontek/react-native-localize)) - Toolbox for app localization: locales, timezones, currencies.

### System & Device

- <b><code>&nbsp;&nbsp;6686⭐</code></b> <b><code>&nbsp;&nbsp;1460🍴</code></b> [react-native-device-info](https://github.com/react-native-device-info/react-native-device-info)) - Device information for iOS and Android.
- <b><code>&nbsp;&nbsp;4373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;847🍴</code></b> [react-native-permissions](https://github.com/zoontek/react-native-permissions)) - Unified permissions API.
- <b><code>&nbsp;&nbsp;3483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;542🍴</code></b> [react-native-keychain](https://github.com/oblador/react-native-keychain)) - Secure keychain and keystore access.
- <b><code>&nbsp;&nbsp;4953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;657🍴</code></b> [react-native-config](https://github.com/react-native-config/react-native-config)) - Expose environment config to your JS and native code.
- <b><code>&nbsp;&nbsp;1708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;595🍴</code></b> [react-native-contacts](https://github.com/morenoh149/react-native-contacts)) - Native contacts access.
- <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [react-native-calendar-events](https://github.com/wmcmahan/react-native-calendar-events)) - Calendar event access for iOS and Android.
- <b><code>&nbsp;&nbsp;3898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;974🍴</code></b> [react-native-share](https://github.com/react-native-share/react-native-share)) - Native share sheet and social sharing.
- <b><code>&nbsp;&nbsp;&nbsp;985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [react-native-haptic-feedback](https://github.com/mkuczera/react-native-haptic-feedback)) - Haptics that feel right, including Core Haptics patterns.
- <b><code>&nbsp;&nbsp;&nbsp;936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [react-native-sensors](https://github.com/react-native-sensors/react-native-sensors)) - Developer-friendly access to device sensors.
- <b><code>&nbsp;&nbsp;1611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [react-native-background-fetch](https://github.com/transistorsoft/react-native-background-fetch)) - Periodic background callbacks on iOS and Android.
- <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [react-native-background-downloader](https://github.com/kesha-antonov/react-native-background-downloader)) - Download and upload large files, even when the app is backgrounded.
- <b><code>&nbsp;&nbsp;1514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;467🍴</code></b> [document-picker](https://github.com/react-native-documents/document-picker)) - Document picker and viewer.
- <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [expo-quick-actions](https://github.com/EvanBacon/expo-quick-actions)) - Home screen quick actions and custom app icons.
- <b><code>&nbsp;&nbsp;&nbsp;410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [react-native-ssl-pinning](https://github.com/MaxToyberman/react-native-ssl-pinning)) - SSL pinning and cookie handling.

### Notifications

- 🌎 [Expo Notifications](docs.expo.dev/versions/latest/sdk/notifications/) - Push and local notifications for Expo apps.
- <b><code>&nbsp;12318⭐</code></b> <b><code>&nbsp;&nbsp;2330🍴</code></b> [react-native-firebase](https://github.com/invertase/react-native-firebase)) - Includes FCM messaging alongside the full Firebase suite.
- <b><code>&nbsp;&nbsp;3340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;751🍴</code></b> [react-native-notifications](https://github.com/wix/react-native-notifications)) - Wix's notification handling library.
- <b><code>&nbsp;&nbsp;1593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;379🍴</code></b> [react-native-onesignal](https://github.com/OneSignal/react-native-onesignal)) - OneSignal push notification SDK.

### Web & WebViews

- <b><code>&nbsp;&nbsp;7197⭐</code></b> <b><code>&nbsp;&nbsp;3174🍴</code></b> [react-native-webview](https://github.com/react-native-webview/react-native-webview)) - The community WebView component.
- <b><code>&nbsp;&nbsp;1418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [react-native-inappbrowser](https://github.com/proyecto26/react-native-inappbrowser)) - In-app browser using Chrome Custom Tabs and SFSafariViewController.
- <b><code>&nbsp;22145⭐</code></b> <b><code>&nbsp;&nbsp;1831🍴</code></b> [react-native-web](https://github.com/necolas/react-native-web)) - Run React Native components and APIs on the web.
- <b><code>&nbsp;&nbsp;4097⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Solito](https://github.com/nandorojo/solito)) - React Native + Next.js, unified navigation for universal apps.

### Other Platforms

- <b><code>&nbsp;17358⭐</code></b> <b><code>&nbsp;&nbsp;1210🍴</code></b> [react-native-windows](https://github.com/microsoft/react-native-windows)) - Build native Windows apps with React.
- <b><code>&nbsp;&nbsp;4393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [react-native-macos](https://github.com/microsoft/react-native-macos)) - Build native macOS apps with React.

## Data

### State Management

- <b><code>&nbsp;58824⭐</code></b> <b><code>&nbsp;&nbsp;2200🍴</code></b> [Zustand](https://github.com/pmndrs/zustand)) - Bear necessities for state management.
- <b><code>&nbsp;21296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;728🍴</code></b> [Jotai](https://github.com/pmndrs/jotai)) - Primitive and flexible atomic state.
- <b><code>&nbsp;11231⭐</code></b> <b><code>&nbsp;&nbsp;1303🍴</code></b> [Redux Toolkit](https://github.com/reduxjs/redux-toolkit)) - The official, batteries-included Redux toolset.
- <b><code>&nbsp;&nbsp;4220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [Legend State](https://github.com/LegendApp/legend-state)) - Super fast state with fine-grained reactivity and built-in sync.

### Storage & Databases

- <b><code>&nbsp;&nbsp;8517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;345🍴</code></b> [react-native-mmkv](https://github.com/mrousavy/react-native-mmkv)) - The fastest key/value storage for React Native, ~30x faster than AsyncStorage.
- <b><code>&nbsp;&nbsp;5073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;485🍴</code></b> [AsyncStorage](https://github.com/react-native-async-storage/async-storage)) - Simple, asynchronous, persistent key-value storage.
- <b><code>&nbsp;&nbsp;1048⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [op-sqlite](https://github.com/OP-Engineering/op-sqlite)) - The fastest SQLite library for React Native.
- 🌎 [expo-sqlite](docs.expo.dev/versions/latest/sdk/sqlite/) - SQLite database access in Expo, with support for Drizzle ORM.
- <b><code>&nbsp;36048⭐</code></b> <b><code>&nbsp;&nbsp;1717🍴</code></b> [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)) - TypeScript ORM with first-class Expo/React Native SQLite support.
- <b><code>&nbsp;11792⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;661🍴</code></b> [WatermelonDB](https://github.com/Nozbe/WatermelonDB)) - Reactive and asynchronous database for powerful apps that scale.
- <b><code>&nbsp;23410⭐</code></b> <b><code>&nbsp;&nbsp;1180🍴</code></b> [RxDB](https://github.com/pubkey/rxdb)) - Local-first, reactive database that replicates with your backend.
- <b><code>&nbsp;&nbsp;6003⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [Realm](https://github.com/realm/realm-js)) - Mobile object database, an alternative to SQLite.

### Networking

- <b><code>&nbsp;50437⭐</code></b> <b><code>&nbsp;&nbsp;4261🍴</code></b> [TanStack Query](https://github.com/TanStack/query)) - Powerful async state management and data fetching.
- <b><code>&nbsp;&nbsp;2885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [apisauce](https://github.com/infinitered/apisauce)) - Axios with standardized errors and request/response transforms.
- <b><code>&nbsp;&nbsp;2180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [react-native-netinfo](https://github.com/react-native-netinfo/react-native-netinfo)) - Network state and connectivity info.
- <b><code>&nbsp;&nbsp;&nbsp;690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [react-native-network-logger](https://github.com/alexbrazier/react-native-network-logger)) - In-app HTTP request monitor.
- <b><code>&nbsp;&nbsp;1072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [react-native-quick-crypto](https://github.com/margelo/react-native-quick-crypto)) - Fast native implementation of Node's crypto module.

## Services & Integrations

- <b><code>&nbsp;12318⭐</code></b> <b><code>&nbsp;&nbsp;2330🍴</code></b> [react-native-firebase](https://github.com/invertase/react-native-firebase)) - Well-tested, feature-rich modular Firebase implementation.
- <b><code>&nbsp;&nbsp;1824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [sentry-react-native](https://github.com/getsentry/sentry-react-native)) - Official Sentry SDK for crash reporting and performance monitoring.
- <b><code>&nbsp;&nbsp;2251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;471🍴</code></b> [react-native-app-auth](https://github.com/FormidableLabs/react-native-app-auth)) - PKCE-compliant OAuth2 client based on AppAuth.
- <b><code>&nbsp;&nbsp;3557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [google-signin](https://github.com/react-native-google-signin/google-signin)) - Google Sign-In for React Native.

## Payments & Monetization

- <b><code>&nbsp;&nbsp;1428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [stripe-react-native](https://github.com/stripe/stripe-react-native)) - Official Stripe SDK for payments in React Native.
- <b><code>&nbsp;&nbsp;1215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [react-native-purchases](https://github.com/RevenueCat/react-native-purchases)) - RevenueCat SDK for in-app purchases and subscriptions.

## Development Tools

### Tooling & IDE

- <b><code>&nbsp;&nbsp;1720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Radon IDE](https://github.com/software-mansion/radon-ide)) - VSCode/Cursor extension that turns your editor into a full-featured React Native IDE with an embedded simulator.
- <b><code>&nbsp;&nbsp;1367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [EAS CLI](https://github.com/expo/eas-cli)) - Build, submit, and update iOS and Android apps from the command line.
- <b><code>&nbsp;&nbsp;2776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [react-native-rename](https://github.com/junedomingo/react-native-rename)) - Rename a React Native app with one command.
- <b><code>&nbsp;&nbsp;1631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [react-native-bundle-visualizer](https://github.com/callstack/react-native-bundle-visualizer)) - See which packages inflate your bundle size.
- <b><code>&nbsp;&nbsp;1946⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [Re.Pack](https://github.com/callstack/repack)) - Webpack/Rspack-based toolkit with code splitting and Module Federation for React Native.

### Debugging

- <b><code>&nbsp;15591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;970🍴</code></b> [Reactotron](https://github.com/infinitered/reactotron)) - Desktop app for inspecting React Native apps: state, API requests, performance.
- <b><code>&nbsp;&nbsp;&nbsp;692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Buoy](https://github.com/Buoy-gg/buoy)) - Devtools that live in your app — and answer to your AI agent.

### Testing

- <b><code>&nbsp;16077⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;991🍴</code></b> [Maestro](https://github.com/mobile-dev-inc/Maestro)) - Painless declarative E2E automation for mobile.
- <b><code>&nbsp;12038⭐</code></b> <b><code>&nbsp;&nbsp;1909🍴</code></b> [Detox](https://github.com/wix/Detox)) - Gray-box end-to-end testing and automation framework.
- <b><code>&nbsp;&nbsp;3422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [React Native Testing Library](https://github.com/callstack/react-native-testing-library)) - Testing utilities that encourage good practices.
- <b><code>&nbsp;&nbsp;1914⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Loki](https://github.com/oblador/loki)) - Visual regression testing for Storybook.

### Builds, Deployment & OTA Updates

- 🌎 [EAS](expo.dev/eas) - Expo Application Services: cloud builds, app store submission, and OTA updates.
- <b><code>&nbsp;&nbsp;1770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [hot-updater](https://github.com/gronxb/hot-updater)) - Self-hostable OTA update solution, a CodePush alternative.
- 🌎 [Fastlane](fastlane.tools) - Automate building, screenshots, and releasing for iOS and Android.

### Building Libraries

- <b><code>&nbsp;&nbsp;3231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [create-react-native-library](https://github.com/callstack/react-native-builder-bob)) - Scaffold and build React Native libraries for distribution.
- <b><code>&nbsp;&nbsp;1965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Nitro Modules](https://github.com/mrousavy/nitro)) - Insanely fast native C++, Swift, or Kotlin modules with statically compiled bindings.

## Starters & Boilerplates

- <b><code>&nbsp;19942⭐</code></b> <b><code>&nbsp;&nbsp;1554🍴</code></b> [Ignite](https://github.com/infinitered/ignite)) - Infinite Red's battle-tested boilerplate with CLI and generators.
- <b><code>&nbsp;&nbsp;5564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;934🍴</code></b> [react-native-boilerplate](https://github.com/thecodingmachine/react-native-boilerplate)) - TheCodingMachine's template for solid, scalable applications.
- 🌎 [Expo Templates](docs.expo.dev/more/create-expo/) - Official Expo templates, from blank to tabs to full navigation setups.

## Open Source Apps

Production apps you can learn from.

- <b><code>&nbsp;18347⭐</code></b> <b><code>&nbsp;&nbsp;2845🍴</code></b> [Bluesky](https://github.com/bluesky-social/social-app)) - The Bluesky social app for web, iOS, and Android.
- <b><code>&nbsp;&nbsp;5062⭐</code></b> <b><code>&nbsp;&nbsp;4057🍴</code></b> [Expensify](https://github.com/Expensify/App)) - New Expensify: financial collaboration, chat-centered.
- <b><code>&nbsp;56751⭐</code></b> <b><code>&nbsp;&nbsp;6344🍴</code></b> [Joplin](https://github.com/laurent22/joplin)) - Privacy-focused note-taking app with sync, on every platform.
- <b><code>&nbsp;&nbsp;2736⭐</code></b> <b><code>&nbsp;&nbsp;1673🍴</code></b> [Mattermost](https://github.com/mattermost/mattermost-mobile)) - Mattermost's mobile apps.
- <b><code>&nbsp;&nbsp;2418⭐</code></b> <b><code>&nbsp;&nbsp;1478🍴</code></b> [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat.ReactNative)) - Rocket.Chat's mobile client.
- <b><code>&nbsp;&nbsp;3779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;593🍴</code></b> [Artsy](https://github.com/artsy/eigen)) - The art world in your pocket.
- <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [YouTrack Mobile](https://github.com/JetBrains/youtrack-mobile)) - JetBrains' YouTrack client for iOS and Android.

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
<b><code>&nbsp;35704⭐</code></b> <b><code>&nbsp;&nbsp;4043🍴</code></b> [jondot/awesome-react-native](https://github.com/jondot/awesome-react-native))