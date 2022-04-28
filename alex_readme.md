az login --use-device-code
az account set --subscription "5763fde3-4253-480c-928f-dfe1e8888a57"
az configure --defaults group="safedriveraz" workspace="aml_safedriver_ws"

git config --global user.email "alzeltov@microsoft.com"
git config --global user.name "Alex Zeltov"
