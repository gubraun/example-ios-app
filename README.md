# Sample iOS Project
Sample project to understand the structure of an iOS project sitting in a workspace. I created this project to confirm that dependencies managed by the Swift Dependency Manager are stored in Package.resolved in the .xcworkspace (and not in the .xcodeproj underneath).

Project has been created with Xcode 13 with the following steps:
1. Start Xcode
2. File -> New -> Workspace. This creates an empty workspace.
3. File -> New -> Project. Follow the steps. Create an App for iOS. In one of the last steps, select the workspace you created in step 2.
4. File -> Add Packages. In the URL field, enter e.g. https://github.com/onevcat/Kingfisher. Complete the steps.
5. Optional: Build and run the project.
