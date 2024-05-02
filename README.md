# README_OPENCOMPASS
Healthcare Agent Data
2024.5.2    

## metadata的信息如下：    
- name:  # 数据集的名称;    
- desc: # 对数据集的简短描述;
- language: # 数据集支持的语言列表;
- dimension: # 数据集涉及的维度;
- sub_dimension: # 更加具体的数据集维度，如vision-language;
- website：# 数据集的官方网址;
- github：# 数据集的github仓库链接;
- paper：# 数据集的学术论文链接;
- release_date: # 数据集的发布日期;
- tags：# 数据集相应的标签;
- download_url：# 可供其他用户下载数据集的链接;
- cn：# 中文配置，配置完成后，用户切换网页语言，可看见对应中文

## README 是数据集的使用相关的详细介绍，包括简介，元数据，使用示例及引用     

```
---
name: {Healthcare Agent Data}
desc: {是用于微调模型的专业医疗健康数据，来自国内外的专业期刊网站}    
language:
- {lang_0}  # Example: cn
- {lang_1}  # Example: en
dimension:
- {}
- {examination | language | knowledge | understanding | reasoning | long-context | safety | code 八选一或者任意填} 
sub_dimension:
- {sub_tag_1}
- {sub_tag_2}
website: {[http://orthomolecular.org/resources/omns/index.shtml,http://orthomolecular.org/resources/omns/index.shtml }
github: {https://github.com/CDL0726/README_OPENCOMPASS/edit/main/README.md}
paper: {paper or tech report url}
release_date: {2024-05-02}
tag:
- {tag_1 e.g. text}
- {tag_2}
- {tag_#}
download_url: {url e.g. OpenDataLab}
cn: # optional, for chinese version website
    name: {cn_desc}
    desc: {cn_name}
---
## Introduction
## Meta Data
## Example
## Citation
```
