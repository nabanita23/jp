Show in the dropdown:

longName (accountingPlatformId | eciId | gwmidentifier | spnId)

partyName instead of longName

partyName (eciID | spn | gwmidentifier)

if partyName not present then show accountingPlatformId

Fetch client infor :
https://mws.test.gaiacloud.jpmchase.net/irrest/fetchClientAccountInfo
--------------------------------------------------------------------------------------
Payload:
{"isCWMUser":"Y","accountDto":{"initType":"ACCT_INIT","accountNumber":"Q45993005","entity":"ALL","businessSystemCode":""},"loginUser":{"sid":"U041330"}} 
----------------------------------------------------------------------------------------
Response:


{"response":{"responseCode":"0","responseMessage":"Success"},"loginUser":{"sid":"U041330"},"userEntitledToStrategicVisibility":true,"dataAvailableButNoVisibility":false,"accountDtoList":[{"response":{},"eci":"0125096008","cas":"0125096008","spn":"5439582","dmEci":"0125096008","partyName":"DAR TECH LLC","corporateProductCode":"00OM1","businessSystemCode":"OMN","accountNumber":"Q45993005","alternateAccountIdentifier":"Q45993005","searchableAccountIdentifier":"Q45993005","partyRole":"Sole Owner","partyTypeCode":"NIND","accountTypeName":"ASSET","accountStatus":"Y","primaryOwner":"UHNW","clientLOB":"UHNW","entity":"USA","accountTitle":"DAR TECH LLC","bankCode":"0000000245","gwmIdentifier":"G0125096008","bookingBranchIdentifier":1,"relationshipTypeCode":"OWN","accountFetchedFromMorcom":false,"primaryLOBCode":"01","primaryOwnerIndicator":"true","accountStatusDesc":"OPENED"},{"response":{},"eci":"0384145108","cas":"0220618998","spn":"8369399","dmEci":"0384145108","partyName":"ANDREW D MEHRTENS","corporateProductCode":"00OM1","businessSystemCode":"OMN","accountNumber":"Q45993005","alternateAccountIdentifier":"Q45993005","searchableAccountIdentifier":"Q45993005","partyRole":"Signer","partyTypeCode":"IND","accountTypeName":"ASSET","accountStatus":"Y","primaryOwner":"UHNW","clientLOB":"UHNW","entity":"USA","accountTitle":"DAR TECH LLC","bankCode":"0000000245","gwmIdentifier":"G0384145108","bookingBranchIdentifier":1,"relationshipTypeCode":"IP","accountFetchedFromMorcom":false,"primaryLOBCode":"01","primaryOwnerIndicator":"false","accountStatusDesc":"OPENED"},{"response":{},"eci":"0664045398","partyName":"FRANCISCO GIOVANNI MCPADDEN","corporateProductCode":"00OM1","businessSystemCode":"OMN","accountNumber":"Q45993005","alternateAccountIdentifier":"Q45993005","searchableAccountIdentifier":"Q45993005","partyRole":"Contact For","partyTypeCode":"IND","accountTypeName":"ASSET","accountStatus":"Y","primaryOwner":"UHNW","clientLOB":"UHNW","entity":"USA","accountTitle":"DAR TECH LLC","bankCode":"0000000245","gwmIdentifier":"U0001198732","bookingBranchIdentifier":1,"relationshipTypeCode":"IP","accountFetchedFromMorcom":false,"primaryLOBCode":"01","primaryOwnerIndicator":"false","accountStatusDesc":"OPENED"},{"response":{},"eci":"0664045439","partyName":"SHENELLY TEHYA SPEIDELL","corporateProductCode":"00OM1","businessSystemCode":"OMN","accountNumber":"Q45993005","alternateAccountIdentifier":"Q45993005","searchableAccountIdentifier":"Q45993005","partyRole":"Contact For","partyTypeCode":"IND","accountTypeName":"ASSET","accountStatus":"Y","primaryOwner":"UHNW","clientLOB":"UHNW","entity":"USA","accountTitle":"DAR TECH LLC","bankCode":"0000000245","gwmIdentifier":"U0001198733","bookingBranchIdentifier":1,"relationshipTypeCode":"IP","accountFetchedFromMorcom":false,"primaryLOBCode":"01","primaryOwnerIndicator":"false","accountStatusDesc":"OPENED"}],"accountDto":{"response":{},"businessSystemCode":"","accountNumber":"Q45993005","entity":"ALL","initType":"ACCT_INIT","bookingBranchIdentifier":0,"accountFetchedFromMorcom":false},"isCWMUser":"Y"}
