# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased] - YYYY-MM-DD
#### Added
#### Changed
#### Deprecated
#### Removed
#### Fixed
#### Security

## [1.2.2] - 2024-08-27
#### Changed
- Updates to Network interface (via @pvg, see [notes](https://patchwork.inkandswitch.com/#automerge-repo-network-adapter-api-changes--4RicZ28GjFaTi12xssztkpDjqruu?type=essay))
  
  - Removed emitting "ready" event.
  - Implemented `isReady` and `whenReady`
  - `disconnect()` already implemented.

## [1.2.1] - 2024-07-27
#### Changed
- Updated refs (automerge-repo)


## [1.1.13] - 2024-05-18
#### Changed
- Updated refs (peerjs)



## [1.1.12] - 2024-05-13
#### Changed
- Updated refs and bump version to 1.1.12 to match main `automerge-repo`.


## [1.1.4] - 2024-03-20
#### Changed
- Update refs and bump version to 1.1.4 to match main `automerge-repo`.


## [1.1.2] - 2024-03-13
#### Changed
- Update refs and bump version to 1.1.2 to match main `automerge-repo`.


## [1.1.1] - 2024-02-28
#### Added
- onData callback method (replacing the rxjs observable pattern from original implementation).
- Export types from package.
- Converted adapter to implement [NetworkAdapterInterface] as [NetworkAdapter] base abstract class deprecated.
#### Changed
- Rename `WebrtcNetworkAdapter` to `PeerjsNetworkAdapter`
- Version set to `1.1.1` to match main `automerge-repo` version.



## [0.0.1] - 2024-02-27
#### Added
- Setup initial project structure.
- Copied over from [source](https://github.com/cellplatform/platform-0.2.0/tree/main/code/ext/ext.lib.automerge.webrtc/src/Store.Network.WebrtcAdapter) monorepo.
- Setup CI/CD.
- Initial publish to NPM.
