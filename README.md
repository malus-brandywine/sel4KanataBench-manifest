### sel4KanataBench-manifest

Manifest of the sel4KanataBench project

### Getting the Project

```
mkdir sel4KanataBench
cd sel4KanataBench
repo init -u https://github.com/malus-brandywine/sel4KanataBench
repo sync
mkdir build
cd build
../init-build.sh -DAARCH64=TRUE -DPLATFORM=tx1
ninja
```
</br>
