# Introduction 
This is a dummy project for testing plugin build and test workflow.

# Folder Structure
```
.
├── Build
├── Source
├── Tests
│     ├── Unit
│     ├── Integration
│     └── System
├── Tools
└── README.md
```

# Requirements
1. Install LabVIEW 2017 64-bit
2. Install LabVIEWCLI (http://www.ni.com/download/labview-command-line-interface-18.0/7545/en/)
3. Install VI Tester Unit Test Framework (http://sine.ni.com/nips/cds/view/p/lang/en/nid/215910)
4. Install JUnit XML TestResults plugin for JKI VI Tester (https://github.com/JKISoftware/JKI-VI-Tester-JUnit-XML-Test-Results)

# Build and Test
1. Run Build.bat to build library
2. Run Test.bat to test library