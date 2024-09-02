<p align="center"><img src= "https://github.com/1Panel-dev/maxkb/assets/52996290/c0694996-0eed-40d8-b369-322bf2a380bf" alt="MaxKB" width="300" /></p>
<h3 align="center">Knowledge Base Q&A System Based on LLM (Large Language Model)</h3>
<p align="center"><a href="https://trendshift.io/repositories/9113" target="_blank"><img src="https://trendshift.io/api/badge/repositories/9113" alt="1Panel-dev%2FMaxKB | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a></p>
<p align="center">
  <a href="https://www.gnu.org/licenses/gpl-3.0.html#license-text"><img src="https://img.shields.io/github/license/1Panel-dev/maxkb?color=%231890FF" alt="License: GPL v3"></a>
  <a href="https://app.codacy.com/gh/1Panel-dev/maxkb?utm_source=github.com&utm_medium=referral&utm_content=1Panel-dev/maxkb&utm_campaign=Badge_Grade_Dashboard"><img src="https://app.codacy.com/project/badge/Grade/da67574fd82b473992781d1386b937ef" alt="Codacy"></a>
  <a href="https://github.com/1Panel-dev/maxkb/releases/latest"><img src="https://img.shields.io/github/v/release/1Panel-dev/maxkb" alt="Latest release"></a>
  <a href="https://github.com/1Panel-dev/maxkb"><img src="https://img.shields.io/github/stars/1Panel-dev/maxkb?color=%231890FF&style=flat-square" alt="Stars"></a>    
  <a href="https://hub.docker.com/r/1panel/maxkb"><img src="https://img.shields.io/docker/pulls/1panel/maxkb?label=downloads" alt="Download"></a>  
</p>
<hr/>

MaxKB = Max Knowledge Base, is an open-source knowledge base Q&A system based on LLM (Large Language Model), widely used in scenarios such as enterprise internal knowledge bases, customer service, academic research, and education.

- **Ready to use**: Supports direct document upload, automatic crawling of online documents, automatic text splitting, vectorization, RAG (Retrieval-Augmented Generation), and intelligent Q&A interaction experience;
- **Model neutral**: Supports integration with various large language models, including local private models (Llama 3 / Qwen 2, etc.), domestic public models (Tongyi Qianwen / Zhipu AI / Baidu Qianfan / Kimi / DeepSeek, etc.), and foreign public models (OpenAI / Azure OpenAI / Gemini, etc.);
- **Flexible orchestration**: Built-in powerful workflow engine, supports orchestrating AI work processes to meet the needs of complex business scenarios;
- **Seamless embedding**: Supports quick embedding into third-party business systems with zero coding, allowing existing systems to quickly have intelligent Q&A capabilities and improve user satisfaction.

## Quick Start

```
docker run -d --name=maxkb -p 8080:8080 -v ~/.maxkb:/var/lib/postgresql/data -v ~/.python-packages:/opt/maxkb/app/sandbox/python-packages cr2.fit2cloud.com/1panel/maxkb

# Username: admin
# Password: MaxKB@123..
```

- You can also quickly deploy MaxKB + Ollama + Llama 3 through the [1Panel App Store](https://apps.fit2cloud.com/1panel), and launch a knowledge base Q&A system based on local large models within 30 minutes, which can be embedded into third-party business systems;
- For intranet environments, it is recommended to use the [offline installation package](https://community.fit2cloud.com/#/products/maxkb/downloads) for installation and deployment;
- You can also experience it online: [DataEase Assistant](https://dataease.io/docs/v2/), which is an intelligent Q&A system built based on MaxKB and has been embedded into DataEase products and online documentation;
- MaxKB product versions are divided into Community Edition and Professional Edition, for details please refer to: [MaxKB Product Version Comparison](https://maxkb.cn/pricing.html).

If you have more questions, you can check the user manual or communicate with us through the forum. If you need to set up a tech blog or knowledge base, we recommend using the [Halo open-source website building tool](https://github.com/halo-dev/halo/). You can experience FIT2CLOUD's official [Tech Blog](https://blog.fit2cloud.com/) and [Knowledge Base](https://kb.fit2cloud.com) cases.

- [User Manual](https://maxkb.cn/docs/)
- [Demo Video](https://www.bilibili.com/video/BV1BE421M7YM/)
- [Forum Help](https://bbs.fit2cloud.com/c/mk/11)
- Technical Exchange Group

<image height="150px" width="150px" src="https://github.com/1Panel-dev/MaxKB/assets/52996290/a083d214-02be-4178-a1db-4f428124153a"/>

## UI Display

<table style="border-collapse: collapse; border: 1px solid black;">
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/1Panel-dev/MaxKB/assets/52996290/d87395fa-a8d7-401c-82bf-c6e475d10ae9" alt="MaxKB Demo1"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/1Panel-dev/MaxKB/assets/52996290/47c35ee4-3a3b-4bd4-9f4f-ee20788b2b9a" alt="MaxKB Demo2"   /></td>
  </tr>
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/1Panel-dev/MaxKB/assets/52996290/1c0c5e32-6194-47f9-bc32-487996349d9c" alt="MaxKB Demo3"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/1Panel-dev/MaxKB/assets/52996290/f32f5fe9-a769-488c-ae0e-783bc2b89b3e" alt="MaxKB Demo4"   /></td>
  </tr>
</table>

## Tech Stack

- Frontend: [Vue.js](https://vuejs.org/)
- Backend: [Python / Django](https://www.djangoproject.com/)
- LangChain: [LangChain](https://www.langchain.com/)
- Vector Database: [PostgreSQL / pgvector](https://www.postgresql.org/)
- Large Models: Various local private or public large models

## Other Star Projects by FIT2CLOUD

- [1Panel](https://github.com/1panel-dev/1panel/) - Modern, open-source Linux server operation and management panel
- [JumpServer](https://github.com/jumpserver/jumpserver/) - Popular open-source bastion host
- [DataEase](https://github.com/dataease/dataease/) - Open-source data visualization and analysis tool for everyone
- [MeterSphere](https://github.com/metersphere/metersphere/) - New generation open-source continuous testing tool
- [Halo](https://github.com/halo-dev/halo/) - Powerful and easy-to-use open-source website building tool

## License

Copyright (c) 2014-2024 FIT2CLOUD, All rights reserved.

Licensed under The GNU General Public License version 3 (GPLv3)  (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

<https://www.gnu.org/licenses/gpl-3.0.html>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.