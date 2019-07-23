FROM circleci/php:7.3
RUN sudo apt-get update -q && \
    sudo apt-get install -y curl mariadb-client lftp && \
    sudo rm -rf /var/lib/apt/lists/*
RUN sudo curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar && \
    sudo chmod +x wp-cli.phar && \
    sudo mv wp-cli.phar bin/wp