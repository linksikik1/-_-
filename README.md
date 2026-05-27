
PS D:\Users\demo26\Desktop\моя курсовая> Start-Service postgresql-x64-16
Start-Service : Не удается найти службу с именем службы "postgresql-x64-16".
строка:1 знак:1
+ Start-Service postgresql-x64-16
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + FullyQualifiedErrorId : NoServiceFoundForGivenName,Microsoft.PowerShell.Commands.StartServiceCommand
 
PS D:\Users\demo26\Desktop\моя курсовая> Start-Service postgresql-x64-18
Start-Service : Не удается запустить службу "postgresql-x64-18 - PostgreSQL Server 18 (postgresql-x64-18)" из-за следующей ошибки: Не удалось открыть службу postgresql-x64-18 на компьютере '.'.
строка:1 знак:1
+ Start-Service postgresql-x64-18
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + FullyQualifiedErrorId : CouldNotStartService,Microsoft.PowerShell.Commands.StartServiceCommand
 
PS D:\Users\demo26\Desktop\моя курсовая> Start-Service postgresql-x64-13
Start-Service : Не удается запустить службу "postgresql-x64-13 - PostgreSQL Server 13 (postgresql-x64-13)" из-за следующей ошибки: Не удалось открыть службу postgresql-x64-13 на компьютере '.'.
строка:1 знак:1
+ Start-Service postgresql-x64-13
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : OpenError: (System.ServiceProcess.ServiceController:ServiceController) [Start-Service], ServiceCommandException
 
PS D:\Users\demo26\Desktop\моя курсовая> winget install PostgreSQL.PostgreSQL.16
winget : Имя "winget" не распознано как имя командлета, функции, файла сценария или выполняемой программы. Проверьте правильность написания имени, а также наличие и правильность пути, после чего повторите по 
пытку.
строка:1 знак:1
+ winget install PostgreSQL.PostgreSQL.16
+ ~~~~~~
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS D:\Users\demo26\Desktop\моя курсовая> Get-Service *postgres*

Status   Name               DisplayName
------   ----               -----------
Running  postgresql-x64-13  postgresql-x64-13 - PostgreSQL Serv...


PS D:\Users\demo26\Desktop\моя курсовая> npm install

up to date, audited 109 packages in 770ms

29 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS D:\Users\demo26\Desktop\моя курсовая> npm start

> start
> nodemon server.js

[nodemon] 3.1.14
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: ������������ "postgres" �� ������ �������� ����������� (�� ������)
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 120,
  severity: '�����',
  code: '28P01',
  detail: undefined,
  hint: undefined,
  position: undefined,
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'auth.c',
  line: '320',
  routine: 'auth_failed'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...


[nodemon] 3.1.14
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: нет доступа к схеме public
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 113,
  severity: 'ОШИБКА',
  code: '42501',
  detail: undefined,
  hint: undefined,
  position: '33',
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'aclchk.c',
  line: '2809',
  routine: 'aclcheck_error'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...










PS D:\Users\demo26\Desktop\моя курсовая> npm install

up to date, audited 109 packages in 822ms

29 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS D:\Users\demo26\Desktop\моя курсовая> npm start

> start
> nodemon server.js

[nodemon] 3.1.14
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: ������������ "postgres" �� ������ �������� ����������� (�� ������)
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 120,
  severity: '�����',
  code: '28P01',
  detail: undefined,
  hint: undefined,
  position: undefined,
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'auth.c',
  line: '320',
  routine: 'auth_failed'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...
[nodemon] restarting due to changes...
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: ������������ "postgres" �� ������ �������� ����������� (�� ������)
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 120,
  severity: '�����',
  code: '28P01',
  detail: undefined,
  hint: undefined,
  position: undefined,
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'auth.c',
  line: '320',
  routine: 'auth_failed'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...
[nodemon] restarting due to changes...
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: нет доступа к схеме public
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 113,
  severity: 'ОШИБКА',
  code: '42501',
  detail: undefined,
  hint: undefined,
  position: '33',
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'aclchk.c',
  line: '2809',
  routine: 'aclcheck_error'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...
[nodemon] restarting due to changes...
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: нет доступа к схеме public
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 113,
  severity: 'ОШИБКА',
  code: '42501',
  detail: undefined,
  hint: undefined,
  position: '33',
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'aclchk.c',
  line: '2809',
  routine: 'aclcheck_error'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...
PS D:\Users\demo26\Desktop\моя курсовая> ^C
PS D:\Users\demo26\Desktop\моя курсовая> npm start

> start
> nodemon server.js

[nodemon] 3.1.14
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node server.js`
Сервер работает на порту: 3000
D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45
    Error.captureStackTrace(err)
          ^

error: нет доступа к схеме public
    at D:\Users\demo26\Desktop\моя курсовая\node_modules\pg-pool\index.js:45:11
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async createTables (file:///D:/Users/demo26/Desktop/%D0%BC%D0%BE%D1%8F%20%D0%BA%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F/server.js:21:3) {
  length: 113,
  severity: 'ОШИБКА',
  code: '42501',
  detail: undefined,
  hint: undefined,
  position: '33',
  internalPosition: undefined,
  internalQuery: undefined,
  where: undefined,
  schema: undefined,
  table: undefined,
  column: undefined,
  dataType: undefined,
  constraint: undefined,
  file: 'aclchk.c',
  line: '2809',
  routine: 'aclcheck_error'
}

Node.js v24.16.0
[nodemon] app crashed - waiting for file changes before starting...
