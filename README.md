# twitterDM-Cleaner
Twitter MASS DM REMOVER
Caution: The following code will remove all your twitter direct messages.

Instructions:
Open your direct messages window, open console , ( chrome users just hit F12 )
pase the following code:


window.delscrpt = setInterval(function() {
  $('.DMInboxItem').each(function() { 
      $(this).click();
      setTimeout(function(){
         $(".Icon .Icon--info").click();
         setTimeout(function(){
                $(".DMConversationSettings-footer .EdgeButton--danger").click();
                    setTimeout(function(){
                      $("#confirm_dialog_submit_button").click();
                     console.log("delete");
                      },200);
                },700);
                
                
      },500);
   });

}, 2000);



