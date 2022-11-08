# QproRiscVTemplate

## Toolchain

| name      | url                                                          |
| --------- | ------------------------------------------------------------ |
| riscv-gcc | https://occ.t-head.cn/community/download?id=4090445921563774976 |
| qemu      | https://occ.t-head.cn/community/download?id=4108987827910414336 |

1. download and extract them to `/opt`

   1. riscv-gcc: `/opt/gcc-riscv`
   2. qemu: `/opt/qemu`

2. add `$PATH`

   ```sh
   export PATH=$PAHT:/opt/gcc-riscv/bin:/opt/qemu/bin
   ```

## Usage

just use `qrun`!
