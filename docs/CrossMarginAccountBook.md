# CrossMarginAccountBook

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Balance change record ID | [optional] 
**Time** | **int64** | The timestamp of the change (in milliseconds) | [optional] 
**Currency** | **string** | Currency changed | [optional] 
**Change** | **string** | Amount changed. Positive value means transferring in, while negative out | [optional] 
**Balance** | **string** | Balance after change | [optional] 
**Type** | **string** | Account change type, including:  - in: transferals into cross margin account - out: transferals out from cross margin account - repay: loan repayment - borrow: borrowed loan - interest: interest - new_order: new order locked - order_fill: order fills - referral_fee: fee refund from referrals - order_fee: order fee generated from fills - futures_in: transfer into futures account - futures_out: transfer out of futures account - unknown: unknown type | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


