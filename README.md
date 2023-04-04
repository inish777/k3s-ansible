# Ansible плейбук для сетапа окружения на основе k3s

Основан на https://github.com/k3s-io/k3s-ansible, но полностью перепилен

## Окружение для работы
В корне лежит environment.yml для конды (конкретно https://docs.conda.io/en/latest/miniconda.html), так что ставим миниконду/анаконду/что нравится и импортируем энв 
```
conda env create -n my-fancy-env-name --file environment.yml

conda activate my-fance-env-name
```

## Инвентори
inventory/ranepa-dev-test - пример реального инвентори

