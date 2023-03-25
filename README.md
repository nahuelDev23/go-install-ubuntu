# Instalar go en ubuntu 20

Te bajas el `.tar.gz` lo descomprimis en donde te guste , ahi mismo pones

`rm -rf /usr/local/go && tar -C /usr/local -xzf go1.20.2.linux-amd64.tar.gz`

Vas al `~/.bashrc` y pegas arriba de todo `export PATH=$PATH:/usr/local/go/bin`

Despues recargas el fichero `source ~/.bashrc`

Listo tiras `go version`

