# Digital-Banking
Notre projet consiste sur la création d'une application qui permet
de gérer des comptes bancaires. chaque compte appartient à un client.
un compte peut subir plusieurs opérations de type DEBIT ou CREDIT.
Il existe deux types de comptes : Comptes courants et comptes épargnes.
L'application se compose des couches suivantes :
- Couche DAO (Entités JPA et Repositories)
- Couche Service définissant les opérations suivantes :
    - Ajouter des comptes
    - Ajouter des client
    - Effectuer un débit (Retrait)
    - Effectuer un crédit (Versement)
    - Effectuer un virement
    - Consulter un compte
- La couche DTO
- Mappers (DTO <=>Entities)
- La couche Web/services (Rest Controllers)

## Cas d'utilisation Digital banking

![digita_bank](./captures/Class.PNG)

## BackendEnd
Structure du projet:
![digita_bank](./captures/back.PNG)

### Entities
![digita_bank](./captures/enti1.PNG)
![digita_bank](./captures/enti2.PNG)
![digita_bank](./captures/enti3.PNG)
![digita_bank](./captures/enti4.PNG)
![digita_bank](./captures/enti5.PNG)
### Repositories
![digita_bank](./captures/repo1.PNG)
![digita_bank](./captures/repo2.PNG)
![digita_bank](./captures/repo3.PNG)

### Services
![digita_bank](./captures/service.PNG)
![digita_bank](./captures/serviceImp1.PNG)
![digita_bank](./captures/serviceImp2.PNG)
![digita_bank](./captures/serviceImp3.PNG)
![digita_bank](./captures/serviceImp4.PNG)
![digita_bank](./captures/serviceImp5.PNG)


### DTOs
![digita_bank](./captures/dtoAccount.PNG)
![digita_bank](./captures/accOp.PNG)
![digita_bank](./captures/dtoBank.PNG)
![digita_bank](./captures/currentBnk.PNG)
![digita_bank](./captures/dtoCust.PNG)
![digita_bank](./captures/debitDTO.PNG)
![digita_bank](./captures/savingBank.PNG)
![digita_bank](./captures/transfertReq.PNG)


### Enums
![digita_bank](./captures/enum1.PNG)
![digita_bank](./captures/enum2.PNG)


### RestControllers
![digita_bank](./captures/bankControl.PNG)

![digita_bank](./captures/custControl.PNG)
okok




## FrontEnd



