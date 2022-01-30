# Glowbyte_Hackathon_2021
Our team won the hackathon - here is a given problem and our solution, as well as some other files.

GIVEN PROBLEM (ROUND 1)

ENG

Tool for analysis and aggregation of data of different structure.
Your customer is a developing bank. The Bank's management wants to improve the system for scoring loan applications for individuals. Now the decision to grant a loan is made only on the basis of data from the questionnaires.
The bank wants to enrich the questionnaires with data from other sources.
You will be provided with documentation of the current scoring and other banking systems, as well as a virtual machine (VM) with the used DBMS and test data set.

The customer wants to revive the scoring process. Enrich questionnaires with interesting data from other systems.
The customer is ready to finalize the decision-making module in accordance with the recommendations of the Team, but for the completion it is required to prepare a data model, solution architecture and an ETL process that will be fed into the module.
The customer asks to pay attention to the potential use of information from different areas, as well as the rational use of computing resources.

Team Tasks:
1. Think about TO BE, the scoring process.
2. Think over the architecture of the solution.
3. Create a new data model that allows you to solve a specific problem.
4. Integrate between sources and figure out how to write ETL.
At the same time, the module itself does not need to be developed or modified. It is enough to write recommendations for using the new data model by the module.

RUS

Инструмент анализа и агрегации различных по структуре данных
Ваш заказчик - развивающийся Банк. Руководство Банка хочет усовершенствовать систему скоринга кредитных заявок физ. лиц. Сейчас принятие решения о выдаче кредита принимается только на основании данных из анкет.
Банк хочет обогатить анкеты данными из других источников.
Вам будет предоставлена документация текущей скоринговой и других банковских систем, а также виртуальная машина (ВМ) с используемыми СУБД и тестовым набором данных.

Заказчик хочет оживить процесс скоринга. Обогатить скудные анкеты интересными данными из остальных систем.
Заказчик готов доработать модуль принятия решения МПР в соответствии с рекомендациями Команды участников, но для проведения доработок требуется подготовить модель данных, архитектуру решения и ETL-процесс который будет подаваться на вход МПР.
Заказчик просит уделить внимание потенциальным возможностям использования информации из разных прикладных областей, а также рациональному использованию вычислительных ресурсов.

Задачи Команд:
1. Продумать TO BE, процесс скоринга.
2. Продумать архитектуру решения.
3. Составить новую модель данных, позволяющую решить определенную задачу.
4. Провести интеграцию между источниками и придумать, как написать ETL.
При этом сам модуль не нужно разрабатывать или дорабатывать. Достаточно написать рекомендации к использованию новой модели данных модулем.

GIVEN PROBLEM (ROUND 2)

ENG 

The customer liked the solution you proposed.
But before implementing it, you need to consider the following details:
1. In accordance with the requirements of the Central Bank, the Bank is obliged to store the data on the basis of which credit decisions were made. Therefore, the customer asks to form a Data Warehouse, the data in which will be resistant to changes at the source. That is, when the data at the source is changed or deleted, the version on the basis of which the decision was made must be saved.
2. How can this repository be used for marketing purposes? Now outdoor advertising is used to attract customers. The customer wants to automate customer profiling to create personalized marketing offers.
3. We welcome the development of the main part of the product in accordance with the recommendations of mentors and the roadmap.

We expect to see in the presentations:
1. Modified TO BE process.
2. Architecture of the solution together with the created repository. 
3. Storage data model.
4. A detailed diagram of the ETL process (taking into account sources and
transformations)

RUS

Заказчику понравилось предложенное вами решение.
Но перед его внедрением необходимо продумать следующие детали:
1. В соответствии с требованиями ЦБ, Банк обязан хранить данные на основании которых были приняты решения о кредитовании. Поэтому заказчик просит сформировать КХД, данные в котором будут устойчивы к изменениям на источнике. То есть, при изменении данных на источнике или их удалении, версия, на основании которой было принято решение, должна быть сохранена.
2. Как это хранилище можно будет использовать в целях маркетинга? Сейчас для привлечения клиентов используется наружная реклама. Заказчик хочет автоматизировать профайлинг клиентов для создания персонализированных маркетинговых предложений.
3. Приветствуется развитие основной части продукта в соответствии с рекомендациями менторов и роад-мапом.

Ожидаем в презентациях увидеть:
1. Доработанный процесс TO BE.
2. Архитектуру решения вместе с созданным хранилищем. 3. Модель данных хранилища.
4. Детальную схему ETL-процесса (с учетом источников и
трансформаций)
