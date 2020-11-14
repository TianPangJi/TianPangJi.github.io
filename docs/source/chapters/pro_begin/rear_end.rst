****************
后端安装及启动
****************


.. code-block:: console

    # 克隆项目
    git clone https://github.com/TianPangJi/drf_admin.git

    # 进入项目目录
    cd drf_admin

    # 安装依赖
    pip install -r requirements.txt

    # 数据库迁移
    python manage.py migrate

    # 修改settings配置文件
    跨域信息、redis配置信息

    # 启动
    python manage.py runserver 0.0.0.0:端口