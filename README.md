### sel4KanataBench-manifest

</br>

Manifest of the sel4KanataBench project

#### Getting the Project

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

#### Configuration

`main.c` defines configuration parameters of the benchmark.</br></br>
There are default parameters:

```
/* Init Test size */
#define KB_INIT_TEST_SIZE           1

/* Delta */
#define KB_DELTA                    1

/* Group size, Number of Tests in a Group */
#define KB_GROUP_SIZE               30

/* Number of Test Groups in a sequence*/
#define KB_N_GROUPS                 5
```

