Refactor Task: Align Package Name with Google Play Console

Please update the entire project to use the mandatory package name: sa.remanalzahrani.bidoonathar

Required Actions:

Update Build Files: Change applicationId to "sa.remanalzahrani.bidoonathar" in all build.gradle and build.gradle.kts files.

Update Manifest: Update the package attribute in AndroidManifest.xml.

Namespace Update: Update the namespace in the android block of build.gradle to match the new package name.

Code Refactoring:

Rename all directory structures to follow: src/main/java/sa/remanalzahrani/bidoonathar/ and src/main/kotlin/sa/remanalzahrani/bidoonathar/.

Update all package declarations and import statements in every .java and .kt file.

Clean & Verify: Ensure no references to the old package name remain in the codebase.

Goal: This is necessary to fix the Google Play Console upload error regarding package name mismatch.
