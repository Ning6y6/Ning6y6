# Yi Ning Cui

I work with Swift, Java and Python. My projects cover native iOS apps, game refactoring and computer vision preprocessing.

## Personal projects

### [Evenfare (食衡)](https://github.com/Ning6y6/Personal-Nutrition-Fitness)

An offline iOS app for weighed meal logging, nutrition history and reusable meal templates. I develop the SwiftUI app and its `FoodDecisionCore` Swift package.

The main engineering work is in nutrition validation, historical snapshots, versioned SwiftData storage and local backup recovery. Save commands isolate writes from unfinished drafts, and missing nutrient values stay distinct from known zeroes.

Code: [meal save transactions](https://github.com/Ning6y6/Personal-Nutrition-Fitness/blob/57ff859478782c39e8ccaf7429a9eed1f4b67fdc/FoodDecisionAssistant/Persistence/MealCreateCommand.swift) · [backup verification](https://github.com/Ning6y6/Personal-Nutrition-Fitness/blob/57ff859478782c39e8ccaf7429a9eed1f4b67fdc/FoodDecisionAssistant/Persistence/LocalStoreBackupService.swift)

**Swift · SwiftUI · SwiftData · Swift Testing**

### [JavaFX Tetris — refactoring and extensions](https://github.com/Ning6y6/-COMP2042-CW2025)

I refactored and extended an existing coursework game, separating board rules, input commands, game states and JavaFX rendering. I added Hold, Hard Drop, ghost previews and remappable controls, with JUnit tests for the core rules.

Selected changes: [board encapsulation](https://github.com/Ning6y6/-COMP2042-CW2025/commit/8ce165b4b42cb3488654deb3946dd3ad63308e75) · [UI and game-loop separation](https://github.com/Ning6y6/-COMP2042-CW2025/commit/a17a9cb486da85d4ab91b1a1bd8d6fda12f02cdb)

**Java · JavaFX · JUnit · Maven**

## Team contributions

### [Skin lesion classification project](https://github.com/UNM-SEGP-Group-6/Skin-Cancer-Model)

I contributed lesion analysis to the OpenCV preprocessing pipeline, fixing GrabCut initialization and refining shape and colour measurements. The classifier training and mobile app are separate parts of the team project.

My changes: [pipeline integration](https://github.com/UNM-SEGP-Group-6/Skin-Cancer-Model/commit/7cf0f4b5431a45a7692ce306a0a259324a4413db) · [segmentation fixes](https://github.com/UNM-SEGP-Group-6/Skin-Cancer-Model/commit/f8d2a731a235ade50df7565a542c07573c15b1c2) · [contour cleanup](https://github.com/UNM-SEGP-Group-6/Skin-Cancer-Model/commit/65829e4d4bc1f82ca6b71d797e9f5fd8a74a8d94)

**Python · OpenCV · NumPy**

### [Dash-Track](https://github.com/Notthack/Dash-Track)

A hackathon voucher prototype with issuing, scanning, redemption and revocation flows. I worked across the Express API, local and Dash Drive storage adapters, and the JavaScript interface, including mobile layout. Payments are simulated.

Selected changes: [storage adapters](https://github.com/Notthack/Dash-Track/commit/9d2c52fd35b70823714a96c05b58b4f7d1530e43) · [mobile interface](https://github.com/Notthack/Dash-Track/commit/295ff57b02c42bd2b428af0818231a11fae66561)

**JavaScript · Node.js · Express · Dash Testnet SDK**
