BHAI when we fill the form with appropriate username and password that is

 and jab submit karte hai toh get request hota hai and response is sent to the browser like this
 
[{"id":"XM35718ebf536545f2a4eefdbb37a24415","jabberAddress":"joe@uc1.mycompany.com","domain":"mydomain.com","externalAddress":"19195551212"},{"id":"XM5514cb720d7f49a9a66a6442f79bbfaf","jabberAddress":"abhayani@xmpp.xyz","externalAddress":"12012993898"},{"id":"XM6ec5ff363a6c401cb7c33dc506110e85","jabberAddress":"sunnyd@xmpp.xyz","domain":"mydomain.com","externalAddress":"12017780615"},{"id":"XMc9f13378afaf41fcba81309292ed60e5","jabberAddress":"draperbuilding_2221@ums.veracitynetworks.com","externalAddress":"12105683634"}]


humara yeh function meh kuch mistake hai


else{
        
         var body = doc.body;
          console.log(body)
        var data = [];
        for (a in body){
         val =body[a];
          var temp={
            id : val.id,
            jabberAddress : val.jabberAddress  
          }
            data.push(temp)      
        } 
        res.send({data : data}) 
       }
 yeh jab run kar rahe hai tab aise output aaraha hai
 
 
 {"data":[{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{},{}]}
