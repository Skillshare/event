# Changelog


## 0.3.2 - Unreleaded

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

### Altered

- Nothing.


## 0.3.1 - 06-09-2014

### Added

- Wildcard listeners: When specifying `*` as the event name to listen to it will listen to all events. Wildcard listeners will be invoked AFTER named event listeners.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Various code style fixes.
- Corrected priority emitter sorting.

### Altered

- Listener invovation is now responsible for retrieving the events attached to an event name. [internal]


## 0.3.0 - 23-08-2014

### Added

- EmitterInterface: an interface is derived from the Emitter class to allow more flexible type hinting and custom implementations. All the code expecting an Emitter now expect an EmitterInterface implementation.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

### Altered

- Nothing.