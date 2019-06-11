# Space Pong

For CSE 190

by Alan Mai

## Source Code

```
git clone https://github.com/Kawaamai/CSE190_FinalProjectTestServer.git
```

populate `yojimbo` and `PhysX`

```
git submodule update --init --recursive
```

build with `premake5 solution`, then build `yojimbo` as 

build `PhysX`: build all of `PhysXSDK` as:

- `release -> Runtime Library-> Multi-threaded Dll (/MD)`
