# Alipay ZeroSdk

> һ������������֧����ת�˹�����

---

### �������ʲô��

������Ӧ����ֱ����ת��֧����ת�˵Ľ��棬�ȸ���ճ��֧�����˺Ÿ������š���ȫ��
Ȼ�����Ĺ��ܾ���ֱ����ת��ת�˽��棬������֧�������


### Ϊʲô���������

֧�����Ľӿڻ������Ƕ���ҵ�û����ŵģ�����ֻ����һ��������ڵĸ��˶�����������˵û��ҪȥŪ��ô�ණ����


### ��ô�ã�

����Ҫ׼��һ����ά�룬��ϸ�������Ķ��ҵĲ��� [**http://blog.feng.moe/2016/08/29/alipay-zerosdk/**](http://blog.feng.moe/2016/08/29/alipay-zerosdk/)

�Ӷ�ά���л�ȡ������Ĳ�����һ��Ӣ�����ֻ�ϵ��ַ�������������ʼ���������

�� Gradle ������������

    allprojects {
        repositories {
            jcenter()
            maven {
                url "https://jitpack.io"
                }
            }
    }

    dependencies {
        compile 'moe.feng:AlipayZeroSdk:1.0'
    }

AlipayZeroSdk ֻ��һ���࣬�����ڿ�ʼʹ��ת�˽�����ת֮ǰ����ü��һ���û��Ƿ�װ֧�����ͻ��ˣ��Ա�������ͬ��Ӧ�Է�ʽ��

`AlipayZeroSdk.hasInstalledAlipayClient(Context)`


ȷ�Ϸ��ؽ��Ϊ true �����ǾͿ�����ת��ת�˽����ˣ���ʱ�����Ҫ�Ӷ�ά���ȡ���Ĳ�����

`AlipayZeroSdk.startAlipayClient(Context, String �Ӷ�ά���ȡ���Ĳ���)`


֮����ܿ���ת�˽��������ˣ�������Щ�����㻹���Բ�ѯ֧����Ӧ�õİ汾�ţ���û��ʲô�þ����ˡ�����


### Demo

<a href="./art/screenshot.png"><img src="./art/screenshot.png" width="40%"/></a>


����Դ� [Github Releases](https://github.com/fython/AlipayZeroSdk/releases) ���ص� Demo �İ�װ��

### ��ϵ��

����΢����[@FungGo](http://weibo.com/fython)

Email��fython#163.com

Telegram��@fython


����Ļ�����֧��һ���ҡ� ֧������316643843#qq.com

### License

```
Copyright 2016 Fung Go (fython)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0 
    
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License. 
```