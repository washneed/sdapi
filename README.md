# 启动 sdui-api

cd stable-diffusion-webui

.\webui.bat --api

# 启动项目

cd sdwebui-api-manager

pip install -r requirements.txt

uvicorn app.main:app --reload --port 5001

# 查看项目 API 文档

http://127.0.0.1:5001/docs#/
