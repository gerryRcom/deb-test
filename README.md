# deb-test
Test a build process for a deb package:

Test version will package a simple binary

- Generate some content pulling system specific info from a csv
- Build .deb for each system based on that content
- Only rebuild if the core binary has changed
