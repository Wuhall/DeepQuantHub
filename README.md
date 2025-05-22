# llama.cpp 量化实践

系统梳理大语言模型（LLM）量化原理、主流量化工具链（如 PyTorch、llama.cpp、Ollama）、模型格式转换、推理部署选型等内容。

## 功能点
- 详细讲解 LLM 量化原理与动机，涵盖 int8/int4 等主流方案
- PyTorch 量化动手实践，代码可直接运行
- llama.cpp 生态与 GGUF 格式详解，主流模型格式转换全流程
- Ollama、vLLM、TGI、LMDeploy 等主流 LLM 部署方式对比与选型建议

## 目录结构
- `量化动手实践.ipynb`：量化原理、PyTorch 量化实战
- `llama_cpp量化专题.ipynb`：llama.cpp、GGUF、Ollama、部署选型全景
- `requirements.txt`：依赖包说明

## 快速开始
1. 克隆本项目
   ```sh
   git clone https://github.com/Wuhall/DeepQuantHub.git
   cd DeepQuantHub
   ```
2. 安装依赖
   ```sh
   pip install -r requirements.txt
   ```

## 贡献与交流
- 欢迎提交 PR、Issue 共同完善内容
- 可补充更多主流模型、量化算法、推理部署案例

## TODO
- 增加更多主流 LLM 量化算法（如 GPTQ、AWQ、SmoothQuant）实战
- 增加 ONNX/TensorRT/NCNN 等推理引擎实践
- 增加移动端/嵌入式部署案例
- 增加模型精度/速度对比实验

