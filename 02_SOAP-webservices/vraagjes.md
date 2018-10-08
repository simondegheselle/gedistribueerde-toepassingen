# vraagjes Labo 2

## Wat is de naam van de aangeboden service?
DictService

## Welke poorten worden er gedefinieerd?
 - DictServiceHttpGet
 - DictServiceHttpPost
 - DictServiceSoap
 - DictServiceSoap12

## Welke transportprotocol gebruikt de DictServiceSoap-binding?
HTTP
http://schemas.xmlsoap.org/soap/http


## Welke operaties worden er in de DictServiceSoap-binding gedefinieerd?
 - ServerInfo 
 - DictionaryList
 - DictionaryListExtended
 - DictionaryInfo
 - Define
 - DefineInDict
 - StrategyList
 - Match
 - MatchInDict
 
## Welke parameters verwacht de operatie MatchInDict?
 - dictId
 - world
 - strategy 

## Wat retourneert de operatie MatchInDict?
```xml 
<MatchInDictResponse xmlns="http://services.aonaware.com/webservices/">
    <MatchInDictResult>
    <DictionaryWord>
        <DictionaryId>string</DictionaryId>
        <Word>string</Word>
    </DictionaryWord>
    <DictionaryWord>
        <DictionaryId>string</DictionaryId>
        <Word>string</Word>
    </DictionaryWord>
    </MatchInDictResult>
</MatchInDictResponse>
```