Dispatcher is just an interface with a dispatch method for invoking methods on an instance.
This interface hides implementation details for concrete method invokers for a JsonRpc service.
Its presence as a separate package is solely to avoid circular references.

MIT License.

## Usage

A simple usage example:

```dart
import 'package:rpc_dispatcher/rpc_dispatcher.dart';
```

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/jwashin/rpc_dispatcher/issues

