FROM mjgargani/puppeteer:trybe1.0
WORKDIR /testes

ADD node_modules.tar.gz /testes/
COPY . .

ENTRYPOINT [ "npm", "test" ]
