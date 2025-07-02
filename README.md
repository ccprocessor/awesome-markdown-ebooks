# Awesome-markdown-ebooks


<div align="center" xmlns="http://www.w3.org/1999/html">
<!-- logo -->
<p align="center">
  <img src="logo.png" alt="the project's logo" width="300px" style="vertical-align:middle;">
  <h4>Your GitHub PDFs, Now AI-Ready.</h4>
  
</p>

[English](README.md) | [简体中文](README_zh-CN.md)

</div>

## Project Introduction

The project gathers high-quality e-book repositories from GitHub and leverages  [MinerU 2.0](https://github.com/opendatalab/MinerU) to transform the PDF content into Markdown format.

Each directory represents a repository originally hosted on GitHub.

If you possess any high-quality e-book resources that require conversion, you’re welcome to submit the links in an issue and we will assist with the PDF-to-Markdown extraction. 

Our goal is to convert more high-quality knowledge data into AI-ready data.

## Converted Repositories List
| Repo url |  Download |
|----|----|
| [ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | [opendatalab/awesome-markdown-ebooks/ChinaTextbook](https://huggingface.co/datasets/opendatalab/awesome-markdown-ebooks/tree/main/ChinaTextbook) |

## Output File Structure Documentation (Based on MinerU2 vlm, [Output File Structure](https://github.com/opendatalab/MinerU/blob/master/docs/output_file_en_us.md))


### 1. Markdown Files and Images
- **File Type**: `.md` file + `images/` folder
- **Description**: Final result of PDF to Markdown conversion
- **Content**: Document text content and image references

### 2. Model Output File
- **Filename**: `model_output.txt`
- **Description**: Intermediate inference data from VLM model
- **Content**: Model's visual understanding results of pages

### 3. Intermediate Processing File
- **Filename**: `middle.json`
- **Description**: Processed result from `model_output.txt`
- **Content**: Contains position information of text, images, formulas, tables, etc. in PDF

### 4. Content List File
- **Filename**: `content_list.json`
- **Description**: Final result converted from `middle.json`
- **Content**: Document conversion results segmented by elements, including page information

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ccprocessor/awesome-markdown-ebooks&type=Date)](https://www.star-history.com/#ccprocessor/awesome-markdown-ebooks&Date)
