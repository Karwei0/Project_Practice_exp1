# 1 实验内容
- 安装Android Studio 4.1之上的版本，更好的支持TensorFlowLite
- 安装JupyterNotebook和相关的Python环境，后续用于机器学习模型构建。
- 安装VisualStudioCode代码编辑器
- 探索上述软件的使用，将安装过程以Markdown语法描述，并上传至Github(或Gitee)
# 2 环境安装
## 2.1 安装 Android Studio
直接进入官网进行选择合适的版本进行下载。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699252260-5e223355-4e2b-4dbd-abe3-411b2d24cbb0.png#averageHue=%235d976e&clientId=u0b04c272-219e-4&from=paste&height=617&id=ub71a471d&originHeight=849&originWidth=1885&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=392356&status=done&style=none&taskId=u98796202-41c8-4464-bf23-dcf41c00a17&title=&width=1370.909090909091)
下载完毕之后，双击运行。
点击 Next 进入下一步。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699435131-a418592e-8d6a-4075-b91d-ac68f39425e7.png#averageHue=%23c3c2c1&clientId=u0b04c272-219e-4&from=paste&height=491&id=u1996cf9b&originHeight=675&originWidth=859&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=219533&status=done&style=none&taskId=u7a722678-8af7-48ad-ad38-943762516d2&title=&width=624.7272727272727)
选择虚拟设备，然后继续 next。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699571420-c578b5c0-7005-4670-9cbe-b82fec40ff36.png#averageHue=%23edecec&clientId=u0b04c272-219e-4&from=paste&height=487&id=uae1fba2a&originHeight=670&originWidth=860&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=86259&status=done&style=none&taskId=u3fd89998-037f-484f-9614-ce8fc013be4&title=&width=625.4545454545455)
选择软件的安装路径，可以通过 browse 选择其他路径。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699598729-e433487a-cd22-403d-82dd-c83819ffdd1d.png#averageHue=%23edecec&clientId=u0b04c272-219e-4&from=paste&height=482&id=u5774f6c9&originHeight=663&originWidth=857&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=167683&status=done&style=none&taskId=u1e0820df-bc51-46e4-b20e-a01b2e4e999&title=&width=623.2727272727273)
然后是关于快捷方式的创建等，选择完毕之后点击 install。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699616044-4a2a5a78-2e6c-4f03-9dd3-cef388707516.png#averageHue=%23f1f0ef&clientId=u0b04c272-219e-4&from=paste&height=473&id=u99a946d4&originHeight=650&originWidth=861&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=248197&status=done&style=none&taskId=u6cf34b7e-c25d-41cc-8692-94269e5baa3&title=&width=626.1818181818181)
等待安装。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699631457-e49eada9-ceed-4854-bd39-72ef3174cb17.png#averageHue=%23ececeb&clientId=u0b04c272-219e-4&from=paste&height=345&id=u22f7a774&originHeight=474&originWidth=801&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=73006&status=done&style=none&taskId=ud8ce03d5-acea-424f-acbf-6b485c4436d&title=&width=582.5454545454545)
然后点击 finish。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699652276-3cae9a5e-9af2-41a4-8154-db1372790ac1.png#averageHue=%23ececec&clientId=u0b04c272-219e-4&from=paste&height=355&id=ub2496aeb&originHeight=488&originWidth=831&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=66449&status=done&style=none&taskId=u103498b4-4cea-4e5b-b8b4-01445720713&title=&width=604.3636363636364)
接着，会让我们进行设置方面的安装。由于是第一次安装，因此就不用 import 外部的设置。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699696254-26dbac2f-96c5-47c2-8945-8b6144f137eb.png#averageHue=%23f2f1f1&clientId=u0b04c272-219e-4&from=paste&height=169&id=uc2cc2712&originHeight=232&originWidth=672&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=49485&status=done&style=none&taskId=ue97c9578-6786-4cc8-aa2b-1c4fc1b4825&title=&width=488.72727272727275)
点击 next。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699729149-53ad1dbd-4588-4b4c-a127-ca522bc7cbbd.png#averageHue=%23545a5a&clientId=u0b04c272-219e-4&from=paste&height=350&id=ua76145cb&originHeight=481&originWidth=835&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=85381&status=done&style=none&taskId=u00e726ea-6a32-4687-9643-7f4cc9ce6bf&title=&width=607.2727272727273)
可以自己定制，也可以选择标准的，这边我们选择 standard。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699742322-eb3f751b-392a-45df-bdb6-3bfdf59c2073.png#averageHue=%23565c5d&clientId=u0b04c272-219e-4&from=paste&height=344&id=u3ffeddad&originHeight=473&originWidth=821&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=77984&status=done&style=none&taskId=u88683c76-1f94-44a5-868f-3ae09d00259&title=&width=597.0909090909091)
选择环境的JDK。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699756183-804f90c0-f0bf-4114-b011-b5d46a6ed5ff.png#averageHue=%23525758&clientId=u0b04c272-219e-4&from=paste&height=346&id=ucdcf5965&originHeight=476&originWidth=838&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=75748&status=done&style=none&taskId=u574f0172-a014-472b-8bb6-7091ac0fae2&title=&width=609.4545454545455)
选择目录安装SDK等组件。因为是第一次启动，软件会请求我们选择目录下载需要的组件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713772666172-7abc754b-4ef5-473c-89db-170e1e15b23b.png#averageHue=%233bab57&clientId=ucc018125-7d42-4&from=paste&height=375&id=uc0395cca&originHeight=515&originWidth=810&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=94935&status=done&style=none&taskId=u9496ad5b-57fd-41be-9eec-e2c57ce9c35&title=&width=589.0909090909091)
选择合适的路径安装。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713772728445-7a8ebde3-4606-4738-954d-7343cfc02c47.png#averageHue=%239fcae1&clientId=ucc018125-7d42-4&from=paste&height=544&id=X4Bzh&originHeight=748&originWidth=979&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=98479&status=done&style=none&taskId=u8e5c2c66-a28c-4cea-98c8-86aa083906c&title=&width=712)
检查安装详情。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713772758194-a8cce889-d7f4-41f5-8045-86c49b51ec77.png#averageHue=%239ecbe1&clientId=ucc018125-7d42-4&from=paste&height=540&id=NvCCy&originHeight=743&originWidth=990&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=69104&status=done&style=none&taskId=ub70d2d1d-39bd-4c36-abae-f0f33cd6bf9&title=&width=720)
同意协议。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713772767137-44664750-3812-417f-8d8b-26508675c272.png#averageHue=%23b6d8e3&clientId=ucc018125-7d42-4&from=paste&height=540&id=un0jr&originHeight=743&originWidth=981&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=110724&status=done&style=none&taskId=u8cea0d41-4e72-4dbb-9be8-b128aefdd59&title=&width=713.4545454545455)
然后是等待安装。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713772778506-7c7d66ec-bf95-4a59-a3a1-a60c7e6c412c.png#averageHue=%239cc6e0&clientId=ucc018125-7d42-4&from=paste&height=535&id=G9OHX&originHeight=735&originWidth=982&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=40120&status=done&style=none&taskId=u995f6a39-9191-4723-951a-0d3985b8786&title=&width=714.1818181818181)
下载完成之后，点击 finish。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713773588380-e31f8999-6862-432b-999f-efc3286f9655.png#averageHue=%23f5eeda&clientId=ucc018125-7d42-4&from=paste&height=548&id=uec1ab6d1&originHeight=753&originWidth=1007&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=100205&status=done&style=none&taskId=u28d05f99-9909-436a-bdc1-56316c7c4fd&title=&width=732.3636363636364)
然后启动程序，新建一个项目
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713700127069-20ec98e7-b90e-4fbb-80e5-8501c2dff853.png#averageHue=%23e3e0c5&clientId=u0b04c272-219e-4&from=paste&height=585&id=u6e2b1ce3&originHeight=804&originWidth=984&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=59907&status=done&style=none&taskId=ufa57e332-cf16-4907-850f-b1e4907233a&title=&width=715.6363636363636)
选择空白。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699930329-14b45251-fa6c-457c-aee8-4fa10ace6648.png#averageHue=%23eaf1f3&clientId=u0b04c272-219e-4&from=paste&height=439&id=u70087f92&originHeight=813&originWidth=1123&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=99378&status=done&style=none&taskId=u7db556c8-8c52-4153-96a7-fd0390c7372&title=&width=605.8181762695312)
选择安装路径以及对应的SDK，注意这边的安装路径下不能有中文（non-ASCII character）。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713700209240-69a049da-c5bb-438c-8e24-63dc9f60d988.png#averageHue=%23f3f5f8&clientId=u0b04c272-219e-4&from=paste&height=591&id=ue68f7ef4&originHeight=813&originWidth=1126&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=80952&status=done&style=none&taskId=u7b2153c5-9cd7-45bc-b956-c0eb0775eee&title=&width=818.9090909090909)
最后进入项目，等待 gradle 等依赖下载和更新。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713773660894-dd376a24-d7fd-439f-9625-50ab55fee638.png#averageHue=%23fcfbfa&clientId=ucc018125-7d42-4&from=paste&height=136&id=u78cad6f4&originHeight=187&originWidth=492&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=15569&status=done&style=none&taskId=u1b00c49e-6fb6-4982-aef0-51bac8c2499&title=&width=357.8181818181818)
直到下载完毕出现如下如下提示，就算创建成功。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713774010969-409c7aa4-66bf-4771-89b5-0249aaf0c793.png#averageHue=%23efe7c7&clientId=u651b4258-5252-4&from=paste&height=579&id=ued3434a8&originHeight=796&originWidth=1376&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=139603&status=done&style=none&taskId=u9b39da70-2250-46fc-87b5-4ec02853b5f&title=&width=1000.7272727272727)
## 2.2 安装 Anocoda
在官网上找到合适的版本，并填写邮箱获取下载地址。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713701905723-c6800d3d-7755-4c5c-a997-bbacbe9d84c0.png#averageHue=%23fdfafa&clientId=u0b04c272-219e-4&from=paste&height=684&id=ue218a165&originHeight=941&originWidth=1879&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=669215&status=done&style=none&taskId=u5519efd9-a49b-4d06-ab83-e09380faa6f&title=&width=1366.5454545454545)
在个人的邮箱内点击地址进行下载。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713701928403-4ddc36a1-b4c7-4597-87da-2c46b83fa77d.png#averageHue=%23faf9f8&clientId=u0b04c272-219e-4&from=paste&height=319&id=u0690226c&originHeight=439&originWidth=555&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=29584&status=done&style=none&taskId=u54736d55-8a4e-422f-b1a6-0f83d1c4357&title=&width=403.6363636363636)
下载完毕之后，启动程序。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713701960115-b9e1f3a1-5fbd-4c9e-b7f7-cbe4493f8b14.png#averageHue=%23f9f7f6&clientId=u0b04c272-219e-4&from=paste&height=554&id=u8f3198dc&originHeight=762&originWidth=986&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=275896&status=done&style=none&taskId=ub1c66da3-2065-4960-bba9-4a6861c4b51&title=&width=717.0909090909091)  
选择安装路径。  
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702041878-ed75f8c8-3aff-4636-9417-297ad2d86ff6.png#averageHue=%23ececec&clientId=u0b04c272-219e-4&from=paste&height=399&id=ube9da551&originHeight=548&originWidth=711&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=78266&status=done&style=none&taskId=uda6255d2-07a9-479d-bc3e-6aae5e2de7e&title=&width=517.0909090909091)
这边会检查机子是否已经有python解释器，如果有请务必勾选。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702113993-433d2e56-0674-49e6-9295-001461c9128e.png#averageHue=%23e7e7e7&clientId=u0b04c272-219e-4&from=paste&height=393&id=u765fe10e&originHeight=540&originWidth=702&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=99051&status=done&style=none&taskId=u85c1e431-1922-4f3d-88df-7dfd6e37450&title=&width=510.54545454545456)  
最后等待安装，图为安装完毕时候的界面。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702196998-e59c791a-578a-4b4d-9323-e9a88a8a7236.png#averageHue=%23f5f5f5&clientId=u0b04c272-219e-4&from=paste&height=401&id=u030c8d58&originHeight=552&originWidth=704&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=86561&status=done&style=none&taskId=u146ca6d3-fcd2-4c55-ae4e-b33dc1913ed&title=&width=512)  
然后我们可以启动 anocado，或者在 cmd 键入 conda 查看是否安装成功。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713704761771-36e51754-6612-4204-aaa7-5f4719f03a24.png#averageHue=%23161413&clientId=u0b04c272-219e-4&from=paste&height=177&id=u5ebfb633&originHeight=243&originWidth=751&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=24981&status=done&style=none&taskId=ufae70dec-bef0-405a-b2de-d93d43cc933&title=&width=546.1818181818181)
## 2.3 安装 Jupyter
在安装了 anocoda 之后 我们可以在 cmd 上输入如下的指令，利用 Anocoda 帮我们安装 Juypter notebook。  
`conda install jupyter notebook`  
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702368228-27fe8a22-4309-43e0-98ce-714767f67990.png#averageHue=%23464545&clientId=u0b04c272-219e-4&from=paste&height=170&id=u4a11c63c&originHeight=234&originWidth=566&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=16768&status=done&style=none&taskId=u02d74460-d37f-4a0f-bc47-4984553ddfb&title=&width=411.6363636363636)  
  安装完毕之后，可以在 cmd 输入 jupyter notebook 或者在 Anocoda 上点击对应图标的 lauch。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702406849-d31daec8-d6d4-415a-9216-709b75ef15b7.png#averageHue=%23211d1a&clientId=u0b04c272-219e-4&from=paste&height=359&id=u9efeaed9&originHeight=493&originWidth=1101&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=115523&status=done&style=none&taskId=u9d7af86e-de78-4ae1-8bd7-ad3a0e12225&title=&width=800.7272727272727)
最后会以浏览器窗口的形式进入。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702420056-d47cdb0d-9667-49db-a15a-5bc1fcf99f2f.png#averageHue=%23f9f8f8&clientId=u0b04c272-219e-4&from=paste&height=672&id=u610aa34a&originHeight=924&originWidth=1903&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=71267&status=done&style=none&taskId=u815960e9-120f-4e49-9911-d738b219a38&title=&width=1384)
## 2.3 安装 VS code
由于本机之前已经安装了 vscode，因此我们只需要在vscode上配置python和jupyter的环境即可。
首先是关于 python 的插件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703517317-23287ea0-8c7f-4b62-a322-be2a9c8ca5ba.png#averageHue=%23faf9f6&clientId=u0b04c272-219e-4&from=paste&height=527&id=u949f69f5&originHeight=725&originWidth=1412&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=137207&status=done&style=none&taskId=u3cfca7db-70d3-42e5-89ef-997ab2397f9&title=&width=1026.909090909091)
然后可以在 preference 的 setting 选择 python 解释器。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703541713-184327a5-877e-4082-bccc-a9bfab531ada.png#averageHue=%23f6f6f6&clientId=u0b04c272-219e-4&from=paste&height=516&id=ueea49b40&originHeight=709&originWidth=1059&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=89780&status=done&style=none&taskId=u93bbbf96-cd32-4f6b-a45b-9b62c8cb5ca&title=&width=770.1818181818181)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703693998-92f3c139-3492-4d1d-bd26-370a21779b38.png#averageHue=%23f1f1f1&clientId=u0b04c272-219e-4&from=paste&height=198&id=u5a77737d&originHeight=272&originWidth=1117&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=31520&status=done&style=none&taskId=ud9b3b620-2267-4a71-9b1b-d9028abd95e&title=&width=812.3636363636364)
同时也可以在 search 栏上键入python:Create Environment 创建虚拟环境。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703794821-b2eb6713-83d6-4df9-9465-f374bb8364b4.png#averageHue=%23f0eceb&clientId=u0b04c272-219e-4&from=paste&height=257&id=udbf555be&originHeight=353&originWidth=1079&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=48690&status=done&style=none&taskId=u1c4fa961-a1c4-4d4e-aef1-83b945293d9&title=&width=784.7272727272727)

---

然后是 Jupyter 的插件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703827320-79a93447-bca0-43d9-9667-6499476dc3be.png#averageHue=%23fbfaf9&clientId=u0b04c272-219e-4&from=paste&height=567&id=ub97926b6&originHeight=780&originWidth=1445&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=139698&status=done&style=none&taskId=uf84945cb-7f78-42e5-9d42-03db6cb83d2&title=&width=1050.909090909091)
最后，我们可以创建一个扩展名为 ipynb 的文件，写一些简单的代码进行测试。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713703902976-629872eb-55c9-4aea-b3e7-61b2ad5e1628.png#averageHue=%23f7f6f6&clientId=u0b04c272-219e-4&from=paste&height=344&id=udd656f67&originHeight=473&originWidth=1139&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=56373&status=done&style=none&taskId=u696a8c09-be61-4571-9c9a-32332dfb76c&title=&width=828.3636363636364)
同时，为了实现 Anocoda 和 VScode 的联动（也可以与 PyCharm），我们可以在 Anocoda 的 preference 将本机vscode 的启动地址填入。  
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713774133560-9a57b720-29e1-4e8f-be88-34b7875ec8f0.png#averageHue=%23f1ecec&clientId=u651b4258-5252-4&from=paste&height=436&id=u11e4874a&originHeight=600&originWidth=615&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=32404&status=done&style=none&taskId=u980dd3bd-ad41-469e-8abf-7054afd4fe0&title=&width=447.27272727272725)
## 2.4 安装 Python
由于本机之前有且只有 python 3.11 一个 python 解释器，因此在安装 Anocoda 的时候需要将该 python 解释器作为默认的解释器，如下图所示：
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713702113993-433d2e56-0674-49e6-9295-001461c9128e.png#averageHue=%23e7e7e7&clientId=u0b04c272-219e-4&from=paste&height=393&id=BI5p6&originHeight=540&originWidth=702&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=99051&status=done&style=none&taskId=u85c1e431-1922-4f3d-88df-7dfd6e37450&title=&width=510.54545454545456)
但图中显示的 python 是 3.7 的，与上文描述不符合，这里只展示对应的场景而已。程序会根据电脑环境检查出其对应的 python 环境。
安装之后，我们可以在 cmd 中键入 python ，查看 python 环境是否存在。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713704071218-c5e154d2-5cc4-4a65-b74a-cef5221a366c.png#averageHue=%23161513&clientId=u0b04c272-219e-4&from=paste&height=95&id=ucc7d3ec0&originHeight=130&originWidth=791&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=12931&status=done&style=none&taskId=u38540415-94e7-48e4-b6a1-a6cc8bed8e5&title=&width=575.2727272727273)
# 3 注意事项
## 3.1 安卓项目的路径问题
当我们在 Android studio 中创建安卓项目的时候，我们需要将项目放在一个全是英文的路径（non-ASCII characters)之下，否则会出错。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38674938/1713699976663-fdcca0d7-81ac-4cc1-a040-c703b785f3d1.png#averageHue=%23f3f5f8&clientId=u0b04c272-219e-4&from=paste&height=596&id=xt3GX&originHeight=819&originWidth=1124&originalType=binary&ratio=1.375&rotation=0&showTitle=false&size=76282&status=done&style=none&taskId=u9cdf01c9-226a-41ea-a2a4-87d7dcc442b&title=&width=817.4545454545455)
