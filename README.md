# publicstellar
this is the doc file for api access to publicstellar


API https://publicstellar.com/api/get_list.php?apiKey=srEjcSb9tQiAp58ethGt43m.Ere2pj3r&currencyType=ASSET&search_term=THB


Function : Get list of currency with issuer details.

Parameters :

apiKey = Valid APIKey to access the api calls.

currency_type = Curreny type , either ASSET/TOKEN

search_term = Term that you want to search for.



API(Example) : http://publicstellar.com/api/register.php?currency_type=TOKEN&currency_id=MICOSL&issuer_address=dsfsdf&federation_address=fdsfsdfsd&description=sdfsdfdsf&issuer_website=dsfsdfsdf&issuer_email=sdfdsf@ggg.com&total_token=hello&issuer_signature=ttretre&apiKey=nr0Hn66xNfrlN26Da8RepvLlTYtD7nlR.


Function : Register your own list



apiKey = Valid APIKey to access the api calls.

currency_type = Curreny type , either ASSET/TOKEN

currency_id = Currency ID like USD,IDR,BTN etc.

issuer_address = Address of Issuer

federation_address = Address of Federation.

description = Description for currency

issuer_website = Website address of Issuer

issuer_email = Email of Issuer

total_token = Total token value if currency_type is TOKEN

issuer_signature = Signature of Issuer like fb,twitter url.


Response : Successful execution of api call will return unique_key that will be used to edit your own list.
