# Awesome-markdown-ebooks


<div align="center" xmlns="http://www.w3.org/1999/html">
<!-- logo -->
<p align="center">
  <img src="logo.png" alt="the project's logo" width="300px" style="vertical-align:middle;">
  <h4>Your GitHub PDFs, Now AI-Ready.</h4>
  
</p>

[English](README.md) | [简体中文](README_zh-CN.md)

</div>



## 项目介绍
本项目收集了github上高质量的电子书项目，并将其中的PDF文件使用[MinerU2.0](https://github.com/opendatalab/MinerU)转为Markdown文件。
其中每个目录都代表了一个github上的仓库。
如果你有一些需要进行转换的高质量电子书资源，欢迎在issue中提供链接，我们会帮助你进行pdf2md的提取工作。
我们的目标是将更多高质量的知识数据转化为AI-Ready数据

## 已转换的仓库列表

| Repo url |  Download |
|----|----|
| [ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | [opendatalab/awesome-markdown-ebooks/ChinaTextbook](https://huggingface.co/datasets/opendatalab/awesome-markdown-ebooks/tree/main/ChinaTextbook) |

## 输出文件结构说明（基于MinerU2 vlm）

### 1. Markdown 文件及图像
- **文件类型**: `.md` 文件 + `images/` 文件夹
- **描述**: PDF 转换为 Markdown 的最终结果
- **内容**: 文档文本内容及图像引用

### 2. 模型输出文件
- **文件名**: `model_output.txt`
- **描述**: VLM 模型输出的中间推理数据
- **内容**: 模型对页面的视觉理解结果

### 3. 中间处理文件
- **文件名**: `middle.json`
- **描述**: `model_output.txt` 处理后的结果
- **内容**: 包含PDF 中文本、图像、公式、表格等内容的位置信息

### 4. 内容列表文件
- **文件名**: `content_list.json`
- **描述**: 由 `middle.json` 转换而来的最终结果
- **内容**: 按元素分段的文档转换结果，包含页码信息


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ccprocessor/awesome-markdown-ebooks&type=Date)](https://www.star-history.com/#ccprocessor/awesome-markdown-ebooks&Date)
