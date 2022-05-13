FROM mongo:latest
COPY apples.json /apples.json
COPY oranges.json /oranges.json
COPY countries.json /countries.json
CMD mongoimport --host mongodb --db fruit --username root --password password --authenticationDatabase admin --collection apples --drop --type json --file /apples.json --jsonArray && \
    mongoimport --host mongodb --db fruit --username root --password password --authenticationDatabase admin --collection oranges --drop --type json --file /oranges.json --jsonArray  && \
    mongoimport --host mongodb --db fruit --username root --password password --authenticationDatabase admin --collection countries --drop --type json --file /countries.json --jsonArray