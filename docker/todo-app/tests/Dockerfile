FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /dockertests

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "test" ]
