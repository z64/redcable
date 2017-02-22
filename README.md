# redcable

### [WIP] This is still in early development and design!

**redcable** is a standalone application that manages a cache and gateway connection to [Discord](https://discordapp.com) for use with other applications that may rely on cached Discord data such as:

- Chat bots (particularly those built that can't hot-reload code)
- Web interfaces

These "child" applications subscribe to a Redis key to be notified when new gateway packets are available for processing.

These apps can also publish to a key to have their packets queued up to be sent out to Discord by a worker.

## Contributors

- [z64](https://github.com/z64) Zac Nowicki - creator, maintainer
