FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD ./node_modules.tar.gz /usr/local/bin
COPY . /usr/local/bin
CMD [ "npm", "test" ]
