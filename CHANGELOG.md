# Changelog

## [0.18.0](https://github.com/dougefla/BangumiKomga/compare/v0.17.0...v0.18.0) (2025-10-06)


### Features

* Bangumi 匹配算法切换为 TheFuzz ([f89cd07](https://github.com/dougefla/BangumiKomga/commit/f89cd07644946b90cab0e403d6086dcba3e69e21))
* prepare for api key ([ea9d9e8](https://github.com/dougefla/BangumiKomga/commit/ea9d9e8d2e25d94e215215ce8ba673599b7c2939))
* support get vol or chap number ([cba4e49](https://github.com/dougefla/BangumiKomga/commit/cba4e495797f5e82e3f69e108740856d8a71c2e5))
* 为logger添加调试器感知功能 ([#93](https://github.com/dougefla/BangumiKomga/issues/93)) ([c486289](https://github.com/dougefla/BangumiKomga/commit/c4862894b2fe47b7a531dca2ec3ec6a271041f3d))
* 为存在`Bangumi`链接的系列在排序标题中添加首字母 ([9bee000](https://github.com/dougefla/BangumiKomga/commit/9bee000666e52f6858ce3023035493666efe643d))
* 优化刮削逻辑，移除`FORCE_REFRESH_LIST`配置 ([c497d30](https://github.com/dougefla/BangumiKomga/commit/c497d3076b0645166e04b7bbfd1e5573e8ed6b18))
* 使用 FUZZ 对 bgm 搜索结果进行过滤和排序 ([b2d1962](https://github.com/dougefla/BangumiKomga/commit/b2d19622cfb29534a26539840ad9afe3e05561df))
* 单册匹配时支持罗马数字 ([2c2651b](https://github.com/dougefla/BangumiKomga/commit/2c2651b9de220b271c5c3993bd094cf1b62d0351)), closes [#26](https://github.com/dougefla/BangumiKomga/issues/26)
* 单册支持 cbl ([96875a2](https://github.com/dougefla/BangumiKomga/commit/96875a2b19c3203df4e5239fb2317e3222f589d6))
* 完善年龄限制逻辑 ([5e9af4f](https://github.com/dougefla/BangumiKomga/commit/5e9af4f9dce50a3fc1e27804a91ceeee42463f05))
* 支持更新元数据时替换单册封面 ([d31a0b7](https://github.com/dougefla/BangumiKomga/commit/d31a0b7fa6f5e05591c2ee6082026a28b1b25684))
* 支持更新元数据时替换系列封面 ([02b853f](https://github.com/dougefla/BangumiKomga/commit/02b853f88773f1e52c83f942219ba84fa310ed92))
* 支持系列在英文字母导航中分类显示 ([7c6996d](https://github.com/dougefla/BangumiKomga/commit/7c6996db55be10f7d3fb0d1acbaa146cf8655b74))
* 支持网页生成配置 ([753d4cf](https://github.com/dougefla/BangumiKomga/commit/753d4cf45f103e1f89792406603b7ef2468678f0))
* 新增 bgm 数据源工厂 ([3a6f4c8](https://github.com/dougefla/BangumiKomga/commit/3a6f4c8cdd9943d810510398fb8aaccac23cb1dd))
* 新增komga收藏的新增、删除、搜索函数 ([d3556e5](https://github.com/dougefla/BangumiKomga/commit/d3556e515d78f9af6aebda42cfa7e5122f4e09d8))
* 新增通知功能 ([0eddf3f](https://github.com/dougefla/BangumiKomga/commit/0eddf3f31e6a7701e57fc703b6f2b5f665b3d584))
* 日志支持同时输出到文件和显示在 docker 日志窗口 ([84ac359](https://github.com/dougefla/BangumiKomga/commit/84ac359f472b2648d13d3470e48afca784c65411)), closes [#23](https://github.com/dougefla/BangumiKomga/issues/23)
* 添加 Archive 下载进度条 ([#103](https://github.com/dougefla/BangumiKomga/issues/103)) ([7c27ad7](https://github.com/dougefla/BangumiKomga/commit/7c27ad75e9a288e71996760c693309023949de4f))
* 添加 bangumi Archive 自动更新器 ([#54](https://github.com/dougefla/BangumiKomga/issues/54)) ([e0dff38](https://github.com/dougefla/BangumiKomga/commit/e0dff38840869986361c6bbe8f53800d35e97f64))
* 添加 bgm 条目平台及关联的枚举类 ([4a61017](https://github.com/dougefla/BangumiKomga/commit/4a61017fb2afc07c73896c45197a540df6ab557b))
* 添加`ARCHIVE_CHECK_INTERVAL`选项, 适配更新检查逻辑 ([#78](https://github.com/dougefla/BangumiKomga/issues/78)) ([05df29f](https://github.com/dougefla/BangumiKomga/commit/05df29f8d9f976b7a27dff03b0f55f4e8b3aa421))
* 添加`file_integrity_verifier()`并改进`update_archive()`的下载 ([#86](https://github.com/dougefla/BangumiKomga/issues/86)) ([1ea5e1c](https://github.com/dougefla/BangumiKomga/commit/1ea5e1c0b9c4f0dd2cbc24288655433998f46ccb))
* 添加`get_new_added_series()`函数, 以支持新增的`refresh_partial_metadata()` ([#64](https://github.com/dougefla/BangumiKomga/issues/64)) ([9f65a9f](https://github.com/dougefla/BangumiKomga/commit/9f65a9fe2817cff2fca5c7753da8c0e521341900))
* 添加`unittest`测试 ([#88](https://github.com/dougefla/BangumiKomga/issues/88)) ([44ed7c2](https://github.com/dougefla/BangumiKomga/commit/44ed7c28f3b07ac0dfe642547aac640ab64a795a))
* 添加Archive索引读取器 ([#60](https://github.com/dougefla/BangumiKomga/issues/60)) ([32a5ab3](https://github.com/dougefla/BangumiKomga/commit/32a5ab3e21f9ee532540d966d739086825ec5c34))
* 添加SSE API ([#81](https://github.com/dougefla/BangumiKomga/issues/81)) ([b386ed5](https://github.com/dougefla/BangumiKomga/commit/b386ed5cf94f7c73e8ef79edd5ef5abc14206adc))
* 添加了 `refreshMetadataServive` 轮询服务 ([#67](https://github.com/dougefla/BangumiKomga/issues/67)) ([6618cee](https://github.com/dougefla/BangumiKomga/commit/6618cee4ed881eeb5ce92275f53d6713d0b83d67))
* 添加启动准备函数, 防止用户端报错 ([#94](https://github.com/dougefla/BangumiKomga/issues/94)) ([af3063f](https://github.com/dougefla/BangumiKomga/commit/af3063faf352d0345bec47ae98676e62ec40726d))
* 添加基本的离线Archive元数据查询功能 ([#48](https://github.com/dougefla/BangumiKomga/issues/48)) ([e176d3c](https://github.com/dougefla/BangumiKomga/commit/e176d3ce5b812b80eb782a2a8797678765a13189))
* 添加新词汇 ([3ca2ac0](https://github.com/dougefla/BangumiKomga/commit/3ca2ac05f96cf8993837983b2ac7803178118170))
* 添加更多漫画语言类型 ([1781a75](https://github.com/dougefla/BangumiKomga/commit/1781a75bce2431824217b7676f6beb633f2bf4f7))
* 添加滑动窗口限流器&漏桶限流器 ([#68](https://github.com/dougefla/BangumiKomga/issues/68)) ([729763b](https://github.com/dougefla/BangumiKomga/commit/729763b9ab98d287432331991718b870fae0d586))
* 添加配置文件生成器 ([#107](https://github.com/dougefla/BangumiKomga/issues/107)) ([84589b9](https://github.com/dougefla/BangumiKomga/commit/84589b933b9e26f685edd5b87531d173d1f4f998))
* 网页版支持解析并加载本地配置 ([668e9e9](https://github.com/dougefla/BangumiKomga/commit/668e9e9907c83df30bf18a55a917f51fbef543ed))
* 适配配置文件生成器中改动的配置项 ([#109](https://github.com/dougefla/BangumiKomga/issues/109)) ([53ef75f](https://github.com/dougefla/BangumiKomga/commit/53ef75fddc078ce72b5aab2f1ed230d663d9b6ce))
* 配置项添加版本说明 ([38f4020](https://github.com/dougefla/BangumiKomga/commit/38f40205069f6131583129bf8cdf4ab2bd50b032))


### Bug Fixes

* fix:  ([c9738ca](https://github.com/dougefla/BangumiKomga/commit/c9738cacba6fb46fcb12169c1cb865df7621ae04))
* fix header ([a2b342b](https://github.com/dougefla/BangumiKomga/commit/a2b342be450d843eefcf869fe3928a768435d9fa))
* fuzz 算法计算时忽略大小写 ([654a66e](https://github.com/dougefla/BangumiKomga/commit/654a66ee8f9eed97505273bd9f6a96bb892cb4db))
* update thumbnail size to large for book metadata ([0380a8d](https://github.com/dougefla/BangumiKomga/commit/0380a8d3675cfeb772c3da8998553e4f227eae59))
* 一次性获取 komga 所有系列 ([ee1adc0](https://github.com/dougefla/BangumiKomga/commit/ee1adc06d410c0c677b177c286e2f2bde5bc9819))
* 上传封面前先检测是否已有海报 ([ebc429c](https://github.com/dougefla/BangumiKomga/commit/ebc429c8d1b4755d2fb0615be68578bbf69f803d))
* 不刮削无序号单行本 ([08d47fe](https://github.com/dougefla/BangumiKomga/commit/08d47fe42a79b2597b8f822450490d92b169a138))
* 使用最新 API ([07cbf1e](https://github.com/dougefla/BangumiKomga/commit/07cbf1ef365886813085efeb3d0b7dd31d7af8a5))
* 使用和系列封面一样的逻辑 ([5fa2fae](https://github.com/dougefla/BangumiKomga/commit/5fa2fae68d7901996b11630247e3bbb24dafd355))
* 修复 sse 库检查错误的问题 ([1f96230](https://github.com/dougefla/BangumiKomga/commit/1f96230ed089935aa32e79f689e51e0dc42b3172))
* 修复 sse 库检查错误的问题 ([33083df](https://github.com/dougefla/BangumiKomga/commit/33083df66a1e11ac6fbc270e159213833bc272b9))
* 修复`get_data_by_id()`的ID类型错误 ([#87](https://github.com/dougefla/BangumiKomga/issues/87)) ([75a2d76](https://github.com/dougefla/BangumiKomga/commit/75a2d7660ef57383ab5ab281d5d1630700ad0062))
* 修复Komga海报因尺寸限制上传失败 ([#89](https://github.com/dougefla/BangumiKomga/issues/89)) ([e8f8f9c](https://github.com/dougefla/BangumiKomga/commit/e8f8f9cd1563273acb07ee769c379f331b1de51f))
* 修复偏移量读取错误 ([90050a1](https://github.com/dougefla/BangumiKomga/commit/90050a1f16ef1a51d1d9a2183269fcf20ef58f3c))
* 修复可选值 ([254f7dd](https://github.com/dougefla/BangumiKomga/commit/254f7ddc25ea859f26b431d8d0f4e08985ebce34))
* 修复图片尺寸参数未配置的错误 ([2ec3365](https://github.com/dougefla/BangumiKomga/commit/2ec33658475b22a4b181f330bcac7a77bd1ddfe4))
* 修复对 `IndexedDataReader` 中成员函数的无效引用 ([#69](https://github.com/dougefla/BangumiKomga/issues/69)) ([3152d8a](https://github.com/dougefla/BangumiKomga/commit/3152d8a0fea33f3d7cfdd5a4e440576e515c65ef))
* 修复已知的`komga_sse_api`恶性错误 ([#101](https://github.com/dougefla/BangumiKomga/issues/101)) ([32beb69](https://github.com/dougefla/BangumiKomga/commit/32beb698644726188e6e623e8571b02801f7596d))
* 修复收藏搜索与删除逻辑 ([fe95d98](https://github.com/dougefla/BangumiKomga/commit/fe95d987ae3b5d339c33d3ab698ce140c73cd3a6))
* 修复获取序号逻辑 ([dbce1cc](https://github.com/dougefla/BangumiKomga/commit/dbce1cca8197734b2b8def339bd15f07a3641fd4))
* 修复获取系列时参数类型不匹配的问题 ([8b860cc](https://github.com/dougefla/BangumiKomga/commit/8b860cc3b5c19cce73c2cc065d63f010e1b27fc8))
* 修正「失败收藏」相关说明 ([9d78344](https://github.com/dougefla/BangumiKomga/commit/9d7834438b3153c31f8594386e0a3a7697e317ab))
* 修正罗马数字匹配问题 ([35c8ef3](https://github.com/dougefla/BangumiKomga/commit/35c8ef370ec2ad7aa8b0bb8fe974face95a293e8))
* 修正语言代码 ([b676c0e](https://github.com/dougefla/BangumiKomga/commit/b676c0ecae0d7354b7a71a1035d95d268623363c))
* 分离了 RECHECK_FAILED_SERIES 和 CREATE_FAILED_COLLECTION 选项 ([#52](https://github.com/dougefla/BangumiKomga/issues/52)) ([9170afe](https://github.com/dougefla/BangumiKomga/commit/9170afe70878be1dc6c789772a6a0fa0caaf72af))
* 处理 relation_list 为 None 的情况 ([406fdfe](https://github.com/dougefla/BangumiKomga/commit/406fdfe7b2ef1a9769a4cb6a82c0aee7ef3e1481))
* 完善缩略图逻辑 ([fa03358](https://github.com/dougefla/BangumiKomga/commit/fa0335850b486799560c7b182ba6958b68c08b19))
* 捕获所有异常 ([d67383a](https://github.com/dougefla/BangumiKomga/commit/d67383a2975fe6be532dc8bff0894d1a9abf9c65))
* 支持命令行配置 KOMGA_COLLECTION_LIST ([3c82407](https://github.com/dougefla/BangumiKomga/commit/3c82407d033dcb5a911f69ba26eeb968187dbab8))
* 更新`unittest-ci`适配新的`run_unit_tests.py`文件名 ([#97](https://github.com/dougefla/BangumiKomga/issues/97)) ([39e38f0](https://github.com/dougefla/BangumiKomga/commit/39e38f08a7662b075335faa6035f2f1b26ea87bc))
* 检查 cbl 获取的元数据是否为空&添加日志 ([c9ecc45](https://github.com/dougefla/BangumiKomga/commit/c9ecc4528410064e3de1d2a998d48404a26728b9))
* 正确处理数字 ([b9174a9](https://github.com/dougefla/BangumiKomga/commit/b9174a969ed1f604eed34f27cee01e46945e0bcb))
* 添加 IS_NOVEL_ONLY 选项指定是否komga只包含小说数据 ([#59](https://github.com/dougefla/BangumiKomga/issues/59)) ([71803a8](https://github.com/dougefla/BangumiKomga/commit/71803a8540b261fd6030ac4c935ae04c2578bcf1))
* 添加更多可配置项 ([528b9fa](https://github.com/dougefla/BangumiKomga/commit/528b9fa36222379b1481bd01b3eee11ca2f07384))
* 移除`|| exit 0`, 保留原始错误状态码 ([#90](https://github.com/dougefla/BangumiKomga/issues/90)) ([562b090](https://github.com/dougefla/BangumiKomga/commit/562b090f5adabab9338b6cb1b55c4b5bd1c4bfe6))
* 移除中文数字匹配 ([5fbbd6e](https://github.com/dougefla/BangumiKomga/commit/5fbbd6e6c18faaeb0696463373412db8c09703e2))
* 移除同步阅读进度中的`FORCE_REFRESH_LIST`配置 ([69ff03a](https://github.com/dougefla/BangumiKomga/commit/69ff03ae76bc39a006844e829a2a58a15cd96c88))
* 类型注解错误 ([c628f6f](https://github.com/dougefla/BangumiKomga/commit/c628f6f4db3bd0e1d6099c4575f9cbac41e21f51))
* 统一为大写 ([5da28f6](https://github.com/dougefla/BangumiKomga/commit/5da28f698b44ecb76c9b711547dc5a5c5386d3c3))
* 繁转简后再执行bangumi查询 ([9af7438](https://github.com/dougefla/BangumiKomga/commit/9af7438da192d988f1c32d3a25d84a8f35fe7483))
* 网页版支持手动配置 komga 库及收藏 ([adecdf2](https://github.com/dougefla/BangumiKomga/commit/adecdf2b9ef6f8a1e1cf98b8559922e25d84ff87))
* 配置支持多选 ([29654b3](https://github.com/dougefla/BangumiKomga/commit/29654b38e64d89ae81d13db8747b8dab368854f0))
* 错误判断文件路径 ([88b2560](https://github.com/dougefla/BangumiKomga/commit/88b25607d043b92d22b0a08b315fba812b381dcb))
* 隐私说明 ([30069c6](https://github.com/dougefla/BangumiKomga/commit/30069c621945f098d380e8108ea5d9d1b6267aaf))


### Performance Improvements

* 不再重复读取人名文件 ([f9bc723](https://github.com/dougefla/BangumiKomga/commit/f9bc72345a3d411307b74be8b5553dfce52fd8a4))
* 调整代码，改为使用 Session ([5292861](https://github.com/dougefla/BangumiKomga/commit/529286169a6ceb4f564eb248ec706f9aba204fc5))


### Documentation

* docs:  ([6876e47](https://github.com/dougefla/BangumiKomga/commit/6876e478a3ffcaf57c0855502fe6b625c61a5b95))
* add Contributors ([ec1b1d9](https://github.com/dougefla/BangumiKomga/commit/ec1b1d9054ff284178caf2b757e062b41dd2698c))
* fix ([7588b0b](https://github.com/dougefla/BangumiKomga/commit/7588b0b695e946f7783cf345d6f3dec04085697f))
* update installation guide ([0fd61e0](https://github.com/dougefla/BangumiKomga/commit/0fd61e0b2df6f6fb7cd7f23c18cf0ae07a937997))
* 修正 cbl 和 RECHECK_FAILED_SERIES 说明 ([38a5b87](https://github.com/dougefla/BangumiKomga/commit/38a5b87accc3895abbc6a839f34e8da337ec84fe))
* 完善 docker 执行说明 ([602dc5d](https://github.com/dougefla/BangumiKomga/commit/602dc5d74d5340a62003aa30bc9f5074431cf9dd))
* 完善 docker 说明 ([2604a9c](https://github.com/dougefla/BangumiKomga/commit/2604a9c21b2d9313f808c6b0ada687b00d45f585))
* 完善快速开始说明 ([c20cfc0](https://github.com/dougefla/BangumiKomga/commit/c20cfc012ef02a7c269f8a7eb78cb5cfdc9ac996))
* 更新 Komga 最低版本要求 ([af066e8](https://github.com/dougefla/BangumiKomga/commit/af066e8e8a74ef9ad8db31bad39d1662df7182d0))
* 更新 Komga 配置说明 ([301a34f](https://github.com/dougefla/BangumiKomga/commit/301a34f66de0f682d8c0ebf74511e0eec32b37b9))
* 更新「为小说添加元数据」的说明 ([88563f4](https://github.com/dougefla/BangumiKomga/commit/88563f44356479b8cf246e5221e1ac7e3c2329a6))
* 更新功能清单 ([896f346](https://github.com/dougefla/BangumiKomga/commit/896f3467f5dcdc6e13cf1546f6fcd4a954c8adde))
* 添加 cbl 修改图例 ([c0169ed](https://github.com/dougefla/BangumiKomga/commit/c0169edab8f022033375d32b3b01116e6bb12700))
* 添加 Docker 镜像示例 ([44e68ac](https://github.com/dougefla/BangumiKomga/commit/44e68ace5d03540bc1ce5864ad792e9e23cd0891))
* 添加 Komga 缩略图说明 ([a4b31d7](https://github.com/dougefla/BangumiKomga/commit/a4b31d7b7b5b70ae2cd3d24797aa394bef3ea70a))
* 添加TODO ([#108](https://github.com/dougefla/BangumiKomga/issues/108)) ([c123426](https://github.com/dougefla/BangumiKomga/commit/c123426fba78483e0f068ace35a16bb75e3b11b8))
* 添加新功能说明 ([eec3c24](https://github.com/dougefla/BangumiKomga/commit/eec3c24fd26a0def0cb5367fce71959a2a4b7be1))
* 添加配置更新警告 ([22ff4a2](https://github.com/dougefla/BangumiKomga/commit/22ff4a2f0d74be54e3dce9d1252891870bf4cb54))
* 补充收藏说明 ([dbccfab](https://github.com/dougefla/BangumiKomga/commit/dbccfaba5636150799efe9b6a25caed9b6b0faa8))

## [0.17.0](https://github.com/chu-shen/BangumiKomga/compare/v0.16.1...v0.17.0) (2025-06-04)


### Features

* 添加`file_integrity_verifier()`并改进`update_archive()`的下载 ([#86](https://github.com/chu-shen/BangumiKomga/issues/86)) ([1ea5e1c](https://github.com/chu-shen/BangumiKomga/commit/1ea5e1c0b9c4f0dd2cbc24288655433998f46ccb))
* 添加`unittest`测试 ([#88](https://github.com/chu-shen/BangumiKomga/issues/88)) ([44ed7c2](https://github.com/chu-shen/BangumiKomga/commit/44ed7c28f3b07ac0dfe642547aac640ab64a795a))


### Bug Fixes

* 修复`get_data_by_id()`的ID类型错误 ([#87](https://github.com/chu-shen/BangumiKomga/issues/87)) ([75a2d76](https://github.com/chu-shen/BangumiKomga/commit/75a2d7660ef57383ab5ab281d5d1630700ad0062))
* 修复Komga海报因尺寸限制上传失败 ([#89](https://github.com/chu-shen/BangumiKomga/issues/89)) ([e8f8f9c](https://github.com/chu-shen/BangumiKomga/commit/e8f8f9cd1563273acb07ee769c379f331b1de51f))
* 修复偏移量读取错误 ([90050a1](https://github.com/chu-shen/BangumiKomga/commit/90050a1f16ef1a51d1d9a2183269fcf20ef58f3c))
* 修复图片尺寸参数未配置的错误 ([2ec3365](https://github.com/chu-shen/BangumiKomga/commit/2ec33658475b22a4b181f330bcac7a77bd1ddfe4))
* 移除`|| exit 0`, 保留原始错误状态码 ([#90](https://github.com/chu-shen/BangumiKomga/issues/90)) ([562b090](https://github.com/chu-shen/BangumiKomga/commit/562b090f5adabab9338b6cb1b55c4b5bd1c4bfe6))


### Documentation

* add Contributors ([ec1b1d9](https://github.com/chu-shen/BangumiKomga/commit/ec1b1d9054ff284178caf2b757e062b41dd2698c))
* 更新 Komga 最低版本要求 ([af066e8](https://github.com/chu-shen/BangumiKomga/commit/af066e8e8a74ef9ad8db31bad39d1662df7182d0))

## [0.16.1](https://github.com/chu-shen/BangumiKomga/compare/v0.16.0...v0.16.1) (2025-05-09)


### Bug Fixes

* 错误判断文件路径 ([88b2560](https://github.com/chu-shen/BangumiKomga/commit/88b25607d043b92d22b0a08b315fba812b381dcb))

## [0.16.0](https://github.com/chu-shen/BangumiKomga/compare/v0.15.0...v0.16.0) (2025-05-08)


### Features

* 添加滑动窗口限流器&漏桶限流器 ([#68](https://github.com/chu-shen/BangumiKomga/issues/68)) ([729763b](https://github.com/chu-shen/BangumiKomga/commit/729763b9ab98d287432331991718b870fae0d586))


### Bug Fixes

* fuzz 算法计算时忽略大小写 ([654a66e](https://github.com/chu-shen/BangumiKomga/commit/654a66ee8f9eed97505273bd9f6a96bb892cb4db))

## [0.15.0](https://github.com/chu-shen/BangumiKomga/compare/v0.14.0...v0.15.0) (2025-05-07)


### Features

* 添加了 `refreshMetadataServive` 轮询服务 ([#67](https://github.com/chu-shen/BangumiKomga/issues/67)) ([6618cee](https://github.com/chu-shen/BangumiKomga/commit/6618cee4ed881eeb5ce92275f53d6713d0b83d67))


### Bug Fixes

* fix header ([a2b342b](https://github.com/chu-shen/BangumiKomga/commit/a2b342be450d843eefcf869fe3928a768435d9fa))
* 修正「失败收藏」相关说明 ([9d78344](https://github.com/chu-shen/BangumiKomga/commit/9d7834438b3153c31f8594386e0a3a7697e317ab))

## [0.14.0](https://github.com/chu-shen/BangumiKomga/compare/v0.13.0...v0.14.0) (2025-05-05)


### Features

* prepare for api key ([ea9d9e8](https://github.com/chu-shen/BangumiKomga/commit/ea9d9e8d2e25d94e215215ce8ba673599b7c2939))
* 添加`get_new_added_series()`函数, 以支持新增的`refresh_partial_metadata()` ([#64](https://github.com/chu-shen/BangumiKomga/issues/64)) ([9f65a9f](https://github.com/chu-shen/BangumiKomga/commit/9f65a9fe2817cff2fca5c7753da8c0e521341900))
* 添加Archive索引读取器 ([#60](https://github.com/chu-shen/BangumiKomga/issues/60)) ([32a5ab3](https://github.com/chu-shen/BangumiKomga/commit/32a5ab3e21f9ee532540d966d739086825ec5c34))
* 添加更多漫画语言类型 ([1781a75](https://github.com/chu-shen/BangumiKomga/commit/1781a75bce2431824217b7676f6beb633f2bf4f7))


### Bug Fixes

* 使用最新 API ([07cbf1e](https://github.com/chu-shen/BangumiKomga/commit/07cbf1ef365886813085efeb3d0b7dd31d7af8a5))
* 修复对 `IndexedDataReader` 中成员函数的无效引用 ([#69](https://github.com/chu-shen/BangumiKomga/issues/69)) ([3152d8a](https://github.com/chu-shen/BangumiKomga/commit/3152d8a0fea33f3d7cfdd5a4e440576e515c65ef))
* 修正语言代码 ([b676c0e](https://github.com/chu-shen/BangumiKomga/commit/b676c0ecae0d7354b7a71a1035d95d268623363c))
* 处理 relation_list 为 None 的情况 ([406fdfe](https://github.com/chu-shen/BangumiKomga/commit/406fdfe7b2ef1a9769a4cb6a82c0aee7ef3e1481))
* 添加 IS_NOVEL_ONLY 选项指定是否komga只包含小说数据 ([#59](https://github.com/chu-shen/BangumiKomga/issues/59)) ([71803a8](https://github.com/chu-shen/BangumiKomga/commit/71803a8540b261fd6030ac4c935ae04c2578bcf1))
* 类型注解错误 ([c628f6f](https://github.com/chu-shen/BangumiKomga/commit/c628f6f4db3bd0e1d6099c4575f9cbac41e21f51))

## [0.13.0](https://github.com/chu-shen/BangumiKomga/compare/v0.12.0...v0.13.0) (2025-04-25)


### Features

* 完善年龄限制逻辑 ([5e9af4f](https://github.com/chu-shen/BangumiKomga/commit/5e9af4f9dce50a3fc1e27804a91ceeee42463f05))
* 新增 bgm 数据源工厂 ([3a6f4c8](https://github.com/chu-shen/BangumiKomga/commit/3a6f4c8cdd9943d810510398fb8aaccac23cb1dd))
* 添加 bangumi Archive 自动更新器 ([#54](https://github.com/chu-shen/BangumiKomga/issues/54)) ([e0dff38](https://github.com/chu-shen/BangumiKomga/commit/e0dff38840869986361c6bbe8f53800d35e97f64))
* 添加 bgm 条目平台及关联的枚举类 ([4a61017](https://github.com/chu-shen/BangumiKomga/commit/4a61017fb2afc07c73896c45197a540df6ab557b))
* 添加基本的离线Archive元数据查询功能 ([#48](https://github.com/chu-shen/BangumiKomga/issues/48)) ([e176d3c](https://github.com/chu-shen/BangumiKomga/commit/e176d3ce5b812b80eb782a2a8797678765a13189))


### Bug Fixes

* 分离了 RECHECK_FAILED_SERIES 和 CREATE_FAILED_COLLECTION 选项 ([#52](https://github.com/chu-shen/BangumiKomga/issues/52)) ([9170afe](https://github.com/chu-shen/BangumiKomga/commit/9170afe70878be1dc6c789772a6a0fa0caaf72af))
* 完善缩略图逻辑 ([fa03358](https://github.com/chu-shen/BangumiKomga/commit/fa0335850b486799560c7b182ba6958b68c08b19))
* 捕获所有异常 ([d67383a](https://github.com/chu-shen/BangumiKomga/commit/d67383a2975fe6be532dc8bff0894d1a9abf9c65))


### Documentation

* 修正 cbl 和 RECHECK_FAILED_SERIES 说明 ([38a5b87](https://github.com/chu-shen/BangumiKomga/commit/38a5b87accc3895abbc6a839f34e8da337ec84fe))
* 更新「为小说添加元数据」的说明 ([88563f4](https://github.com/chu-shen/BangumiKomga/commit/88563f44356479b8cf246e5221e1ac7e3c2329a6))
* 添加配置更新警告 ([22ff4a2](https://github.com/chu-shen/BangumiKomga/commit/22ff4a2f0d74be54e3dce9d1252891870bf4cb54))

## [0.12.0](https://github.com/chu-shen/BangumiKomga/compare/v0.11.0...v0.12.0) (2025-03-29)


### Features

* 使用 FUZZ 对 bgm 搜索结果进行过滤和排序 ([b2d1962](https://github.com/chu-shen/BangumiKomga/commit/b2d19622cfb29534a26539840ad9afe3e05561df))

## [0.11.0](https://github.com/chu-shen/BangumiKomga/compare/v0.10.0...v0.11.0) (2025-03-27)


### Features

* 日志支持同时输出到文件和显示在 docker 日志窗口 ([84ac359](https://github.com/chu-shen/BangumiKomga/commit/84ac359f472b2648d13d3470e48afca784c65411)), closes [#23](https://github.com/chu-shen/BangumiKomga/issues/23)


### Bug Fixes

* 检查 cbl 获取的元数据是否为空&添加日志 ([c9ecc45](https://github.com/chu-shen/BangumiKomga/commit/c9ecc4528410064e3de1d2a998d48404a26728b9))


### Documentation

* 添加 cbl 修改图例 ([c0169ed](https://github.com/chu-shen/BangumiKomga/commit/c0169edab8f022033375d32b3b01116e6bb12700))

## [0.10.0](https://github.com/chu-shen/BangumiKomga/compare/v0.9.1...v0.10.0) (2025-03-05)


### Features

* 为存在`Bangumi`链接的系列在排序标题中添加首字母 ([9bee000](https://github.com/chu-shen/BangumiKomga/commit/9bee000666e52f6858ce3023035493666efe643d))
* 支持系列在英文字母导航中分类显示 ([7c6996d](https://github.com/chu-shen/BangumiKomga/commit/7c6996db55be10f7d3fb0d1acbaa146cf8655b74))


### Documentation

* 完善 docker 执行说明 ([602dc5d](https://github.com/chu-shen/BangumiKomga/commit/602dc5d74d5340a62003aa30bc9f5074431cf9dd))

## [0.9.1](https://github.com/chu-shen/BangumiKomga/compare/v0.9.0...v0.9.1) (2025-01-14)


### Bug Fixes

* 修正罗马数字匹配问题 ([35c8ef3](https://github.com/chu-shen/BangumiKomga/commit/35c8ef370ec2ad7aa8b0bb8fe974face95a293e8))

## [0.9.0](https://github.com/chu-shen/BangumiKomga/compare/v0.8.3...v0.9.0) (2024-12-27)


### Features

* 单册匹配时支持罗马数字 ([2c2651b](https://github.com/chu-shen/BangumiKomga/commit/2c2651b9de220b271c5c3993bd094cf1b62d0351)), closes [#26](https://github.com/chu-shen/BangumiKomga/issues/26)
* 单册支持 cbl ([96875a2](https://github.com/chu-shen/BangumiKomga/commit/96875a2b19c3203df4e5239fb2317e3222f589d6))


### Bug Fixes

* 移除同步阅读进度中的`FORCE_REFRESH_LIST`配置 ([69ff03a](https://github.com/chu-shen/BangumiKomga/commit/69ff03ae76bc39a006844e829a2a58a15cd96c88))

## [0.8.3](https://github.com/chu-shen/BangumiKomga/compare/v0.8.2...v0.8.3) (2024-10-17)


### Bug Fixes

* 修复获取序号逻辑 ([dbce1cc](https://github.com/chu-shen/BangumiKomga/commit/dbce1cca8197734b2b8def339bd15f07a3641fd4))
* 移除中文数字匹配 ([5fbbd6e](https://github.com/chu-shen/BangumiKomga/commit/5fbbd6e6c18faaeb0696463373412db8c09703e2))

## [0.8.2](https://github.com/chu-shen/BangumiKomga/compare/v0.8.1...v0.8.2) (2024-10-17)


### Bug Fixes

* 不刮削无序号单行本 ([08d47fe](https://github.com/chu-shen/BangumiKomga/commit/08d47fe42a79b2597b8f822450490d92b169a138))

## [0.8.1](https://github.com/chu-shen/BangumiKomga/compare/v0.8.0...v0.8.1) (2024-10-17)


### Documentation

* update installation guide ([0fd61e0](https://github.com/chu-shen/BangumiKomga/commit/0fd61e0b2df6f6fb7cd7f23c18cf0ae07a937997))

## [0.8.0](https://github.com/chu-shen/BangumiKomga/compare/v0.7.0...v0.8.0) (2024-10-17)


### Features

* Bangumi 匹配算法切换为 TheFuzz ([f89cd07](https://github.com/chu-shen/BangumiKomga/commit/f89cd07644946b90cab0e403d6086dcba3e69e21))
* 优化刮削逻辑，移除`FORCE_REFRESH_LIST`配置 ([c497d30](https://github.com/chu-shen/BangumiKomga/commit/c497d3076b0645166e04b7bbfd1e5573e8ed6b18))

## [0.7.0](https://github.com/chu-shen/BangumiKomga/compare/v0.6.0...v0.7.0) (2024-10-15)


### Features

* support get vol or chap number ([cba4e49](https://github.com/chu-shen/BangumiKomga/commit/cba4e495797f5e82e3f69e108740856d8a71c2e5))


### Performance Improvements

* 不再重复读取人名文件 ([f9bc723](https://github.com/chu-shen/BangumiKomga/commit/f9bc72345a3d411307b74be8b5553dfce52fd8a4))


### Documentation

* 完善 docker 说明 ([2604a9c](https://github.com/chu-shen/BangumiKomga/commit/2604a9c21b2d9313f808c6b0ada687b00d45f585))

## [0.6.0](https://github.com/chu-shen/BangumiKomga/compare/v0.5.0...v0.6.0) (2024-07-01)


### Features

* 支持更新元数据时替换单册封面 ([d31a0b7](https://github.com/chu-shen/BangumiKomga/commit/d31a0b7fa6f5e05591c2ee6082026a28b1b25684))

## [0.5.0](https://github.com/chu-shen/BangumiKomga/compare/v0.4.1...v0.5.0) (2024-06-02)


### Features

* 支持更新元数据时替换系列封面 ([02b853f](https://github.com/chu-shen/BangumiKomga/commit/02b853f88773f1e52c83f942219ba84fa310ed92))


### Bug Fixes

* 上传封面前先检测是否已有海报 ([ebc429c](https://github.com/chu-shen/BangumiKomga/commit/ebc429c8d1b4755d2fb0615be68578bbf69f803d))


### Performance Improvements

* 调整代码，改为使用 Session ([5292861](https://github.com/chu-shen/BangumiKomga/commit/529286169a6ceb4f564eb248ec706f9aba204fc5))


### Documentation

* 添加 Komga 缩略图说明 ([a4b31d7](https://github.com/chu-shen/BangumiKomga/commit/a4b31d7b7b5b70ae2cd3d24797aa394bef3ea70a))

## [0.4.1](https://github.com/chu-shen/BangumiKomga/compare/v0.4.0...v0.4.1) (2024-06-01)


### Bug Fixes

* 一次性获取 komga 所有系列 ([ee1adc0](https://github.com/chu-shen/BangumiKomga/commit/ee1adc06d410c0c677b177c286e2f2bde5bc9819))


### Documentation

* 添加 Docker 镜像示例 ([44e68ac](https://github.com/chu-shen/BangumiKomga/commit/44e68ace5d03540bc1ce5864ad792e9e23cd0891))

## 0.4.0 (2023-07-07)


### Features

* 新增komga收藏的新增、删除、搜索函数 ([d3556e5](https://github.com/chu-shen/BangumiKomga/commit/d3556e515d78f9af6aebda42cfa7e5122f4e09d8))
* 新增通知功能 ([0eddf3f](https://github.com/chu-shen/BangumiKomga/commit/0eddf3f31e6a7701e57fc703b6f2b5f665b3d584))


### Bug Fixes

* 修复收藏搜索与删除逻辑 ([fe95d98](https://github.com/chu-shen/BangumiKomga/commit/fe95d987ae3b5d339c33d3ab698ce140c73cd3a6))
* 繁转简后再执行bangumi查询 ([9af7438](https://github.com/chu-shen/BangumiKomga/commit/9af7438da192d988f1c32d3a25d84a8f35fe7483))


### Documentation

* docs:  ([6876e47](https://github.com/chu-shen/BangumiKomga/commit/6876e478a3ffcaf57c0855502fe6b625c61a5b95))
* fix ([7588b0b](https://github.com/chu-shen/BangumiKomga/commit/7588b0b695e946f7783cf345d6f3dec04085697f))
* 添加新功能说明 ([eec3c24](https://github.com/chu-shen/BangumiKomga/commit/eec3c24fd26a0def0cb5367fce71959a2a4b7be1))
* 补充收藏说明 ([dbccfab](https://github.com/chu-shen/BangumiKomga/commit/dbccfaba5636150799efe9b6a25caed9b6b0faa8))
