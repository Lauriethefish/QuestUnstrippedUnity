# Quest Unstripped Unity
This repo contains versions of `libunity.so` built for il2cpp arm64-v8a, that have none of their code stripped.
`index.json` contains a map of which games need which SO file.

Replacing the `libunity.so` during modding makes working with the code later much easier, since you can call any Unity function and not worry about stripping.