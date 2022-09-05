# OccAndThreejs

编译occ并且在threejs中使用

#编译occ步骤如下

1.配置emscritption：https://ihaier.feishu.cn/docs/doccnwI3tlLwsbjCpuufMKGDH0d

2.编译occ：https://ihaier.feishu.cn/docs/doccnYpn6LJ7LDSx15f517wvgYc，由于编译

    需要写入大量.a库，方便起见编写 emcc_cmd.js 脚本使用方法:
  
    cd occ_threejs
  
    node emcc_cmd.js
  
    注意：编译和执行emcc_cmd.js时间较长，请耐心等待
  
3.运行demo

    cd occ_threejs
  
    python -m http.server 8090
  
    浏览器中输入：http://localhost:8090/
