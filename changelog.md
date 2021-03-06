# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

current dev branch

## [0.2.0]

### Fixed

- config loading did not respect mycroft format

### Added

- local deepspeech STT
- local streaming deepspeech STT
- new method for STT
    - finalize() is called before closing STT stream
- vosk Kaldi STT
- vosk Kaldi Streaming STT

    
### Changed

- removed mycroft engines (only mycroft-core should have those)
- remove useless GoogleJsonSTT abstract class

## [0.1.0]

extracted mycroft.stt into a standalone package

[unreleased]: https://github.com/JarbasAl/speech2text/tree/dev
[0.2.0]: https://github.com/JarbasAl/speech2text/tree/0.2.0
[0.1.0]: https://github.com/JarbasAl/speech2text/tree/0.1.0
