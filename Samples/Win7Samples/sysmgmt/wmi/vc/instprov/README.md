



## ENV

- Win11
- Visual Studio 2022



## Build Failed Output

The project is old and vs2022 failed to compile directly

![image-20241203150625544](./assets/image-20241203150625544.png)



## Solution, The vs2022 build can be successful

Try to add `vcruntime.lib` and `ucrt.lib` to your additional dependencies. **===> properties->Linker->Input->Additional Dependencies**



if debug module, using  `vcruntimed.lib` and`ucrtd.lib`

![image-20241203150810932](./assets/image-20241203150810932.png)



![image-20241203151123846](./assets/image-20241203151123846.png)