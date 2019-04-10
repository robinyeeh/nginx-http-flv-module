https://github.com/arut/nginx-rtmp-module/archive/v1.2.1.tar.gz


yum -y install lrzsz
wget https://github.com/arut/nginx-rtmp-module/archive/v1.2.1.tar.gz
tar zxvf v1.2.1.tar.gz


$ ./configure --prefix=/opt/app/nginx --add-module=/opt/install/nginx/nginx-rtmp-module --add-module=/opt/install/nginx/nginx-http-flv-module-1.2.2 --with-http_ssl_module --
with-debug
$ make & make install