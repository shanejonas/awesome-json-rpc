# awesome-json-rpc
Curated list of JSON-RPC resources.

## Official

- [JSON-RPC - Wikipedia](https://en.wikipedia.org/wiki/JSON-RPC) - Informative JSON-RPC Wikipedia article.
- [JSON-RPC](https://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
- [JSON-RPC.info](https://json-rpc.info/) - Historical use cases of JSON-RPC.
- [JSON-RPC Google Group](https://groups.google.com/forum/#!forum/json-rpc) - Some useful historical conversations around JSON-RPC.

## Libraries

- Javascript
  - [Jayson](https://github.com/tedeh/jayson) - Jayson is a simple but featureful JSON-RPC 2.0/1.0 client and server for node.js 
  - [multi-transport-jsonrpc](https://www.npmjs.com/package/multitransport-jsonrpc) - Provides a JSON-RPC solution for both the traditional HTTP scenario as well as for persistent, raw TCP connections. 
  - [mqtt-json-rpc](https://github.com/rse/mqtt-json-rpc) - JSON-RPC over mqtt
  - [pmrpc](https://github.com/statianzo/pmrpc) - JSON-RPC over html5 postMessage
  - [node-mole-rpc](https://github.com/koorchik/node-mole-rpc) - Tiny transport agnostic JSON-RPC 2.0 client and server which can work everywhere. NodeJs, Browser, Electron. On any transport; Even custom.
    - [node-mole-rpc-transport-mqtt](https://github.com/koorchik/node-mole-rpc-transport-mqtt) - MQTT transport for Mole-RPC (JSON RPC library)
    - [node-mole-rpc-transport-eventemitter](https://github.com/koorchik/node-mole-rpc-transport-eventemitter) - Event Emitter Mole RPC (JSON RPC library) transport

    - [node-mole-rpc-transport-ws](https://github.com/koorchik/node-mole-rpc-transport-ws) - WebSocket(ws) transport for Mole-RPC (JSON RPC library)
    - [node-mole-rpc-transport-webworker](https://github.com/koorchik/node-mole-rpc-transport-webworker) - Easy way to communicate with webworker using Mole-RPC (JSON RPC library)

- Swift
  - [JSONRPCKit](https://github.com/bricklife/JSONRPCKit) - A type-safe JSON-RPC 2.0 library purely written in Swift.
- .NET
  - [Microsoft/vs-streamjsonrpc](https://github.com/Microsoft/vs-streamjsonrpc) - The StreamJsonRpc library offers JSON-RPC 2.0 over any .NET Stream, WebSocket, or Pipe. With bonus support for request cancellation, client proxy generation, and more.
  - [JsonRpc.Router](https://github.com/edjCase/JsonRpc) - A .NetStandard 2.0 IRouter implementation for Json Rpc v2 requests for Microsoft.AspNetCore.Routing.
  - [JSON-RPC.NET](https://github.com/Astn/JSON-RPC.NET) - JSON-RPC.Net is a high performance Json-Rpc 2.0 server, leveraging the popular JSON.NET library. Host in ASP.NET, also supports sockets and pipes, oh my!
- Nim
  - [nim-json-rpc](https://github.com/status-im/nim-json-rpc) - Nim library for implementing JSON-RPC clients and servers
- Golang
  - [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0 in golang
- Python
  - [pavlov99](https://github.com/pavlov99/json-rpc) - JSON-RPC 1/2 transport implementation. Supports python 2/3 and pypy.
- PHP
  - [EvilScott/junior](https://github.com/EvilScott/junior) - PHP client/server library for JSON-RPC 2.0
- C
  - [cesanta/mjson](https://github.com/cesanta/mjson) - C/C++ JSON parser, emitter, JSON-RPC engine for embedded systems
- Ruby
  - [helios-technologies/json-rpc](https://github.com/helios-technologies/json-rpc) - Implementation of JSON RPC 2.0 protocol. It allows you to create easily a json rpc server in pure Rack, in Rails, or asynchronous using Thin and EventMachine.

## Framework Integrations

- [Loopback JSON-RPC connector](https://loopback.io/doc/en/lb2/JSON-RPC-connector.html)
- [Django JSON-RPC](https://github.com/samuraisam/django-json-rpc)

## Tools

- [ApEye.org](https://apeye.org) - APEye is a jQuery widget for issuing HTTP requests
- [JSON-RPC 2.0 Shell](http://software.dzhuvinov.com/json-rpc-2.0-shell.html) - Interactive RPC shell for rapid querying, testing and
debugging of JSON-RPC 2.0 web services

### Interface Description

- [open-rpc/spec](https://github.com/open-rpc/spec) - A specification for a standard, programming language-agnostic interface description for JSON-RPC 2.0 APIs. 
- [open-rpc/meta-schema](https://github.com/open-rpc/meta-schema) - JSON Schema file representing the open-rpc specification.
- [open-rpc/playground](https://github.com/open-rpc/playground) - A play to play around with open-rpc.
- [open-rpc/editor-extensions-vscode](https://github.com/open-rpc/editor-extensions-vscode) - A vscode extension to provide validation and auto completion for open-rpc documents.
- [open-rpc/generator-client](https://github.com/open-rpc/generator-client) - Mono repo for the client generators for each target language 
- [open-rpc/generator-docs](https://github.com/open-rpc/generator-docs) - Generate documentation from your open-rpc document
- [open-rpc/examples](https://github.com/open-rpc/examples) - Collection of example open-rpc documents

#### Uses of JSON-RPC

- [Arm mbed IoT Platform](https://cloud.mbed.com/docs/current/connecting/json-rpc.html#protocol-translator-register)
- [Bitcoin](https://en.bitcoinwiki.org/wiki/JSON-RPC)
- [Dash](https://github.com/dashpay/dash)
- [Dogecoin](https://github.com/dogecoin/dogecoin)
- [Ethereum Classic](https://github.com/ethereumproject/wiki/wiki/JSON-RPC)
- [Ethereum](https://github.com/ethereum/wiki/wiki/JSON-RPC)
- [FreeIPA](https://www.freeipa.org)
- [Kodi](https://kodi.wiki/view/JSON-RPC_API)
- [Litecoin](https://github.com/litecoin-project/litecoin)
- [Microsoft Language Server](https://docs.microsoft.com/en-us/visualstudio/extensibility/language-server-protocol?view=vs-2017)
- [Microsoft SQL Tools Service](https://github.com/Microsoft/sqltoolsservice/)
- [Monero](https://github.com/monero-project/monero)
- [OpenDaylight](https://www.opendaylight.org/)
- [PPIO](https://www.pp.io)
- [Qtum](https://qtumproject.github.io/qtumjs-doc/)
- [Quorum](https://github.com/jpmorganchase/quorum)
- [RANDOM.ORG](https://api.random.org/json-rpc/1/)
- [Ripple](https://developers.ripple.com/get-started-with-the-rippled-api.html)
- [Tarantool](https://github.com/tarantool/nginx_upstream_module)
- [Tezos](https://tezos.gitlab.io/alphanet/tutorials/rpc.html)
- [Visual Studio Language Server Extensions](https://code.visualstudio.com/api/language-extensions/language-server-extension-guide)
- [Zcash](https://github.com/zcash/zcash)
