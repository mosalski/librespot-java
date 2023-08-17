# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

_This is a fork of librespot-java for Jetispot, an Android unofficial Spotify client. Modifications were required because of updated protobufs that are needed to proper UI, better queue event handling for "Now Playing UI" and for less reflection usage due to private methods/fields._

## [1.6.3_mod] - 16-08-2023
### Changed
- Updated librespot-java to match latest changes


## [1.6.2_mod] - 05-06-2022
### Added
- Public bridges to StateWrapper + handlePlay (d560dda15123f013603dd53296a04dcd3e0cacf7)
- Support for Extended AAC + FLAC in API + ability to set custom quality picker (e37a815f1a12ff74dfa1cd1d49d3922bac297d6a)
- Add context description display option (65e00863cfa309b5494e9fbc4b9ccb0d1e03bc33)
- Public cleanup function for CacheManager (af2278fe685cc0bf07d03db560713fc3508c8f90)

### Changed
- Updated protobufs (7bdb521120a14026bb7d12849ad8444c7e65c03a)
- Updated protoc + protobuf runtime (bb7c20893565cbd4bf70eec6f0f1f50161c2d478)
