FROM mjgargani/puppeteer:trybe1.0
ADD ./node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3003:80
ENTRYPOINT ["npm", "test"]