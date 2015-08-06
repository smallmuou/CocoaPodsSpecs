# CocoaPodsSpecs

## 概述
该Repo是构建CocoaPods的私有Specs，主要为了解决官方CocoaPods的更新慢的问题.

## 添加第三方库
通过spec-sync.sh将CocoaPods的Specs同步到CocoaPodsSpecs中.

<pre>
./spec-sync.sh AFNetworking 2.5.4
</pre>

## Podfile
修改Podfile的source
<pre>
source 'https://github.com/smallmuou/CocoaPodsSpecs.git'
</pre>
之后执行`pod install`速度秒杀官方的Specs