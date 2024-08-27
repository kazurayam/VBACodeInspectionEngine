# VBA Code Inspection Engine
A ”Visual Basic for Application” language recognizer written in Java, which is based on the ANTLR4 grammar originated by the Rubberduck VBA project

The Rubberduck project publishes ANTLR4 Grammar for Visual Basic for Application at:
- https://github.com/rubberduck-vba/Rubberduck/tree/next/Rubberduck.Parsing/Grammar

I (kazurayam) got interested in building a Java program that can parse and recognize VBA codes based on this grammar. So I created this Gradle project. The `build.gradle` will include the following tasks:

1. `DownloadRubberduckGrammars`
2. `test`
3. `publishVBACodeInspectionEngineArtifactToGHa`