<!---
  Licensed to the Apache Software Foundation (ASF) under one
  or more contributor license agreements.  See the NOTICE file
  distributed with this work for additional information
  regarding copyright ownership.  The ASF licenses this file
  to you under the Apache License, Version 2.0 (the
  "License"); you may not use this file except in compliance
  with the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing,
  software distributed under the License is distributed on an
  "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  KIND, either express or implied.  See the License for the
  specific language governing permissions and limitations
  under the License.
-->

## Generated Code

The prost/tonic code can be generated by running `./regen.sh`, which in turn invokes the Rust binary located in [gen](./gen)

This is necessary after modifying the protobuf definitions or altering the dependencies of [gen](./gen), and requires a
valid installation of [protoc] (see [installation instructions] for details).

```bash
./regen.sh
```

[protoc]: https://github.com/protocolbuffers/protobuf#protocol-compiler-installation
[installation instructions]: https://datafusion.apache.org/contributor-guide/getting_started.html#protoc-installation
