-----------------------------------------------------
Van https://medium.com/@kaustubhtalathi/mock-data-for-angular-5-applications-with-json-server-part-1-d377eced223b
-----------------------------------------------------
github:
commit 1: single api calls and dataset
commit 2: multiple api calls and dataset
-----------------------------------------------------
commit 1

ng new x
npm i --save-dev json-server
npm i --save-dev concurrently

run appart;
npm run mock:server
npm run start:proxy

//gebruik concurrently
npm run start:proxy:mock:server

Visit http://localhost:4200/people and verify if the response data is same as http:localhost:3000/people.

http://localhost:4200/people
http://localhost:3000/people

-----------------------------------------------------
commit 2

todo

-----------------------------------------------------

angular app zonder backend
create http get met loading json file vanuit /src/app/assets/mocks/data.json
zie;
https://stackoverflow.com/questions/44042223/load-json-from-local-file-with-http-get-in-angular-2/47023181