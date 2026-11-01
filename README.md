# niqivoAI 下载

niqivoAI 是基于 [Toonflow-app](https://github.com/HBAI-Ltd/Toonflow-app) 修改的本地视频创作工作台。

## 下载与安装

在本仓库的 **Releases** 页面下载 `niqivoAI-2.1.0-Setup.exe`。

- 支持 Windows x64，安装包约 46 MiB。
- 运行安装器，选择安装目录，完成后打开 niqivoAI。
- 更新已有安装时，请先保存工作并关闭 niqivoAI，再安装到原目录。
- 图片、视频及文本生成需在软件设置中配置自己的服务商 API Key，费用以服务商结算为准。
- 当前下载提供主程序。本地 QwenTTS 配音还需要另行安装约 20 GB 的配音模块；该模块不包含在此安装包中。
- 本次发布提供手动下载安装更新，软件内在线升级源尚未启用。

## APIMart 设置

在“设置 → 媒体模型 → APIMart → 编辑模型”中填写自己的 API Key，将“请求地区”设置为 **2**，然后保存。

地区 2 使用 `https://api.apimart.ai/v1`。2026 年 11 月 1 日，在当前验证环境中，地区 1 使用的国内入口出现证书校验错误，而地区 2 的安全连接及模型列表查询通过。此结果不代表所有网络环境或付费生成任务均已验证。

## 文件校验

发行版同时提供 `SHA256SUMS.txt`，可与本地下载文件的 SHA-256 对比。

## 开源来源

- 工作台基于 [HBAI-Ltd/Toonflow-app](https://github.com/HBAI-Ltd/Toonflow-app)，原项目采用 MIT 许可证，见本仓库 `LICENSE`。
- 配音功能基于 [HAIGC/Comfyui-HAIGC-QwenTTS](https://github.com/HAIGC/Comfyui-HAIGC-QwenTTS) 及 Qwen3-TTS；配音模型和运行模块需单独安装，并遵循各自许可证。
- niqivoAI 是修改构建版本；原项目及随附第三方组件的版权和许可证仍归原权利人所有。
