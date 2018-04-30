# Bus Spider fusesoc generated Quartus project

The main Bus Spider repo is https://github.com/miet-riscv-workgroup/de10-nano-bus-spider

This repo contains only fusesoc generated Quartus project just for demonstration.

For building project from the de10-nano-bus-spider-bld-quartus directory do the following (change Quartus installation path QP if necessary):

```
QP=/opt/altera/17.1/quartus
export PATH=$PATH:$QP/sopc_builder/bin:$QP/bin

make -C bld-quartus
```
